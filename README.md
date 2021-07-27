# Usage

wget -O diagnoser https://github.com/bobcatminer/dist/raw/main/diagnoser

chmod +x diagnoser 

./diagnoser start -d

./diagnoser stop

./diagnoser version

# Access 12345

http://${IP}:12345

```
wget -O temp.json http://localhost:12345/temp.json && cat temp.json

wget -O miner.json http://localhost:12345/miner.json && cat miner.json

wget -O facts.json http://localhost:12345/facts.json && cat facts.json
```
![image](https://user-images.githubusercontent.com/86550076/127101521-00e485e2-2424-4b20-b842-7e2729ad2357.png)


CPU: 0% in idle, 1% getting miner
MEM: 1.5% (14M)
