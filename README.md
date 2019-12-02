# 博物馆动静皆宜

#### 加值宣言
目前像博物馆这类公共场所对身障者的关怀主要是体现在设立无障碍卫生间、在楼梯旁建缓坡或者安装升降电梯，但却很少考虑到身障者在游览博物馆过程中的体验。而对多动症用户的关怀更是少之又少。因此我们将调用路径规划API，以此来根据用户的属性来帮助他们选择规划最佳的博物馆游览路径；调用人像分割API，为参观者提供一定的趣味活动，尽可能地减少烦躁情绪

#### 核心价值：（最小可行性产品）
着眼于用户的对于博物馆最基本需求——参观游览博物馆，为用户选择最佳的游览路径以获取最佳的体验感，同时还能提供娱乐休闲服务。

#### 背景
+ 身障者行动不便，体力和精力也有限。
+ 多动症者注意力短暂，活动过多
如果有一个产品可以根据两者的特性，为其规划博物馆游览路线，并且还具备娱乐功能，这或许能使用户获得最佳体验感

#### 目的
让身障者和多动症者，获得博物馆游览的最佳体验

#### 用户
身障者和多动症患者

#### 用户痛点
+ 身障者行动不便，体力和精力也有限
+ 多动症者注意力短暂，活动过多，情绪易激动

#### 用户需求:（使用的人工智能要反映到需求列表中）
|用户需求|对应功能|重要程度|
|:-|:-:|-:|
|用户想选择最佳的游览路线|路径规划|重要|
|用户想要进行娱乐活动|人像分割|重要|
|用户想知道某个区域当前有多少人流量|人流量统计|次重要|
|用户想知道某个区域哪里有便利设施|地理围栏|次重要|


#### 产品原型

+ 首页
![首页](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E9%A6%96%E9%A1%B5.png)

+ 人像分割
![人像分割](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E4%BA%BA%E5%83%8F%E5%88%86%E5%89%B21.png)
![人像分割](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E4%BA%BA%E5%83%8F%E6%8A%A0%E5%9B%BE2.png)

+ 人流量统计
![人流量统计](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E4%BA%BA%E6%B5%81%E9%87%8F%E7%BB%9F%E8%AE%A1.png)

+ 路径规划
![路径规划](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92.png)

+ 地理围栏
![地理围栏](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E5%9C%B0%E7%90%86%E5%9B%B4%E6%A0%8F1.png)
![地理围栏](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E5%9C%B0%E7%90%86%E5%9B%B4%E6%A0%8F2.png)


+ 我
![我-路径规划记录](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E6%88%911.png)
![我-便利设施记录](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E6%88%914.png)
![我-相册](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E6%88%913.png)
![我-人流量统计](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E6%88%912.png)

#### 产品结构图
+ 产品结构图
![产品结构图](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E5%8D%9A%E7%89%A9%E9%A6%86%E5%8A%A8%E9%9D%99%E7%9A%86%E5%AE%9C%E4%BA%A7%E5%93%81%E7%BB%93%E6%9E%84%E5%9B%BE.jpg)

+ 产品信息结构图
![产品信息结构图](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E5%8D%9A%E7%89%A9%E9%A6%86%E5%8A%A8%E9%9D%99%E7%9A%86%E5%AE%9C%E4%BA%A7%E5%93%81%E4%BF%A1%E6%81%AF%E7%BB%93%E6%9E%84%E5%9B%BE.jpg)

+ 产品功能结构图
![产品功能结构图](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/博物馆动静皆宜功能结构图.jpg)

+ 产品流程图
![产品流程图](https://raw.githubusercontent.com/DLIERBA/museum_movement_tranquility/master/museum_images/%E5%8D%9A%E7%89%A9%E9%A6%86%E5%8A%A8%E9%9D%99%E7%9A%86%E5%AE%9C%E4%BA%A7%E5%93%81%E6%B5%81%E7%A8%8B%E5%9B%BE.jpg)

#### API的运用和API的价值宣言
1. 百度API——人像分割
+ HTTP 方法：POST
+ 请求URL： https://aip.baidubce.com/rest/2.0/image-classify/v1/body_seg
+ API价值主张
①将原始图片中的人像分离出来，选择新的背景图像进行替换、合成
②人像分割算法业界领先
③支持返回分割后的二值图、灰度图、人像前景图，并可通过参数设置，自主设置返回哪些结果图，避免造成带宽浪费
④对于输入的一张图片（可正常解码，且长宽比适宜），识别人体的轮廓范围，与背景进行分离，适用于拍照背景替换、照片合成、身体特效等场景。输入正常人像图片，返回分割后的二值结果图、灰度图、透明背景的人像图（png格式）。

+ 免费配额

![免费配额](https://raw.githubusercontent.com/DLIERBA/API_ML_AI/master/images/%E7%99%BE%E5%BA%A6API%E4%BA%BA%E5%83%8F%E5%88%86%E5%89%B2.png)

+ 请求代码示例
``` 
# encoding:utf-8

import requests
import base64

'''
人像分割
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/body_seg"
# 二进制方式打开图片文件
f = open('[本地文件]', 'rb')
img = base64.b64encode(f.read())

params = {"image":img}
access_token = '[调用鉴权接口获取的token]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
``` 
+ 返回示例
```
{
	"log_id": 716033439,
	"labelmap": "xxxx",
	"scoremap": "xxxx",
	"foreground": "xxxx"
}

```

2. 百度API——人流量统计
+ HTTP 方法：POST
+ 请求URL： https://aip.baidubce.com/rest/2.0/image-classify/v1/body_num
+ 请求代码示例：
```
# encoding:utf-8

import requests
import base64

'''
人流量统计
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/body_num"
# 二进制方式打开图片文件
f = open('[本地文件]', 'rb')
img = base64.b64encode(f.read())

params = {"image":img}
access_token = '[调用鉴权接口获取的token]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```
+ 返回示例
```
{
    "log_id": 716033439,
    "person_num": 16,
    "image": "/9j/4AAoFS2P/9k="
}
```

3. 高德API——路径规划
+ 根据目的地、出发地以及路径策略设置，为用户量身设计出行方案。同时可结合实时交通，帮助用户绕开拥堵路段，提供更贴心、更人性化的出行体验。
[高德API路径规划]: https://lbs.amap.com/api/webservice/guide/api/direction

4. 高德API——地理围栏
+ API价值定位
开发者根据业务需求合理的在地图上圈定指定区域，创建围栏，定位 SDK 提供根据高德POI，行政区划，自定义圆形，多边形四种方式创建地理围栏，开发者可根据围栏圈定的范围进行精准操作。
[高德API地理围栏]: https://lbs.amap.com/api/webservice/guide/api/geofence_service

+ API的配额

![免费配额](https://raw.githubusercontent.com/DLIERBA/API_ML_AI/master/images/%E9%85%8D%E9%A2%9D.png)

#### API的实际运用
1. 百度API——人像分割
+ 通过该API的使用，是用户更为真切地体验古人的衣着服饰上身的效果，为参观者提供这类趣味活动，尽可能地减少烦躁情绪的产生

2. 百度API——人流量统计
+ 提供馆内各地区的人流量数据给游客，以供游客选择人流合适的地方游览或者错峰游览
3. 高德API——路径规划
+ 针对身障者：可以帮助身障者规划进入博物馆的最佳路径，让他们可以以最短最近的距离完成参观却又达到参观最佳效果

4. 高德API——地理围栏
+ 通过地理围栏，判断身障者的位置，显示周边的便利设施（残疾人通道、无障碍卫生间），以此方便身障者的出行

#### AI产品概率性
+ 高精度头肩检测算法，准确率90%以上
+ 人像分割算法业界领先，评测IoU 90%以上

#### API使用风险评估
在云环境下，API提供了对应功能的访问权限，这增加了云平台的攻击面，攻击者可能存在滥用或找流行API代码中的漏洞，实现攻击云用户与云服务，因此，云安全联盟也表示不安全的API是云计算面临的最大威胁之一

+ 应对措施
1. 通过API网关进行监视
2. 安全思维贯彻开发过程始终
3. 应用行业安全最佳实践和标准

+ 参考文章
[API安全风险]: https://www.fisec.cn/854.html
[API成为企业黑客攻击目标，你的API还安全吗？]: https://baijiahao.baidu.com/s?id=1607045952862598854&wfr=spider&for=pc
