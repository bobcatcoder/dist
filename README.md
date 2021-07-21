# Usage

wget https://github.com/bobcatminer/dist/raw/main/diagnoser 

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
