---
description: >-
  Describes supported calls for the Pricebot service provided by the DEEPSPACE
  Team
---

# API Methods

{% hint style="warning" %}
_**IN DEVELOPMENT - Content subject to change**_
{% endhint %}

{% api-method method="get" host="https://token.deepspace.game" path="/price" %}
{% api-method-summary %}
Price
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get the Price for DEEPSPACE \(DPS\) token and for Binance Coin \(BNB\).
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Price successfully retrieved.
{% endapi-method-response-example-description %}

```
{"price":0.029047851950416766,"TOKEN_BNB":0.00007096305321524767,"BNB_USD":409.3376853770339}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



