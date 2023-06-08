# Aura-Upgrade

Stop node

    sudo systemctl stop aurad
    
Install

    cd aura
    git checkout aura_v0.4.5
    make install
    
Check version

    aurad version
    
Restart node

    sudo systemctl daemon-reload
    sudo systemctl enable aurad
    sudo systemctl start aurad

    sudo journalctl -u aurad -f --no-hostname -o cat
