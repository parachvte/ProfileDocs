执行头抬升
====
启用执行头抬升后，打印头会在完成打印层的打印，但是每层最短冷却时间还未结束时，暂停并略微抬起，等待打印层完成冷却。

如果某一层的面积太小，以至于如果按正常打印速度来打印，其打印时间将少于每层最短冷却时间，则实际打印速度会降低，使得该层仍按每层最短冷却时间来打印。但打印速度不会降低到最小打印速度以下。如果按最小打印速度来打印该层所需的时间仍少于每层最短冷却时间，则打印机将在该层打印完成后暂停等待，直到每层最短冷却时间结束。启用执行头抬升后，执行头会在这种面积极小的层打印完成时，略微抬起，进入等待状态。

如果禁用此设置，执行头仍然会在该层打印结束后暂停等待，但喷嘴会与打印件接触。

![When the minimum layer time is reached, the head may lift up](../images/cool_fan_speed.svg)

执行头的抬升高度固定为 3mm。目前尚无设置可以修改这一距离。