外壁擦嘴长度
====
启用此设置，喷嘴将在每个外壁打印结束时空跑一小段距离，擦拭轮廓使其闭合。

![A small travel move after completing the outer wall](../images/wall_0_wipe_dist.png)

此设置目的是降低接缝的可见性。通常，喷嘴在刚打印完外壁时，出料口会挂有少量余料。通过一小段空跑，喷嘴可以将外壁轮廓的终点与起点粘连起来，闭合接缝。

虽然接缝无法完全消失，但通过短距离喷嘴擦拭，打印效果应稍有改善。若将外壁擦嘴长度设置过高，不仅无法进一步缩小轮廓接缝，还会导致喷嘴跑出接缝之外。过长的空跑距离会导致喷嘴腔内耗材漏空，造成喷嘴在开始下一层打印时挤出不足。

若启用[滑行](../experimental/coasting_enable.md)，则喷嘴在轮廓即将完成打印之际停止挤出，产生的效果与此设置基本相反。
