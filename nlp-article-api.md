## 推荐
### 获取推荐列表 /recommended

+ Description
    + [must] header.X-User-ssid 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + [must] cookie.X_U_SSID 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + [must] 用户登录后需要附带登录标记
    
+ Parameters
    + filter[shown] 是否展示过，【必填】，示例：filter[shown]=false|true
    + filter[firstRecTime] 打开推荐页面的时间，【非必填】，当filter[shown]=true时，【该参数必填】，格式比须按照[yyyy-MM-dd hh:mm:ss]填写，示例：filter[firstRecTime]=2019-03-27 15:27:39
    + page[number] 页码，【非必填】，不填时默认为1，当filter[shown]=false时，【该参数必须为1或不填】
    + page[size] 页长，【非必填】，不填时默认为10

+ Response 200 (application/json)

        {
            "meta": {
                "totalPages": 1,
                "totalElements": 8,
                "size": 10,
                "number": 1,
                "numberOfElements": 8,
                "first": true,
                "last": true,
                "sort": null
            },
            "links": {
                "self": "/topics/search?page[number]=1&page[size]=10",
                "first": "/topics/search?page[number]=1&page[size]=10",
                "last": "/topics/search?page[number]=1&page[size]=10"
            },
            "data": [
                {
                    "id": "1602207",
                    "meta": {
                        "score": 0.20977913
                    },
                    "forumId": 3,
                    "forumName": "新闻",
                    "topicType": 0,
                    "topicTypeValue": "正常",
                    "imageSingle": false,
                    "imageRotation": false,
                    "creator": 0,
                    "created": "2019-03-22 17:00:00",
                    "modified": "2019-03-24 21:37:37",
                    "wx": 1,
                    "wxTopicId": 132584,
                    "articleTopicId": 1602207,
                    "reviews": 0,
                    "replies": 0,
                    "thumbsUp": 0,
                    "thumbsDown": 0,
                    "thumbs": 0,
                    "liked": 0,
                    "favorite": 0,
                    "brand": null,
                    "rotations": null,
                    "images": [
                        {
                            "filename": "//static.mifanxing.com/wx/image/238/15/1044168.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/238/15/1044169.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/238/15/1044170.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/238/15/1044171.jpg"
                        }
                    ],
                    "coverImages": null,
                    "from": {
                        "image": "//static.mifanxing.com/iyyren/image/201808/27/1317/377531032376852480.jpg",
                        "fetchReviews": 213,
                        "reviews": 213,
                        "wxSeedId": 227,
                        "seedId": 373,
                        "origin": "http://mp.weixin.qq.com/s?__biz=MzAxNzUxMTg4NA==&mid=2649596718&idx=1&sn=ce0d37a5f95947ea26bc1474b234cd9f&chksm=83fd678db48aee9b677b8e4b006193d42d5d28d1e34c82ddca34c9363791f11ace0380b6dfcc&scene=27#wechat_redirect&seedId=227&groupSign=1553325544110&top=1&original=100&articletime=1553245200",
                        "host": "null://null",
                        "rating": null,
                        "source": "SHOWVEN孝文科技",
                        "fetchThumbsUp": 1,
                        "channelId": 366
                    },
                    "wxCategoryId": 4,
                    "post": {
                        "postType": 1,
                        "postTypeValue": "爬取",
                        "title": "SONICBOOM PLUS | 音爆王双管速喷气柱",
                        "description": "音爆王双管速喷气柱 SHOWVEN 最新研发，高端速喷气柱--SONICBOOM PLUS音爆王双管速喷气柱。采用创新独特双管输出设计，响应速度快，出烟量极大，安全性高，携带方便，安装灵活，适宜于各类大型舞台演出、酒吧夜店、新品发布会等活动，效果震撼！ 配置38颗9W LED灯珠，能显著增亮气柱，提..."
                    },
                    "document": {
                        "postDate": "2019-03-22",
                        "author": "SHOWVEN孝文科技",
                        "documentType": 1,
                        "original": 0
                    },
                    "similarities": []
                },
                {
                    "id": "1602253",
                    "meta": {
                        "score": 0.19294451
                    },
                    "forumId": 3,
                    "forumName": "新闻",
                    "topicType": 0,
                    "topicTypeValue": "正常",
                    "imageSingle": false,
                    "imageRotation": false,
                    "creator": 0,
                    "created": "2019-03-23 19:19:41",
                    "modified": "2019-03-26 11:31:35",
                    "wx": 1,
                    "wxTopicId": 132613,
                    "articleTopicId": 1602253,
                    "reviews": 5,
                    "replies": 0,
                    "thumbsUp": 0,
                    "thumbsDown": 0,
                    "thumbs": 0,
                    "liked": 0,
                    "favorite": 0,
                    "brand": null,
                    "rotations": null,
                    "images": [
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044466.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044467.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044469.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044470.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044471.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044472.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044473.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044474.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044475.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044476.jpg"
                        }
                    ],
                    "coverImages": null,
                    "from": {
                        "image": "//static.mifanxing.com/iyyren/image/201802/03/1621/303287728718626816.jpg",
                        "fetchReviews": 503,
                        "reviews": 503,
                        "wxSeedId": 8,
                        "seedId": 132,
                        "origin": "http://mp.weixin.qq.com/s?__biz=MzA5MDU2NjA4MA==&mid=2651881838&idx=2&sn=77425d7fae7da5b427b1c044f27a1670&chksm=8bed9dc1bc9a14d702e7f47db460e031bb808c3e4be36d95160d4d6849f5399c2bfe401a49b8&scene=27#wechat_redirect&seedId=8&groupSign=1553341007851&top=0&original=11&articletime=1553339981",
                        "host": "null://null",
                        "rating": null,
                        "source": "Eplay吉他",
                        "fetchThumbsUp": 6,
                        "channelId": 118
                    },
                    "wxCategoryId": 4,
                    "post": {
                        "postType": 1,
                        "postTypeValue": "爬取",
                        "title": "《春、来了》吉他指弹视频 和春天有一个约会...",
                        "description": "春为岁首，万物萌新 春是一年的开始，是希望的开始 是一切美好的开始 常言道：一年之计在于春、一日之计在于晨 春作为二十四节气中的第一个节气 立春和立夏、立秋、立冬一样 反映着四季的交换 也意味着新的轮回已再度开启 最寒冷的冬季过去时、春天降临 天气开始逐渐变暖，万物渐次复苏 春天最是适合旅游的时候 ..."
                    },
                    "document": {
                        "postDate": "2019-03-23",
                        "author": "Eplay吉他",
                        "documentType": 1,
                        "original": 1
                    },
                    "similarities": []
                }
            ]
        }

### 获取未展示的推荐文章个数 /recommended/notShowSize

+ Description
    + [must] header.X-User-ssid 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + [must] cookie.X_U_SSID 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + [must] 用户登录后需要附带登录标记

+ Response 200 (application/json)       
     
        {
            "data": 20
        }

### 主动触发推荐任务 /recommended/satrtRecommending
+ Description
    + [must] header.X-User-ssid 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + [must] cookie.X_U_SSID 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + 用户登录后需要保存登录信息
+ Response 200 (application/json)


## 分类




### 查询类别详情[GET] /admin/Classifications/{id}

+ Parameters
     +  id 类别id

+ Response 200 (Application/json)

      {
        "data": {
            "id": 17,
            "dimension": 2,
            "parentId": 10,
            "classificationName": "综合",
            "parent": {
                "id": 10,
                "dimension": 2,
                "parentId": 0,
                "classificationName": "专业领域"
            }
        }
      }

### 查询类别列表[GET] /admin/Classifications
+ Parameters
     +  dimension 分类维度，0：是否行业相关，1：文章功能，2：专业领域
+ Description 
     + filter[parentId]=0&sort=dimension（参数固定值；获取父节点）；注意：顺序按dimension字段0，1，2展示
     + filter[parentId]=1&filter[dimension]=0（参数固定值；获子节点）；注意：parentId参数为父节点id值;dimension参数为父节点的dimension值
     + page[number]=1&page[size]=10
     + sort -modified(从新到旧) | modified(从旧到新)

+ Response 200 (Application/json) (获取父节点示例)

      {
        "meta": {
            "totalPages": 1,
            "totalElements": 1,
            "size": 10,
            "number": 1,
            "numberOfElements": 1,
            "first": true,
            "last": true,
            "sort": null
        },
        "links": {
            "self": "/admin/Classifications?filter[dimension]=0&filter[parentId]=0&page[number]=1&page[size]=10",
            "first": "/admin/Classifications?filter[dimension]=0&filter[parentId]=0&page[number]=1&page[size]=10",
            "last": "/admin/Classifications?filter[dimension]=0&filter[parentId]=0&page[number]=1&page[size]=10"
        },
        "data": [
            {
                "id": 1,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "dimension": 0,
                "parentId": 0,
                "classificationName": "行业相关",
                "leaf": 0,
                "displayorder": 0
            }
        ]
      }

+ Response 200 (Application/json) (获取某个父节点下的子数据)

      {
        "meta": {
            "totalPages": 1,
            "totalElements": 2,
            "size": 10,
            "number": 1,
            "numberOfElements": 2,
            "first": true,
            "last": true,
            "sort": null
        },
        "links": {
            "self": "/admin/Classifications?filter[dimension]=0&filter[parentId]=1&page[number]=1&page[size]=10",
            "first": "/admin/Classifications?filter[dimension]=0&filter[parentId]=1&page[number]=1&page[size]=10",
            "last": "/admin/Classifications?filter[dimension]=0&filter[parentId]=1&page[number]=1&page[size]=10"
        },
        "data": [
            {
                "id": 2,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "dimension": 0,
                "parentId": 1,
                "classificationName": "正",
                "leaf": 1,
                "displayorder": 0
            },
            {
                "id": 3,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "dimension": 0,
                "parentId": 1,
                "classificationName": "负",
                "leaf": 1,
                "displayorder": 0
            }
        ]
      }

### 保存文章类别 [POST] /admin/ArticleClassification
+ Description
    + [MUST] authenticated
    + [MUST] ROLE_ADMIN
+ Description 
    + articleId - 文章ID （必填项）
    + dimension - 分类维度值（必填项）
    + classificationId - 分类ID（必填项）

+ Request（application/json）

       {
    	 "data":{
    		"articleId":3,
    		"dimension":1,
    		"classificationId":15
    	 }
      }

+ Response 200 (Application/json)

      {
        "data": {
           "id": 1,
           "type": "Classification"
       }
      }
      
      
      
### 文章详情类别展示[GET] /topics/articleClassification/{id}     
 + Parameters
   +  id 类别id；示例id=3
+ Description
   + 接口根据dimension字段顺序展示0，1，2
+ Response 200 (Application/json)

      {
        "data": [
            {
                "id": 2,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "dimension": 0,
                "parentId": 1,
                "classificationName": "正",
                "leaf": 1,
                "displayorder": 0
            },
            {
                "id": 9,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "dimension": 1,
                "parentId": 4,
                "classificationName": "声装",
                "leaf": 1,
                "displayorder": 0
            },
            {
                "id": 16,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "dimension": 2,
                "parentId": 10,
                "classificationName": "器乐",
                "leaf": 1,
                "displayorder": 0
            }
        ]
      }


    
