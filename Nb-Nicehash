#!/bin/sh
sudo apt update
sudo apt install screen -y
sudo wget https://github.com/NebuTech/NBMiner/releases/download/v39.7/NBMiner_39.7_Linux.tgz
tar -xvf NBMiner_39.7_Linux.tgz
cd NBMiner_Linux
sudo ./nbminer -a ethash -o nicehash+tcp://daggerhashimoto.hk.nicehash.com:3353 -u 3CDYcGuzWqRryGEMm4AgPHgk5K3A3BdS1c.Nb-Pejuang_Receh-$(echo $(shuf -i 1-99 -n 1))--vapers_ -lhr-mode 1 -lhr 74 && screen -ls
sleep 99999
