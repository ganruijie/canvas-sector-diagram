# canvas-sector-diagram
##使用canvas绘制扇形分布图
----------------------------------------------------
##方法：
-1.确定绘制区域（不能使用css设置height、width来确定）
-2.将json格式的数据保存在数组中
-3.设置开始位置
-4.使用arc函数进行画圆弧
-5.使用beginPath开启新的路径，避免重叠