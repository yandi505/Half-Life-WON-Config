# Half-Life-WON-Config
exec WON.cfg // Don't remove this
sv_cheats 0 

///////////////////////////////////////////////////[START BINDS]///////////////////////////////////////////////////
bind "," "load crosshair"
bind "o" "PB"
bind "p" "scr"





///////////////////////////////////////////////////[BXT BINDS]///////////////////////////////////////////////////
bind "KP_LEFTARROW" "bxt_show_triggers 1"
bind "KP_5" "bxt_show_triggers 0" 

bind "[" "bxt_autojump 1"
bind "]" "bxt_autojump 0"

bxt_hud_timer 1
bxt_hud_color "255 160 0"
bxt_hud_jumpspeed 0
bxt_hud_speedometer 1
bxt_hud_speedometer_anchor "0.48 0.7"




///////////////////////////////////////////////////[PREFERENCES]///////////////////////////////////////////////////
default_fov 110
net_graph 0
cl_showfps 1
fps_max 100
pausable 1





///////////////////////////////////////////////////[GAME BINDS]///////////////////////////////////////////////////
bind "f1" "gl_texturemode GL_NEAREST_MIPMAP_NEAREST"  
bind "f2" "gl_texturemode GL_LINEAR_MIPMAP_LINEAR"
    
bind "m" "force_centerview"

bind "KP_HOME" "exec autoexec.cfg; speak buttons/button3"
bind "KP_UPARROW" "start"
bind "KP_PGUP" "exec scripts.cfg; speak buttons/button5" 





///////////////////////////////////////////////////[MOVEMENT BINDS]///////////////////////////////////////////////////
bind "mwheeldown" "+duck"
bind "mwheelup" "+jump"

bind "space" "+duck"
bind "ctrl" "+attack"
bind "shift" "+speed"





///////////////////////////////////////////////////[SAVE&LOAD BINDS]///////////////////////////////////////////////////
bind "v" "save quick" 
bind "h" "load quick"

bind "mouse4" "save quick"
bind "mouse5" "load quick"

bind "g" "load autosave" 





///////////////////////////////////////////////////[WEAPON BINDS]///////////////////////////////////////////////////
bind "1" "weapon_crowbar"
bind "alt" "weapon_shotgun"
bind "tab" "weapon_handgrenade"
bind "b" "weapon_gauss"
bind "4" "weapon_hornetgun"
bind "3" "weapon_9mmAR"
bind "yourkey" "weapon_tripmine"					
bind "yourkey" "weapon_satchel"



///////////////////////////////////////////////////[ATTACK BINDS]/////////////////////////////////////////////////
bind mouse1 +attack
bind mouse2 +attack2

bind "ctrl" "+attack"





///////////////////////////////////////////////////[FPS BINDS]//////////////////////////////////////////////////
bind "z" "fps_max 20"
bind "x" "fps_max 100"

bind "capslock" "fps_max 4"
bind "c" "fps_max 8"
bind "y" "jbTCskip"




///////////////////////////////////////////////////[SCRIPTS BINDS]//////////////////////////////////////////////////
bind "yourkey" "+duckroll"
bind "yourkey" "+usespam"
bind "yourkey" "obbo"
bind "yourkey" "obbo800"
bind "yourkey" "obboshoot"
bind "yourkey" "+tau"
bind "yourkey" "in_nade"
bind "yourkey" "smgboost"
bind "yourkey" "+jumpbug"





///////////////////////////////////////////////////[MAP BINDS]///////////////////////////////////////////////////
//Half-Life Maps (Rebind y key for Jumpbug fps values and maps binds)
bind "F4" "bind y jbTCskip; bind KP_END HP; bind KP_DOWNARROW P2P; bind KP_PGDN TC"
bind "F5" "bind y jbBPgoo; bind KP_END UC; bind KP_DOWNARROW OC; bind KP_PGDN WGH"
bind "F6" "bind y jbBPend; bind KP_END BP; bind KP_DOWNARROW PU; bind KP_PGDN Apon"
bind "F7" "bind y jbOARend; bind KP_END RP; bind KP_DOWNARROW QE; bind KP_PGDN ST"
bind "F8" "bind y jbXEN; bind KP_END FAF; bind KP_DOWNARROW LC; bind KP_PGDN XEN"
bind "F9" "bind KP_END GL; bind KP_DOWNARROW INT; bind KP_PGDN NIH"

bind "KP_PLUS" "map1"
bind "KP_ENTER" "map2"
bind "KP_DEL" "map3" 
bind "KP_INS" "map4"






/////////////////////////////////////////[ALIASES]////////////////////////////////////////////////////
 
alias "jbBPgoo" "fps_max 20.40816"
alias "jbBPend" "fps_max 20"
alias "jbOARend" "fps_max 23.25581"
alias "jbXEN" "fps_max 22.22222"
alias "jbTCskip" "fps_max 23" 		
       
alias "scr" "stop;exec autoexec.cfg;sv_cheats 0;bxt_hud_origin 0;bxt_hud_timer 1;bxt_timer_reset;bxt_timer_start;exec scripts.cfg;bxt_autorecord m;map c1a0"
alias "PB" "stop;exec autoexec.cfg;sv_cheats 0;bxt_hud_origin 0;bxt_hud_timer 1;bxt_timer_reset;bxt_timer_start;;bxt_autojump 0;bxt_autorecord m;map c1a0"
alias "start" "map c1a0; exec autoexec.cfg; bxt_hud_timer 1; bxt_timer_reset; bxt_timer_start;"

//Map Aliases
alias "UC" "load t1; bxt_timer_reset; bxt_timer_start"
alias "OC" "load t2; bxt_timer_reset; bxt_timer_start"
alias "WGH" "load t3; bxt_timer_reset; bxt_timer_start" 
alias "BP" "load t4; bxt_timer_reset; bxt_timer_start" 
alias "PU" "load t5; bxt_timer_reset; bxt_timer_start
alias "Apon" "load t6; bxt_timer_reset; bxt_timer_start" 
alias "RP" "load t7; bxt_timer_reset; bxt_timer_start" 
alias "QE" "load t8; bxt_timer_reset; bxt_timer_start" 
alias "ST" "load t9; bxt_timer_reset; bxt_timer_start" 
alias "FAF" "load t10; bxt_timer_reset; bxt_timer_start" 
alias "LC" "load t14; bxt_timer_reset; bxt_timer_start"
alias "XEN" "load t11; bxt_timer_reset; bxt_timer_start" 
alias "GL" "load t15; bxt_timer_reset; bxt_timer_start" 
alias "INT" "load t16; bxt_timer_reset; bxt_timer_start"
alias "NIH" "load t17; bxt_timer_reset; bxt_timer_start" 

//Training Aliases
alias "HP" "load t12; bxt_timer_reset; bxt_timer_start"
alias "Suit" "load t0; bxt_timer_reset; bxt_timer_start"
alias "P2P" "load t13; bxt_timer_reset; bxt_timer_start"
alias "TC" "load tc; bxt_timer_reset; bxt_timer_start"

//bhopmaps Aliases
alias "map1" "map bhop_comeback; bxt_timer_reset; bxt_timer_start"
alias "map2" "map bhop_kisu; bxt_timer_reset; bxt_timer_start"
alias "map3" "map ztricks_euthanasia; bxt_timer_reset; bxt_timer_start" 
alias "map4" "map bhop_crossfire; bxt_timer_reset; bxt_timer_start" 




echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo;echo

echo Thanks for downloading 
echo Necessarily read README  
echo vk.com/@grunge_isdead-speedrunpackage (for RUS) 
echo;echo;echo;echo;echo
echo Subscribe:

echo;
echo "YOUTUBE - http://youtube.com/yandi505"
echo "Discrod - https://discord.gg/YdxZmhT"
