# HoRStify
HoRStify is a smart contract analyis tool for dependency based 2-safety security properties. The research was conducted at [Max Planck Institute for Security and Privacy](https://www.mpi-sp.org/) and [Saarland University](https://saarland-informatics-campus.de/).

## Paper Abstract
The cryptocurrency Ethereum is the most widely used execution platform for smart contracts. Smart contracts are distributed applications, which govern financial assets and, hence, can implement advanced financial instruments, such as decentralized exchanges or autonomous organizations (DAOs). Their financial nature makes smart contracts an attractive attack target, as demonstrated by numerous exploits on popular contracts resulting in financial damage of millions of dollars. This omnipresent attack hazard motivates the need for sound static analysis tools, which assist smart contract developers in eliminating contract vulnerabilities a priori to deployment. Vulnerability assessment that is sound and insightful for EVM contracts is a formidable challenge because contracts execute low-level bytecode in a largely unknown and potentially hostile execution environment. So far, there exists no provably sound automated analyzer that allows for the verification of security properties based on program dependencies, even though prevalent attack classes fall into this category. In this work, we present HoRStify, the first automated analyzer for dependency properties of Ethereum smart contracts based on sound static analysis. HoRStify grounds its soundness proof on a formal proof framework for static program slicing that we instantiate to the semantics of EVM bytecode. We demonstrate that HoRStify is flexible enough to soundly verify the absence of famous attack classes such as timestamp dependency and, at the same time, performant enough to analyze real-world smart contracts. 

## Tool
Soon at GitHub!

## Publications
- [HoRStify Research Paper](https://www.computer.org/csdl/proceedings-article/csf/2023/219200a347/1Mv21Jp8HyE) to be presented at [IEEE CSF 2023](https://www.ieee-security.org/TC/CSF2023/) in Dubrovnik, Croatia.
- Short version presented at [LPAR 2023](https://easychair.org/smart-program/LPAR2023/index.html) in Manizales, Colombia.
- [Full Version with technical details](https://arxiv.org/abs/2301.13769) at arXiv

### Citation
```
@inproceedings{holler2023horstify,
  title={HoRStify: Sound Security Analysis of Smart Contracts},
  author={Holler, Sebastian and Biewer, Sebastian and Schneidewind, Clara},
  booktitle={2023 2023 IEEE 36th Computer Security Foundations Symposium (CSF)(CSF)},
  pages={347--362},
  year={2023},
  organization={IEEE Computer Society}
}
```
