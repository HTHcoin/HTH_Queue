# HTH QUEUE POSITION

Enter following line on your server where you have a HTH full node. This will only work if you installed your masternode with an install script. If you have compiled from source than you would need to edit the path to where your hth-cli is located. If you did build `nano queue.sh` and replace the path to cli. So change `MNLISTCMD="hth-cli masternodelist full 2>/dev/null"` to the following line
`MNLISTCMD="/full/path/to/hth-cli masternodelist full 2>/dev/null"` **Change /full/path/to your actual path to hth-cli**

```
sudo wget https://raw.githubusercontent.com/dk808/HTH_Queue/master/queue.sh && sudo chmod u+x queue.sh && sudo ./queue.sh
```
After script is installed look up your queue position by entering `./queue.sh your_hth_mn_address`
