# Bepolia (Sepolia Beaconchain)

TTD: `17000000000000000`

GENESIS_FORK_VERSION: `0x90000069`

ENR for consensus clients:
```yaml
# EF bootnode
  - "enr:-Iq4QMCTfIMXnow27baRUb35Q8iiFHSIDBJh6hQM5Axohhf4b6Kr_cOCu0htQ5WvVqKvFgY28893DHAg8gnBAXsAVqmGAX53x8JggmlkgnY0gmlwhLKAlv6Jc2VjcDI1NmsxoQK6S-Cii_KmfFdUJL2TANL3ksaKUnNXvTCv1tLwXs0QgIN1ZHCCIyk"
  - "enr:-KG4QE5OIg5ThTjkzrlVF32WT_-XT14WeJtIz2zoTqLLjQhYAmJlnk4ItSoH41_2x0RX0wTFIe5GgjRzU2u7Q1fN4vADhGV0aDKQqP7o7pAAAHAyAAAAAAAAAIJpZIJ2NIJpcISlFsStiXNlY3AyNTZrMaEC-Rrd_bBZwhKpXzFCrStKp1q_HmGOewxY3KwM8ofAj_ODdGNwgiMog3VkcIIjKA"
# Teku bootnode
    - "enr:-KG4QMJSJ7DHk6v2p-W8zQ3Xv7FfssZ_1E3p2eY6kN13staMObUonAurqyWhODoeY6edXtV8e9eL9RnhgZ9va2SMDRQMhGV0aDKQS-iVMYAAAHD0AQAAAAAAAIJpZIJ2NIJpcIQDhAAhiXNlY3AyNTZrMaEDXBVUZhhmdy1MYor1eGdRJ4vHYghFKDgjyHgt6sJ-IlCDdGNwgiMog3VkcIIjKA"
 ```


Altair will fork at epoch 50 and merge epoch at 100.
```yaml
genesis_time: 1655733600
genesis_state_root: 0xfb9afe32150fa39f4b346be2519a67e2a4f5efcd50a1dc192c3f6b3d013d2798
genesis_latest_block_header:
  slot: 0
  proposer_index: 0
  parent_root: 0x0000000000000000000000000000000000000000000000000000000000000000
  state_root: 0x0000000000000000000000000000000000000000000000000000000000000000
  body_root: 0xccb62460692be0ec813b56be97f68a82cf57abc102e27bf49ebf4190ff22eedd
genesis_block_root_no_state_root: 0xeade62f0457b2fdf48e7d3fc4b60736688286be7c7a3ac4c9a16a5e0600bd9e4
genesis_block_root_updated_state_root: 0xfb9b64fe445f76696407e1e3cc390371edff147bf712db86db6197d4b31ede43
genesis_validators_root: 0xd8ea171f3c94aea21ebc42a1ed61052acf3f9209c00e4efbaaddac09ed9b8078
genesis_validators_count: 1570
genesis_active_validators_count: 1570
genesis_total_active_stake_gwei: 50240000000000
genesis_total_balance_gwei: 1570000000000000000
eth1_data:
  deposit_root: 0xd70a234731285c6804c2a4f56711ddb8c82c99740f207854891028af34e27e5e
  deposit_count: 0
  block_hash: 0x491ebac1b7f9c0eb426047a495dc577140cb3e09036cd3f7266eda86b635d9fa
deposit index: 0
genesis_fork_version: 0x90000069
genesis_fork_digest: 0xa8fee8ee
pre_genesis_fork_digest: 0xd3010778
```

Key <> client team mapping:
```
EF: 0-100
Nethermind: 100-199
Besu: 200-299
Erigon: 300-399
Lighthouse: 400-499
Teku: 500-599
Nimbus: 600-699
Lodestar: 700-799
Prysm: 800-899
Attestant/Vouch: 900-999
q9f: 1000-1099
Lightclient: 1100-1199
Kiln.fi: 1200-1299
Ralexstokes: 1300-1399
Simply staking: 1400-1499
EF Security: 1500-1549
Blox staking: 1573-1672
```
