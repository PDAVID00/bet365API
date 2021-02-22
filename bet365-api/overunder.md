---
description: Please contact us by Telegram to get token.
---

# OverUnder API

## HTTP Request

`GET http://api.bet365data.com/api/bet365/overUnder`

### 

### Request Header

| Parameter | Required? | Description |
| :--- | :--- | :--- |
| KEY | Yes | Please contact to get 7 days free trial |
| Method | Yes | GET |

## Response Parameter

| Parameter | Description |
| :--- | :--- |
| msg | Success or Request failed description |
| code | Request status code, 0 means success, see error code for other details |
| data | Response object |
| data.sync\_time | Message synchronization time |
| data.list.channel | Data return channel |
| data.list.team\_pair | Team name |
| data.list.goals | Total team score |
| data.list.play\_time | Play time |
| data.list.league | League |
| data.list.full\_time | Over under odds list |
| data.list.event\_id | Event ID |

### HTTP Response

```text
{
    "code": 0,
    "data": {
        "list": [
            {
                "event_id": "贺拉戴克 克拉劳夫",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "2.5",
                            "handicap_number_raw": "2.5",
                            "over_odd": "3.550",
                            "under_odd": "1.275"
                        }
                    ]
                },
                "goals": [
                    "1",
                    "1"
                ],
                "league": "精英联赛",
                "play_time": [
                    "84:12"
                ],
                "team_pair": [
                    "贺拉戴克 克拉劳夫",
                    "塔波斯科"
                ]
            },
            {
                "event_id": "祖克瑞乔",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "2",
                            "handicap_number_raw": "2",
                            "over_odd": "2.000",
                            "under_odd": "1.800"
                        }
                    ]
                },
                "goals": [
                    "1",
                    "0"
                ],
                "league": "肯尼亚超级联赛",
                "play_time": [
                    "45:00"
                ],
                "team_pair": [
                    "祖克瑞乔",
                    "波斯塔流浪"
                ]
            },
            {
                "event_id": "Bashundhara Kings",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "2/2.5",
                            "handicap_number_raw": "2.0,2.5",
                            "over_odd": "1.725",
                            "under_odd": "2.075"
                        }
                    ]
                },
                "goals": [
                    "1",
                    "0"
                ],
                "league": "孟加拉超级联赛",
                "play_time": [
                    "45:00"
                ],
                "team_pair": [
                    "Bashundhara Kings",
                    "Uttar Baridhara俱乐部"
                ]
            },
            {
                "event_id": "西利夫里士邦",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "2",
                            "handicap_number_raw": "2",
                            "over_odd": "1.875",
                            "under_odd": "1.925"
                        }
                    ]
                },
                "goals": [
                    "1",
                    "0"
                ],
                "league": "土耳其丙级联赛",
                "play_time": [
                    "45:00"
                ],
                "team_pair": [
                    "西利夫里士邦",
                    "Muglaspor"
                ]
            },
            {
                "event_id": "班加罗尔Eagles",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "3.5/4",
                            "handicap_number_raw": "3.5,4.0",
                            "over_odd": "1.975",
                            "under_odd": "1.825"
                        }
                    ]
                },
                "goals": [
                    "2",
                    "0"
                ],
                "league": "印度班加罗尔超級联赛",
                "play_time": [
                    "45:00"
                ],
                "team_pair": [
                    "班加罗尔Eagles",
                    "班加罗尔Dream United FC"
                ]
            },
            {
                "event_id": "FK 辛尼卡",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "3/3.5",
                            "handicap_number_raw": "3.0,3.5",
                            "over_odd": "1.900",
                            "under_odd": "1.900"
                        }
                    ]
                },
                "goals": [
                    "0",
                    "0"
                ],
                "league": "欧洲友谊赛",
                "play_time": [
                    "01:15"
                ],
                "team_pair": [
                    "FK 辛尼卡",
                    "波德布雷佐瓦FK"
                ]
            },
            {
                "event_id": "克拉科夫维斯拉",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "3.5",
                            "handicap_number_raw": "3.5",
                            "over_odd": "1.950",
                            "under_odd": "1.850"
                        }
                    ]
                },
                "goals": [
                    "0",
                    "0"
                ],
                "league": "欧洲友谊赛",
                "play_time": [
                    "02:33"
                ],
                "team_pair": [
                    "克拉科夫维斯拉",
                    "波德海勒新塔尔格"
                ]
            },
            {
                "event_id": "卡芬堡",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "5/5.5",
                            "handicap_number_raw": "5.0,5.5",
                            "over_odd": "1.875",
                            "under_odd": "1.925"
                        }
                    ]
                },
                "goals": [
                    "1",
                    "3"
                ],
                "league": "欧洲友谊赛",
                "play_time": [
                    "54:02"
                ],
                "team_pair": [
                    "卡芬堡",
                    "NS Mura"
                ]
            },
            {
                "event_id": "美迪梅积",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "4.5",
                            "handicap_number_raw": "4.5",
                            "over_odd": "1.850",
                            "under_odd": "1.950"
                        }
                    ]
                },
                "goals": [
                    "0",
                    "2"
                ],
                "league": "欧洲友谊赛",
                "play_time": [
                    "49:49"
                ],
                "team_pair": [
                    "美迪梅积",
                    "希别尼克"
                ]
            },
            {
                "event_id": "苏尔杜利察工人",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "1.5",
                            "handicap_number_raw": "1.5",
                            "over_odd": "1.900",
                            "under_odd": "1.900"
                        }
                    ]
                },
                "goals": [
                    "0",
                    "0"
                ],
                "league": "欧洲友谊赛",
                "play_time": [
                    ""
                ],
                "team_pair": [
                    "苏尔杜利察工人",
                    "FK Dubocica"
                ]
            },
            {
                "event_id": "Raticate 522 (PSG) Esports",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "4.5/5",
                            "handicap_number_raw": "4.5,5.0",
                            "over_odd": "1.800",
                            "under_odd": "1.900"
                        }
                    ]
                },
                "goals": [
                    "0",
                    "1"
                ],
                "league": "足球电竞职业联赛 - 12分钟赛事",
                "play_time": [
                    "00:56"
                ],
                "team_pair": [
                    "Raticate 522 (PSG) Esports",
                    "Legion (LEG) Esports"
                ]
            },
            {
                "event_id": "D. Kiev (orlovsky1) Esports",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "",
                            "handicap_number_raw": "",
                            "over_odd": "",
                            "under_odd": ""
                        }
                    ]
                },
                "goals": [
                    "0",
                    "3"
                ],
                "league": "足球电竞之战 - 8分钟赛事",
                "play_time": [
                    "05:30"
                ],
                "team_pair": [
                    "D. Kiev (orlovsky1) Esports",
                    "S. Moscow (DangerDim77) Esports"
                ]
            },
            {
                "event_id": "Man City (Upcake22) Esports",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "1.5",
                            "handicap_number_raw": "1.5",
                            "over_odd": "1.800",
                            "under_odd": "1.900"
                        }
                    ]
                },
                "goals": [
                    "0",
                    "0"
                ],
                "league": "足球电竞之战 - 8分钟赛事",
                "play_time": [
                    "01:50"
                ],
                "team_pair": [
                    "Man City (Upcake22) Esports",
                    "Chelsea (Kray) Esports"
                ]
            },
            {
                "event_id": "Man Utd (Olle) Esports",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "3.5",
                            "handicap_number_raw": "3.5",
                            "over_odd": "1.875",
                            "under_odd": "1.825"
                        }
                    ]
                },
                "goals": [
                    "0",
                    "1"
                ],
                "league": "足球电竞之战 - 8分钟赛事",
                "play_time": [
                    "01:42"
                ],
                "team_pair": [
                    "Man Utd (Olle) Esports",
                    "Tottenham (TAKA) Esports"
                ]
            },
            {
                "event_id": "Shakhtar (white_boy1927) Esports",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "",
                            "handicap_number_raw": "",
                            "over_odd": "",
                            "under_odd": ""
                        }
                    ]
                },
                "goals": [
                    "1",
                    "4"
                ],
                "league": "足球电竞之战 - 8分钟赛事",
                "play_time": [
                    "05:19"
                ],
                "team_pair": [
                    "Shakhtar (white_boy1927) Esports",
                    "CSKA (slezaintima) Esports"
                ]
            },
            {
                "event_id": "Chelsea (Quavo) Esports",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "3.5",
                            "handicap_number_raw": "3.5",
                            "over_odd": "1.775",
                            "under_odd": "1.925"
                        }
                    ]
                },
                "goals": [
                    "0",
                    "1"
                ],
                "league": "足球电竞球场现场赛 - 10分钟赛事",
                "play_time": [
                    "03:05"
                ],
                "team_pair": [
                    "Chelsea (Quavo) Esports",
                    "A.Madrid (Dimqaa) Esports"
                ]
            },
            {
                "event_id": "Inter (OoLancer) Esports",
                "full_time": {
                    "over_under_odd": [
                        {
                            "handicap_number": "6",
                            "handicap_number_raw": "6",
                            "over_odd": "1.800",
                            "under_odd": "1.900"
                        }
                    ]
                },
                "goals": [
                    "2",
                    "1"
                ],
                "league": "足球电竞球场现场赛 - 10分钟赛事",
                "play_time": [
                    "03:10"
                ],
                "team_pair": [
                    "Inter (OoLancer) Esports",
                    "Man Utd (CarlWhizzer) Esports"
                ]
            }
        ],
        "total": 17,
        "channel": "bet365_over_under",
        "sync_time": 1610535836
    },
    "msg": "Success"
}
```

