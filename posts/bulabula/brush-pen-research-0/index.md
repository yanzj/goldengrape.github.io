<!--
.. title: 毛笔字简单研究(0)
.. slug: brush-pen-research-0
.. date: 2018-1-5 22:00:06 UTC+08:00
.. tags:
.. category:
.. link:
.. description:
.. type: text
-->
[未完成, 待更新, 待插图]

最近在看[<黄简讲书法> 的课程](https://www.youtube.com/playlist?list=PL54cajc78e_S8g1Ow2r3epz9GfDLu6iKT), 初级课程已经全部看完了. 这一部分讲的是如何用笔. 说实话黄简老师讲的用笔方法和我小时候学到的完全不同, 比如在转向的时候, 笔尖其实是转了一个小圈再行走.

因为看这种艺术课程, 讲述的技艺和自己之前没有接触过, 难以判断真伪, 所以必须回到基础的物理学去理解. 这是所谓的”first principle thinking”吧.

所以首先对毛笔的运行过程进行一下建模.

<!-- TEASER_END -->
# 简化模型

毛笔还是很复杂的结构, 笔管是圆柱, 以相对简单的散卓笔为例: 笔毛是两种不同硬度的毛构成的, 中心是硬度大弹性好的笔心, 笔心的毛较少; 周边是更柔软的毛作为包被. 如果是韦诞笔, 则结构还要更加复杂.

毛笔在运行过程中:

* 可能保持弹性形变状态, 笔管压向纸面时毛笔笔锋弹性形变, 压力解除时弹性形变几乎完全恢复.
* 也可能进入不可逆的形变, 比如更大的压力压迫到笔腰乃至笔根弯曲, 笔心的笔毛散开, 无法再聚拢.
  * 或者笔心的毛互相绞在一起, 形成绞锋.比如用笔管不绕自己中轴旋转的前提下, 用毛笔画一个360度的圆周, 一定会发生绞锋.

  * 所以有字母O的文字一定不会用毛笔的吧.(此处似乎有反例, 日文中"假名的半浊点")

相对简化的模型是现在用海绵头做成的软笔, 这种笔总是可以保持弹性形变.

# 合理假设

不考虑笔上墨汁损耗的前提下.

写一笔完成之后, 应当使毛笔能够恢复到 __"最大表现力的状态"__ , 也就是笔尖尖锐, 笔心聚拢, 笔尖在笔管的中轴线上, 就是所谓的"聚锋"状态. 这是毛笔的初始状态, 也应当是一笔写完后的理想状态.

如果不能恢复到"聚锋"状态, 那么下一笔能够写出的笔画, 或者能够表现的线条就必然受限. 甚至表现力降低到0, 就需要重新舔笔, 将笔毛捋顺聚拢.

所以所有的用笔方式都是在控制行笔的过程, 使笔尖一直保持在弹性形变内.

# 直线行笔

先不说写"尖锋线", 只讨论"侧锋线". 侧锋是笔管倾斜, 笔尖弯曲, 笔尖指向行进方向的背向.

纸面是一个平面P_0

笔管的中心线L_0, 和笔行进的直线L_1, 这两条直线会形成一个平面P_1.

    要让笔锋走在笔画线条的中央,
    笔管的中心线L_0, 和笔行进的直线L_1所构成的P_1平面
    应当**垂直于**P_0平面(纸面).

这大概是最重要的原理了.

笔尖走在线条的中央, 线的两侧都是光滑的, 而且笔尖受到的摩擦力是对称的, 不容易把笔尖打散.

如果笔管与行进直线构成的平面P_1不与纸面P_0垂直, 那么必然会使笔尖偏向线条的一侧, 形成偏锋的行笔, 这种运动笔尖两侧的摩擦力不同, 更可能使笔尖散开. 造成不可逆的形变.

# 转向
保持线条不断开的前提下:

## 精确解

要在转向时仍然保持笔管与行进直线构成的平面P_1**垂直于**纸面P_0, **精确解只有一个**. 就是将笔管提高, 只有笔尖一点接触纸面, 将笔管中心线L_0先扶正, 使之垂直于纸面P_0, 然后再转向.

由于L_0垂直于P_0, 而行进直线L_1是在纸面内的, 所以不论L_1转向到哪个方向, L_0与L_1形成的平面总是垂直于纸面的.

## 近似解

在小量范围内, 笔尖可以容忍一定的非对称受力而不散开, 相应的, 笔管也可以在一定的倾斜角度和笔管压力范围内变化.

这就是整个书法初级课程中讲的九用了.