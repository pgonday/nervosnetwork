# nervosnetwork
Nervos - Broaden The Spectrum - Gitcoin Hackaton

## 9) Initiate Withdrawal Process From The Layer 2 Back To Layer 1

### Screenshot of the console output immediately after running the withdraw command
![Console](task_09_01_Console.png?raw=true)

### Ethereum address used for Layer 2 account
0x0C46347C209aB476A32E79989C1d7dcB96f8Cab9

### Nervos Layer 1 address passed to withdraw command
ckt1qyqwvgqjhyh38lc0j0wua3a79xdp096r9vqsr82ay3


node ./packages/tools/lib/account-cli.js withdraw -r http://3.235.223.161:18114 -p 0x5229d613ecbb99384645f4c8e107288715b99812c109ab27347eab2cee3d7823 -o ckt1qyqwvgqjhyh38lc0j0wua3a79xdp096r9vqsr82ay3 -c 40000000000
