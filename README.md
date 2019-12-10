# api_graduation

|  发布日期 | 2019-12-01 |
 | -- | -- |
 |  名称 | 毕业册 |
 |  文件现状 | 已完成 |
 |  文件的主人 |  刘主茵|
 |  领头的设计师 | 刘主茵 |
 |  领头的开发者 |  刘主茵|
 |  领头的测试者 |  刘主茵 |
# 价值主张设计：
为了制作出更具有纪念价值和能承载美好回忆的毕业册，第一，本产品会使用face++的人脸美颜为所有毕业生的毕业照进行美颜处理，使得毕业生观看浏览时心情更为愉悦；第二，会使用高德地图的JS地图api来绘制3D版的学校地图，学生可以在3D的学校建筑楼当中输入自己的留言；第三，还会使用Face++的相册聚类api，识别毕业册中照片的人脸，然后照片可根据人脸进行自动聚类，毕业生可以轻易找到出现自己或某个特定的人的照片。
## （一）加值宣言：
1. Face++人脸美颜api可以基于高精度的人脸关键点，实现贴合脸型的智能美颜，并且能根据不同光照场景实现自然的美颜效果。
2. 高德地图的JS地图api提供了2D、3D地图模式，满足绝大多数开发者对地图展示、地图自定义、图层加载、点标记添加、矢量图形绘制的需求。
3. Face++相册聚类api识别相册中照片的人脸，然后照片可根据人脸进行自动聚类，具有高精度、容许多相册的特点，新入库的照片也可按照人脸自动归类。
## （二）核心价值：（最小可行性产品）
1. 将上传的毕业照中出现的人脸进行人脸美颜处理
2. 为毕业院校绘制该校的3D地图
3. 通过人脸的检测进行相册的聚类
## （三）背景：
每年都有大批的毕业生离开校园，他们都会举行毕业典礼纪念这一特殊的日子，毕业册则是他们寄存多年校园生活的载体，里面有图片有文字等，但是格式总是千篇一律且缺乏互动性，因此设计一款智能毕业册更能满足毕业生的多样的需求。
## （四）目的：
为毕业生设计一款更具有交互性和能以更多样的媒介记载学校经历的智能毕业册。
## （五）用户：中大南方2021届毕业生
## （六）用户痛点：
1. 纸质毕业册只能较好的展示一些照片和文字，为2D平面，不够生动和多样化。
2. 纸质毕业册不具有互动性，无法做出较大的更改和排版
3. 纸质毕业册的照片挑选空间较少，出现丑照的概率性大
4. 毕业册中出现的图片多以班级或活动或时间分类，不能依照人脸进行分类
## （七）用户需求:（使用的人工智能要反映到需求列表中）
| 用户案例	| 对应标题	| 重要程度 |
| -- | -- | -- |
| 毕业生想浏览有出现自己的所有照片	| Face++通过相册聚类将出现该毕业生的照片集合成一个相册供毕业生浏览	|高  |
| 毕业生想将别人上传的照片中的自己美颜一下	| Face++人脸美颜为其进行自然美艳	|  中|
| 毕业生想回忆学校的场所并以文字记载相应的故事| 高德JS api将绘制学校3D地图供毕业生浏览叠加文字信息  |高|

### 具体应用场景
毕业后，翻看毕业册怀念曾经的大学生活，点击观看曾经在校园照下的照片和学校的场景。
