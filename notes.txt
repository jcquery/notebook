#shows the first x lines
head -n x file

#shows the last x lines
tail - n x file

#copies to the clipboard
pbcopy

#opens a file using a man-style pager
less

#moves/renames a target file
mv backup.txt ../

#displays terminal history
history

#double >> appends to a file's contents
echo 'hello hello' >> notes.txt

#single > replaces a file's contents
echo 'hello hello' > notes.txt

#deletes a file
rm morenotes.txt

#read two files into the terminal
cat notes.txt morenotes.txt

#copies a file into another file
cp notes.txt morenotes.txt

#create a file
touch notes.txt

#shorthand for ls -hal
la

#displays a visual file tree to the nth level
tree -L 1

#opens a file or folder
open documents

ls -n
ls -ln
ls -rS
man ls
ls -help
ls -Ss
ls -s
ls -lG
hal -G
ls -halG
ls -@l
ls -@
cat .config/fish/config.fish
ll .config/fish
ll .config
ll .config/
ls -hal
-ll
ls -h
ls -hl
ls Documents/
ls -l
cd ~/Downloads/
cd ~/Applications/
groups
whoami
open http://jcquery.surge.sh
git commit -m 'Fixed CNAME'
git add CNAME
git commit -m 'Add an itty bitty web page'
git add index.html
surge
git commit -m 'Add a CNAME'
atom CNAME
touch CNAME
open index.html
atom .
touch index.html
git init
cd jcquery.surge.sh/
mkdir ~/Projects/jcquery.surge.sh
cd ~/Projects
mkdir ~/Projects
surge -V
surge -v
npm install -g surge
l
rm ~/Desktop/test.js
rm ~Desktop/test.js
node ~/Desktop/test.js
node ~!/Desktop/test.js
node !/Desktop/test.js
atom ~/Desktop/test.js
node
node -v
brew install node
curl -fsSL https://git.io/vgqFH | sh
git config --global user.email
git config --global user.name
git config --global user.email 'jcarney000@gmail.com'
git config --global user.name 'John Carney'
which git
git --version
brew install git
echo $PATH
echo PATH
echo $EDITOR
atom ~/.config/fish/config.fish
brew info fish
fish_update_completions
curl -fsSL https://git.io/vgqFU | ruby
chsh -s /usr/local/bin/fish
echo '/usr/local/bin/fish' | sudo tee -a /etc/shells
brew install fish
brew doctor
brew update
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
ls -G
uname
