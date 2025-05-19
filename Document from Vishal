#include <stdlib.h>
#include <stdio.h>
#include <string.h>

char EDITOR[1024]="nvim ";
char CONFIG_HOME[1024]="~/.config/";

int main(int argc,char * argv[]){

	printf("config menu------------------ \n \n");
	printf(" 1) sway \n 2) foot \n 3) nvim \n 4) waybar \n 5) fastfetch \n 6) wofi \n 7) hyprland \n");
	int n;
	if(argc==1){
	printf("enter which config to edit: ");
  scanf("%d",&n);
	}else{
		n=atoi(argv[1]);
		printf("%d",n);
	}
	switch(n){
		case 1:
			system(strcat(EDITOR,strcat(CONFIG_HOME,"sway/config")));
			break;
		case 2:
			system(strcat(EDITOR,strcat(CONFIG_HOME,"foot/foot.ini")));
			break;
		case 3:
			system(strcat(EDITOR,strcat(CONFIG_HOME,"nvim/init.lua")));
			break;
	  case 4:
			system(strcat(EDITOR,strcat(CONFIG_HOME,"waybar/config.jsonc")));
			break;
		case 5:
			system(strcat(EDITOR,strcat(CONFIG_HOME,"fastfetch/config.jsonc")));
			break;	
		case 6:
			system(strcat(EDITOR,strcat(CONFIG_HOME,"wofi/config")));
			break;
		case 7:
			system(strcat(EDITOR,strcat(CONFIG_HOME,"hypr/hyprland.conf")));
			break;
		default:
			printf("invalid option");
			break;
}
	

	return 0;
}
