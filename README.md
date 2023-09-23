st - simple terminal Version:0.8.5
---
 st is a simple terminal emulator for X which sucks less.
 
Dependecy
---
 The default Shell of this build is zsh.\
 If zsh is not installed or installed in other than /usr/bin/zsh\
 edit, comment uncomment
  - static char *shell of config.h
  - /*	if ((sh = getenv("SHELL")) == NULL) */\
		sh = "/usr/bin/zsh";\
    /*		sh = (pw->pw_shell[0]) ? pw->pw_shell : cmd; */\
    of st.c

 

Keys
---
 This build of st is set to-


Mod Key
---

    Default Mod: Super (Mod4)    
    TermMod:     Ctrl+Shift
   
Actions
---

    Copy:        Ctrl+Shift+c
    Paste:       Ctrl+Shift+v
    
    Color:       Ctrl+Shift+p
    
    Zoom:
      - In:      Ctrl+Shift+pgup
      - Out:     Ctrl+Shift+pgdn
      - Reset:   Ctrl+Shift+home
      
    Scroll:
      - Up:      Alt+Ctrl+k
      - Down:    Alt+Ctrl+j
    
    Url:
      - Select:  Super+l
      - Open:    Super+u
