# Colemak z polskimi ogonkami na ubuntu

## Sprawdzone na wersji 20.04

Podmieniłem odpowiednie klawisze na polskie ogonki w pliku z colemak'iem w wersji US.

Aby mieć polskie znaki musisz:

1. git clone 
2. cd polish-colemak-linux-ubuntu
3. zamienić plik /usr/share/X11/xkb/symbols/us na ten z repo (sudo cp ./us usr/share/X11/xkb/symbols/us)
4. reboot
