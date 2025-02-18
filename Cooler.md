# 散热器

最受欢迎的液体冷却器是一体化(AIO)。它们是预先组装好的闭环套件。如果你不确定应该购买哪种AIO套件，YouTube频道GamersNexus提供了非常全面的评论。套件通过内部USB 2.0头连接到你的主板。当创建USB映射时，您需要考虑这一点，否则您将无法控制它。

不包括其他的和来自Asetek的第一代AIO套件，它们将具有挥发性或持久性记忆:

1. NZXT和Corsair具有易失性内存，只要电源模块通电就会持续存在(I)。
2. EVGA套件有持久的内存。使用Windows中的软件更改设置可以让你写入内存。如果电源模块下电(O)，设置不会丢失。

几乎所有的内部硬件都是由Asetek提供的。用主板是不可能控制它们的。他们不是这种方式而设计的。三针连接器的CPU头是只有报告泵和散热器风扇的速度。这是一种单向通信。控制这些变量的唯一方法是通过USB头与软件。其他AIO套件，不是基于阿斯泰克有能力控制通过主板通过4针CPU头。曜越科技和深度酷是一些例子。

GitHub上有一些基于Python的工具可以控制你的套件，但这通常是不必要的，因为在Windows中设置一次就足够了，直到关闭电源。基于Python的[liquidctl](https://github.com/jonasmalacofilho/liquidctl) 是为macOS开发的，适用于NZXT, EVGA和Corsair的一些型号。

AIO套件和macOS之间不存在真正的兼容性问题。无论启动的是什么操作系统，只要初始设置是Windows，它们都可以工作。
