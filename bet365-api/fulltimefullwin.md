---
description: Please contact us by Telegram to get token.
---

# FullTimeFullWin API

## HTTP Request

`GET http://api.bet365data.com/bet365/api/fullTimeFullWin`

### 

### Request Header

| Parameter | Required? | Description |
| :--- | :--- | :--- |
| Authorization | Yes | Please contact to get 7 days free trial |
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
    "code": 0,
    "data": {
        "list": [
            {
                "handicap_list": [],
                "odds_list": [
                    "4.33",
                    "2.00",
                    "3.00"
                ],
                "play_time": [
                    "66:28"
                ],
                "team_pair": [
                    "Karlsruher SC",
                    "Greuther Furth"
                ],
                "team_score": [
                    "2",
                    "2"
                ]
            },
            {
                "handicap_list": [],
                "odds_list": [],
                "play_time": [
                    "69:38"
                ],
                "team_pair": [
                    "Sandhausen",
                    "Heidenheim"
                ],
                "team_score": [
                    "3",
                    "0"
                ]
            },
            {
                "handicap_list": [],
                "odds_list": [
                    "3.10",
                    "3.10",
                    "2.45"
                ],
                "play_time": [
                    "00:00"
                ],
                "team_pair": [
                    "Chateauroux",
                    "Guingamp"
                ],
                "team_score": [
                    "0",
                    "0"
                ]
            },
            {
                "handicap_list": [],
                "odds_list": [
                    "6.00",
                    "4.00",
                    "1.60"
                ],
                "play_time": [
                    "00:00"
                ],
                "team_pair": [
                    "Dunkerque",
                    "Troyes"
                ],
                "team_score": [
                    "0",
                    "0"
                ]
            },
            {
                "handicap_list": [],
                "odds_list": [
                    "2.15",
                    "3.00",
                    "3.75"
                ],
                "play_time": [
                    "00:00"
                ],
                "team_pair": [
                    "Le Havre",
                    "Valenciennes"
                ],
                "team_score": [
                    "0",
                    "0"
                ]
            },
            {
                "handicap_list": [],
                "odds_list": [
                    "2.20",
                    "2.90",
                    "3.75"
                ],
                "play_time": [
                    "00:00"
                ],
                "team_pair": [
                    "Nancy",
                    "Rodez"
                ],
                "team_score": [
                    "0",
                    "0"
                ]
            },
            {
                "handicap_list": [],
                "odds_list": [
                    "3.00",
                    "3.10",
                    "2.50"
                ],
                "play_time": [
                    ""
                ],
                "team_pair": [
                    "Niort",
                    "Amiens"
                ],
                "team_score": [
                    "0",
                    "0"
                ]
            },
            {
                "handicap_list": [],
                "odds_list": [
                    "2.30",
                    "3.00",
                    "3.50"
                ],
                "play_time": [
                    ""
                ],
                "team_pair": [
                    "Paris FC",
                    "AC Ajaccio"
                ],
                "team_score": [
                    "0",
                    "0"
                ]
            },
            {
                "handicap_list": [],
                "odds_list": [
                    "2.80",
                    "2.90",
                    "2.60"
                ],
                "play_time": [
                    ""
                ],
                "team_pair": [
                    "Pau",
                    "Chambly Thelle FC"
                ],
                "team_score": [
                    "0",
                    "0"
                ]
            }
        ],
        "total": 9,
        "channel": "Fulltime Result",
        "sync_time": 1610132262
    },
    "msg": "Success"
}
```

