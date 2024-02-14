# Proven
Circuit Breaker 2024

## Running instructions
1. Install docker and kurtosis (https://www.kurtosis.com/)
2. Create and run the latest Ethereum kurtosis net locally: `kurtosis --enclave local-eth-testnet run github.com/kurtosis-tech/ethereum-package`
3. Now change the network_params.param to "capella" or "shanghai" to create your local different Ethereum versions.
You would modify the arguments yaml file and modify your enclaves like so: `kurtosis clean -a && kurtosis run --enclave local-eth-testnet github.com/kurtosis-tech/ethereum-package --args-file ~/eth-network-params.yaml`
4. The other option is to modify the arguments directly before creating the enclaves.
