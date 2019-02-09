Steps :- 
    Required Packages :-
           apt-get install silversearcher-ag
           apt-get install build-essential cmake python3-dev

    Procedure To install Plugins:- 
        
        1) install Vundle using " git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim"
        2) move vimrc file to ~/.vimrc ( CMD: " mv vimrc ~/.vimrc" )
        3) open vim and execute command ":PluginInstall"
        
    To Enable "YouCompleteMe" For C-lang:- 
    
          cd ~/.vim/bundle/YouCompleteMe/ 
          ./install.py --clang-completer 

