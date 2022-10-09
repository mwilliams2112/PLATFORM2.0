#!/bin/bash

sudo add-apt-repository http://dl.openfoam.org/ubuntu
sudo sh -c "wget -O - http://dl.openfoam.org/gpg.key | apt-key add -"

sudo apt-get update
sudo apt-get -y install openfoam240
sudo apt-get -y install paraviewopenfoam410

echo 'source /opt/openfoam240/etc/bashrc' >> .bashrc


