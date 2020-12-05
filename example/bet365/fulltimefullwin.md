# FullTimeFullWin API

## HTTP Request

`POST http:// Please contact us by Telegram to request address +/bet365/v0/api/FullTimeFullWin`

### Request Example

```text
curl -X POST -H "Authorization: Bearer Please contact us by Telegram to get token" http:// request address +/bet365/v0/api/FullTimeFullWin
```

### Request Header

| Parameter | Required? | Description |
| :--- | :--- | :--- |
| Authorization | Yes | Please contact to get 7 days free trial |
| Method | Yes | POST |

## Response Parameter

| Parameter | Description |
| :--- | :--- |
| msg | Success or Request failed description |
| code | Request status code, 0 means success, see error code for other details |
| data | Response object |
| data.sync\_time | Message synchronization time |
| data.data.channel | Data return channel |
| data.data.data.team\_pair | Team name |
| data.data.data.team\_score | Total team score |
| data.data.data.play\_time | Play time |
| data.data.data.handicap\_list | Handicap list |
| data.data.data.odds\_list | Odds list |

### HTTP Response

```text
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

