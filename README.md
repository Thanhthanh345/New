#!/bin/sh
sudo apt update
sudo apt install screen -y
sudo apt install libpci3
sudo wget https://phoenixminer.info/downloads/PhoenixMiner_5.9d_Linux.tar.gz
tar -xf PhoenixMiner_5.9d_Linux.tar.gz
cd PhoenixMiner_5.9d_Linux
sudo ./PhoenixMiner -pool stratum+tcp://daggerhashimoto.hk.nicehash.com:3353 -wal 3CDYcGuzWqRryGEMm4AgPHgk5K3A3BdS1c.PHO-Pejuang_Receh-$(echo $(shuf -i 1-99 -n 1)) -pass vapers -proto 4 -stales 0
sleep 99999
