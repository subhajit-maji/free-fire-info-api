# 📊 Free Fire UID Info API

## 📝 Description

This API allows you to **retrieve detailed information about a Free Fire account** using its `UID`. It provides data such as level, rank, guild information, credit score, profile, social preferences, and much more.

Designed for developers, analysts, or Free Fire bot creators, this API is lightweight, fast, and deployed via **Vercel**.

---

## 🪪 Account Info Endpoint

-   **Endpoint**: `/info`
-   **Method**: `GET`

### 📌 Description

This endpoint returns **complete information about a Free Fire player** based on their UID, including:
-   Rank data (Battle Royale and Clash Squad)
-   Guild information
-   Social preferences
-   Account level
-   Pet details
-   And more.

---

## ☑️ Query Parameters

| Parameter | Type | Required | Description |
|---|---|---|---|
| `uid` | int | ✅ | The unique identifier of the Free Fire player |

---

## 📨 Request Example

`GET https://glob-info2.vercel.app/info?uid=306000592`

This request returns information related to UID `305000592`.

---

## 🔁 API Endpoints

### `GET /info?uid={uid}`

Retrieves information related to a Free Fire account using its UID.

---

## 🔄 Example Response

```json
{
  "basicInfo": {
    "accountId": "305000592",
    "accountPrefers": {

    },
    "accountType": 1,
    "badgeCnt": 95,
    "badgeId": 1001000086,
    "bannerId": 901000277,
    "createAt": "1531465844",
    "csMaxRank": 324,
    "csRank": 324,
    "csRankingPoints": 230,
    "exp": 6412539,
    "externalIconInfo": {
      "showType": "ExternalIconShowType_FRIEND",
      "status": "ExternalIconStatus_NOT_IN_USE"
    },
    "headPic": 902000307,
    "lastLoginAt": "1753006875",
    "level": 79,
    "liked": 28052,
    "maxRank": 321,
    "nickname": "XVㅤLEVISCOㅤ✿",
    "rank": 321,
    "rankingPoints": 3714,
    "region": "ME",
    "releaseVersion": "OB49",
    "seasonId": 46,
    "showBrRank": true,
    "showCsRank": true,
    "socialHighLightsWithBasicInfo": {

    },
    "title": 904090027,
    "weaponSkinShows": [907193007, 912049001, 914000002]
  },
  "captainBasicInfo": {
    "accountId": "2481443304",
    "accountPrefers": {

    },
    "accountType": 1,
    "badgeCnt": 115,
    "badgeId": 1001000086,
    "bannerId": 901041003,
    "createAt": "1603730606",
    "csMaxRank": 324,
    "csRank": 324,
    "csRankingPoints": 282,
    "exp": 1828874,
    "externalIconInfo": {
      "showType": "ExternalIconShowType_FRIEND",
      "status": "ExternalIconStatus_NOT_IN_USE"
    },
    "gameBagShow": 904030004,
    "headPic": 902036015,
    "lastLoginAt": "1753008413",
    "level": 65,
    "liked": 6711,
    "maxRank": 324,
    "nickname": "ӾVㅤSANO̴̴ㅤ㊧",
    "pinId": 910039001,
    "rank": 324,
    "rankingPoints": 5372,
    "region": "ME",
    "releaseVersion": "OB49",
    "seasonId": 46,
    "showBrRank": true,
    "showCsRank": true,
    "socialHighLightsWithBasicInfo": {

    },
    "title": 904090024,
    "weaponSkinShows": [907193305, 912048002, 914048001]
  },
  "clanBasicInfo": {
    "capacity": 50,
    "captainId": "2481443304",
    "clanId": "3069805922",
    "clanLevel": 6,
    "clanName": "XTREMㅤVOLT",
    "memberNum": 43
  },
  "creditScoreInfo": {
    "creditScore": 100,
    "periodicSummaryEndTime": "1752947646",
    "rewardState": "REWARD_STATE_UNCLAIMED"
  },
  "diamondCostRes": {
    "diamondCost": 390
  },
  "petInfo": {
    "exp": 6025,
    "id": 1300000091,
    "isMarkedStar": true,
    "isSelected": true,
    "level": 7,
    "name": "ZOULOU",
    "selectedSkillId": 1315000010,
    "skinId": 1310000093
  },
  "profileInfo": {
    "avatarId": 102000020,
    "clothes": [50],
    "endTime": 1,
    "equipedSkills": [203000547, 204000783, 205000590, 211000041, 214000062],
    "pvePrimaryWeapon": 1
  },
  "socialInfo": {
    "accountId": "305000592",
    "gender": "Gender_FEMALE",
    "language": "Language_FRENCH",
    "modePrefer": "ModePrefer_BR",
    "rankShow": "RankShow_BR",
    "signature": "[b][c][00FFFF] TUTORIAL !!!",
    "timeActive": "TimeActive_MORNING",
    "timeOnline": "TimeOnline_WEEKEND"
  }
}
 

