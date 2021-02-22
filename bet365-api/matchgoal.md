---
description: Please contact us by Telegram to get token.
---

# MatchGoal API

## HTTP Request

`GET http://api.bet365data.com/api/bet365/matchGoal`



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
| data.data.channel | Data return channel |
| data.data.data.team\_pair | Team name |
| data.data.data.team\_score | Total team score |
| data.data.data.play\_time | Play time |
| data.data.data.handicap\_list | Handicap list |
| data.data.data.odds\_list | Odds list |

### HTTP Response

```text
{
    "msg": "Success",
    "data": {
        "data": {
            "channel": [
                "比赛进球"
            ],
            "data": [
                {
                    "team_pair": [
                        "SSGC",
                        "Masha United"
                    ],
                    "team_score": [
                        "3",
                        "1"
                    ],
                    "play_time": [
                        "92:40"
                    ],
                    "handicap_list": [],
                    "odds_list": []
                },
                {
                    "team_pair": [
                        "贾马尔普尔Kacharipara Akadas 女子",
                        "Begum Anwara SC 女子"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "22:23"
                    ],
                    "handicap_list": [
                        "3.5",
                        "3.5"
                    ],
                    "odds_list": [
                        "2.25",
                        "1.57"
                    ]
                },
                {
                    "team_pair": [
                        "多乐 21岁以下",
                        "Pho Hien U21"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "35:35"
                    ],
                    "handicap_list": [],
                    "odds_list": []
                },
                {
                    "team_pair": [
                        "河内FC 21岁以下",
                        "Luxury Ha Long 21岁以下"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "34:05"
                    ],
                    "handicap_list": [],
                    "odds_list": []
                },
                {
                    "team_pair": [
                        "The Cong FC 21岁以下",
                        "南定 21岁以下"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "34:08"
                    ],
                    "handicap_list": [
                        "2.5",
                        "2.5"
                    ],
                    "odds_list": [
                        "2.10",
                        "1.66"
                    ]
                },
                {
                    "team_pair": [
                        "Cong An Nhan Dan U21",
                        "西宁 21岁以下"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "35:11"
                    ],
                    "handicap_list": [
                        "2.5",
                        "2.5"
                    ],
                    "odds_list": [
                        "1.83",
                        "1.83"
                    ]
                },
                {
                    "team_pair": [
                        "黄安嘉莱 21岁以下",
                        "义安蓝江 21岁以下"
                    ],
                    "team_score": [
                        "0",
                        "1"
                    ],
                    "play_time": [
                        "35:19"
                    ],
                    "handicap_list": [
                        "2.5",
                        "2.5"
                    ],
                    "odds_list": [
                        "1.80",
                        "1.90"
                    ]
                },
                {
                    "team_pair": [
                        "隆安 21岁以下",
                        "同塔 21岁以下"
                    ],
                    "team_score": [
                        "1",
                        "0"
                    ],
                    "play_time": [
                        "35:05"
                    ],
                    "handicap_list": [
                        "2.5",
                        "2.5"
                    ],
                    "odds_list": [
                        "1.72",
                        "2.00"
                    ]
                },
                {
                    "team_pair": [
                        "Im Not Over (PNZ) Esports",
                        "Megapolice (MEG) Esports"
                    ],
                    "team_score": [
                        "2",
                        "1"
                    ],
                    "play_time": [
                        "10:09"
                    ],
                    "handicap_list": [],
                    "odds_list": []
                },
                {
                    "team_pair": [
                        "Argentina (slezaintima) Esports",
                        "Netherlands (d1pseN) Esports"
                    ],
                    "team_score": [
                        "1",
                        "0"
                    ],
                    "play_time": [
                        "05:10"
                    ],
                    "handicap_list": [
                        "2.5",
                        "2.5"
                    ],
                    "odds_list": [
                        "2.20",
                        "1.61"
                    ]
                },
                {
                    "team_pair": [
                        "Spain (nikkitta) Esports",
                        "England (Bombi1t0) Esports"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "05:12"
                    ],
                    "handicap_list": [
                        "0.5",
                        "0.5"
                    ],
                    "odds_list": [
                        "2.00",
                        "1.72"
                    ]
                },
                {
                    "team_pair": [
                        "Bayern (hotShot) Esports",
                        "Leverkusen (Boulevard_Prospect) Esports"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "00:00"
                    ],
                    "handicap_list": [
                        "1.5",
                        "1.5"
                    ],
                    "odds_list": [
                        "1.50",
                        "2.50"
                    ]
                },
                {
                    "team_pair": [
                        "RB Leipzig (Kodak) Esports",
                        "Dortmund (vrico) Esports"
                    ],
                    "team_score": [
                        "0",
                        "0"
                    ],
                    "play_time": [
                        "00:00"
                    ],
                    "handicap_list": [
                        "2.5",
                        "2.5"
                    ],
                    "odds_list": [
                        "2.10",
                        "1.66"
                    ]
                },
                {
                    "team_pair": [
                        "Man City (Dimqaa) Esports",
                        "Liverpool (Critic) Esports"
                    ],
                    "team_score": [
                        "2",
                        "0"
                    ],
                    "play_time": [
                        "06:26"
                    ],
                    "handicap_list": [
                        "3.5",
                        "3.5"
                    ],
                    "odds_list": [
                        "2.20",
                        "1.61"
                    ]
                },
                {
                    "team_pair": [
                        "Man Utd (Stig) Esports",
                        "Tottenham (CarlWhizzer) Esports"
                    ],
                    "team_score": [
                        "2",
                        "1"
                    ],
                    "play_time": [
                        "05:58"
                    ],
                    "handicap_list": [
                        "4.5",
                        "4.5"
                    ],
                    "odds_list": [
                        "1.61",
                        "2.20"
                    ]
                }
            ]
        },
        "sync_time": 1606899119
    }
}
```

