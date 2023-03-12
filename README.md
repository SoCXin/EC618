# [EC618](https://doc.soc.xin/EC618)

* [eigencomm](http://www.eigencomm.com/): [Cortex-M3](https://github.com/SoCXin/Cortex)
* [L3R3](https://github.com/SoCXin/Level): 204 MHz

## [简介](https://github.com/SoCXin/EC618/wiki)

[EC618](http://www.eigencomm.com/Content/1117083.html) 是上海移芯通信科技2018年发布的更高集成、更低功耗、更优成本、更小尺寸的Cat.1bis芯片，支持3GPP R13/R14 Cat.1bis标准。也是当前最低成本Cat.1模组采用的方案，模组价格低至￥18。

内部集成电源管理芯片，支持WiFi Scan，支持无外部32K晶体，以更低成本支出客户多样化功能需求。

### 关键参数

* 26/102/204 MHz Cortex-M3
* 1MB SRAM + 4MB SiP NOR flash
* 支持供电 3.1v - 4.5v
* 3GPP R14 Cat.1bis standard: DL 10Mbps/ UL 5Mbps
    * LB: 617 MHz - 960 MHz (5, 8, 12, 13, 14, 18, 19, 20, 26, 28, 71)
    * MB: 1710 MHz - 2200 MHz (1, 2, 3, 4, 25, 34, 39, 66)
    * HB: 2300 MHz - 2690 MHz (7, 38, 40, 41)
* SPIx2，I2Cx2，GPIOx32，UARTx3，PWMx6，ADCx4，USIMx2，FEM IOx8，OneWirex1，RTCx1，WDTx1，PWRKEY
* 封装 LFBGA，134balls (6.1*6.1*1.14mm，pitch 0.5mm)

接收灵敏度等射频指标综合水平更优，TDD频段接收灵敏度相对竞品提高2-3dB，低至-101.x dBm，有效提升弱信号下传输成功率

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin/EC618)

[EC618](https://github.com/SoCXin/EC618) 同类Cat.1bis竞品包括：

* [ASR1606](https://github.com/SoCXin/ASR1606)
* [ASR1601](https://github.com/SoCXin/ASR1601)
* [V8850](https://github.com/SoCXin/V8850)
* [UIS8910DM](https://github.com/SoCXin/UIS8910DM)

Cat.4速率更高，上行最高50Mbps、下行最高150Mbps的，但在功耗、集成度、价格方面很难满足部分行业的物联网应用需求，而Cat.1兼顾制式、性能、功耗、成本等优势，尤其成本比Cat.4低近30%。
