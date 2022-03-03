1. https://github.com/lervag/vimtex I'm using this in my vimrc
2. https://tug.org/texlive/acquire-netinstall.html download tar.gz file from here and extract anywhere - I did ~/Downloads
3. cd ~/Downloads/install-tl-20211222 and run `sudo perl install-tl` hit `i` for command "install".
4. needed to apt install some stuff...
sudo apt install texlive-bibtex-extra biber texlive-lang-english texlive-fonts-recommended texlive-fonts-extra
5. I think I also needed to add something here to my PATH:
/usr/local/texlive/2021/bin/x86_64-linux
I honestly don't know if that's all of texlive, just some plugins or something? no idea...
