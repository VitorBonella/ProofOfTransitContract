Example network running a proof of transit protocol under PolKA.

Config files, example linear topology and scripts to run the network are provided.

This is meant to run under a mininet-wifi VM. See [preparing the environment](https://github.com/nerds-ufes/polka?tab=readme-ov-file#preparing-the-environment)
1. Setup VM
2. Clone this repository
3. `cd` into [polka-example/polka]
4. run `make && sudo python ../run_linear_topology.py` (`sudo` is needed to manage ifaces)

From [Henriquelay/polka-halfsiphash](https://github.com/Henriquelay/polka-halfsiphash), a fork from [nerds-ufes/polka](https://github.com/nerds-ufes/polka)
