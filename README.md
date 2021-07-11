# Colemak z polskimi ogonkami na Ubuntu

*Sprawdzone na wersji Ubuntu 20.04*

#### Aby mieć polskie znaki musisz:

    git clone && cd polish-colemak-linux-ubuntu
    
zamienić plik /usr/share/X11/xkb/symbols/us na ten z repo
    
    sudo cp ./us usr/share/X11/xkb/symbols/us
uruchomić ponownie

    reboot
    
Ustawić klawiature US Colemak
![region](https://user-images.githubusercontent.com/67120623/125198584-b4079400-e262-11eb-9771-d0a1c309b3a6.png)
