---
description: Describes supported calls for the Pricebot service provided by the DEEPSPACE Team
---
# API Methods

{% hint style="warning" %}
_**IN DEVELOPMENT - Content subject to change**_
{% endhint %}

{% swagger baseUrl="https://token.deepspace.game" path="/price" method="get" summary="Price" %}
{% swagger-description %}
This endpoint allows you to get the Price for DEEPSPACE (DPS) token and for Binance Coin (BNB).
{% endswagger-description %}

{% swagger-response status="200" description="Price successfully retrieved." %}
```
{"price":0.029047851950416766,"TOKEN_BNB":0.00007096305321524767,"BNB_USD":409.3376853770339}
```
{% endswagger-response %}
{% endswagger %}

