# new-linux-setup
新しいLinuxマシンのセットアップメモ

## 設定ファイル

- .bashrc
    ```diff
    @@ -57,7 +57,7 @@
     fi
     
     if [ "$color_prompt" = yes ]; then
    -    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\w\[\033[00m\]\$ '
    +    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\w\[\033[00m\]\n\$ '
     else
         PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w\$ '
     fi
    ```
- .vimrc
    ```
    ```
