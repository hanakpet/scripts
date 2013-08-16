## How to install leiningen with emacs on Lubuntu 13.04

sudo apt-get install leiningen

sudo apt-get remove leiningen

RESTART

cd /bin

sudo wget https://raw.github.com/technomancy/leiningen/stable/bin/lein

sudo chmod a+x lein

lein

lein version

sudo apt-get install openjdk-7-jdk

# Installation of Emacs 24 with custom theme from edtsech

sudo apt-add-repository ppa:cassou/emacs

sudo apt-get update

sudo apt-get install emacs-snapshot emacs-goodies-el

git clone git@github.com:edtsech/clojure-emacs-setup.git ~/.emacs.d
