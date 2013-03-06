# Description:
Private and public ssh keys to my github projects + .ssh/config to manage multiple keys.
Allow you login into machines without typing a password.

## Annotation:

Gerwazy - the Key Holder from XIXth century Polish national epic poem Pan Tadeusz by Adam Mickiewicz.


## Howto:

    mkdir $HOME/.ssh
    chmod 700 $HOME/.ssh
    cp id_rsa.elk $HOME/.ssh/
    cp id_rsa.emu $HOME/.ssh/
    chmod 600 $HOME/.ssh/id_rsa*
    chmod 644 $HOME/.ssh/id_rsa*.pub
    cat config >> $HOME/.ssh/config
    chmod 600 $HOME/.ssh/config
