# CIKM-CUP-2019-TRACK2-rank10
solution implement(之后会上传代码).<br>

#### CIKM 2019 EComm AI - Efficient and Novel Item Retrieval for Large-scale Online Shopping Recommendation

#### 队伍名称
kupuV

#### 赛题地址（competition address）:
* [in CIKM] (http://www.cikm2019.net/challenge.html).<br>
* [in tianchi] (https://tianchi.aliyun.com/competition/entrance/231721/introduction).<br>

#### 赛题解释（competition explanation）:
这是一个推荐topK类型的问题.<br>
要从全量商品库中精确地检索到用户最感兴趣的topK个商品，并且要求时间复杂度在O(n)以下(TRACK1没有时间复杂度要求)，即避免穷举计算.<br>
> 提供方案的时间复杂度必须在O(n)以下才被视作有效<br>
> 对于类似于构建索引结构的预处理操作，其处理流程不计入时间复杂度计算<br>

初赛与复赛的评价指标不一样，所以初赛复赛的解决方案会不太相同<br>
* 初赛指标: 推荐的item可以包含之前点击过的<br>
* 复赛指标: 推荐的item不能包含之前点击过的<br>

#### 运行环境
- python==3.6.5
- keras==2.2.4
- lightfm==1.15
---
主要是内存很小，数据要采样，如果数据量可以再大一点，结果应该可以更好:(

#### 方案说明

wait...