# Velodyne-VLP-16
Velodyne-VLP-16 激光雷达基础知识  相关配置 windows linux ros
## 激光雷达基础知识 （参考：http://www.slamtec.com/en/News/Detail/220）

多线激光雷达是指同时发射及接收多束激光的激光旋转测距雷达，市场上目前有4线、8线、16 线、32 线、 64 线和128线之分，多线激光雷达可以识别物体的高度信息并获取周围环境的3D扫描图，主要应用于无人驾驶领域。

在无人驾驶领域，多线激光雷达主要有以下两个核心作用：

3D建模及环境感知：通过多线激光雷达可以扫描到汽车周围环境的3D模型，运用相关算法对比上一帧及下一帧环境的变化，能较为容易的检测出周围的车辆及行人。

SLAM定位加强：同步建图（SLAM）是其另一大特性，通过实时得到的全局地图与高精度地图中的特征物进行比对，能加强车辆的定位精度并实现自主导航。

目前，用于无人驾驶的激光雷达多集中于国外，包括美国的Velodyne、Quanegy以及德国的IBEO品牌等。以Velodyne为首的多线激光雷达价格昂贵，均在万元（美元）级别以上，一般车企难以承受如此高昂的价格。

相比来说，单线激光雷达成本就低的多，单线激光雷达是指激光源发出的线束是单线的雷达，目前主要应用于机器人领域，以服务机器人居多，可以帮助机器人规避障碍物，其扫描速度快、分辨率强、可靠性高， 相比多线激光雷达，单线激光雷达在角频率及灵敏度上反应更快捷，所以，在测试周围障碍物的距离和精度上都更加精准。但单线雷达只能平面式扫描，不能测量物体高度，当前主要应用于我们常见的扫地机器人、送餐机器人、及酒店等服务机器人身上。

有别于无人驾驶领域的多线激光雷达，我国用于机器人领域的单线激光雷达已较为成熟，以思岚科技为代表的单线激光雷达已能达到40米的测量半径，同时，可以有效避免环境光与强日光的干扰，在室内外均能稳定使用，除此之外，其机身超薄，小巧轻便，可适用更多更大场景的应用。

总的来说，多线激光雷达的应用场景更为复杂，对性能的要求更高，但其价格昂贵，是大多数企业难以承受的。相比来说，单线激光雷达的结构更为简单，成本也更低，更容易满足服务机器人的使用需求，在距离及精度上更加精准。
