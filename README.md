# Description:
Private and public ssh keys to my github projects.
Allow you login into machines without typing a password.

## Annotation:

Gerwazy - the Key Holder from XIXth century Polish national epic poem Pan Tadeusz by Adam Mickiewicz.


## Howto:

    mkdir $HOME/.ssh
    chmod 700 $HOME/.ssh
    cp id_rsa* $HOME/.ssh/
    chmod 600 id_rsa*
    chmod 644 id_rsa*.pub
