# PRD_Museum
| 发布日期 | 2019-12-3 |
| --------   | -----:  |
| 史诗 | 小博物 | 
| 文件状态 | 进行中 | 
| 文件主人 | 吴玮馨 | 
| 领头的设计师  | 吴玮馨 | 
| 领头的开发者  | 吴玮馨 | 
| 领头的测试者  | 吴玮馨 | 

## 一、价值主张设计
### 1. 加值宣言
在逛博物馆的时候，用户几乎都想知道什么路线去找哪个藏品最快；博物馆里有哪些商家；想找博物馆中的一个地方，但是不知道该怎么走；想找一个地方，忘记字怎么打了；和家人一起出游,走散了;诸如此类的问题。这个APP运用了百度地图-室内图API和百度-短语音识别API来为用户探寻最快的游览路线。用户想要知道商店在哪里，要怎么走;和家人朋友走散了,又难以描述所在位置,可以通过百度地图-室内图API，轻松切换楼层展示不同楼层商户信息,室内餐饮、卫生间
ATM机，搜啥有啥,探寻最合适的路线规划，帮助您快速找到目的地。用户着急找一个地方（例如：厕所），连输入厕所两个字都等不及了的时候，可以用百度-短语音识别API，摆脱按键操作，通过语音识别直接输入文字，快速返回识别结果。从而让用户能快速地找到目的地，愉快地和家人朋友游览博物馆。

优先级：
百度地图API-室内图：利用三角定位技术、增强WI-FI指纹模型技术、地磁技术、蓝牙等技术，实现业界领先的定位性能，解决室内的一切难题。

次优先：
百度API-短语音识别：将60秒内的语音快速识别为文字，适用于手机语音输入、语音搜索、人机对话等语音交互场景。

### 2. 核心价值
本产品着眼于解决用户着急输入文字，摆脱生僻字和拼音障碍，以及在陌生的博物馆难以找到目的地点的问题。

### 3. 用户
想要舒适、愉快、快速地游览博物馆，带有小孩、老人（容易走散）的人。

### 4. 使用场景
- 用户被相似的拼音混淆了，打不出想要的字，这时在APP中打开短语音识别，说出你想要的文字。
- 用户想知道某个藏品在哪里，且不知道可以走什么路线，在APP中打开室内地图，输入想知道的藏品，能跨楼层精准的点到点室内路径规划，灵活周到的路线指引。
- 用户想要大概了解博物馆的内部构造，在APP中打开室内地图，室内三维效果展现，可自定义渲染效果。支持楼层切换，支持多种手势，全方位查看博物馆。
- 用户想知道博物馆有没有商店，在APP中打开室内地图，输入商店，能实现室内POI搜索，精准的聚合分类搜索，支持用户输入关键字/词快速搜索。

### 5. 核心价值与用户痛点
- 用户忘记了文字的拼音，或者是生僻字不认识。
- 用户不知道某藏品在哪层的什么位置。
- 用户不知道什么路线去找某藏品最为快捷。
- 用户不知道博物馆内部的具体构造。
- 用户不知道博物馆内有没有商店。

### 6. 人工智能概率性与用户痛点
#### 百度地图-室内图API：
- 精准：1-3m的室内精准定位服务精准的轨迹推算。
- 持续：室内外无缝衔接定位信息平滑连贯。
- 便捷：轻松找到室内ATM、问询处、店铺等位置 。
- 多种定位方式融合：结合WI-FI、气压计、蓝牙地磁传感器等定位技术。

#### 百度-短语音识别API：
- 技术世界领先：采用领先国际的流式端到端语音语言一体化建模方法，近场中文普通话识别准确率达98%。
- 服务稳定高效：企业级稳定服务保障，专有集群承载大流量并发高效灵活，以及99.9%服务稳定性保障。
- 模型自助优化：中文输入法、搜索模型均可在语音自训练平台上零代码自助训练，上传文本语料即可有效提升业务词汇的识别准确率5-25%。

#### 室内图利用三角定位技术、增强WI-FI指纹模型技术、地磁技术、蓝牙等技术，实现业界领先的定位性能，已是米级定位精度，三重定位下，失误概率更是大大降低了。而短语音识别采用流式端到端语音语言一体化建模方法，近场中文普通话识别准确率达98%，且服务器稳定，还有模型自助优化，那就可以在用户使用的过程自主训练，达到更好。

### 7. 需求列表与人工智能API加值
| 用户案例	| API接口	| 重要程度 |
| -- | -- | -- |
| 用户不知道某藏品在哪层的什么位置，以什么路线去最为快捷 | 室内图 	| 重要 |
| 用户不知道博物馆内部的具体构造 |  室内图	| 重要 |
| 用户不知道博物馆内有没有商店	| 室内图	| 重要 |
| 用户忘记了文字的拼音，或者是生僻字不认识。	| 短语音识别	| 次重要 |

## 二、原型

### [原型文档交互展示](https://nfunm081.github.io/prototype-museum/)
### [原型文档下载区](https://github.com/NFUNM081/prototype-museum)

### 1. 产品流程图
![博物馆APP流程图](https://images.gitee.com/uploads/images/2019/1230/221039_cb22848b_1922090.jpeg "博物馆APP流程图.jpg")

### 2. 产品功能结构图
![博物馆APP功能结构图](https://images.gitee.com/uploads/images/2019/1230/221151_4bb1b61f_1922090.jpeg "博物馆APP功能结构图.jpg")

### 3. 产品信息结构图
![博物馆APP信息结构图](https://images.gitee.com/uploads/images/2019/1230/221221_2326e7c7_1922090.jpeg "博物馆APP信息结构图.jpg")
