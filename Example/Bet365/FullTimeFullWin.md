# FullTimeFullWin API

------

## requestAddress 
```联系客户获取地址+/bet365/v0/api/FullTimeFullWin```


## Request Example

```zsh
curl -X POST -H "Authorization: Bearer 联系客户获取token" 联系客户获取地址+//bet365/v0/api/AsianHandiCap "
```
###  Request Header

| 参数       | 是否必填   |  备注  |
| --------   | -----:  | :----:  |
| Authorization |是 |   联系客户获取7天免费试用   |
| Method | 是支持Post请求|   POST   |

## Response Example

| 参数       | 注释   |  备注  |
| --------   | :-----  | :----:  |
| msg |成功，获取请求失败说明 |      |
| code |Response 请求状态码，0是成功，其他详见错误码|      |
| data |Response 返回对象|      |
| data.sync_time |消息同步时间|      |
| data.data.channel |数据返回通道|      |
| data.data.data.team_pair |球队名称|      |
| data.data.data.team_score |队员总分|      |
| data.data.data.paly_time |比赛时间|      |
| data.data.data.handicap_list |让分列表|      |
| data.data.data.odds_list |赔率列表|      |
```
{
    "msg":"Success",
    "data":{
        "data":{
            "channel":[
                "滚球亚洲盘"
            ],
            "data":[
                {
                    "team_pair":[
                        "马格达莱纳联盟",
                        "希拿体育会"
                    ],
                    "team_score":[
                        "2",
                        "3"
                    ],
                    "paly_time":[
                        "87:12"
                    ],
                    "handicap_list":[
                        "0.0",
                        "0.0"
                    ],
                    "odds_list":[
                        "1.500",
                        "2.500"
                    ]
                },
                {
                    "team_pair":[
                        "Sakh (FCS) Esports",
                        "ICE (ISE) Esports"
                    ],
                    "team_score":[
                        "2",
                        "1"
                    ],
                    "paly_time":[
                        "07:34"
                    ],
                    "handicap_list":[
                        "-1.5",
                        "+1.5"
                    ],
                    "odds_list":[
                        "1.950",
                        "1.750"
                    ]
                },
                {
                    "team_pair":[
                        "Belgium (Kray) Esports",
                        "Brazil (MeLToSiK) Esports"
                    ],
                    "team_score":[
                        "0",
                        "1"
                    ],
                    "paly_time":[
                        "01:46"
                    ],
                    "handicap_list":[
                        "0.0",
                        "0.0"
                    ],
                    "odds_list":[
                        "1.900",
                        "1.800"
                    ]
                },
                {
                    "team_pair":[
                        "Portugal (mooneycb) Esports",
                        "France (labotryas) Esports"
                    ],
                    "team_score":[
                        "1",
                        "0"
                    ],
                    "paly_time":[
                        "01:48"
                    ],
                    "handicap_list":[
                        "0.0",
                        "0.0"
                    ],
                    "odds_list":[
                        "1.750",
                        "1.950"
                    ]
                },
                {
                    "team_pair":[
                        "Real Betis (kiser) Esports",
                        "Valencia (Veep) Esports"
                    ],
                    "team_score":[
                        "2",
                        "0"
                    ],
                    "paly_time":[
                        "06:58"
                    ],
                    "handicap_list":[
                        "-0.5",
                        "+0.5"
                    ],
                    "odds_list":[
                        "1.875",
                        "1.825"
                    ]
                },
                {
                    "team_pair":[
                        "Real Sociedad (Fagur) Esports",
                        "Athletic Bilbao (Alback) Esports"
                    ],
                    "team_score":[
                        "2",
                        "1"
                    ],
                    "paly_time":[
                        "07:08"
                    ],
                    "handicap_list":[
                        "0.0,-0.5",
                        "0.0,+0.5"
                    ],
                    "odds_list":[
                        "1.925",
                        "1.775"
                    ]
                }
            ]
        },
        "sync_time":1606791016
    }
}
```