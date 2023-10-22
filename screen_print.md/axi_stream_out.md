![image](https://github.com/2427jim2427/soc_lab3/assets/143332407/8929a4fd-be5e-4696-a851-83f94806246e)
after we do the fir calculate ,we ouput the result data with axi_stream.
first check whether sm_tready is high, then output data on sm_tdata port and set sm_tvalid high for slave to receive it. 

when ap_done,set sm_tlast high for the last data.
