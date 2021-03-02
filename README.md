# Bridging Guild [![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/BridgingGuild/community)

This is the bridge makers' guarantee to the users that they are informed symmetrically. Also a proof of each others willingness to collaborate and bridge the bridges :).

## Cooperation Space
- discussions: https://gitter.im/BridgingGuild/community
- common types, interfaces, APIs
    - interface with relayers
    - interchanging relayers
- collaborative features comparison table on GSheets: https://docs.google.com/spreadsheets/d/1N8GRDWghm83EhH_q5vWS-RT75rD8kDgw1kTltZmA0I0/edit?usp=sharing
- inter-bridge applications

## Projects

### EVM <-> EVM support (& more)

- ChainBridge - https://github.com/ChainSafe/ChainBridge
- TokenBridge - https://github.com/poanetwork/tokenbridge
- GoldenGate - https://github.com/loredanacirstea/goldengate

### Other Bridges
(not EVM <-> EVM)

- https://github.com/near/rainbow-bridge
- https://github.com/KyberNetwork/bridge_eos_smart_contracts
- https://github.com/certusone/wormhole
- https://github.com/renproject/ren/wiki
- https://github.com/keep-network/tbtc
- https://github.com/enigmampc/EthereumBridge

| Bridge           | Outbound           | Inbound            |
|------------------|--------------------|--------------------|
| wBTC & renBTC    | Trusted Federation | Trusted Federation |
| tBTC             | Stateless SPV      | Bonded Federation (validity proofs) |
| Custom IBC       | Relayed SPV        | Relayed SPV        |
| Rainbow Bridge   | Relayed SPV        | Bonded Federation (fraud proofs) |
| Wormhole (today) | Trusted Federation | Trusted Federation |
| Wormhole (goals) | Relayed SPV        | Bonded Federation (fraud proofs) |
| xDAI             | Trusted Federation | Trusted Federation |
| eth2 deposit     | Trusted Federation (open, dynamic) | n/a |
--------------------------------------------------------------

(Table by James Prestwich https://youtu.be/b0mC-ZqN8Oo)


## Members

- Gregory Markou @GregTheGreek /github
- Loredana Cirstea @loredanacirstea / github

## Invited members:

- Gregory Markou (ChainBridge)
- Igor Barinov (TokenBridge)
- Loredana Cirstea (GoldenGate)

by https://twitter.com/lorecirstea/status/1365702996630331393
