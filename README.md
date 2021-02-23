## EOS Mainnet - `PowerUp` Configurations

![image](https://user-images.githubusercontent.com/550895/108793981-e2563280-7552-11eb-9e84-7320e5985b46.png)

> [EOS Nation NRC Calculator](https://eos-nation.github.io/nrm-calc/?&powerup=0.00001&minprice=2500&maxprice=75000&exponent=2)

### Chain Stats

- Block Number: `169,785,951`
- REX total lent: `32,529,829.2017 EOS`
- EOS staked: `449,561,227.0934 EOS`

### Assumed Stake Weight

- Total staked: `482,091,056.2951 EOS`
- Assumed NET: `96,418,211.2590 EOS`
- Assumed CPU: `385,672,845.0360 EOS`

### References

- [EOSIO contracts v1.9.2](https://github.com/EOSIO/eosio.contracts/releases/tag/v1.9.2)


### Config

```json
{
   "args": {
      "cpu": {
         "assumed_stake_weight": 3856728450360,
         "current_weight_ratio": "1000000000000000",
         "decay_secs": 86400,
         "exponent": "2.00000000000000000",
         "max_price": "75000.0000 EOS",
         "min_price": "2500.0000 EOS",
         "target_timestamp": "2021-04-08T08:08:08.888",
         "target_weight_ratio": "10000000000000"
      },
      "net": {
         "assumed_stake_weight": 964182112590,
         "current_weight_ratio": "1000000000000000",
         "decay_secs": 86400,
         "exponent": "2.00000000000000000",
         "max_price": "75000.0000 EOS",
         "min_price": "2500.0000 EOS",
         "target_timestamp": "2021-04-08T08:08:08.888",
         "target_weight_ratio": "10000000000000"
      },
      "min_powerup_fee": "0.0001 EOS",
      "powerup_days": 1
   }
}
```
