---
description: >-
  Describes supported calls for the Token Stats service provided by the
  DEEPSPACE Team
---

# API Methods

{% hint style="warning" %}
_**IN DEVELOPMENT - Content subject to change**_
{% endhint %}

{% api-method method="get" host="https://token.deepspace.game" path="/api/totalsupply" %}
{% api-method-summary %}
Total Supply
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get Total Supply for DEEPSPACE \(DPS\) token
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Total Supply successfully retrieved.
{% endapi-method-response-example-description %}

```
89862942.99096464
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=400 %}
{% api-method-response-example-description %}
Invalid command sent.
{% endapi-method-response-example-description %}

```
invalid command
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://token.deepspace.game" path="/api/circulatingsupply" %}
{% api-method-summary %}
Circulating Supply
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get Circulating Supply for DEEPSPACE \(DPS\) token.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Circulating Supply successfully retrieved.
{% endapi-method-response-example-description %}

```
58007555.857481994
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=400 %}
{% api-method-response-example-description %}
Invalid command sent.
{% endapi-method-response-example-description %}

```
invalid command
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://token.deepspace.game" path="/api/price" %}
{% api-method-summary %}
Price
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get Price for DEEPSPACE \(DPS\) token.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
0.07179762303241174
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=400 %}
{% api-method-response-example-description %}
Invalid command sent.
{% endapi-method-response-example-description %}

```
invalid command
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://token.deepspace.game" path="/api" %}
{% api-method-summary %}
Token Information
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get token information for DEEPSPACE \(DPS\).
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Token information successfully retrieved.
{% endapi-method-response-example-description %}

```
{
  "contract": "0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C",
  "name": "DEEPSPACE",
  "symbol": "DPS",
  "divisor": 9,
  "burn_address": "0x000000000000000000000000000000000000dead",
  "burned": 10137057.009035368,
  "price": 0.07976675065729347,
  "volume": 4532.85,
  "maximum_supply": 100000000,
  "total_supply": 89862942.99096464,
  "market_cap": 4627074.244322789,
  "circulating_supply": 58007555.857481994,
  "total_liquidity": 5149279.828533681,
  "liquidity_ratio": 8.87691224430293,
  "social_score": 20666,
  "total_transactions": 7346,
  "holders": 4082,
  "median_transfer": 1560.527544557,
  "average_transfer": 47722.52247471674,
  "total_transfer": 350569650.099269,
  "days_active": 29,
  "senders": 1144,
  "first_day_active": "2021-08-02",
  "last_day_active": "2021-08-30",
  "launch_date": "2021-08-23",
  "short_description": "DEEPSPACE – A revolutionary evolving platform that leverages and gamifies risk for dynamic yield generating strategies!",
  "long_description": "Our project combines frictionless passive income and play-to-earn mechanics that directly reward you for playing!\r\n\r\nEarn through sharing transaction tax rewards and creating, owning, upgrading, and fighting with spacecraft!\r\n\r\nA blockchain-based Play-to-Earn game with a supporting NFT marketplace is currently under development.\r\n\r\nGrab a starship and explore the galaxy of DEEPSPACE. Travel to the edges of the galaxy to mine, build, and battle!",
  "platform": "BEP20",
  "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C",
  "key_wallet_list": [
    {
      "address": "0xaCc34268f5D7Cb9B11BfB1ba4D8bD2bc2B49EE4E",
      "tag": "Core Team Multi-Sig",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 21718326.087505683,
      "percentage": 24.168278229758595,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0xaCc34268f5D7Cb9B11BfB1ba4D8bD2bc2B49EE4E"
    },
    {
      "address": "0x83F2cd3881aEfd6ABF3997f7c132F6273CAFfBe9",
      "tag": "Game Dev Multi-Sig",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 6082234.20542122,
      "percentage": 6.768345218821471,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0x83F2cd3881aEfd6ABF3997f7c132F6273CAFfBe9"
    },
    {
      "address": "0x7c5705e10D6b1700aCa01274a53Be25292357809",
      "tag": "Solidity Dev Multi-Sig",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 3041117.10271061,
      "percentage": 3.3841726094107356,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0x7c5705e10D6b1700aCa01274a53Be25292357809"
    },
    {
      "address": "0xbdAed74Fc8b18d6c99122c2076068444941da5A4",
      "tag": "Flex / Marketing Multi-Sig",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 1013705.700903536,
      "percentage": 1.1280575364702445,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0xbdAed74Fc8b18d6c99122c2076068444941da5A4"
    },
    {
      "address": "0xdc198708112Cc391927239cC1F4BDc086b0C1F35",
      "tag": "Binance BUIDL Rewards",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 2.027411401,
      "percentage": 0.000002256115072042375,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0xdc198708112Cc391927239cC1F4BDc086b0C1F35"
    },
    {
      "address": "0x4617bd5b57ab47dd6f72e6372d52c426fc5a3e82",
      "tag": "Deepspace - Deployer",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 2.009530196,
      "percentage": 0.000002236216764236233,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0x4617bd5b57ab47dd6f72e6372d52c426fc5a3e82"
    },
    {
      "address": "0x18be965c08923fe3d957503c108e264bef0d5669",
      "tag": "PancakeSwap V2: DPS 14",
      "owner": "Liquidity Provisioning",
      "status": "Unlocked",
      "exclude_circulating_supply": "False",
      "balance": 5149279.828533681,
      "percentage": 5.730148220330844,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0x18be965c08923fe3d957503c108e264bef0d5669"
    }
  ],
  "logo_list": [
    {
      "logo_size": "512x512",
      "logo_url": "https://dps.fyi/tkn-logo-512"
    },
    {
      "logo_size": "256x256",
      "logo_url": "https://dps.fyi/tkn-logo-256"
    },
    {
      "logo_size": "200x200",
      "logo_url": "https://dps.fyi/tkn-logo-200"
    },
    {
      "logo_size": "96x96",
      "logo_url": "https://dps.fyi/tkn-logo-96"
    },
    {
      "logo_size": "32x32",
      "logo_url": "https://dps.fyi/tkn-logo-32"
    }
  ],
  "last_updated": "Mon Aug 30 2021 15:09:13 GMT+0000 (Coordinated Universal Time)"
}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=400 %}
{% api-method-response-example-description %}
Invalid command sent.
{% endapi-method-response-example-description %}

```
invalid command
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



