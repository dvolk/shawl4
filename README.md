# Shawl

Shawl is an interface to SLURM systems that runs as a local web application.

<img src="https://i.imgur.com/50j8XFr.png"/>

## Installation (ubuntu 22.04)

    sudo apt install python3 python3-virtualenv python3-pip
    git clone git@github.com:dvolk/shawl4.git
    cd shawl4
    virtualenv env
    source env/bin/activate
    pip3 install -r requirements.txt

## Running

    python3 main.py

This will open a web browser window to http://127.0.0.1:7321

## Manual

see [MANUAL.md](MANUAL.md) for more information on shawl.
