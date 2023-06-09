
**简要描述：** 

- 商品列表搜索

**请求URL：** 
- ` https://api-ugo-web.itheima.net/api/public/v1/goods/search `

**请求方式：**
- GET

**参数：** 

|参数名|必选|类型|说明|
|:----    |:---|:----- |-----   |
|query |否  |string |关键字   |
|cid |否  |string | 分类id |
|pagenum     |否  |number | 页码 |
|pagesize |否 |number | 页容量 |

 **返回示例**

``` json
{
    "message": {
        "total": 10,
        "pagenum": 1,
        "goods": [
            {
                "goods_id": 57445,
                "cat_id": 9,
                "goods_name": "创维（Skyworth）65V9E 65英寸25核4K HDR高清智能电视",
                "goods_price": 6499,
                "goods_number": 100,
                "goods_weight": 100,
                "goods_big_logo": "",
                "goods_small_logo": "",
                "add_time": 1516663280,
                "upd_time": 1516663280,
                "hot_mumber": 0,
                "is_promote": false,
                "cat_one_id": 1,
                "cat_two_id": 3,
                "cat_three_id": 9
            }
        ]
    },
    "meta": {
        "msg": "获取成功",
        "status": 200
    }
}
```

 **返回参数说明** 

|                  |              |      |
| ---------------- | ------------ | ---- |
| 参数名           | 参数说明     | 备注 |
| total            | 总条数     |      |
| pagenum          | 当前页数     |      |
| goods_id         | 商品ID       |      |
| cat_id           | 分类ID       |      |
| goods_name       | 商品名称     |      |
| goods_price      | 商品价格     |      |
| goods_number     | 商品数量     |      |
| goods_weight     | 商品重量     |      |
| goods_big_logo   | 商品大图标   |      |
| goods_small_logo | 商品小图标   |      |
| add_time         | 商品添加时间 |      |
| upd_time         | 商品更新时间 |      |
| hot_mumber       | 热门商品数   |      |
| cat_one_id       | 所属一级分类 |      |
| cat_two_id       | 所属二级分类 |      |
| cat_three_id     | 所属三级分类 |      |

 **备注** 

- 更多返回错误代码请看首页的错误代码描述


