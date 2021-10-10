---
description: Describes supported calls for the Token Stats service provided by the DEEPSPACE Team
---
# API Methods

{% hint style="warning" %}
_**IN DEVELOPMENT - Content subject to change**_
{% endhint %}

{% swagger baseUrl="https://token.deepspace.game" path="/api/totalsupply" method="get" summary="Total Supply" %}
{% swagger-description %}
This endpoint allows you to get Total Supply for DEEPSPACE (DPS) token
{% endswagger-description %}

{% swagger-response status="200" description="Total Supply successfully retrieved." %}
```
89862942.99096464
```
{% endswagger-response %}

{% swagger-response status="400" description="Invalid command sent." %}
```
invalid command
```
{% endswagger-response %}
{% endswagger %}

{% swagger baseUrl="https://token.deepspace.game" path="/api/circulatingsupply" method="get" summary="Circulating Supply" %}
{% swagger-description %}
This endpoint allows you to get Circulating Supply for DEEPSPACE (DPS) token.
{% endswagger-description %}

{% swagger-response status="200" description="Circulating Supply successfully retrieved." %}
```
58007555.857481994
```
{% endswagger-response %}

{% swagger-response status="400" description="Invalid command sent." %}
```
invalid command
```
{% endswagger-response %}
{% endswagger %}

{% swagger baseUrl="https://token.deepspace.game" path="/api/holders" method="get" summary="" %}
{% swagger-description %}
This endpoint allows you to get Holders for DEEPSPACE (DPS) token.
{% endswagger-description %}

{% swagger-response status="200" description="" %}
```
3576
```
{% endswagger-response %}

{% swagger-response status="400" description="Invalid command sent." %}
```
invalid command
```
{% endswagger-response %}
{% endswagger %}

{% swagger baseUrl="https://token.deepspace.game" path="/api/price" method="get" summary="Price" %}
{% swagger-description %}
This endpoint allows you to get Price for DEEPSPACE (DPS) token.
{% endswagger-description %}

{% swagger-response status="200" description="" %}
```
0.07179762303241174
```
{% endswagger-response %}

{% swagger-response status="400" description="Invalid command sent." %}
```
invalid command
```
{% endswagger-response %}
{% endswagger %}

{% swagger baseUrl="https://token.deepspace.game" path="/api" method="get" summary="Token Information" %}
{% swagger-description %}
This endpoint allows you to get token information for DEEPSPACE (DPS).
{% endswagger-description %}

{% swagger-response status="200" description="Token information successfully retrieved." %}
```
{
  "contract": "0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C",
  "name": "DEEPSPACE",
  "symbol": "DPS",
  "divisor": 9,
  "burn_address": "0x000000000000000000000000000000000000dead",
  "burned": 10257261.068428513,
  "price": 0.029062313177140267,
  "volume": 16200.31,
  "maximum_supply": 100000000,
  "total_supply": 89742738.93157148,
  "market_cap": 1671272.866891683,
  "circulating_supply": 57506532.83188301,
  "total_liquidity": 8301395.935525442,
  "liquidity_ratio": 14.435570233027414,
  "social_score": 20666,
  "total_transactions": 9826,
  "receivers": 4662,
  "holders": 3576,
  "median_transfer": 1708.445561414,
  "average_transfer": 38360.96875949132,
  "total_transfer": 376934879.0307616,
  "days_active": 44,
  "senders": 1768,
  "first_day_active": "2021-08-02",
  "last_day_active": "2021-09-14",
  "launch_date": "2021-08-23",
  "launch_price": 0.04,
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
      "balance": 21978940.94644877,
      "percentage": 24.491052098607813,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0xaCc34268f5D7Cb9B11BfB1ba4D8bD2bc2B49EE4E"
    },
    {
      "address": "0x83F2cd3881aEfd6ABF3997f7c132F6273CAFfBe9",
      "tag": "Game Dev Multi-Sig",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 6154356.641057107,
      "percentage": 6.857776700742087,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0x83F2cd3881aEfd6ABF3997f7c132F6273CAFfBe9"
    },
    {
      "address": "0x7c5705e10D6b1700aCa01274a53Be25292357809",
      "tag": "Solidity Dev Multi-Sig",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 3077178.320528553,
      "percentage": 3.4288883503710426,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0x7c5705e10D6b1700aCa01274a53Be25292357809"
    },
    {
      "address": "0xbdAed74Fc8b18d6c99122c2076068444941da5A4",
      "tag": "Flex / Marketing Multi-Sig",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 1025726.106842851,
      "percentage": 1.1429627834570144,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0xbdAed74Fc8b18d6c99122c2076068444941da5A4"
    },
    {
      "address": "0xdc198708112Cc391927239cC1F4BDc086b0C1F35",
      "tag": "Binance BUIDL Rewards",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 2.051452213,
      "percentage": 0.0000022859255661499534,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0xdc198708112Cc391927239cC1F4BDc086b0C1F35"
    },
    {
      "address": "0x4617bd5b57ab47dd6f72e6372d52c426fc5a3e82",
      "tag": "Deepspace - Deployer",
      "owner": "Team",
      "status": "Unlocked",
      "exclude_circulating_supply": "True",
      "balance": 2.033358974,
      "percentage": 0.000002265764337269034,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0x4617bd5b57ab47dd6f72e6372d52c426fc5a3e82"
    },
    {
      "address": "0x18be965c08923fe3d957503c108e264bef0d5669",
      "tag": "PancakeSwap V2: DPS 14",
      "owner": "Liquidity Provisioning",
      "status": "Unlocked",
      "exclude_circulating_supply": "False",
      "balance": 8301395.935525442,
      "percentage": 9.250214596030132,
      "explorer_link": "https://bscscan.com/token/0xf275e1AC303a4C9D987a2c48b8E555A77FeC3F1C?a=0x18be965c08923fe3d957503c108e264bef0d5669"
    }
  ],
  "logo_list": [
    {
      "logo_size": "SVG",
      "logo_url": "https://dps.fyi/tkn-logo-svg"
    },
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
    },
    {
      "logo_size": "1000x1000-animated",
      "logo_url": "https://dps.fyi/tkn-logo-anm-1000"
    },
    {
      "logo_size": "512x512-animated",
      "logo_url": "https://dps.fyi/tkn-logo-anm-512"
    }
  ],
  "last_updated": "Tue Sep 14 2021 15:35:32 GMT+0000 (Coordinated Universal Time)"
}
```
{% endswagger-response %}

{% swagger-response status="400" description="Invalid command sent." %}
```
invalid command
```
{% endswagger-response %}
{% endswagger %}

