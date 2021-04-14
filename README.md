# YAAP - Yet Another Accessible Plutus (Playground)

A simple and cost-effective deployment of [Plutus Playground](https://playground.plutus.iohkdev.io/) on AWS. Our aim is to enable less infrastructure savvy folks to run their own Plutus deployment, develop, build and contribute to the Cardano ecosystem.

Brought to you by [SALTY](https://saltypool.net/) stakepool, the smart choice in a sea of opportunity.


## Why?

We recieved a question on reddit which made us think - _what would a novice developer wanting to dabble with Plutus need for a minimal setup?_. YAAP isn't aimed to replace the official Plutus [deployment](https://github.com/input-output-hk/plutus/tree/master/deployment) but rather to provide an accessible (and inexpensive) way of setting up a personal instance. Our estimate is that the cost of YAAP vs. a full-official deployment is 1/8.


## Getting Started

The following instructions will help you deploy the Plutus Playground to an AWS EC2 instance in your account where you can start tinkering. Estimated time to deploy is around half an hour.


### Prerequisites

- An AWS Account
- Keen interest in the platform
- [Optional] basic familiarity with AWS and/or Linux


### Estimated Costs

**Overall daily**: $2 

**Breakdown**:
- Assuming use of N. Virginia (`us-east-1`)
- `t3a.large` instance at $0.0752/hour = $1.8
- 30GB of `gp2` volume at $0.10/GB = $0.1

#### Keeping Costs Down

One benefit with cloud is that you can turn off your instances (virtual machines) to minimize costs to only those relating to storage. Once you need the playground again, simply turn the instance on and play.

**TODO** steps for that


## Deployment

**TODO**: insert step by step including Launch Stack link including explanation of parameters

## Acknowledgments

- The IOHK team on their stellar job, specifically on [deployment](https://github.com/input-output-hk/plutus/tree/master/deployment) of Plutus
- [r/CardanoStakePools](https://www.reddit.com/r/CardanoStakePools/) and the broader Cardano community
