# 博物馆动静皆宜
#### 1句话版本价值宣言
调用人像分割API让用户更为真切地体验古人的衣着服饰上身的效果，调用人流量统计API提供馆内各地区的人流量数据给游客，以供游客选择人流合适的地方游览或者错峰游览，调用路径规划API帮助身障者规划进入博物馆的最佳路径，调用地理围栏API判断身障者的位置，显示周边的便利设施（残疾人通道、无障碍卫生间），以此方便身障者的出行。

#### 1分钟版本价值宣言 (图文线上可阅读含可查连结)
+ 目前像博物馆这类公共场所对身障者的关怀主要是体现在设立无障碍卫生间、在楼梯旁建缓坡或者安装升降电梯，但却很少考虑到身障者在游览博物馆过程中的体验。而对多动症用户的关怀更是少之又少。
+ 因此该款APP将针对身障者和多动者。调用人像分割API让用户更为真切地体验古人的衣着服饰上身的效果，增加游览的趣味性；调用人流量统计API提供馆内各地区的人流量数据给游客，以供游客选择人流合适的地方游览或者错峰游览；调用路径规划API帮助身障者规划进入博物馆的最佳路径，调用地理围栏API判断身障者的位置，显示周边的便利设施（残疾人通道、无障碍卫生间），以此方便身障者的出行。
+ 之所以选择高德的地理API是因为如果不考虑POI数据的话，从对开发者友好角度，从容易上手角度：高德完胜百度。高德的API十分简单易上手，高德一行代码，百度最少要五行。而在人像分割API上之所以选择百度API是因为百度人脸识别API，功能强大，简单易用。
+ 以上功能将以一个APP形式存在，因为可以实现完整功能，灵活性强；能够在交互、视觉等用户体验上满足用户的高要求；界面内容更丰富，运转速度快，系统更加流畅

[人脸识别API参考文章](https://zhuanlan.zhihu.com/p/92732557)
[小程序与APP的区别、优劣分析](https://baijiahao.baidu.com/s?id=1607470904871676194&wfr=spider&for=pc)

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
① 将原始图片中的人像分离出来，选择新的背景图像进行替换、合成
② 人像分割算法业界领先
③ 支持返回分割后的二值图、灰度图、人像前景图，并可通过参数设置，自主设置返回哪些结果图，避免造成带宽浪费
④ 对于输入的一张图片（可正常解码，且长宽比适宜），识别人体的轮廓范围，与背景进行分离，适用于拍照背景替换、照片合成、身体特效等场景。输入正常人像图片，返回分割后的二值结果图、灰度图、透明背景的人像图（png格式）。

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
[API安全风险](https://www.fisec.cn/854.html)
[API成为企业黑客攻击目标，你的API还安全吗？](https://baijiahao.baidu.com/s?id=1607045952862598854&wfr=spider&for=pc)

#### API功能对比
1. 百度地图API和高德地图API
+ 如果不考虑POI数据的话，从对开发者友好角度，从容易上手角度：高德完胜百度。高德的API十分简单易上手，高德一行代码，百度最少要五行。
+ 百度地图各个子产品各自为战，相当混乱，配置麻烦，问题较多，总而言之就是技术混乱。不过百度有着丰富的数据资源。
+ 百度的坐标不可逆，用了百度不容易改别的，而高德则可以。
+ 高德拥有测绘权，地理坐标信息比百度精准
+ 从中英双语支持上，高德比较友好

2. 人脸识别API
+ 国际人脸识别评估集LFW榜， face++ 99.5% 商汤 99.53% 腾讯 99.65% 百度 99.77%，非思丸 99.77% 中科云从 99.5% 道奇智能99.64%，FaceTo 99.4% 宇泛智能 99%这些都是基于国内的
+ 百度人脸识别API，功能强大，简单易用；至少有很多人工智能的大师是在百度工作过，也是国内最早进军人工的企业之一，虽然后来大师都从百度出走，但是人家积累的根基还是很厚的。
+ face++号称是一个提供免费人脸检测、人脸识别、人脸属性分析等服务的云端服务平台，但是它所谓的免费其实就是注册和试用。但价格上应该还是可以接受的
+ 非思丸这家公司提供免费SDK，免费API，免费APK，而且不需要提供太多资料
+ 虹软技术号称提供免费的sdk，到底是怎么收费不清楚，当时对于这种不是很知名，试用就要提供一大堆个人信息还是不要用为妙。

[参考文章](https://zhuanlan.zhihu.com/p/92732557)


#### 产品可行性
1. 该产品是一个APP
+ App可以实现完整功能，灵活性强
+ APP能够在交互、视觉等用户体验上满足用户的高要求
+ App的界面内容更丰富，运转速度快，系统更加流畅

2. 该产品需求明确，而且需求针对的特定的群体普遍偏年轻，其优势就是年轻群体对新鲜事物的接受度较高且具有较强的传播能力

3. 该产品有核心功能和辅助功能，功能多样而且新颖

4. 该产品能有效解决用户日常生活中较为常见的尴尬情况

+ 参考文章
[小程序与APP的区别、优劣分析](https://baijiahao.baidu.com/s?id=1607470904871676194&wfr=spider&for=pc)

#### 交互需求
1. 当涉及到下载或其他很耗费流量的操作时，会进行2G/3G网络还是wifi网络的判断，当判断出是非wifi时，会进行提醒。其他需要向后台请求数据时，只进行简单的网络状况是否良好的判断，当网络状况不良时进行提示。
2. 当用户上传的图片不符合要求时，会提醒用户重新上传
3. 当用户没有开启地理定位时，会提醒用户开启地理定位，否则无法正常行使该功能

#### 异常流
+ 如果地理定位不成功，给出具体字段的错误提示信息，提示用户去到较为空旷或者有标志性建筑的地方
+ 如果地理围栏的信息不正确，提示用户可以手动选择和更改以及报错。
+ 如果人像抠图不成功，给出具体字段的错误提示信息，让用户重新上传照片

#### 非功能性需求
1. 性能需求描述：
+ 响应时间：

① 在95％的情况下，一般时段响应时间不超过1.5秒，高峰时段不超过4秒。

② 定位系统从点击到第一个界面显示出来所需要的时间不得超过300毫秒。

③ 在网络畅通时，拨号连接GPRS网络所需时间不得超过5秒。

④ 在网络畅通时，电子地图刷新时间不超过10秒。

⑤ 在非高峰时间根据编号和名称特定条件进行搜索，可以在3秒内得到搜索结果。

+ 业务量：

① 估计用户数为1万人，每天登录用户数为3000左右，网络的带宽为100M带宽。

② 系统可以同时满足10,000个用户请求，并为25,000个并发用户提供浏览功能。


+ 系统容量：

① 支持3万用户，支持GB级数据。

② 数据库表行数不超过100万行，数据库最大容量不超过1000GB，磁盘空间至少需要40G以上。

+ 精度：
① 定位精度误差不超过80米。

② 当通过互联网接入系统的时候，期望在编号和名称搜索时最长查询时间<15秒。

③ 计算的精确性到小数点后7位。

+ 资源使用率：
① CPU占用率<=50%。

② 内存占用率<=50%。

2. 安全需求描述：

① 严格权限访问控制，用户在经过身份认证后，只能访问其权限范围内的数据，只能进行其权限范围内的操作。

② 不同的用户具有不同的身份和权限，需要在用户身份真实可信的前提下，提供可信的授权管理服务，保护数据不被非法/越权访问和篡改，要确保数据的机密性和完整性。

③ 提供运行日志管理及安全审计功能，可追踪系统的历史使用情况。

④ 能经受来自互联网的一般性恶意攻击。如病毒（包括木马）攻击、口令猜测攻击、黑客入侵等。

⑤ 至少99%的攻击需要在10秒内检测到。

⑥ 当用户的账号在常用设备以外的设备登录了，要及时发消息通知用户；当用户出现登录异常的情况时，要开启动态口令验证（例如短信发生动态码）等。

3. 可靠性需求描述：

① 对输入有提示，数据有检查，防止数据异常。

② 系统健壮性强，应该能处理系统运行过程中出现的各种异常情况，如：人为操作错误、输入非法数据、硬件设备失败等，系统应该能正确的处理，恰当的回避。

③ 因软件系统的失效而造成不能完成业务的概率要小于5‰。

④ 要求系统7x24小时运行，全年持续运行故障停运时间累计不能超过10小时。

⑥ 系统缺陷率每1,000小时最多发生1次故障。

⑥ 在1,000,000次交易中，最多出现1次需要重新启动系统的情况。

4. 兼容性需求描述：

① 系统应支持IOS，Android 操作系统

② 系统应支持Oracle, DB2 数据库系统

③ 替换关系数据库系统的平均时间不超过2小时，并且保证没有数据丢失。

5. 数据保密需求描述：

网络传递数据应经过加密。需要保证数据在采集、传输和处理过程中不被偷窥、窃取、篡改。业务数据需要在存储时进行加密，确保不可破解。



6. 易用性需求描述案例：
 功能操作简单，界面清晰简洁，某些较复杂的操作需要给用户提供操作指引。

7. 可用性需求描述：

① 有些农村地区网络质量差，带宽小。在网络环境差的条件下保证系统的可用性等。

② 在95%的故障中，系统最多需要20秒重启。

③ 提供数据备份和恢复功能，使得在由于系统的错误或其他原因引起系统的数据丢失或系统的数据被破坏时，能够及时恢复和还原数据（由硬件及第三方软件提供此功能）。

8. 可测试性需求描述：

① 一个模块的最大圈复杂度不能超过15。

② 开发活动必须使用回归测试，并允许在12小时内重新进行完整的测试。

9. 可维护性需求描述：

① 从接到修改请求后，对于普通修改应在1~2天内完成；对于评估后为重大需求或设计修改应在1周内完成。

② 90%的BUG修改时间不超过1个工作日，其他不超过2个工作日。

③ 代码的圈复杂度必须在10以内。

④ 任何对象的任何方法都不允许超过200行代码。

⑤ 安装新版本必须保持所有的数据库内容和所有个人设置不变。

⑥ 产品必须提供可跟踪任何数据库字段的工具。

[参考文章](https://blog.csdn.net/zhangjunli/article/details/102968598)
#### 结果预期
+ 上线初期，先在一个小区域内（例如某个地区的高校）进行推广，然后收集这一部分使用者的体验评价，根据情况进行完善
+ 当APP功能基本完善，用户评价普遍向好时，面向整个市场推出使用，不过刚开始需要使用一些奖励措施，吸引更多的用户使用APP
+ 到APP被广泛应用，拥有较为稳定的用户群体时，可减少甚至取消先前为了吸引新用户所采取的奖励，并且可以考虑增加其他功能，利用持续创新的手段吸引新用户以及留住旧用户
+ 发展到一定阶段后，APP可能会接手广告业务获利；或者在APP内开设购物功能，贩卖博物馆周边之类的；也有可能选择增设会员服务，以吸引用户在APP内消费，最终实现APP盈利

#### 附录
[博物馆](http://nfunm080.gitee.io/museum)
