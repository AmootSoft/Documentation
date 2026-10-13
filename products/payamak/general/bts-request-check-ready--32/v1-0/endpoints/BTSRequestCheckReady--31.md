---
hub_id: 32
product: "payamak"
version: "1.0"
type: "api-endpoint"
endpoint_id: 31
source: amoot-hub
---

# بررسی وضعیت آماده بودن درخواست BTS

**Protocol:** `Rest`  
**Method:** `POST`  
**Path:** `/rest/BTSRequestCheckReady`

با این متد میتوانید وضعیت آماده بودن درخواست BTS برای ارسال را دریافت کنید

## Parameters

| Name | In | Type | Required | Description |
| --- | --- | --- | --- | --- |
| Token | Header | String | Yes | توکن ثبت شده در سامانه پیامک آموت |
| BTSRequestID | Body | Int | Yes | کد درخواست BTS که از متد BTSRequestCreate بعد از ثبت موفق بدست آورده میشود |

[بازگشت به فهرست مستند](../README.md)
