<p align="center"><a href="https://github.com/eth-clients/goerli">Goerli (2019)</a> | <strong>Sepolia (2021)</strong> | <a href="https://github.com/eth-clients/holesky">Holešky (2023)</a></p>
<p align="center"><img src="./assets/sepolia.png" /></p>

# Sepolia Testnet
The `--sepolia` cross-client proof-of-authority testnet configuration. Sepolia replaced the sunset Rinkeby and Kovan networks and is the perfect place to test decentralized applications, smart contracts, and other EVM functionality.

* https://sepolia.ethpandaops.io/

## Meta data: Sepolia

- Name: **Sepolia**
- Flag: `--sepolia`
- Stage: _launched_
  - PoW Engine: `ethash`
  - Difficulty: `131072`
  - Genesis hash: `0x25a5cc106eea7138acab33231d7160d69cb777ee0c2c553fcddf5138993e6dd9`
  - Network ID: `11155111`
  - Chain ID: `11155111`
- EVM Version: `London`
  - Homestead: `0` (block number)
  - Byzantium: `0` (block number)
  - Constantinople: `0` (block number)
  - Petersfork: `0` (block number)
  - Istanbul: `0` (block number)
  - Berlin: `0` (block number)
  - MuirGlacier: `0` (block number)
  - London: `0` (block number)
  - Shanghai: `1677557088` (unix time)
  - Cancun: `1706655072` (unix time)
- Bootnodes:
  - `enode://9246d00bc8fd1742e5ad2428b80fc4dc45d786283e05ef6edbd9002cbc335d40998444732fbe921cb88e1d2c73d1b1de53bae6a2237996e9bfe14f871baf7066@18.168.182.86:30303`
  - `enode://ec66ddcf1a974950bd4c782789a7e04f8aa7110a72569b6e65fcd51e937e74eed303b1ea734e4d19cfaec9fbff9b6ee65bf31dcb50ba79acce9dd63a6aca61c7@52.14.151.177:30303`
- Status Dashboard:
  - https://stats.noderpc.xyz
- Block Explorers:
  - https://sepolia.otterscan.io
  - https://sepolia.etherscan.io
  - https://eth-sepolia.blockscout.com/
- Faucets:
  - https://grabteeth.xyz
  - https://sepolia-faucet.pk910.de/ (PoW powered)
  - https://faucet-sepolia.rockx.com/
  - https://faucet.quicknode.com/ethereum/sepolia
  - https://sepoliafaucet.com/ (Alchemy's free faucet)
  - https://learnweb3.io/faucets/sepolia (LearnWeb3's free faucet)
  - https://infura.io/faucet
  - https://unitap.app/gastap
- Open RPC Endpoints:
  - https://rpc.sepolia.online
  - https://www.sepoliarpc.space
  - https://rpc.sepolia.org (status: https://status.sepolia.org)
  - https://rpc-sepolia.rockx.com
  - https://rpc.bordel.wtf/sepolia

### Resources

- [ethereum/go-ethereum#23730: cmd/geth: add support for sepolia testnet](https://github.com/ethereum/go-ethereum/pull/23730)
- [hyperledger/besu#2933: Add Sepolia configs and address baseFee at genesis case](https://github.com/hyperledger/besu/pull/2933)
- [ethereum/pm#460: Post-Merge testnets](https://github.com/ethereum/pm/issues/460)

## Meta-data: Bepolia

Bepolia Testnet is the beacon-chain to be merged with the Sepolia testnet.

- Merge TTD: `17000000000000000`
- GENESIS_FORK_VERSION: `0x90000069`
- Genesis Time: `1655733600` (Jun-20-2022 02:00:00 PM +UTC)
- Genesis Fork Version: `0x90000069`
- Altair fork epoch: `50`
- Bellatrix fork epoch: `100`
- Capella fork epoch: `56832`
- Fork Digest: `0xa8fee8ee` (`0xd3010778` pre-genesis fork digest)
- Initial State Root: `0xfb9afe32150fa39f4b346be2519a67e2a4f5efcd50a1dc192c3f6b3d013d2798`
- Genesis Block Root:
	- Without state root update: `0xeade62f0457b2fdf48e7d3fc4b60736688286be7c7a3ac4c9a16a5e0600bd9e4`
	- With state root update: `0xfb9b64fe445f76696407e1e3cc390371edff147bf712db86db6197d4b31ede43`
- Genesis Validators Root: `0xd8ea171f3c94aea21ebc42a1ed61052acf3f9209c00e4efbaaddac09ed9b8078`
- Genesis Validators Count: `1570`
- Eth1 Data:
  - Deposit Root: `0xd70a234731285c6804c2a4f56711ddb8c82c99740f207854891028af34e27e5e`
  - Deposit Count: `0`
  - Block Hash: `0x491ebac1b7f9c0eb426047a495dc577140cb3e09036cd3f7266eda86b635d9fa`

ENR for consensus clients:

```yaml
# EF bootnode
  - "enr:-Iq4QMCTfIMXnow27baRUb35Q8iiFHSIDBJh6hQM5Axohhf4b6Kr_cOCu0htQ5WvVqKvFgY28893DHAg8gnBAXsAVqmGAX53x8JggmlkgnY0gmlwhLKAlv6Jc2VjcDI1NmsxoQK6S-Cii_KmfFdUJL2TANL3ksaKUnNXvTCv1tLwXs0QgIN1ZHCCIyk"
  - "enr:-KG4QE5OIg5ThTjkzrlVF32WT_-XT14WeJtIz2zoTqLLjQhYAmJlnk4ItSoH41_2x0RX0wTFIe5GgjRzU2u7Q1fN4vADhGV0aDKQqP7o7pAAAHAyAAAAAAAAAIJpZIJ2NIJpcISlFsStiXNlY3AyNTZrMaEC-Rrd_bBZwhKpXzFCrStKp1q_HmGOewxY3KwM8ofAj_ODdGNwgiMog3VkcIIjKA"
# Teku bootnode
    - "enr:-KG4QMJSJ7DHk6v2p-W8zQ3Xv7FfssZ_1E3p2eY6kN13staMObUonAurqyWhODoeY6edXtV8e9eL9RnhgZ9va2SMDRQMhGV0aDKQS-iVMYAAAHD0AQAAAAAAAIJpZIJ2NIJpcIQDhAAhiXNlY3AyNTZrMaEDXBVUZhhmdy1MYor1eGdRJ4vHYghFKDgjyHgt6sJ-IlCDdGNwgiMog3VkcIIjKA"
 ```

## Contribute

Run a node, contribute services, and [report issues](https://github.com/goerli/sepolia/issues).
