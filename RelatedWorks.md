## Pioneer: verifying code integrity and enforcing untampered code execution on legacy systems

>摘要
>* 服务器不受信任
>* 不需要硬件支持
>* 可验证代码执行

>三种代码篡改方式
>* 修改源码
>* 执行其他代码
>* 修改代码运行时状态

>主要手段
>* Pioneer包含一个verification function，能做到self-checking
>* 如果校验计算被篡改，校验计算将会显著减慢

### VRASED: A Verified Hardware/Software Co-Design for Remote Attestation
>* 形式化验证的远程证明
>* 针对嵌入式设备
>* 安全级别与基于硬件的远程证明相当

### A Taxonomy of Software Integrity Protection Techniques
>* 最终人攻击——用户篡改应用程序
>* 提出了对现有防御方案的分类法

### SμμV—The Security MicroVisor: A Formally-Verified Software-Based Security Architecture for the Internet of Things
>* IoT设备安全性
>* 基于软件的内存隔离
>* 基于软件的远程认证

### Establishing Software Root of Trust Unconditionally
>* 无条件的信任根(无秘密，无可信硬件模块，无指令和运算能力限制)
>* 需要真随机数

### FPGA-Based Remote-Code Integrity Verification of Programs in Distributed Embedded Systems

>基本信息
>* IEEE Transactions on Systems, Man, and Cybernetics, Part C (Applications and Reviews)
>* 2012
>* 9

>摘要
>* 可重配置计算(reconfigurable computing)
>* 使用FPGA进行完整性验证, FPGA可远程更新
>* 没有提供软件安全方案，是近三年的总结

## New results for timing-based attestation

### HEALED: HEaling & Attestation for Low-End Embedded Devices
>* 第一个嵌入式设备远程认证方案
>* 既可以检测软件漏洞，也可以对受感染设备消毒
>* 使用了梅克尔哈希树(Merkle Hash Trees)

### Towards Systematic Design of Collective Remote Attestation Protocols
>* 多个嵌入式设备的集体远程认证

### US-AID: Unattended Scalable Attestation of IoT Devices
>* 多个嵌入式设备的集体远程认证
>* 使用密钥交换和不存在证明(Proofs-of-non-Absence)完成连续性的网络内认证

### DIAT: Data Integrity Attestation for Resilient Collaboration of Autonomous Systems
>* a novel approach that allows to verify the correctness of data by attesting the correct generation as well as processing of data using control-flow attestation
>* 使网络中的设备能够进行安全交互
>* 数据在发出设备上生成和处理期间都不会被更改
>* 嵌入式设备中的软件被分为不同模块，仅涉及到数据处理模块的软件才会被验证

### AAoT: Lightweight attestation and authentication of low-resource things in IoT and CPS
>* 为嵌入式设备提供软件完整性、相互身份验证和防篡改功能
>* 基于物理不可克隆(physical unclonable functions)的内存填充
>* 基于快遍历的校验和
>* 伪随机函数
>* 反向模糊提取器(reverse fuzzy extractor)和随机数生成器

### LiteHAX: Lightweight Hardware-Assisted Attestation of Program Execution
>* 硬件辅助远程证明
>* 可同时检测控制流攻击和DOP攻击
>* 持续跟着在远程设备上执行的程序的控制流和数据流，并将他们报告给受信任的验证方

### Scalable and Forward Secure Network Attestation With Privacy-Preserving in Cloud-Assisted Internet of Things
>* 允许任何人公开集体验证嵌入式设备
>* 证明者身份信息不会泄露给验证者

### Distributed Detection of Sensor Worms Using Sequential Analysis and Remote Software Attestations

>基本信息
>* IEEE Access
>* 2017
>* 4

>摘要
>* 检测传感器网络(sensor networks)中的蠕虫传播
>* 监测蠕虫传播时触发的特殊网络流量


## Leakage

### ReDABLS: revisiting device attestation with bounded leakage of secrets