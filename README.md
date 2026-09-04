# The-Macpocalypse
Down With the Mac's

## The First Steps
You'll need brew, and to install this
- open your terminal via the search key at the top somewhere
- open terminal
 - first run ```cd```
 - then ```mkdir ~/Homebrew```
 - then run this command ```git clone https://github.com/Homebrew/brew/ ~/Homebrew```
 - then ```mkdir -p ~/bin && ln -s ~/Homebrew/bin/brew ~/bin/brew```
 - then ```echo '[ -d "$HOME/bin" ] && export PATH="$PATH:$HOME/bin"' >> ~/.zshrc```
 - then ```source ~/.zshrc```
Now after all that run ```brew``` and that should do somthing other than ```command not found: brew```
> **It didn't work**: well now just download the homebrew folder above

## The Second Step
Wonderful you have brew now, It is now time to install wine
> **Wine is not the only thing you can install with brew**

- First run ```brew install --cask The-Wineskin-Project/wineskin/wineskin``` press y when asked then when password press CTRL+X or Z or C Which ever one
- now in finder, find the file in your directory (>R2.D2 on the left) open Homebrew>Caskroom>Wineskin>*version number*>Wineskin Winery
- open then and DONT DELETE THE FILE, choose the other option
- put this commnad in the prompt and dont enter it ```xattr -rd com.apple.quarantine``` add a space and drag the Wineskin Application from finder in to the terminal
- after this now open wineskin and click the + create new thingy after that create the enviroment or something, name it, click ok, and wait for it to finish
