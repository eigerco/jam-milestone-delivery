# JAM Milestone Delivery 


## Company details


- Company's name: Eiger
- Company's GitHub: [https://github.com/eigerco](https://github.com/eigerco)
- Programming language and language set: Go (set A)
- Links to previous deliveries: there was one closed [PR](https://github.com/w3f/jam-milestone-delivery/pull/6) before


## Documentation checklist


We declare that:

- [x] we have completed **the Web3 Foundation KYC/KYB process**.
- [x] we used **a clear and permissive open-source license**.
- [x] we submitted **a clear Git history and public, credibly timestamped commits**.
- [x] we used third party libraries for:
  - Bandersnatch, Rust FFI of [github.com/davxy/ark-ec-vrfs](https://github.com/davxy/ark-ec-vrfs)
  - Ed25519 [golang.org/x/crypto](https://pkg.go.dev/golang.org/x/crypto)
  - In memory db [github.com/cockroachdb/pebble](https://github.com/cockroachdb/pebble)
  - FFI [github.com/ebitengine/purego](https://github.com/ebitengine/purego)
- [ ] we provided **Gas, trie/DB, signature-verification, and availability (EC/DB) performance tests** to be run on standard hardware.
  - Not relevant in this milestone
- [x] we viewed the following **JAM implementation code** before | during our implementation: 
  - [PolkaVM](https://github.com/paritytech/polkavm) - on early stage of development as a testing reference
- [x] we have not had private conversations with **other implementers**.
- [x] we have not had **concerns about collusion**.
- [x] we agree to a recorded interview by the *Polkadot Technical Fellowship* on any matter arising from this milestone submission.
- [x] we understand that this milestone submission will need to be ratified with an on-chain remark by the *Polkadot Technical Fellowship* before it can be merged.



## Context

This is Strawberry 🍓. Our Jam implementation is in Go. We filled out the form to work on Jam minutes after the Graypaper was announced and have been working on this code for a long time. We are happy to contribute to Polkadot and turn this vision into executable code.

Our repository is public and fully available for tracking our progress.


## Deliverables


- [x] 1. IMPORTER: State-transitioning conformance tests pass and can import blocks.
- [ ] 2. AUTHOR: Fully conformant and can produce blocks (including networking, off-chain).
- [ ] 3. HALF-SPEED: Conformance and Kusama-level performance (including PVM implementation).
- [ ] 4. FULL-SPEED: Conformance and Polkadot-level performance (including PVM implementation).
- [ ] 5. SECURE: Fully audited.



| Number	| Deliverable	 | Link	                               | Notes                      |
|---------|------------|-------------------------------------|----------------------------|
|1.	| source     | https://github.com/eigerco/strawberry | submission tag `v0.0.5-ct` |
|2.	| release	   | https://github.com/eigerco/strawberry/releases/tag/v0.0.5-ct	 |                            |
|3.	| executable | https://github.com/eigerco/strawberry/releases/download/v0.0.5-ct/strawberry-linux-x86_64|                            |


## Additional Information

This milestone submission applies to graypaper v0.7.2.
