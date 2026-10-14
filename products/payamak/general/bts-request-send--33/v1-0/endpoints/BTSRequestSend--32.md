---
hub_id: 33
product: "payamak"
version: "1.0"
type: "api-endpoint"
endpoint_id: 32
source: amoot-hub
---

# وب سرویس ارسال BTS

**Protocol:** `Rest`  
**Method:** `POST`  
**Path:** `/rest/BTSRequestSend`

با استفاده از این متد می‌‍توانید بعد از آماده بودن آن ، یکبار ارسال انجام دهید

## Parameters

| Name | In | Type | Required | Description |
| --- | --- | --- | --- | --- |
| Token | Header | String | Yes | توکن ثبت شده در سامانه پیامک آموت |
| BTSRequestID | Body | Int | Yes | کد درخواست BTS که از متد BTSRequestCreate بعد از ثبت موفق بدست آورده میشود |
| SMSMessageText | Body | String | Yes | متن پیامک |
| SendDateTime | Body | DateTime | Yes | تاریخ/زمان ارسال |
| SendCount | Body | Int | Yes | حداکثر تعداد ارسال کل |

[بازگشت به فهرست مستند](../README.md)
