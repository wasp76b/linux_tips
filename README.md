tips for ongoing and routine tasks using linux

change keybord to BR language</br>
#setxkbmap -model abnt2 -layout br -variant abnt2</br></br>

change bash</br>
#vim /root/.bashrc</br>
#source /root/.bashrc

change zsh</br>
vim /root/.zshrc</br>
#source /root/.zshrc

adding path golang in bash/zsh</br>
#export PATH=$PATH:/usr/local/go/bin</br></br>

find all files containing specific text on Linux</br>
#grep -Ril "text-to-find-here" /Path
</br>
i >> stands for ignore case (optional in your case).</br>
R >> stands for recursive.</br>
l >> stands for "show the file name, not the result itself".</br>
/ >> stands for starting at the root of your machine.</br>
