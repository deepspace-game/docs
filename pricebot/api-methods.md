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
This endpoint allows you to get free cakes.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Price successfully retrieved.
{% endapi-method-response-example-description %}

```
{"price":0.06260323695247162,"TOKEN_BNB":0.0001329353463709432,"BNB_USD":470.92995701672425}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



