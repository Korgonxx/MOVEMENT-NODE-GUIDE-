![validators (1)](https://github.com/user-attachments/assets/298b7ddc-4540-4b51-81dc-526e7be43666)
About Movement Labs 

> [MOVEMENTLABS](https://movementlabs.xyz/) focuses on creating a global community of developers building decentralized networks using Move-based blockchains. Their key initiatives include enhancing security, performance, and user experience. They introduced M2, the first MoveVM ZK Layer Two on Ethereum, offering low gas fees and high transaction speeds. Their ecosystem supports various applications, including DeFi, gaming, and NFTs. Movement Labs aims to simplify decentralized app deployment and democratize the growth of Move technology.

> Movement Labs is on a mission to create a global community of Move builders, working together to increase the security, performance, and user experience of building in decentralized networks.

> Movement abstracts away the complexity of decentralized application deployments across modular blockchain networks through instantiations of connected Move Virtual Machines, making it easy for developers and infrastructure providers to integrate across many networks with a single command line interface (CLI).

   <p align="left">
      <a href="https://movementlabs.xyz/">
        <img alt="Visit Movement Website" src="https://img.shields.io/badge/WEBSITE-red"> 
      </p>
           <p align="left">
      <a href="https://github.com/movementlabsxyz">
         <img alt="Github" title="Movement Github" src="https://img.shields.io/badge/GITHUB-yellow">
      </p>
        <p>
           <a href="https://x.com/movementlabsxyz">
         <img alt="Twitter" title="Follow Movementon X" src="https://img.shields.io/badge/TWITTER-blue">
        </p>
     <p>
         <a href="https://discord.gg/Nw93MK6Z">
         <img alt="Discord" title=" Join Movement" <img alt="Static Badge" src="https://img.shields.io/badge/DISCORD-green">
     </p>

# Hardware Requirements

```yaml
- **Memory**: 16 GB RAM
- **CPU**: 8 CPU (or vCPU)
- **Disk**: 128 GB NVME SSD
- **Bandwidth**: 100mbps Gbps for Download / Upload

```

# Installaion
## Install the Movement CLI:

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/movemntdev/M1/main/scripts/install.sh) --latest
```
## Add movement to .bashrc 
```
export PATH="/root/.movement/bin:$PATH"
source ~/.bashrc
```
## Install the testnet artifacts:
```
movement manage install m1 testnet
```
## Start the subnet service:
```
movement ctl start m1 testnet
```


# NOTE CURRENLY TESTNET IS NOT LIVE YET WE WILL UPDATE THE GUIDE ASAP WHENEVER TESTNET GOES LIVE !!!!!!!
