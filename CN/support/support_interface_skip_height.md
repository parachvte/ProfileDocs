支撑接触面分辨率
====
在确定支撑接触面的打印位置时，Luban 需要检查支撑在 Z 轴方向上与模型接触的位置。此参数决定了 Luban 在检查位置时的分辨率。

调高此参数的值会降低 Luban 进行检查时的分辨率，从而加快切片速度。但是，如果此参数的值过大，而支撑上方或下方的模型区域面积又非常小，那么 Luban 在确定支撑接触面的位置时就可能会跳过这些部位。如果模型结构非常小，Luban 进行的检查就可能直接跳过这些结构，也就不会在这些结构下方打印支撑接触面。