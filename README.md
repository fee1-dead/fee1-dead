Email: ent3rm4n@gmail.com

<details>
<summary>
c3aa162009a846983b4c1c557013847be457fb167004fc4f74692e58eebc82737f59aeeca2b21c1bd0521a6f9d24c4934542199cdb0a019c09744afc71e8031e
</summary>

  ```rust
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
