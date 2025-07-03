# cppmake - simple cpp folder init script
to setup:
```
mkdir -p ~/Scripts

paste you cppmake file to ~/Scripts/

chmod +x ~/Scripts/cppmake

sudo nano ~/.zshrc: export PATH="$HOME/scripts:$PATH"

source ~/.zshrc
```
to use anywhere on your system: `cppmake myprogramhere`

uses: mydsafolder/cpp/*
                  ----> prg1/prg1.cpp & helper files
                  ----> prg2/prg2.cpp & helper files
                  ----> prg3/prg3.cpp & helper files
                  ----> prg4/prg4.cpp & helper files
