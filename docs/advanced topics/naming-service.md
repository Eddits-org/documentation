---
sidebar_position: 4
---

# ENS configuration
To enable **Ethereum Name System** integration for EDDITS, using [eddits.xyz](eddits.xyz) domain (or use another domain), follow these step:
- Register a domain (currently only .xyz, .luxe and .kred are supported by ENS resolvers, other domains should come soon™️).
- Enable DNSSEC for this domain. Make sure the domain provider you selected supports DNSSEC. This is usually done on your DNS settings dashboard.
- Add a `TXT` entry in DNS configuration with key `_ens.eddits.xyz` (replace eddits.xyz by the desired domain) and value `a=0x1234` (replace `0x1234` by the wallet to own the domain).
- Go to [https://app.ens.domains/name/eddits.xyz](https://app.ens.domains/name/eddits.xyz) (link is for `eddits.xyz`, replace by the desired domain name).
- Connect to the ENS dApp with the owner wallet (the one in `a=0x1234`). And follow the registration process (this induces fees, that can be high as of February 2021 on the mainnet). ENS is also supported by the Ropsten network for testing.

Current owner of the domain `eddits.xyz` is the wallet `0x4DE2ddE8a59126523f92775572A267c27212DF31`, private key known by Kevin Thizy <kevin.thizy@intech.lu> ([Nakasar](https://github.com/nakasar)).
