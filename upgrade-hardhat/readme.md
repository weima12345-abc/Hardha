1. 从Box升级到BoxV2
2. 代理合约从指向Box转为指向BoxV2

1.  手动部署代理
2.  hardhat-deploy built-in proxies
<!-- 3.  openzeppelin upgrades plugin -->

hardhat部署合约 设置Proxy属性中合约和admin

deploying "BoxProxyAdmin" (tx: 0x63f6747b97c40eb8d26459caf761072d973d195d5db91bf025f4e8c44e76479b)...: deployed at 0x5FbDB2315678afecb367f032d93F642f64180aa3 with 886443 gas
deploying "Box_Implementation" (tx: 0xf58179890d05516b14fbcd4268646668984c36f5a30d83b1352dc917018ec09b)...: deployed at 0xe7f1725E7734CE288F8367e1Bb143E90bb3F0512 with 148423 gas
deploying "Box_Proxy" (tx: 0x3e89eaa8d7a06c718ab6eac4f0c332170a3791ee89bd62888d196fbc5987bd0a)...: deployed at 0x9fE46736679d2D9a65F0992F2272dE9f3c7fa6e0 with 544341 gas
deploying "BoxV2" (tx: 0x466b92ba75163ee45b05021954d70a84a33886a4491a62843b9ba03eb723fb58)...: deployed at 0xCf7Ed3AccA5a467e9e704C703E8D87F634fB0Fc9 with 198607 gas

Account #0: 0xf39fd6e51aad88f6f4ce6ab8827279cfffb92266 (10000 ETH)
Private Key: 0xac0974bec39a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80

Account #1: 0x70997970c51812dc3a010c7d01b50e0d17dc79c8 (10000 ETH)
Private Key: 0x59c6995e998f97a5a0044966f0945389dc9e86dae88c7a8412f4603b6b78690d
