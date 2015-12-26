# ChangeKeys
Shell script to change the mapping of keys on a Japanese Microsoft Sculpt keyboard. 

The Microsoft Sculpt keyboard is an excellent,reasonably-priced ergonomic keyboard. Interestingly, the Japanese version has two keys next to spacebar which are unused when used as an English keyboard. By mapping the key left of the spacebar to BackSpace and the key right of the spacebar to Enter, the ergonomics of the keyboard are greatly improved since the thumbs can take the load off the commonly used pinkie finger. In addition, the capslock key is remapped to escape for use with Vim keybindings and the keys to the left of the shift and backspace keys are mapped to Shift and Backspace, respectively.

This script can be made into an executable by using the following command in the ChangeKeys directory -

```
chmod +x changeKeys.sh
```

To the last line in the .bashrc file, add the following line to be able to run the script outside of the ChangeKeys folder (Note: You will need to reload the terminal after adding this line)-

```
alias changeKeys='FILEPATH_TO_changeKeys.sh'
```
