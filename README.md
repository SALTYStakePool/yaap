# YAAP - Yet Another Accessible Plutus (Playground)

A simple and cost-effective deployment of [Plutus Playground](https://playground.plutus.iohkdev.io/) on AWS. Our aim is to enable less infrastructure savvy folks to run their own Plutus deployment, develop, build and contribute to the Cardano ecosystem.

Brought to you by [SALTY](https://saltypool.net/) stakepool, the smart choice in a sea of opportunity.


## Why?

We recieved a question on reddit which made us think - _what would a novice developer wanting to dabble with Plutus need for a minimal setup?_. YAAP isn't aimed to replace the official Plutus [deployment](https://github.com/input-output-hk/plutus/tree/master/deployment) but rather to provide an accessible (and inexpensive) way of setting up a personal instance. Our estimate is that the cost of YAAP vs. a full-official deployment is 1/8.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.


### Prerequisites

- An AWS Account
- Keen interest in the platform
- [Optional] basic familiarity with AWS and/or Linux


### Estimated Costs

**Overall**: $60 

**Breakdown**:
- Assuming use of N. Virginia (`us-east-1`)
- `t3a.large` instance, 740 hours/month at $0.0752/hour = $55.7
- 30GB of `gp2` volume at $0.10/GB = $3


## Deployment

**TODO**: insert step by step including Launch Stack link including explanation of parameters

## Acknowledgments

- The IOHK team on their stellar job, specifically on [deployment](https://github.com/input-output-hk/plutus/tree/master/deployment) of Plutus
- [r/CardanoStakePools](https://www.reddit.com/r/CardanoStakePools/) and the broader Cardano community
