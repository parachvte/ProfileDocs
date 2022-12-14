Z 缝对齐
====
你可以通过此设置来选择每个轮廓上 Z 缝所在的位置。通过调整 Z 缝的位置，可以减小 Z 缝对打印件外观的影响，或者让您在后期处理中能更轻松地去除 Z 缝。

Z 缝是开始和结束打印每层轮廓时在 Z 方向上形成的缝隙。使用此设置可以使 Z 缝隐藏在某处或分布在不同位置。

用户指定
----
![User specified](../images/z_seam_type_user.png)

此选项可以手动选择位置。Z 缝将被置于离所选位置最近的角。这样可以将 Z 缝紧密对齐，然后轻松裁掉。您也可以对 Z 缝的位置进行精确控制。

默认情况下会将 Z 缝置于打印件后方的位置。

最短
----
![Shortest](../images/z_seam_type_shortest.png)

此选项让喷嘴在完成前一层打印后的最近位置开始打印本层轮廓，使空跑距离最短，从而节省一点空跑时间。且喷嘴落在轮廓上时的渗出更少， Z 缝也就会稍小一些。

选取靠近喷嘴位置的角时，缝隙角偏好设置仍然有效。在进行了缝隙角偏好设置以后，“最短”选择的可能不是离喷嘴最近的角，而是在满足了角偏好设置以后，选取相对较近的角作为缝隙位置。

随机
----
![Random](../images/z_seam_type_random.png)

此选项会在轮廓边缘随机选择 Z 缝位置。每层中的随机位置都会发生变化，因此 Z 缝将均匀分布在模型周围。因为不同层的 Z 缝没有对齐，在模型上几乎看不见 Z 缝。但模型表面整体会有点不平整。

最尖角
----
![Sharpest corner](../images/z_seam_type_sharpest.png)

按照 [缝隙角偏好设置](z_seam_corner.md) 选择的角偏好，将 Z 缝放置在整个轮廓中最尖锐的角上。这可能会增加空跑距离，但可以通过角偏好设置尽可能隐藏或暴露 Z 缝。