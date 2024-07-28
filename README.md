![validators (1)](https://github.com/user-attachments/assets/298b7ddc-4540-4b51-81dc-526e7be43666)
About Movement Labs 

> [MOVEMENTLABS](https://movementlabs.xyz/) focuses on creating a global community of developers building decentralized networks using Move-based blockchains. Their key initiatives include enhancing security, performance, and user experience. They introduced M2, the first MoveVM ZK Layer Two on Ethereum, offering low gas fees and high transaction speeds. Their ecosystem supports various applications, including DeFi, gaming, and NFTs. Movement Labs aims to simplify decentralized app deployment and democratize the growth of Move technology.

> Movement Labs is on a mission to create a global community of Move builders, working together to increase the security, performance, and user experience of building in decentralized networks.

> Movement abstracts away the complexity of decentralized application deployments across modular blockchain networks through instantiations of connected Move Virtual Machines, making it easy for developers and infrastructure providers to integrate across many networks with a single command line interface (CLI).

<a href="https://movementlabs.xyz/" target="_blank"><img src="https://github.com/user-attachments/assets/cdb62800-9a8d-4e9e-848a-46c8278afd24" alt="Website" width="100" height="22"></a>


<a href="https://github.com/movementlabsxyz" target="_blank"><img src="https://github.com/user-attachments/assets/b03b6a35-8eb1-43e6-8831-35e34167f76c" alt="GitHub" width="100" height="22" ></a>


<a href="https://x.com/movementlabsxyz" target="_blank"><img src="https://github.com/user-attachments/assets/2a436f53-54f9-4f15-bf6b-539a5fa24a13" alt="Twitter" width="100" height="22"></a>


<a href="https://discord.gg/Nw93MK6Z" target="_blank"><img src="https://github.com/user-attachments/assets/e072562a-487a-4bc9-ae92-cfa9fa5798c8" alt="Discord" width="100" height="22"></a>

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
