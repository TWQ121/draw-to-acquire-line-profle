# draw-to-acquire-line-profle
要使用draw, 在程序面板上右击显示控件, 创建->调用节点->Get Last Event和Clear Roi.
Which evetns 创建常量 选择draw.
Coordinates输出给line profile.vi或centroid.vi或其他需要四坐标确定处理区域的vi.
draw给出的四个数字, 若是line, 则是两个点的两个坐标; 若是方形, 则是对角线点的两个坐标; 若是椭圆, 则是bounding rectangle的左上右下四个坐标;
line profile输出图像选择混合信号图.
Clear Roi连接while循环.
注意!若要同时获得line profile以及centroid, 不能画水平或竖直的线.
