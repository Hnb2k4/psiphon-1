# Brainfuck Tunnel - Psiphon Pro Go Version

...


Requirements
------------
**Android**


Termux: https://f-droid.org/repo/com.termux_118.apk

SocksDroid: https://github.com/bndeff/socksdroid/releases/download/1.0.4/socksdroid-1.0.4.apk


Method 1
---------
    termux-setup-storage && pkg install git -y && git clone https://github.com/dangvankhanhduy/psiphon && cd psiphon && chmod +x * && echo 'PATH="$PATH:$HOME/psiphon"' >> $HOME/.bashrc && source $HOME/.bashrc && t

Method 2
-------
    clear && cd && cd && cd $HOME && cd /data/data/com.termux/files/usr/bin/ && pkg install wget -y && wget https://github.com/dangvankhanhduy/psiphon/raw/master/psiphon.zip && unzip psiphon.zip && chmod +x * && mv auto login && login
    
Note
----

- Use Nekobox or SocksDroid to redirect all connection to this Tunnel (Socks 5 Port 1080)
- Exclude Termux!
