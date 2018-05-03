# secure-parity-wallet
A case study in securing calls between smart contracts using the Parity wallet.



| Deployer         | Additions                | Added Deployment Cost (in gas units) | Added Deployment Cost (as a percentage of original)|
|------------------|--------------------------|--------------------------------------|----------------------------------------------------|
| Service Provider | Library Instrumentation  | 807111 | 35.23%|
| User | FullPM + FullEM Monitoring | 354017 + 295818 | 97.46% + 81.44%|
 || FullPM + (ResidualEM) Monitoring | 354017 + 210829 | 97.46% + 58.04% |
 || (ResidualPM) + (ResidualEM) Monitoring | 325911 + 210829 | 89.73% + 58.04% |
