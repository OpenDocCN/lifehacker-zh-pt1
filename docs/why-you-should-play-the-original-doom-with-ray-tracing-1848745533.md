# 为什么你应该用光线追踪播放原版的《毁灭战士》

> 原文：<https://lifehacker.com/why-you-should-play-the-original-doom-with-ray-tracing-1848745533>

当你听到“光线追踪”这个词时，你的脑海中很可能浮现出尖端游戏的画面。光线跟踪直到 2018 年才进入主流 PC GPUs，只有最新一代的游戏机支持这项技术，所以直到最近，它才成为大多数游戏社区的考虑因素。尽管如此，复古游戏仍然可以受益于光线追踪——即使是像*末日*这样近 30 年的经典。

Watch

对于外行来说，光线追踪是一种渲染过程，与传统的游戏内照明方法相比，它在游戏中产生的比更真实的闪电条件。基本上是从玩家的角度发出【rays；如果光线击中一个物体，它就会向近光源发出光线，所以它知道这个物体应该如何被照亮。这与让计算机追踪该区域所有光源的光线的方法相反，因为在任何给定的时刻，你只需追踪正在处理的光线。

回到手头的主题:开发者 sultim-t 已经创建了一个版本的 *Doom* ，它以一种非常酷的方式利用了光线追踪。提醒你一下，并不是 franchose 中较新的条目之一:Sultim-t 已经在很久以前的 1993 年的 *Doom* 的前三集中添加了光线追踪。

正如你在下面的视频中看到的，结果是惊人的。游戏本身保持不变像素化的杰作，你可能已经知道和喜欢，但增加的光线追踪真的使环境流行。黑暗的房间更怪异，爆炸和更具爆炸性，熔岩和等离子体发出红色和紫色的荧光，mod 为 30 岁的游戏注入了新的生命。

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-i2Ld9YNUWls&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-i2Ld9YNUWls&start=0) 

为了亲自检验效果，你需要一个 Nvidia GPU 。(希望我们将来会看到 AMD GPU 支持。)你还需要一个原*末日*的. wad 文件。你可以从像 [Steam](https://store.steampowered.com/app/2280/Ultimate_Doom/) 或 [GOG](https://www.gog.com/game/the_ultimate_doom?pp=35e995c107a71caeb833bb3b79f9f54781b33fa1) 这样的商店购买的*终极毁灭*版本中获取这个文件，后者在撰写本文时销量还不错。

如果你有 Nvidia GPU，设置游戏相对简单:首先， [下载并解压在 sultim-t 的 GitHub 页面找到的 prboom-rt.zip 文件](https://github.com/sultim-t/prboom-plus-rt/releases) 到一个新的空白文件夹。将你的 DOOM.wad 文件放入这个文件夹，然后运行“prboom-plus”应用程序开始运行。

不幸的是，即使有了 NVIDIA GPU，一些用户也会遇到问题，包括我自己—当我试图运行游戏时，我会遇到一个“信号 11”错误。这不一定是 sultim-t 的 mod，的问题，因为这个信号 11 错误 [似乎是 PrBoom 应用](https://github.com/sultim-t/prboom-plus-rt/issues/12) 的遗留问题。幸运的话，你的机器不会经历这个问题，你可以在*末日*的走廊里奔跑，享受光线追踪的荣耀。

这个并不是唯一受益于光线追踪模型的复古游戏。Sultim-t 还增加了光线追踪到 [*半衰期*](https://www.youtube.com/watch?v=SsteDE8h6jc) 和 [*严重 Sam TFE*](https://www.youtube.com/watch?v=mFUwx8zLKfE) 。玩这些游戏中的任何一个都会向你展示光线追踪能做什么，甚至是不发生在地狱的游戏。