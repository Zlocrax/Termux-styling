# Termux-styling
Hello and welcome to an easy way to make termux your style

Copy and paste

Clone this repository


Back up your current bashrc file with 

cd /data/data/com.termux/files/usr/etc && cp -v bash.bashrc $HOME/termux-bashrc/backup/ && cd -

Copy the bashrc file to your file path dir with

cd termux-bashrc && cp bash.bashrc /data/data/com.termux/files/usr/etc && exit

Now done restart termux 

Now lets start editing the file with 

edit-bashrc

Open a second window in termux and Type figlist for the list of fonts for your header once chosen go back to your original window 

Then add at the end of the script under display

figlet -f <font> <nameforheader>

Then scroll up to prompt to change the colors of your cmd line 

List of colors: 

31:red
32:green
33:yellow
34:blue
35:purple

Now scroll up to user to rename your system user to a  name of your choosing then scroll up to username to change the name you want to appear on your cmd line

Now click ctrl x and save the buffer exit termux and load it back up now your terminal should be customised to your liking for extra customisation options you can always download termux styling from this repository here 

https://github.com/termux/termux-styling

Enjoy

-ZłO
