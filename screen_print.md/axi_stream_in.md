![image](https://github.com/2427jim2427/soc_lab3/assets/143332407/87d0a9b9-a7d4-4684-8bc0-e6c5a0c088b9)
before receive ap_start, keep ss_tready low then ss_tdata will not go on to the next data.

![image](https://github.com/2427jim2427/soc_lab3/assets/143332407/d892ed5b-53c8-4538-afb0-81c5722fe14b)
after ap_start, with ss_tvalid high,we restore the ss_tdata to the bram and set ss_tready high when finish restoring.

![image](https://github.com/2427jim2427/soc_lab3/assets/143332407/6c68d88d-edd5-4fec-bc15-4d02d1f55ebb)
then just keep going,until ... ss_tlast = 1.
![image](https://github.com/2427jim2427/soc_lab3/assets/143332407/50b57bc4-9957-4154-8e0e-f746eb885453)

