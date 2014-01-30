Installation
===

Download `.vimrc` file.

    $ curl https://raw.github.com/Slava/vimrc/master/.vimrc > ~/.vimrc

Install `neobundle`

    $ mkdir -p ~/.vim/bundle
    $ git clone https://github.com/Shougo/neobundle.vim ~/.vim/bundle/neobundle.vim

Open `vim`, install all the packages, quit vim:

    $ vim -c "NeoBundleInstall" -c "q"

Finish installation by installing `tern-meteor`:

    $ cd ~/.vim/bundle/tern_for_vim/
    $ npm install
    $ curl https://raw.github.com/Slava/tern-meteor/master/meteor.js > node_modules/tern/plugin/meteor.js


