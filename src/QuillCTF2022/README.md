# QuillHash CTF 2022 Solutions

Here's the link to the challenges page: https://quillctf.super.site/challenges. I highly recommend to solve the problems before checking the solutions!

---

**Table of Contents**
- [QuillHash CTF 2022 Solutions](#quillhash-ctf-2022-solutions)
  - [Road closed:](#road-closed)
    - [VIP Bank:](#vip-bank)

---

## Road closed:
https://quillctf.super.site/challenges/quillctf-challenges/road-closed

**Objective**:
- Become the owner of the contract
- Change the value of hacked to true

Goerli link: https://goerli.etherscan.io/address/0xd2372eb76c559586be0745914e9538c17878e812
 
```
forge test --match-contract QuillCTF1Solved -vvvv
```


### VIP Bank:
https://quillctf.super.site/challenges/quillctf-challenges/vip-bank

**Objective:**
At any cost, lock the VIP user balance forever into the contract.

Goerli Link: https://goerli.etherscan.io/address/0x28e42e7c4bda7c0381da503240f2e54c70226be2

```
forge test --match-contract QuillCTF3Solved -vvvv
```