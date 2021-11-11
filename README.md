Email: ent3rm4n@gmail.com

```
BTC: 325LmaguUwq8rgnYETi61DkMn63LqMK89U
BCH: bitcoincash:ppe55z0hr5dj30m2ymanwkpzczsq7xkanyqllf93u8
XMR: 87kiAuVQQdbU4Gcf2MJ8RsVesLaokY4r1W1AtVeE6mDDEQ26fAazCQ98qX1BU3B65kA7JnB5V7yD2FwAkfqrNybSJjqd7Yt
FLOW: 0x070acff2b598b161
NANO: nano_1r5wbf3dkkkq6jp185qf1x8pktmhfhnq76ptpz7nu14ymdyc7oqfh3xtaum5
ETH: 0x6dcc6b9ee000bddde3764438eb4bf16b3d2995df
LTC: LRkyJNAGEiUda2pcEK2GusuhLfTkZ6VEDR

/* Note: These are Kraken deposit addresses. If you wish to donate a small amount please contact me so I can create my own wallet and put the address on there */
```

<details>
<summary>
  <sup><sub>.</sub></sup>
</summary>

  ```rust
// c3aa162009a846983b4c1c557013847be457fb167004fc4f74692e58eebc82737f59aeeca2b21c1bd0521a6f9d24c4934542199cdb0a019c09744afc71e8031e
use tiny_keccak::{Hasher, Sha3};
fn main() {
    let mut buffer = [0; 64];
    let mut sha3 = Sha3::v512();
    sha3.update(b"Birth Year");
    sha3.finalize(&mut buffer);

    for byte in buffer {
        print!("{:02x}", byte);
    }
}
  ```
  
</details>
