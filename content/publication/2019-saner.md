+++
abstract = "Attacks on transactions of Ethereum could be dangerous because they could lead to a big loss of money. There are many tools detecting vulnerabilities in smart contracts trying to avoid potential attacks. However, we found that there are still many missed vulnerabilities in contracts. Motivated by this, we propose a methodology to reinforce EVM to stop dangerous transactions in real time even when the smart contract contains vulnerabilities. Basically, the methodology consists of three steps: monitoring strategy definition, opcode-structure maintenance and EVM instrumentation. Monitoring strategy definition refers to the specific rule to test whether there is a dangerous operation during transaction execution. Opcode-structure maintenance is to maintain a structure to store the rule related opcodes and analyze it before an operation execution. EVM instrumentation inserts the monitoring strategy, interrupting mechanism and the opcode-structure operations in EVM source code. For evaluation, we implement EVM * on js-evm, a widely-used EVM platform written in javascript. We collect 10 contracts online with known bugs and use each contract to execute a dangerous transaction, all of them have been interrupted by our reinforced EVM * , while the original EVM permits all attack transactions. For the time overhead, the reinforced EVM * is slower than the original one by 20-30%, which is tolerable for the financial critical applications."
authors = ["Fuchen Ma, Ying Fu, Meng Ren, Mingzhe Wang, Yu Jiang"]
date = "2019-02-24"
image_preview = ""
math = true
publication = "In Proceedings of the 2019 IEEE 26th International Conference on Software Analysis, Evolution and Reengineering"
publication_short = "SANER"
selected = false
title = "EVM*: From offline detection to Online Reinforcement for Ethereum Virtual Machine"
url_code = ""
url_dataset = ""
url_pdf = "http://www.wingtecher.com/themes/WingTecherResearch/assets/papers/saner-evm.pdf"
url_project = ""
url_slides = ""
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""

+++

**Citeable as**:


