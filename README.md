# 硬件敏捷开发与验证方法学研讨

### RISC-V中国峰会同期活动 8月27日下午线上举办

随着数字芯片的设计规模和复杂度越来越大，数字芯片市场的竞争越来越激烈，如何提升数字芯片的开发和验证效率成为业界关注的焦点。虽然各种设计工具、方法学层出不穷，但是一直没有得到业界广泛认可。目前业界普遍采用的还是基于Verilog和VHDL的工具和方法。



近年来随着Chisel、SpinalHDL等等一众新一代HDL的推出，业界逐步感受到新一代HDL在数字芯片设计效率方面的提升。相比Verilog和VHDL，这些新一代HDL在语法表达能力、代码简洁程度、错误检查等方面有不小的提升；相比高阶综合HLS，这些新一代HDL支持RTL级描述能力，在芯片性能的把控方面远超HLS。此外，基于Python，以Cocotb和pyuvm为代表的新一代验证框架的推出，使得验证的周期得到一定程度的缩减，特别是基于Python的验证框架可以复用Python生态丰富的已有工具和模型，大大减少了Golden Reference的工作量。



更重要的是，这些新一代HDL打开了全新的数字芯片敏捷设计和验证的方法学大门。比如多年前业界就有把函数式编程应用于数字芯片设计的尝试，以BlueSpec Haskell为代表，其借鉴了函数式编程语言Haskell的语法特征。不约而同，Chisel和SpinalHDL也是基于函数式编程语言Scala。在数字芯片设计方面，函数式编程已经证明了能极大提高设计效率；在验证方面，函数式编程也具有潜在优势，函数式编程和形式化验证同属形式化方法的范畴，常见函数式编程语言大都已经实现了一些形式化验证的模型检查工具，比如Haskell的QuickCheck和Scala的ScalaCheck，那么基于同一门函数式编程既可以做数字硬件设计，也可以对数字硬件做形式化验证，既提升设计效率，也提升验证效率。业界已经有一些这方面的前沿工作，尝试把函数式编程引入数字芯片验证领域，比如基于Haskell的BlueCheck和BlarneyCheck等。



目前，关于硬件敏捷开发与验证的方法学还在百花齐放，方兴未艾的阶段。特别的，由于数字芯片研发流程长，对三大EDA公司的商业化工具依赖强，如何在现有数字芯片研发流程中落地硬件敏捷开发与验证，是业界非常关注的焦点。本次研讨将邀请业界多位专家分享他们在各自领域的硬件敏捷开发与验证实践经验，为业界提供一次深入探讨和交流的机会，促进硬件敏捷开发与验证方法学的发展与落地。



参与本次研讨的听众可以深入了解业界关于硬件敏捷开发与验证的最前沿探索，诸如：
1. 新一代HDL在数字芯片设计方面的实践经验；
2. 新一代验证框架在数字芯片验证方面的实践经验；
3. 硬件敏捷开发与验证和已有芯片研发流程结合的实践经验。

## 议程：


本次研讨会于8月27日下午线上举行，具体议程如下：
| 时间 | 演讲题目 | 分享嘉宾 | 嘉宾工作单位 |
| :-----:| :---- | :----: | :---- |
| 13:15-13:30 | 开场介绍 | 王 璞 | 达坦科技联合创始人 |
| 13:30-14:15 | 硬件敏捷验证方法 | 赖晓铮 | 华南理工大学计算机学院副教授 |
| 14:15-15:00 | 香山处理器敏捷开发与验证实践 | 王凯帆 | 中科院计算所博士 |
| 15:00-15:45 | 通过Chainsaw实现硬件算子敏捷开发 | 李天瑞 | 中山大学电子工程系博士 |
| 15:45-16:30 | 基于Scala的DSL语言在芯片开发中的应用 | 郭继经 | 小米SoC设计专家 |
| 16:30-17:15 | NaxRiscv CPU : Introduction and Extension Demonstration | Charles Papon | SpinalHDL Creator |

线上直播链接：
https://t.elecfans.com/live/2113.html








感兴趣的听众可以添加群主二维码加入微信讨论群，添加时请注明硬件敏捷开发和验证方法学研讨。

<img src="bar_code.jpg" alt="群主二维码" width="25%"/>
