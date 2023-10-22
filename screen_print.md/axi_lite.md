![image](https://github.com/2427jim2427/soc_lab3/assets/143332407/5c443cd0-806f-47cd-833e-e674eb561a24)
if the awvalid high, we can get data address from awaddr.
if the wvalid high,we can get data from wdata.
after we restore tap coef in bram, we set wready high and go on to the next data.

![image](https://github.com/2427jim2427/soc_lab3/assets/143332407/8708e46b-5951-4cdb-b81a-5a6876b6a332)
when arvalid high , we can get the data address from "host read request".

![image](https://github.com/2427jim2427/soc_lab3/assets/143332407/d49df5fc-4c93-4dad-a635-fdb06ac4ee73)
if rready is high, we can set rvalid to high and output the tap data on rdata port for host to read
