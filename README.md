# Usage

Install in usr's bin

```
pkill diagnoser

cd /usr/bin

wget -O diagnoser https://github.com/bobcatminer/dist/releases/download/1.1.8/diagnoser

./diagnoser version

chmod +x diagnoser 

diagnoser start -d
```

# Stop 

./diagnoser stop

# Access

http://${IP}

```
wget -O temp.json http://localhost/temp.json && cat temp.json

wget -O miner.json http://localhost/miner.json && cat miner.json

wget -O status.json http://localhost/status.json && cat status.json

wget -O led.json http://localhost/led.json && cat led.json

wget -O dig.json http://localhost/dig.json && cat dig.json

wget -O speed.json http://localhost/speed.json && cat speed.json

```


CPU: 0% in idle, 1% getting miner
MEM: 1.5% (14M)
