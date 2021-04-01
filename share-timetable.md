###### tags: `timetable`
# share-timetable 分享課表
## /share-timetable
front to back

| 說明 | key        | value |
| ---- | ---------- | ----- |
| 帳號 | uid         | string      |
| 分享種類編號 | shareTypeId   | int      |
| 對象 | toId       | string      |
| 課表編號 | timetableId | int      |
| 學年 | schoolYear | string      |
| 學期 | semester   | string      |


back to front

| 說明         | key      | value |
| ------------ | -------- | ----- |
| 分享課表結果 | response | bool  |

---
uid:
 >account>uid

shareTypeId:
 >判斷他是要傳給某人或是某個群組

toId:
 >account>uid

timetableId:
 >personal_timetable>timetable_no

schoolYear:
 >personal_timetable>semester

兩個會合起來存回資料庫

semester:
 >personal_timetable>semester

---
* **類型編號 typeId:**
    1. 好友
    2. 群組