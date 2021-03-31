###### tags: `timetable`
# sharecode-accept-timetable 分享碼接受課表
## /sharecode-accept-timetable
front to back

| 說明   | key       | value  |
| ------ | --------- | ------ |
| 帳號   | uid        | string |
| 分享碼 | shareCode | string |


back to front

| 說明               | key      | value |
| ------------------ | -------- | ----- |
| 分享碼接受課表結果 | response | bool  |

---
uid:
 >account>uid

shareCode:
 >


---
**前端注意**  
使用者接收課表成功表示課表資料已經寫入資料庫了，因此只需重整頁面即可得到新課表