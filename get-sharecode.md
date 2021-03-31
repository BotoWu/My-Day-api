###### tags: `timetable`
# get-sharecode 取得分享碼
## /get-sharecode
front to back

| 說明 | key        | value  |
| ---- | ---------- | ------ |
| 帳號 | uid         | string |
| 學年 | schoolYear | string |
| 學期 | semester   | string |


back to front

| 說明   | key       | value  |
| ------ | --------- | ------ |
| 分享碼 | shareCode | string |

---
uid:
 >account>uid

schoolYear:
 >personal_timetable>semester

兩個會合起來存回資料庫

semester:
 >personal_timetable>semester

---
* **分享碼 shareCode:**  
學年+學期+課表編號  
    ```
    ex:109學年第一學期的課表編號是12345
        則分享碼為1090112345
    ```
