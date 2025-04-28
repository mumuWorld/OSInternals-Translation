
## 2. E Pluribus Unum: The *OS Architecture

### 原文
> The architecture of Apple's OSes is fairly complex, and is the product of a long evolution.  
> Even if one discounts the prehistoric MacOS 9 origins and consider its progenitor to be  
> NeXTSTEP, one finds significant enhancements, across all areas of the system, from Objective-C  
> 2.0, to changes in the Mach and BSD layers with new traps and proprietary system calls.  
> The evolution became more diversified with the introduction of iOS (then: iPhoneOS). Here  
> was the first time that Apple adapted their operating system to deal with mobile devices. With  
> the advent of TVOS, WatchOS and recently the "eOS" (which drives the MacBook Pro's Touch  
> Bar), this diversification has grown and widened, though it still leaves more commonalities than  
> differences.  
> This chapter explores the architecture of Apple's OSes, layer by layer. Rather than adopting  
> Apple's "official" perspective, which is prevalent in their documentation, it suggests a less elegant  
> (but, in some respect, more accurate) rendition of the architecture, highlighting not just the  
> layered structure, but also the divergences between MacOS, iOS, and the iOS variants, where applicable.

### 翻译
> 苹果操作系统的架构相当复杂，是长期演化的产物。即使我们忽略史前的 MacOS 9 起源，并认为它的前身是 NeXTSTEP，  
> 仍然可以发现，系统各个领域的显著提升，从 Objective-C 2.0 到 Mach 和 BSD 层的变化，新的陷阱和专有系统调用。  
> 随着 iOS（当时是 iPhoneOS）的引入，演化变得更加多样化。苹果首次将其操作系统调整以应对移动设备。随着 TVOS、WatchOS 和最近的“eOS”（为 MacBook Pro 的 Touch Bar 提供驱动程序）的出现，这种多样化不断扩大，  
> 尽管如此，仍然有更多的相似之处，而不是差异。  
> 本章将逐层探讨苹果操作系统的架构。与苹果文档中普遍采用的“官方”视角不同，本章采用了一种不那么优雅（但从某些方面更准确）的架构表现方式，  
> 强调不仅是分层结构，还探讨了 MacOS、iOS 及其变种之间的差异。
