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

#### 产品结构图


#### API的运用和API的价值宣言
1. 百度API——人像分割

2. 百度API——人流量统计

3. 高德API——路径规划
+ 根据目的地、出发地以及路径策略设置，为用户量身设计出行方案。同时可结合实时交通，帮助用户绕开拥堵路段，提供更贴心、更人性化的出行体验。

4. 高德API——地理围栏

#### API的运用
1. 百度API——人像分割
+ 通过该API的使用，是用户更为真切地体验古人的衣着服饰上身的效果，为参观者提供这类趣味活动，尽可能地减少烦躁情绪的产生

2. 百度API——人流量统计
+ 提供馆内各地区的人流量数据给游客，以供游客选择人流合适的地方游览或者错峰游览
3. 高德API——路径规划
+ 针对身障者：可以帮助身障者规划进入博物馆的最佳路径，让他们可以以最短最近的距离完成参观却又达到参观最佳效果

4. 高德API——地理围栏
+ 通过地理围栏，判断身障者的位置，显示周边的便利设施（残疾人通道、无障碍卫生间），以此方便身障者的出行
