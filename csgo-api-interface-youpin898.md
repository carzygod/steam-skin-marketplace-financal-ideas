```
https://market.csgo.com/api/graphql
```

Method

```
Post
```

Payload

```
{
    "operationName": "items",
    "variables": {
        "filters": [
            {
                "id": "type",
                "items": [
                    {
                        "id": "Container"
                    }
                ]
            }
        ],
        "order": {
            "id": "popularity",
            "direction": "desc"
        },
        "page": 0,
        "count": 720
    },
    "query": "query items($count: Int, $filters: [FilterInputType], $page: Int, $order: OrderInputType!) {\n  items(count: $count, filters: $filters, page: $page, order: $order) {\n    paginatorInfo {\n      count\n      currentPage\n      hasMorePages\n      lastPage\n      perPage\n      total\n      __typename\n    }\n    filters {\n      id\n      items {\n        color\n        enabled\n        id\n        name\n        value\n        image\n        __typename\n      }\n      max\n      min\n      name\n      order\n      type\n      value\n      __typename\n    }\n    meta {\n      title\n      description\n      __typename\n    }\n    data {\n      color\n      id\n      currency\n      stattrak\n      slot\n      popularity\n      features\n      rarity\n      rarity_ext {\n        id\n        name\n        __typename\n      }\n      ctp\n      quality\n      phase\n      descriptions {\n        type\n        value\n        __typename\n      }\n      type\n      tags {\n        category\n        category_name\n        localized_category_name\n        localized_tag_name\n        internal_name\n        name\n        value {\n          name\n          link\n          __typename\n        }\n        __typename\n      }\n      image_512\n      image_100\n      image_150\n      image_300\n      seo {\n        category\n        type\n        __typename\n      }\n      market_hash_name\n      market_name\n      price\n      stickers {\n        image\n        name\n        __typename\n      }\n      __typename\n    }\n    paginatorInfo {\n      count\n      currentPage\n      hasMorePages\n      lastPage\n      perPage\n      total\n      __typename\n    }\n    __typename\n  }\n}"
}
```

```
{
  "operationName": "items",
  "variables": {
    "filters": [
      {
        "id": "type",
        "items": [
          {
            "id": "Container"
          }
        ]
      }
    ],
    "order": {
      "id": "popularity",
      "direction": "desc"
    },
    "page": 0,
    "count": 720
  },
  "query": "query items($count: Int, $filters: [FilterInputType], $page: Int, $order: OrderInputType!) {\n  items(count: $count, filters: $filters, page: $page, order: $order) {\n    paginatorInfo {\n      count\n      currentPage\n      hasMorePages\n      lastPage\n      perPage\n      total\n      __typename\n    }\n    filters {\n      id\n      items {\n        color\n        enabled\n        id\n        name\n        value\n        image\n        __typename\n      }\n      max\n      min\n      name\n      order\n      type\n      value\n      __typename\n    }\n    meta {\n      title\n      description\n      __typename\n    }\n    data {\n      color\n      id\n      currency\n      stattrak\n      slot\n      popularity\n      features\n      rarity\n      rarity_ext {\n        id\n        name\n        __typename\n      }\n      ctp\n      quality\n      phase\n      descriptions {\n        type\n        value\n        __typename\n      }\n      type\n      tags {\n        category\n        category_name\n        localized_category_name\n        localized_tag_name\n        internal_name\n        name\n        value {\n          name\n          link\n          __typename\n        }\n        __typename\n      }\n      image_512\n      image_100\n      image_150\n      image_300\n      seo {\n        category\n        type\n        __typename\n      }\n      market_hash_name\n      market_name\n      price\n      stickers {\n        image\n        name\n        __typename\n      }\n      __typename\n    }\n    paginatorInfo {\n      count\n      currentPage\n      hasMorePages\n      lastPage\n      perPage\n      total\n      __typename\n    }\n    __typename\n  }\n}"
}
```



Response

```
{
    "data": {
        "items": {
            "paginatorInfo": {
                "count": 321,
                "currentPage": 0,
                "hasMorePages": false,
                "lastPage": 0,
                "perPage": 400,
                "total": 321,
                "__typename": "ItemsPaginator"
            },
            "filters": [
                {
                    "id": "price",
                    "items": [],
                    "max": 1465.979,
                    "min": 0.139,
                    "name": "Search by price",
                    "order": 1,
                    "type": "RANGE",
                    "value": "",
                    "__typename": "FilterType"
                },
                {
                    "id": "stickers",
                    "items": [],
                    "max": null,
                    "min": null,
                    "name": "Sticker search",
                    "order": 8,
                    "type": "SMART_SEARCH",
                    "value": null,
                    "__typename": "FilterType"
                }
            ],
            "meta": {
                "title": "CS:GO Cases | Buy, Sell On Market CS:GO",
                "description": "Buy, Sell CS:GO Caseson one of the best CS:GO marketplace for trading in-game items and skins. Find the Best Prices on CS:GO Skins &amp;amp;amp; Items at Market CS:GO.",
                "__typename": "MetaTypeItems"
            },
            "data": [
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4944,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 19,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Kilowatt%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Kilowatt%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Kilowatt%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Kilowatt%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Kilowatt Case",
                    "market_name": "Kilowatt Case",
                    "price": 4.561,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2749,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 28,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Operation%20Breakout%20Weapon%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Operation%20Breakout%20Weapon%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Operation%20Breakout%20Weapon%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Operation%20Breakout%20Weapon%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Operation Breakout Weapon Case",
                    "market_name": "Operation Breakout Weapon Case",
                    "price": 4.673,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 901,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 20,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Operation%20Riptide%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Operation%20Riptide%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Operation%20Riptide%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Operation%20Riptide%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Operation Riptide Case",
                    "market_name": "Operation Riptide Case",
                    "price": 4.111,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 351,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Vertigo%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Vertigo%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Vertigo%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Vertigo%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Vertigo Souvenir Package",
                    "market_name": "Antwerp 2022 Vertigo Souvenir Package",
                    "price": 6.069,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 129,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Huntsman%20Weapon%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Huntsman%20Weapon%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Huntsman%20Weapon%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Huntsman%20Weapon%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Huntsman Weapon Case",
                    "market_name": "Huntsman Weapon Case",
                    "price": 6.342,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 124,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 19,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/eSports%202014%20Summer%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/eSports%202014%20Summer%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/eSports%202014%20Summer%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/eSports%202014%20Summer%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "eSports 2014 Summer Case",
                    "market_name": "Летний кейс eSports 2014",
                    "price": 5.845,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 115,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 14,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Dust%20II%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Dust%20II%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Dust%20II%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Dust%20II%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Dust II Souvenir Package",
                    "market_name": "Stockholm 2021 Dust II Souvenir Package",
                    "price": 5.45,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 108,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 17,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case%202/512.png",
                    "image_100": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case%202/100.png",
                    "image_150": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case%202/150.png",
                    "image_300": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case%202/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "CS:GO Weapon Case 2",
                    "market_name": "CS:GO Weapon Case 2",
                    "price": 10.009,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 94,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Operation%20Hydra%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Operation%20Hydra%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Operation%20Hydra%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Operation%20Hydra%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Operation Hydra Case",
                    "market_name": "Operation Hydra Case",
                    "price": 13.29,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 87,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "CS:GO Weapon Case",
                    "market_name": "CS:GO Weapon Case",
                    "price": 66,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 72,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 19,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Operation%20Bravo%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Operation%20Bravo%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Operation%20Bravo%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Operation%20Bravo%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Operation Bravo Case",
                    "market_name": "Operation Bravo Case",
                    "price": 33.663,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 61,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 19,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case%203/512.png",
                    "image_100": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case%203/100.png",
                    "image_150": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case%203/150.png",
                    "image_300": "https://cdn2.csgo.com/item/CS%3AGO%20Weapon%20Case%203/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "CS:GO Weapon Case 3",
                    "market_name": "Оружейный кейс CS:GO, тираж #3",
                    "price": 5.35,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 60,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 19,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Sticker%20Capsule%202/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Sticker%20Capsule%202/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Sticker%20Capsule%202/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Sticker%20Capsule%202/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Sticker Capsule 2",
                    "market_name": "Sticker Capsule 2",
                    "price": 14.124,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 48,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 33,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Collectible%20Pins%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Collectible%20Pins%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Collectible%20Pins%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Collectible%20Pins%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Half-Life: Alyx Collectible Pins Capsule",
                    "market_name": "Half-Life: Alyx Collectible Pins Capsule",
                    "price": 5.7,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 42,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 27,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Winter%20Offensive%20Weapon%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Winter%20Offensive%20Weapon%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Winter%20Offensive%20Weapon%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Winter%20Offensive%20Weapon%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Winter Offensive Weapon Case",
                    "market_name": "Winter Offensive Weapon Case",
                    "price": 4.037,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 36,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%203/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%203/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%203/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%203/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Collectible Pins Capsule Series 3",
                    "market_name": "Collectible Pins Capsule Series 3",
                    "price": 6.849,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 34,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%201/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%201/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%201/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%201/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Collectible Pins Capsule Series 1",
                    "market_name": "Collectible Pins Capsule Series 1",
                    "price": 6.229,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 33,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 19,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/eSports%202013%20Winter%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/eSports%202013%20Winter%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/eSports%202013%20Winter%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/eSports%202013%20Winter%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "eSports 2013 Winter Case",
                    "market_name": "eSports 2013 Winter Case",
                    "price": 6.453,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": true,
                    "slot": "",
                    "popularity": 29,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 7,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Masterminds%20Music%20Kit%20Box/512.png",
                    "image_100": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Masterminds%20Music%20Kit%20Box/100.png",
                    "image_150": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Masterminds%20Music%20Kit%20Box/150.png",
                    "image_300": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Masterminds%20Music%20Kit%20Box/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "StatTrak™ Masterminds Music Kit Box",
                    "market_name": "StatTrak™ Masterminds Music Kit Box",
                    "price": 6.827,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 28,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Legends%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Legends%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Legends%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Legends%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Legends Autograph Capsule",
                    "market_name": "Katowice 2019 Legends Autograph Capsule",
                    "price": 4.18,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 23,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Cologne%202016%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Cologne%202016%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Cologne%202016%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Cologne%202016%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Cologne 2016 Challengers (Holo-Foil)",
                    "market_name": "Cologne 2016 Challengers (Holo/Foil)",
                    "price": 42.106,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 22,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 25,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Minor%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Minor%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Minor%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Minor%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Minor Challengers Autograph Capsule",
                    "market_name": "Katowice 2019 Minor Challengers Autograph Capsule",
                    "price": 6.572,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 21,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 20,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%202/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%202/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%202/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Collectible%20Pins%20Capsule%20Series%202/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Collectible Pins Capsule Series 2",
                    "market_name": "Collectible Pins Capsule Series 2",
                    "price": 6.702,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 16,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 25,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Legends%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Legends%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Legends%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Legends%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Legends (Holo-Foil)",
                    "market_name": "Katowice 2019 Legends (Holo/Foil)",
                    "price": 7.53,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 15,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "MLG Columbus 2016 Challengers (Holo-Foil)",
                    "market_name": "Претенденты MLG Columbus 2016 (голографические/металлические)",
                    "price": 45.609,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 12,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Contenders%20Patch%20Pack/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Contenders%20Patch%20Pack/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Contenders%20Patch%20Pack/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Contenders%20Patch%20Pack/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Contenders Patch Pack",
                    "market_name": "Stockholm 2021 Contenders Patch Pack",
                    "price": 5.892,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 10,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 27,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Dust%20II%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Dust%20II%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Dust%20II%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Dust%20II%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Dust II Souvenir Package",
                    "market_name": "Antwerp 2022 Dust II Souvenir Package",
                    "price": 7.178,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 8,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 28,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Minor%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Minor%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Minor%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Minor%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Minor Challengers (Holo-Foil)",
                    "market_name": "Katowice 2019 Minor Challengers (Holo/Foil)",
                    "price": 7.175,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": true,
                    "slot": "",
                    "popularity": 7,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 33,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Initiators%20Music%20Kit%20Box/512.png",
                    "image_100": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Initiators%20Music%20Kit%20Box/100.png",
                    "image_150": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Initiators%20Music%20Kit%20Box/150.png",
                    "image_300": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Initiators%20Music%20Kit%20Box/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "StatTrak™ Initiators Music Kit Box",
                    "market_name": "StatTrak™ Initiators Music Kit Box",
                    "price": 5.445,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 7,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 5,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Legends%20Patch%20Pack/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Legends%20Patch%20Pack/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Legends%20Patch%20Pack/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Legends%20Patch%20Pack/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Legends Patch Pack",
                    "market_name": "Stockholm 2021 Legends Patch Pack",
                    "price": 4.388,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 6,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 14,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Luminosity Gaming | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Luminosity Gaming | MLG Columbus 2016",
                    "price": 5.321,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 6,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Returning%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Returning%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Returning%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Returning%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Returning Challengers Autograph Capsule",
                    "market_name": "Katowice 2019 Returning Challengers Autograph Capsule",
                    "price": 5.081,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 6,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Ancient%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Ancient%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Ancient%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Ancient%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Ancient Souvenir Package",
                    "market_name": "Antwerp 2022 Ancient Souvenir Package",
                    "price": 4.15,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 5,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 32,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Challengers (Foil) | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Challengers (Foil) | Cluj-Napoca 2015",
                    "price": 40.179,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 5,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team EnVyUs | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Team EnVyUs | MLG Columbus 2016",
                    "price": 5.144,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 5,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Astralis | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Astralis | MLG Columbus 2016",
                    "price": 5.602,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 5,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Cloud9 | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Cloud9 | MLG Columbus 2016",
                    "price": 21.719,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Krakow%202017%20Legends%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Krakow%202017%20Legends%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Krakow%202017%20Legends%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Krakow%202017%20Legends%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Krakow 2017 Legends Autograph Capsule",
                    "market_name": "Krakow 2017 Legends Autograph Capsule",
                    "price": 31.664,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 7,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Legends%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Legends%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Legends%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Legends%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Legends Autograph Capsule",
                    "market_name": "London 2018 Legends Autograph Capsule",
                    "price": 10.317,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 20,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Legends%20%28Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Legends%20%28Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Legends%20%28Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Legends%20%28Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Cologne 2015 Legends (Foil)",
                    "market_name": "ESL One Cologne 2015 Legends (Foil)",
                    "price": 15.699,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 15,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Vertigo%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Vertigo%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Vertigo%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Vertigo%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Vertigo Souvenir Package",
                    "market_name": "Rio 2022 Vertigo Souvenir Package",
                    "price": 4.87,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 4,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Overpass%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Overpass%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Overpass%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Overpass%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Overpass Souvenir Package",
                    "market_name": "Stockholm 2021 Overpass Souvenir Package",
                    "price": 4.492,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Challengers%20Patch%20Pack/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Challengers%20Patch%20Pack/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Challengers%20Patch%20Pack/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Challengers%20Patch%20Pack/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Challengers Patch Pack",
                    "market_name": "Stockholm 2021 Challengers Patch Pack",
                    "price": 9.111,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Immunity%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Immunity%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Immunity%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Immunity%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team Immunity | Cologne 2015",
                    "market_name": "Autograph Capsule | Team Immunity | Cologne 2015",
                    "price": 11.04,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 20,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Returning%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Returning%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Returning%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Returning%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Returning Challengers Autograph Capsule",
                    "market_name": "Boston 2018 Returning Challengers Autograph Capsule",
                    "price": 11.239,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 9,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Cologne%202016%20Legends%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Cologne%202016%20Legends%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Cologne%202016%20Legends%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Cologne%202016%20Legends%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Cologne 2016 Legends (Holo-Foil)",
                    "market_name": "Cologne 2016 Legends (Holo/Foil)",
                    "price": 25.199,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 3,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Attending%20Legends%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Attending%20Legends%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Attending%20Legends%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Attending%20Legends%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Attending Legends Autograph Capsule",
                    "market_name": "Boston 2018 Attending Legends Autograph Capsule",
                    "price": 11.946,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 30,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | mousesports | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | mousesports | MLG Columbus 2016",
                    "price": 5.973,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 6,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Kinguin%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Kinguin%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Kinguin%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Kinguin%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team Kinguin | Cologne 2015",
                    "market_name": "Autograph Capsule | Team Kinguin | Cologne 2015",
                    "price": 4.556,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Returning%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Returning%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Returning%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Returning%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Returning Challengers (Holo-Foil)",
                    "market_name": "Katowice 2019 Returning Challengers (Holo/Foil)",
                    "price": 10.781,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 25,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Legends%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Legends%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Legends%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Legends%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Legends (Holo-Foil)",
                    "market_name": "London 2018 Legends (Holo/Foil)",
                    "price": 12.29,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 15,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Returning%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Returning%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Returning%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Returning%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Returning Challengers Autograph Capsule",
                    "market_name": "London 2018 Returning Challengers Autograph Capsule",
                    "price": 9.752,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Overpass%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Overpass%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Overpass%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Overpass%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Overpass Souvenir Package",
                    "market_name": "Antwerp 2022 Overpass Souvenir Package",
                    "price": 4.74,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 22,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Legends/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Legends/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Legends/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Legends/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Cologne 2014 Legends",
                    "market_name": "ESL One Cologne 2014 Legends",
                    "price": 73.467,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 10,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Krakow%202017%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Krakow%202017%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Krakow%202017%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Krakow%202017%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Krakow 2017 Challengers (Holo-Foil)",
                    "market_name": "Krakow 2017 Challengers (Holo/Foil)",
                    "price": 25,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 27,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Overpass%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Overpass%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Overpass%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Overpass%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Overpass Souvenir Package",
                    "market_name": "Berlin 2019 Overpass Souvenir Package",
                    "price": 6.247,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Virtus.Pro | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Virtus.Pro | Cluj-Napoca 2015",
                    "price": 4.742,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Inferno Souvenir Package",
                    "market_name": "Katowice 2019 Inferno Souvenir Package",
                    "price": 12.26,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 25,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20C%20%28Foil%29%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20C%20%28Foil%29%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20C%20%28Foil%29%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20C%20%28Foil%29%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Group C (Foil) | Cologne 2015",
                    "market_name": "Autograph Capsule | Group C (Foil) | Cologne 2015",
                    "price": 16.199,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 36,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team Liquid | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Team Liquid | MLG Columbus 2016",
                    "price": 4.561,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Flipsid3 Tactics | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Flipsid3 Tactics | Cluj-Napoca 2015",
                    "price": 12.003,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Renegades%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Renegades%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Renegades%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Renegades%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Renegades | Cologne 2015",
                    "market_name": "Autograph Capsule | Renegades | Cologne 2015",
                    "price": 7.14,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 8,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Titan%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Titan%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Titan%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Titan%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Titan | Cologne 2015",
                    "market_name": "Autograph Capsule | Titan | Cologne 2015",
                    "price": 16,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Train%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Train%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Train%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Train%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Train Souvenir Package",
                    "market_name": "Katowice 2019 Train Souvenir Package",
                    "price": 12.29,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 15,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Minor%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Minor%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Minor%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Minor%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Minor Challengers Autograph Capsule",
                    "market_name": "London 2018 Minor Challengers Autograph Capsule",
                    "price": 9.774,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 3,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Overpass%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Overpass%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Overpass%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Overpass%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Overpass Souvenir Package",
                    "market_name": "Katowice 2019 Overpass Souvenir Package",
                    "price": 12.91,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Minor%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Minor%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Minor%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Minor%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Minor Challengers (Holo-Foil)",
                    "market_name": "London 2018 Minor Challengers (Holo/Foil)",
                    "price": 18.427,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Dust%20II%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Dust%20II%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Dust%20II%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Dust%20II%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Dust II Souvenir Package",
                    "market_name": "Berlin 2019 Dust II Souvenir Package",
                    "price": 10.811,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 12,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Challengers/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Challengers/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Challengers/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Challengers/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Cologne 2014 Challengers",
                    "market_name": "ESL One Cologne 2014 Challengers",
                    "price": 67.948,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 2,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Nuke%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Nuke%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Nuke%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Nuke%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Nuke Souvenir Package",
                    "market_name": "Katowice 2019 Nuke Souvenir Package",
                    "price": 9.46,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Vertigo%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Vertigo%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Vertigo%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Vertigo%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Vertigo Souvenir Package",
                    "market_name": "Berlin 2019 Vertigo Souvenir Package",
                    "price": 6.984,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 2,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Virtus.Pro | Atlanta 2017",
                    "market_name": "Autograph Capsule | Virtus.Pro | Atlanta 2017",
                    "price": 4.67,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 5,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Nuke%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Nuke%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Nuke%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Nuke%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Nuke Souvenir Package",
                    "market_name": "Berlin 2019 Nuke Souvenir Package",
                    "price": 13.345,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Challengers%20%28Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Challengers%20%28Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Challengers%20%28Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Challengers%20%28Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "DreamHack Cluj-Napoca 2015 Challengers (Foil)",
                    "market_name": "DreamHack Cluj-Napoca 2015 Challengers (Foil)",
                    "price": 52.919,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/eSports%202013%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/eSports%202013%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/eSports%202013%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/eSports%202013%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "eSports 2013 Case",
                    "market_name": "eSports 2013 Case",
                    "price": 32.74,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Inferno Souvenir Package",
                    "market_name": "Berlin 2019 Inferno Souvenir Package",
                    "price": 8.506,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 18,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Cologne%202016%20Cache%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Cologne%202016%20Cache%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Cologne%202016%20Cache%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Cologne%202016%20Cache%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Cologne 2016 Cache Souvenir Package",
                    "market_name": "Cologne 2016 Cache Souvenir Package",
                    "price": 23.65,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 15,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Cobblestone%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Cobblestone%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Cobblestone%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Cobblestone%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Cologne 2015 Cobblestone Souvenir Package",
                    "market_name": "ESL One Cologne 2015 Cobblestone Souvenir Package",
                    "price": 1249.999,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 15,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Cobblestone%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Cobblestone%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Cobblestone%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Cobblestone%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "DreamHack Cluj-Napoca 2015 Cobblestone Souvenir Package",
                    "market_name": "DreamHack Cluj-Napoca 2015 Cobblestone Souvenir Package",
                    "price": 1385,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Fnatic | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Fnatic | MLG Columbus 2016",
                    "price": 5.256,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | G2 Esports | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | G2 Esports | Cluj-Napoca 2015",
                    "price": 5.499,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | mousesports | Cologne 2015",
                    "market_name": "Autograph Capsule | mousesports | Cologne 2015",
                    "price": 8.001,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 18,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20eBettle%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20eBettle%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20eBettle%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20eBettle%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team eBettle | Cologne 2015",
                    "market_name": "Autograph Capsule | Team eBettle | Cologne 2015",
                    "price": 5.27,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team EnVyUs | Cologne 2015",
                    "market_name": "Autograph Capsule | Team EnVyUs | Cologne 2015",
                    "price": 9.244,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 10,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Legends%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Legends%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Legends%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Legends%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "MLG Columbus 2016 Legends (Holo-Foil)",
                    "market_name": "Легенды MLG Columbus 2016 (голографические/металлические)",
                    "price": 31.012,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Counter Logic Gaming | Cologne 2015",
                    "market_name": "Autograph Capsule | Counter Logic Gaming | Cologne 2015",
                    "price": 10.06,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Fnatic | Cologne 2016",
                    "market_name": "Autograph Capsule | Fnatic | Cologne 2016",
                    "price": 7.484,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 4,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20B%20%28Foil%29%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20B%20%28Foil%29%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20B%20%28Foil%29%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20B%20%28Foil%29%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Group B (Foil) | Cologne 2015",
                    "market_name": "Autograph Capsule | Group B (Foil) | Cologne 2015",
                    "price": 16.665,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Legends (Foil) | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Legends (Foil) | MLG Columbus 2016",
                    "price": 54.285,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Vexed%20Gaming%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Vexed%20Gaming%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Vexed%20Gaming%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Vexed%20Gaming%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Vexed Gaming | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Vexed Gaming | Cluj-Napoca 2015",
                    "price": 9.6,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 17,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Krakow%202017%20Cache%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Krakow%202017%20Cache%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Krakow%202017%20Cache%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Krakow%202017%20Cache%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Krakow 2017 Cache Souvenir Package",
                    "market_name": "Krakow 2017 Cache Souvenir Package",
                    "price": 39.489,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Krakow%202017%20Legends%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Krakow%202017%20Legends%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Krakow%202017%20Legends%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Krakow%202017%20Legends%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Krakow 2017 Legends (Holo-Foil)",
                    "market_name": "Krakow 2017 Legends (Holo/Foil)",
                    "price": 13.643,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 13,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20G2A%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20G2A%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20G2A%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20G2A%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Cloud9 G2A | Cologne 2015",
                    "market_name": "Autograph Capsule | Cloud9 G2A | Cologne 2015",
                    "price": 6.95,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Fnatic | Atlanta 2017",
                    "market_name": "Autograph Capsule | Fnatic | Atlanta 2017",
                    "price": 6.145,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Natus Vincere | Cologne 2015",
                    "market_name": "Autograph Capsule | Natus Vincere | Cologne 2015",
                    "price": 4.887,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 18,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20North%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20North%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20North%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20North%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | North | Atlanta 2017",
                    "market_name": "Autograph Capsule | North | Atlanta 2017",
                    "price": 7.76,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 19,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Virtus.Pro | Cologne 2016",
                    "market_name": "Autograph Capsule | Virtus.Pro | Cologne 2016",
                    "price": 6.552,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Cache%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Cache%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Cache%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Cache%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Cache Souvenir Package",
                    "market_name": "Katowice 2019 Cache Souvenir Package",
                    "price": 21.719,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2001,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 10,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Challengers Autograph Capsule",
                    "market_name": "Paris 2023 Challengers Autograph Capsule",
                    "price": 0.277,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 719,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Champions%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Champions%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Champions%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Champions%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Champions Autograph Capsule",
                    "market_name": "Paris 2023 Champions Autograph Capsule",
                    "price": 0.209,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 24,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Krakow%202017%20Mirage%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Krakow%202017%20Mirage%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Krakow%202017%20Mirage%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Krakow%202017%20Mirage%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Krakow 2017 Mirage Souvenir Package",
                    "market_name": "Krakow 2017 Mirage Souvenir Package",
                    "price": 24.1,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Nuke%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Nuke%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Nuke%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Nuke%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Nuke Souvenir Package",
                    "market_name": "London 2018 Nuke Souvenir Package",
                    "price": 23,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Mirage%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Mirage%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Mirage%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Mirage%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Mirage Souvenir Package",
                    "market_name": "Berlin 2019 Mirage Souvenir Package",
                    "price": 12.392,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Attending%20Legends%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Attending%20Legends%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Attending%20Legends%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Attending%20Legends%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Attending Legends (Holo-Foil)",
                    "market_name": "Boston 2018 Attending Legends (Holo/Foil)",
                    "price": 28.356,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Cologne%202016%20Cobblestone%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Cologne%202016%20Cobblestone%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Cologne%202016%20Cobblestone%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Cologne%202016%20Cobblestone%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Cologne 2016 Cobblestone Souvenir Package",
                    "market_name": "Cologne 2016 Cobblestone Souvenir Package",
                    "price": 1272.009,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 69,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 8,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Challengers Autograph Capsule",
                    "market_name": "Antwerp 2022 Challengers Autograph Capsule",
                    "price": 0.486,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202014%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Cologne 2014 Inferno Souvenir Package",
                    "market_name": "ESL One Cologne 2014 Inferno Souvenir Package",
                    "price": 86.319,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4413,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 29,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Prisma%202%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Prisma%202%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Prisma%202%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Prisma%202%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Prisma 2 Case",
                    "market_name": "Prisma 2 Case",
                    "price": 0.542,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 6834,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 28,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Danger%20Zone%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Danger%20Zone%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Danger%20Zone%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Danger%20Zone%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Danger Zone Case",
                    "market_name": "Danger Zone Case",
                    "price": 0.57,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 9,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "MLG Columbus 2016 Inferno Souvenir Package",
                    "market_name": "MLG Columbus 2016 Inferno Souvenir Package",
                    "price": 40.608,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Astralis | Atlanta 2017",
                    "market_name": "Autograph Capsule | Astralis | Atlanta 2017",
                    "price": 6.581,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Challengers (Foil) | Cologne 2016",
                    "market_name": "Autograph Capsule | Challengers (Foil) | Cologne 2016",
                    "price": 82.61,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Counter Logic Gaming | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Counter Logic Gaming | Cluj-Napoca 2015",
                    "price": 6.286,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 4,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20A%20%28Foil%29%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20A%20%28Foil%29%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20A%20%28Foil%29%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20A%20%28Foil%29%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Group A (Foil) | Cologne 2015",
                    "market_name": "Autograph Capsule | Group A (Foil) | Cologne 2015",
                    "price": 16.26,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 8,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20D%20%28Foil%29%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20D%20%28Foil%29%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20D%20%28Foil%29%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Group%20D%20%28Foil%29%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Group D (Foil) | Cologne 2015",
                    "market_name": "Autograph Capsule | Group D (Foil) | Cologne 2015",
                    "price": 29.319,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 6,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Natus Vincere | Atlanta 2017",
                    "market_name": "Autograph Capsule | Natus Vincere | Atlanta 2017",
                    "price": 17.145,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20SK%20Gaming%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20SK%20Gaming%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20SK%20Gaming%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20SK%20Gaming%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | SK Gaming | Cologne 2016",
                    "market_name": "Autograph Capsule | SK Gaming | Cologne 2016",
                    "price": 11.09,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Dignitas%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Dignitas%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Dignitas%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Dignitas%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team Dignitas | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Team Dignitas | Cluj-Napoca 2015",
                    "price": 45.67,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Dignitas%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Dignitas%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Dignitas%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Dignitas%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team Dignitas | Cologne 2016",
                    "market_name": "Autograph Capsule | Team Dignitas | Cologne 2016",
                    "price": 22.862,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 183,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/10%20Year%20Birthday%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/10%20Year%20Birthday%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/10%20Year%20Birthday%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/10%20Year%20Birthday%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "10 Year Birthday Sticker Capsule",
                    "market_name": "10 Year Birthday Sticker Capsule",
                    "price": 1.052,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 228,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 13,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/2020%20RMR%20Challengers/512.png",
                    "image_100": "https://cdn2.csgo.com/item/2020%20RMR%20Challengers/100.png",
                    "image_150": "https://cdn2.csgo.com/item/2020%20RMR%20Challengers/150.png",
                    "image_300": "https://cdn2.csgo.com/item/2020%20RMR%20Challengers/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "2020 RMR Challengers",
                    "market_name": "2020 RMR Challengers",
                    "price": 0.25,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 219,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/2020%20RMR%20Contenders/512.png",
                    "image_100": "https://cdn2.csgo.com/item/2020%20RMR%20Contenders/100.png",
                    "image_150": "https://cdn2.csgo.com/item/2020%20RMR%20Contenders/150.png",
                    "image_300": "https://cdn2.csgo.com/item/2020%20RMR%20Contenders/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "2020 RMR Contenders",
                    "market_name": "2020 RMR Contenders",
                    "price": 0.26,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 858,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 15,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/2020%20RMR%20Legends/512.png",
                    "image_100": "https://cdn2.csgo.com/item/2020%20RMR%20Legends/100.png",
                    "image_150": "https://cdn2.csgo.com/item/2020%20RMR%20Legends/150.png",
                    "image_300": "https://cdn2.csgo.com/item/2020%20RMR%20Legends/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "2020 RMR Legends",
                    "market_name": "2020 RMR Legends",
                    "price": 0.221,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 70,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/2021%20Community%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/2021%20Community%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/2021%20Community%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/2021%20Community%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "2021 Community Sticker Capsule",
                    "market_name": "2021 Community Sticker Capsule",
                    "price": 1.316,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1143,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Revolver%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Revolver%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Revolver%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Revolver%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Revolver Case",
                    "market_name": "Revolver Case",
                    "price": 1.269,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 159,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Contenders%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Contenders%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Contenders%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Contenders%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Contenders Autograph Capsule",
                    "market_name": "Rio 2022 Contenders Autograph Capsule",
                    "price": 0.448,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 12,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 20,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Overpass%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Overpass%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Overpass%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Overpass%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Overpass Souvenir Package",
                    "market_name": "Rio 2022 Overpass Souvenir Package",
                    "price": 3.196,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 26,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Patch%20Pack/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Patch%20Pack/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Patch%20Pack/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Patch%20Pack/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Half-Life: Alyx Patch Pack",
                    "market_name": "Half-Life: Alyx Patch Pack",
                    "price": 1.242,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 922,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Operation%20Phoenix%20Weapon%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Operation%20Phoenix%20Weapon%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Operation%20Phoenix%20Weapon%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Operation%20Phoenix%20Weapon%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Operation Phoenix Weapon Case",
                    "market_name": "Operation Phoenix Weapon Case",
                    "price": 2.3,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Train%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Train%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Train%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Train%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Train Souvenir Package",
                    "market_name": "London 2018 Train Souvenir Package",
                    "price": 9.8,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 327,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 17,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Minor%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Minor%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Minor%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Minor%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Minor Challengers (Holo-Foil)",
                    "market_name": "Berlin 2019 Minor Challengers (Holo/Foil)",
                    "price": 1.525,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 38,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 18,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Returning%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Returning%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Returning%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Returning%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Returning Challengers (Holo-Foil)",
                    "market_name": "Berlin 2019 Returning Challengers (Holo/Foil)",
                    "price": 1.801,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Train%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Train%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Train%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Train%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Train Souvenir Package",
                    "market_name": "Berlin 2019 Train Souvenir Package",
                    "price": 14.999,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Mirage%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Mirage%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Mirage%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Mirage%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Mirage Souvenir Package",
                    "market_name": "Boston 2018 Mirage Souvenir Package",
                    "price": 10.356,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 65,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 10,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Pinups%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Pinups%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Pinups%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Pinups%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Pinups Capsule",
                    "market_name": "Pinups Capsule",
                    "price": 1.053,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 5993,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 31,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Clutch%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Clutch%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Clutch%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Clutch%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Clutch Case",
                    "market_name": "Clutch Case",
                    "price": 0.338,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1080,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Contenders%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Contenders%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Contenders%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Contenders%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Contenders Sticker Capsule",
                    "market_name": "Antwerp 2022 Contenders Sticker Capsule",
                    "price": 0.588,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 5,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 24,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Inferno Souvenir Package",
                    "market_name": "Antwerp 2022 Inferno Souvenir Package",
                    "price": 2.851,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 15,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Nuke%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Nuke%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Nuke%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Nuke%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Nuke Souvenir Package",
                    "market_name": "Antwerp 2022 Nuke Souvenir Package",
                    "price": 2.82,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Atlanta%202017%20Train%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Atlanta%202017%20Train%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Atlanta%202017%20Train%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Atlanta%202017%20Train%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Atlanta 2017 Train Souvenir Package",
                    "market_name": "Atlanta 2017 Train Souvenir Package",
                    "price": 22.24,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 10,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Challengers%20%28Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Challengers%20%28Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Challengers%20%28Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Challengers%20%28Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Cologne 2015 Challengers (Foil)",
                    "market_name": "ESL One Cologne 2015 Challengers (Foil)",
                    "price": 35.72,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Mirage%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Mirage%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Mirage%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Mirage%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Cologne 2015 Mirage Souvenir Package",
                    "market_name": "ESL One Cologne 2015 Mirage Souvenir Package",
                    "price": 36.21,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Legends%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Legends%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Legends%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Legends%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Katowice 2015 Legends (Holo-Foil)",
                    "market_name": "ESL One Katowice 2015 Legends (Holo/Foil)",
                    "price": 206.215,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 8971,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Recoil%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Recoil%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Recoil%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Recoil%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Recoil Case",
                    "market_name": "Recoil Case",
                    "price": 0.139,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 224,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Challengers Autograph Capsule",
                    "market_name": "Rio 2022 Challengers Autograph Capsule",
                    "price": 0.489,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 15398,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 25,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Fracture%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Fracture%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Fracture%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Fracture%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Fracture Case",
                    "market_name": "Fracture Case",
                    "price": 0.209,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/DreamHack%202014%20Legends%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/DreamHack%202014%20Legends%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/DreamHack%202014%20Legends%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/DreamHack%202014%20Legends%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "DreamHack 2014 Legends (Holo-Foil)",
                    "market_name": "DreamHack 2014 Legends (Holo/Foil)",
                    "price": 278.58,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "DreamHack Cluj-Napoca 2015 Inferno Souvenir Package",
                    "market_name": "DreamHack Cluj-Napoca 2015 Inferno Souvenir Package",
                    "price": 50.55,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Krakow%202017%20Train%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Krakow%202017%20Train%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Krakow%202017%20Train%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Krakow%202017%20Train%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Krakow 2017 Train Souvenir Package",
                    "market_name": "Krakow 2017 Train Souvenir Package",
                    "price": 24.129,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 81,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Bestiary%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Bestiary%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Bestiary%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Bestiary%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Bestiary Capsule",
                    "market_name": "Bestiary Capsule",
                    "price": 0.86,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 13,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Minor%20Challengers%20with%20Flash%20Gaming%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Minor%20Challengers%20with%20Flash%20Gaming%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Minor%20Challengers%20with%20Flash%20Gaming%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Minor%20Challengers%20with%20Flash%20Gaming%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Minor Challengers with Flash Gaming Autograph Capsule",
                    "market_name": "Boston 2018 Minor Challengers with Flash Gaming Autograph Capsule",
                    "price": 19.547,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 6,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Perfect%20World%20Graffiti%20Box/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Perfect%20World%20Graffiti%20Box/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Perfect%20World%20Graffiti%20Box/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Perfect%20World%20Graffiti%20Box/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Perfect World Graffiti Box",
                    "market_name": "Perfect World Graffiti Box",
                    "price": 1.106,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 20,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Overpass%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Overpass%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Overpass%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Overpass%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Overpass Souvenir Package",
                    "market_name": "Boston 2018 Overpass Souvenir Package",
                    "price": 30.6,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 103,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 18,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Legends%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Legends%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Legends%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Legends%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Legends Autograph Capsule",
                    "market_name": "Antwerp 2022 Legends Autograph Capsule",
                    "price": 0.325,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 98,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Enfu%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Enfu%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Enfu%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Enfu%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Enfu Sticker Capsule",
                    "market_name": "Enfu Sticker Capsule",
                    "price": 1.211,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 3,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Train%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Train%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Train%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Train%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Cologne 2015 Train Souvenir Package",
                    "market_name": "ESL One Cologne 2015 Train Souvenir Package",
                    "price": 24.68,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 12,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Virtus.Pro | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Virtus.Pro | MLG Columbus 2016",
                    "price": 11,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2377,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Glove%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Glove%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Glove%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Glove%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Glove Case",
                    "market_name": "Glove Case",
                    "price": 3.59,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 105,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 5,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Half-Life%3A%20Alyx%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Half-Life: Alyx Sticker Capsule",
                    "market_name": "Half-Life: Alyx Sticker Capsule",
                    "price": 1.053,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 375,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Operation%20Broken%20Fang%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Operation%20Broken%20Fang%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Operation%20Broken%20Fang%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Operation%20Broken%20Fang%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Operation Broken Fang Case",
                    "market_name": "Operation Broken Fang Case",
                    "price": 3.612,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 968,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 11,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Contenders%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Contenders%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Contenders%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Contenders%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Contenders Autograph Capsule",
                    "market_name": "Paris 2023 Contenders Autograph Capsule",
                    "price": 0.24,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 112,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Inferno Souvenir Package",
                    "market_name": "Paris 2023 Inferno Souvenir Package",
                    "price": 2.398,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 671,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 8,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Legends%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Legends%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Legends%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Legends%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Legends Autograph Capsule",
                    "market_name": "Paris 2023 Legends Autograph Capsule",
                    "price": 0.247,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 504,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Legends%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Legends%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Legends%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Legends%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Legends (Holo-Foil)",
                    "market_name": "Berlin 2019 Legends (Holo/Foil)",
                    "price": 1.355,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 22,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Minor%20Challengers%20with%20Flash%20Gaming%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Minor%20Challengers%20with%20Flash%20Gaming%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Minor%20Challengers%20with%20Flash%20Gaming%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Minor%20Challengers%20with%20Flash%20Gaming%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Minor Challengers with Flash Gaming (Holo-Foil)",
                    "market_name": "Boston 2018 Minor Challengers with Flash Gaming (Holo/Foil)",
                    "price": 29.11,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 15,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Nuke%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Nuke%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Nuke%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Nuke%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Nuke Souvenir Package",
                    "market_name": "Boston 2018 Nuke Souvenir Package",
                    "price": 54.296,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 68,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Chicken%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Chicken%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Chicken%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Chicken%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Chicken Capsule",
                    "market_name": "Chicken Capsule",
                    "price": 1.106,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 5,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 12,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Community%20Graffiti%20Box%201/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Community%20Graffiti%20Box%201/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Community%20Graffiti%20Box%201/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Community%20Graffiti%20Box%201/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Community Graffiti Box 1",
                    "market_name": "Community Graffiti Box 1",
                    "price": 1.085,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 96,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 15,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Champions%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Champions%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Champions%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Champions%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Champions Autograph Capsule",
                    "market_name": "Antwerp 2022 Champions Autograph Capsule",
                    "price": 0.321,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 165,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 11,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Contenders%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Contenders%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Contenders%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Contenders%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Contenders Autograph Capsule",
                    "market_name": "Antwerp 2022 Contenders Autograph Capsule",
                    "price": 0.52,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 41,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 22,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Mirage%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Mirage%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Mirage%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Mirage%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Mirage Souvenir Package",
                    "market_name": "Antwerp 2022 Mirage Souvenir Package",
                    "price": 3.71,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Cologne 2015 Inferno Souvenir Package",
                    "market_name": "ESL One Cologne 2015 Inferno Souvenir Package",
                    "price": 21.566,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 116,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Slid3%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Slid3%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Slid3%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Slid3%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Slid3 Capsule",
                    "market_name": "Slid3 Capsule",
                    "price": 1.847,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 20,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Ancient%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Ancient%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Ancient%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Ancient%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Ancient Souvenir Package",
                    "market_name": "Rio 2022 Ancient Souvenir Package",
                    "price": 3.391,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 514,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 15,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Challengers%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Challengers%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Challengers%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Challengers%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Challengers Sticker Capsule",
                    "market_name": "Rio 2022 Challengers Sticker Capsule",
                    "price": 0.289,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Inferno Souvenir Package",
                    "market_name": "Rio 2022 Inferno Souvenir Package",
                    "price": 3.102,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 8,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Nuke%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Nuke%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Nuke%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Nuke%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Nuke Souvenir Package",
                    "market_name": "Rio 2022 Nuke Souvenir Package",
                    "price": 3.7,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 33,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/DreamHack%202014%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/DreamHack%202014%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/DreamHack%202014%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/DreamHack%202014%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "DreamHack 2014 Inferno Souvenir Package",
                    "market_name": "DreamHack 2014 Inferno Souvenir Package",
                    "price": 214.995,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 11,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Legends%20%28Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Legends%20%28Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Legends%20%28Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Legends%20%28Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "DreamHack Cluj-Napoca 2015 Legends (Foil)",
                    "market_name": "DreamHack Cluj-Napoca 2015 Legends (Foil)",
                    "price": 18.73,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 9788,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 22,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Dreams%20%26%20Nightmares%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Dreams%20%26%20Nightmares%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Dreams%20%26%20Nightmares%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Dreams%20%26%20Nightmares%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Dreams & Nightmares Case",
                    "market_name": "Dreams & Nightmares Case",
                    "price": 0.569,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 164,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Overpass%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Overpass%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Overpass%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Overpass%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Overpass Souvenir Package",
                    "market_name": "Paris 2023 Overpass Souvenir Package",
                    "price": 1.9,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 13,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Cobblestone%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Cobblestone%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Cobblestone%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Cobblestone%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Cobblestone Souvenir Package",
                    "market_name": "Boston 2018 Cobblestone Souvenir Package",
                    "price": 1302.35,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2017,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 24,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Chroma%202%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Chroma%202%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Chroma%202%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Chroma%202%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Chroma 2 Case",
                    "market_name": "Chroma 2 Case",
                    "price": 1.744,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4339,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 27,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Chroma%203%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Chroma%203%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Chroma%203%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Chroma%203%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Chroma 3 Case",
                    "market_name": "Chroma 3 Case",
                    "price": 1.54,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 691,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Chroma%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Chroma%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Chroma%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Chroma%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Chroma Case",
                    "market_name": "Chroma Case",
                    "price": 2.068,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 22,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Atlanta%202017%20Legends%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Atlanta%202017%20Legends%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Atlanta%202017%20Legends%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Atlanta%202017%20Legends%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Atlanta 2017 Legends (Holo-Foil)",
                    "market_name": "Atlanta 2017 Legends (Holo/Foil)",
                    "price": 84.592,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Dust%20II%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Dust%20II%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Dust%20II%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Cologne%202015%20Dust%20II%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Cologne 2015 Dust II Souvenir Package",
                    "market_name": "ESL One Cologne 2015 Dust II Souvenir Package",
                    "price": 63.63,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Katowice 2015 Challengers (Holo-Foil)",
                    "market_name": "ESL One Katowice 2015 Challengers (Holo/Foil)",
                    "price": 750,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 74,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Espionage%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Espionage%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Espionage%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Espionage%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Espionage Sticker Capsule",
                    "market_name": "Espionage Sticker Capsule",
                    "price": 1.06,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 14,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 32,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Initiators%20Music%20Kit%20Box/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Initiators%20Music%20Kit%20Box/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Initiators%20Music%20Kit%20Box/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Initiators%20Music%20Kit%20Box/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Initiators Music Kit Box",
                    "market_name": "Initiators Music Kit Box",
                    "price": 2.6,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Train%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Train%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Train%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/DreamHack%20Cluj-Napoca%202015%20Train%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "DreamHack Cluj-Napoca 2015 Train Souvenir Package",
                    "market_name": "DreamHack Cluj-Napoca 2015 Train Souvenir Package",
                    "price": 32.426,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Krakow%202017%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Krakow%202017%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Krakow%202017%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Krakow%202017%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Krakow 2017 Inferno Souvenir Package",
                    "market_name": "Krakow 2017 Inferno Souvenir Package",
                    "price": 201.76,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4870,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 10,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Contenders%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Contenders%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Contenders%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Contenders%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Contenders Sticker Capsule",
                    "market_name": "Paris 2023 Contenders Sticker Capsule",
                    "price": 0.223,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 12,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 12,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/CS%3AGO%20Graffiti%20Box/512.png",
                    "image_100": "https://cdn2.csgo.com/item/CS%3AGO%20Graffiti%20Box/100.png",
                    "image_150": "https://cdn2.csgo.com/item/CS%3AGO%20Graffiti%20Box/150.png",
                    "image_300": "https://cdn2.csgo.com/item/CS%3AGO%20Graffiti%20Box/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "CS:GO Graffiti Box",
                    "market_name": "CS:GO Graffiti Box",
                    "price": 0.975,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 384,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 17,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Challengers%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Challengers%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Challengers%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Challengers%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Challengers Sticker Capsule",
                    "market_name": "Antwerp 2022 Challengers Sticker Capsule",
                    "price": 0.511,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3141,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Gamma%202%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Gamma%202%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Gamma%202%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Gamma%202%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Gamma 2 Case",
                    "market_name": "Gamma 2 Case",
                    "price": 1.644,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 120,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Champions%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Champions%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Champions%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Champions%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Champions Autograph Capsule",
                    "market_name": "Rio 2022 Champions Autograph Capsule",
                    "price": 0.429,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 82,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Legends%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Legends%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Legends%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Legends%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Legends Autograph Capsule",
                    "market_name": "Rio 2022 Legends Autograph Capsule",
                    "price": 0.467,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/DreamHack%202014%20Dust%20II%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/DreamHack%202014%20Dust%20II%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/DreamHack%202014%20Dust%20II%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/DreamHack%202014%20Dust%20II%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "DreamHack 2014 Dust II Souvenir Package",
                    "market_name": "DreamHack 2014 Dust II Souvenir Package",
                    "price": 325.339,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 95,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Anubis%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Anubis%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Anubis%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Anubis%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Anubis Souvenir Package",
                    "market_name": "Paris 2023 Anubis Souvenir Package",
                    "price": 1.89,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 14,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Krakow%202017%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Krakow%202017%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Krakow%202017%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Krakow%202017%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Krakow 2017 Challengers Autograph Capsule",
                    "market_name": "Krakow 2017 Challengers Autograph Capsule",
                    "price": 30.857,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 169,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 29,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Vertigo%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Vertigo%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Vertigo%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Vertigo%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Vertigo Souvenir Package",
                    "market_name": "Paris 2023 Vertigo Souvenir Package",
                    "price": 1.97,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 11,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Mirage%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Mirage%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Mirage%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Mirage%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Mirage Souvenir Package",
                    "market_name": "London 2018 Mirage Souvenir Package",
                    "price": 9.39,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 21,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Returning%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Returning%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Returning%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Returning%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Returning Challengers (Holo-Foil)",
                    "market_name": "London 2018 Returning Challengers (Holo/Foil)",
                    "price": 12.91,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 27,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Minor%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Minor%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Minor%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Minor%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Minor Challengers Autograph Capsule",
                    "market_name": "Berlin 2019 Minor Challengers Autograph Capsule",
                    "price": 1.619,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 69,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Perfect%20World%20Sticker%20Capsule%202/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Perfect%20World%20Sticker%20Capsule%202/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Perfect%20World%20Sticker%20Capsule%202/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Perfect%20World%20Sticker%20Capsule%202/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Perfect World Sticker Capsule 2",
                    "market_name": "Perfect World Sticker Capsule 2",
                    "price": 1.106,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Cologne%202016%20Train%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Cologne%202016%20Train%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Cologne%202016%20Train%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Cologne%202016%20Train%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Cologne 2016 Train Souvenir Package",
                    "market_name": "Cologne 2016 Train Souvenir Package",
                    "price": 20,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 94,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 1,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Community%20Capsule%202018/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Community%20Capsule%202018/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Community%20Capsule%202018/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Community%20Capsule%202018/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Community Capsule 2018",
                    "market_name": "Community Capsule 2018",
                    "price": 1.137,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 914,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Antwerp%202022%20Legends%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Antwerp%202022%20Legends%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Antwerp%202022%20Legends%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Antwerp%202022%20Legends%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Antwerp 2022 Legends Sticker Capsule",
                    "market_name": "Antwerp 2022 Legends Sticker Capsule",
                    "price": 0.837,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 648,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Anubis%20Collection%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Anubis%20Collection%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Anubis%20Collection%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Anubis%20Collection%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Anubis Collection Package",
                    "market_name": "Anubis Collection Package",
                    "price": 1.27,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 11,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Atlanta%202017%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Atlanta%202017%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Atlanta%202017%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Atlanta%202017%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Atlanta 2017 Challengers (Holo-Foil)",
                    "market_name": "Atlanta 2017 Challengers (Holo/Foil)",
                    "price": 73.52,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 4,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Atlanta%202017%20Mirage%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Atlanta%202017%20Mirage%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Atlanta%202017%20Mirage%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Atlanta%202017%20Mirage%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Atlanta 2017 Mirage Souvenir Package",
                    "market_name": "Atlanta 2017 Mirage Souvenir Package",
                    "price": 19.98,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 64,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 30,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Ancient%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Ancient%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Ancient%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Ancient%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Ancient Souvenir Package",
                    "market_name": "Paris 2023 Ancient Souvenir Package",
                    "price": 2.17,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Dust%20II%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Dust%20II%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Dust%20II%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Dust%20II%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Dust II Souvenir Package",
                    "market_name": "London 2018 Dust II Souvenir Package",
                    "price": 20,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 67,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Returning%20Challengers%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Returning%20Challengers%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Returning%20Challengers%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Returning%20Challengers%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Returning Challengers Autograph Capsule",
                    "market_name": "Berlin 2019 Returning Challengers Autograph Capsule",
                    "price": 0.753,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Returning%20Challengers%20%28Holo-Foil%29/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Returning%20Challengers%20%28Holo-Foil%29/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Returning%20Challengers%20%28Holo-Foil%29/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Returning%20Challengers%20%28Holo-Foil%29/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Returning Challengers (Holo-Foil)",
                    "market_name": "Boston 2018 Returning Challengers (Holo/Foil)",
                    "price": 44.519,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 89,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 5,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Poorly%20Drawn%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Poorly%20Drawn%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Poorly%20Drawn%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Poorly%20Drawn%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Poorly Drawn Capsule",
                    "market_name": "Poorly Drawn Capsule",
                    "price": 1.106,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 31,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Cologne%202016%20Overpass%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Cologne%202016%20Overpass%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Cologne%202016%20Overpass%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Cologne%202016%20Overpass%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Cologne 2016 Overpass Souvenir Package",
                    "market_name": "Cologne 2016 Overpass Souvenir Package",
                    "price": 90,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3104,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 24,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Gamma%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Gamma%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Gamma%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Gamma%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Gamma Case",
                    "market_name": "Gamma Case",
                    "price": 1.639,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Atlanta%202017%20Dust%20II%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Atlanta%202017%20Dust%20II%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Atlanta%202017%20Dust%20II%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Atlanta%202017%20Dust%20II%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Atlanta 2017 Dust II Souvenir Package",
                    "market_name": "Atlanta 2017 Dust II Souvenir Package",
                    "price": 27.94,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3066,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 30,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Prisma%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Prisma%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Prisma%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Prisma%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Prisma Case",
                    "market_name": "Prisma Case",
                    "price": 0.48,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Overpass%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Overpass%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Overpass%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Overpass%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "MLG Columbus 2016 Overpass Souvenir Package",
                    "market_name": "MLG Columbus 2016 Overpass Souvenir Package",
                    "price": 108.591,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 22,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Astralis%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Astralis | Cologne 2016",
                    "market_name": "Autograph Capsule | Astralis | Cologne 2016",
                    "price": 11.95,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 51,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 4,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Feral%20Predators%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Feral%20Predators%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Feral%20Predators%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Feral%20Predators%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Feral Predators Capsule",
                    "market_name": "Feral Predators Capsule",
                    "price": 1.053,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | FaZe Clan | Atlanta 2017",
                    "market_name": "Autograph Capsule | FaZe Clan | Atlanta 2017",
                    "price": 10.287,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Flipsid3 Tactics | Atlanta 2017",
                    "market_name": "Autograph Capsule | Flipsid3 Tactics | Atlanta 2017",
                    "price": 32.97,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Flipsid3 Tactics | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Flipsid3 Tactics | MLG Columbus 2016",
                    "price": 6.859,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20HellRaisers%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20HellRaisers%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20HellRaisers%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20HellRaisers%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | HellRaisers | Atlanta 2017",
                    "market_name": "Autograph Capsule | HellRaisers | Atlanta 2017",
                    "price": 7.201,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Legends (Foil) | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Legends (Foil) | Cluj-Napoca 2015",
                    "price": 23.887,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 2,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Luminosity Gaming | Cologne 2015",
                    "market_name": "Autograph Capsule | Luminosity Gaming | Cologne 2015",
                    "price": 10.88,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | mousesports | Atlanta 2017",
                    "market_name": "Autograph Capsule | mousesports | Atlanta 2017",
                    "price": 11.393,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 5,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Ninjas%20in%20Pyjamas%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Ninjas%20in%20Pyjamas%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Ninjas%20in%20Pyjamas%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Ninjas%20in%20Pyjamas%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Ninjas in Pyjamas | Cologne 2015",
                    "market_name": "Autograph Capsule | Ninjas in Pyjamas | Cologne 2015",
                    "price": 3.46,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 14,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Splyce%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Splyce%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Splyce%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Splyce%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Splyce | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Splyce | MLG Columbus 2016",
                    "price": 8.3,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team EnVyUs | Atlanta 2017",
                    "market_name": "Autograph Capsule | Team EnVyUs | Atlanta 2017",
                    "price": 9.38,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20EnVyUs%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team EnVyUs | Cologne 2016",
                    "market_name": "Autograph Capsule | Team EnVyUs | Cologne 2016",
                    "price": 21.13,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 10,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team Liquid | Atlanta 2017",
                    "market_name": "Autograph Capsule | Team Liquid | Atlanta 2017",
                    "price": 12.487,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team Liquid | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Team Liquid | Cluj-Napoca 2015",
                    "price": 16.529,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 27,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Virtus.Pro%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Virtus.Pro | Cologne 2015",
                    "market_name": "Autograph Capsule | Virtus.Pro | Cologne 2015",
                    "price": 3.429,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 544,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 8,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Contenders%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Contenders%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Contenders%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Contenders%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Contenders Sticker Capsule",
                    "market_name": "Rio 2022 Contenders Sticker Capsule",
                    "price": 0.385,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 604,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Legends%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Legends%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Legends%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Legends%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Legends Sticker Capsule",
                    "market_name": "Rio 2022 Legends Sticker Capsule",
                    "price": 0.533,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 95,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Halo%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Halo%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Halo%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Halo%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Halo Capsule",
                    "market_name": "Halo Capsule",
                    "price": 1.106,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/DreamHack%202013%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/DreamHack%202013%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/DreamHack%202013%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/DreamHack%202013%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "DreamHack 2013 Souvenir Package",
                    "market_name": "DreamHack 2013 Souvenir Package",
                    "price": 868.728,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 7,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Katowice%202019%20Dust%20II%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Katowice%202019%20Dust%20II%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Katowice%202019%20Dust%20II%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Katowice%202019%20Dust%20II%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Katowice 2019 Dust II Souvenir Package",
                    "market_name": "Katowice 2019 Dust II Souvenir Package",
                    "price": 14.13,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Inferno Souvenir Package",
                    "market_name": "London 2018 Inferno Souvenir Package",
                    "price": 16.456,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/London%202018%20Overpass%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/London%202018%20Overpass%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/London%202018%20Overpass%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/London%202018%20Overpass%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "London 2018 Overpass Souvenir Package",
                    "market_name": "London 2018 Overpass Souvenir Package",
                    "price": 22.907,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 779,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 20,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Operation%20Wildfire%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Operation%20Wildfire%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Operation%20Wildfire%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Operation%20Wildfire%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Operation Wildfire Case",
                    "market_name": "Operation Wildfire Case",
                    "price": 1.664,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 87,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Battlefield%202042%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Battlefield%202042%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Battlefield%202042%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Battlefield%202042%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Battlefield 2042 Sticker Capsule",
                    "market_name": "Battlefield 2042 Sticker Capsule",
                    "price": 1.053,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 99,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 13,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Berlin%202019%20Legends%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Berlin%202019%20Legends%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Berlin%202019%20Legends%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Berlin%202019%20Legends%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Berlin 2019 Legends Autograph Capsule",
                    "market_name": "Berlin 2019 Legends Autograph Capsule",
                    "price": 0.69,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Train%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Train%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Train%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Train%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Train Souvenir Package",
                    "market_name": "Boston 2018 Train Souvenir Package",
                    "price": 14.07,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 137,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 19,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Community%20Sticker%20Capsule%201/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Community%20Sticker%20Capsule%201/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Community%20Sticker%20Capsule%201/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Community%20Sticker%20Capsule%201/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Community Sticker Capsule 1",
                    "market_name": "Community Sticker Capsule 1",
                    "price": 2.989,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 117,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/CS20%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/CS20%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/CS20%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/CS20%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "CS20 Sticker Capsule",
                    "market_name": "CS20 Sticker Capsule",
                    "price": 0.902,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 31,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/CS%3AGO%20Patch%20Pack/512.png",
                    "image_100": "https://cdn2.csgo.com/item/CS%3AGO%20Patch%20Pack/100.png",
                    "image_150": "https://cdn2.csgo.com/item/CS%3AGO%20Patch%20Pack/150.png",
                    "image_300": "https://cdn2.csgo.com/item/CS%3AGO%20Patch%20Pack/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "CS:GO Patch Pack",
                    "market_name": "CS:GO Patch Pack",
                    "price": 1.353,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Ambush%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Ambush%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Ambush%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Ambush%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Ambush Sticker Capsule",
                    "market_name": "Ambush Sticker Capsule",
                    "price": 1.2,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 16,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Cobblestone%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Cobblestone%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Cobblestone%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/ESL%20One%20Katowice%202015%20Cobblestone%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "ESL One Katowice 2015 Cobblestone Souvenir Package",
                    "market_name": "ESL One Katowice 2015 Cobblestone Souvenir Package",
                    "price": 1357.31,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 51,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 33,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Masterminds%20Music%20Kit%20Box/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Masterminds%20Music%20Kit%20Box/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Masterminds%20Music%20Kit%20Box/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Masterminds%20Music%20Kit%20Box/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Masterminds Music Kit Box",
                    "market_name": "Masterminds Music Kit Box",
                    "price": 3.21,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 18,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Cloud9%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Cloud9 | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Cloud9 | Cluj-Napoca 2015",
                    "price": 15.33,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | FaZe Clan | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | FaZe Clan | MLG Columbus 2016",
                    "price": 6.173,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | G2 Esports | Atlanta 2017",
                    "market_name": "Autograph Capsule | G2 Esports | Atlanta 2017",
                    "price": 6.858,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 24,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | G2 Esports | Cologne 2016",
                    "market_name": "Autograph Capsule | G2 Esports | Cologne 2016",
                    "price": 14.02,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 54,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Gambit%20Gaming%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Gambit%20Gaming%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Gambit%20Gaming%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Gambit%20Gaming%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Gambit Gaming | Cologne 2016",
                    "market_name": "Autograph Capsule | Gambit Gaming | Cologne 2016",
                    "price": 10.489,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Legends (Foil) | Atlanta 2017",
                    "market_name": "Autograph Capsule | Legends (Foil) | Atlanta 2017",
                    "price": 110.85,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Legends%20%28Foil%29%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Legends (Foil) | Cologne 2016",
                    "market_name": "Autograph Capsule | Legends (Foil) | Cologne 2016",
                    "price": 75.83,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Luminosity%20Gaming%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Luminosity Gaming | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Luminosity Gaming | Cluj-Napoca 2015",
                    "price": 9.739,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Natus Vincere | Cologne 2016",
                    "market_name": "Autograph Capsule | Natus Vincere | Cologne 2016",
                    "price": 12.886,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 42,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20OpTic%20Gaming%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20OpTic%20Gaming%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20OpTic%20Gaming%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20OpTic%20Gaming%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | OpTic Gaming | Cologne 2016",
                    "market_name": "Autograph Capsule | OpTic Gaming | Cologne 2016",
                    "price": 16.54,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 6,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 28,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20SoloMid%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20SoloMid%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20SoloMid%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20SoloMid%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team SoloMid | Cologne 2015",
                    "market_name": "Autograph Capsule | Team SoloMid | Cologne 2015",
                    "price": 2.84,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 290,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 24,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Dust%20II%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Dust%20II%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Dust%20II%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Dust%20II%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Dust II Souvenir Package",
                    "market_name": "Rio 2022 Dust II Souvenir Package",
                    "price": 3.77,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 22,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 14,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Rio%202022%20Mirage%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Rio%202022%20Mirage%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Rio%202022%20Mirage%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Rio%202022%20Mirage%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Rio 2022 Mirage Souvenir Package",
                    "market_name": "Rio 2022 Mirage Souvenir Package",
                    "price": 3.02,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2987,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Horizon%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Horizon%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Horizon%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Horizon%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Horizon Case",
                    "market_name": "Horizon Case",
                    "price": 0.621,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4021,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 17,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Challengers%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Challengers%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Challengers%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Challengers%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Challengers Sticker Capsule",
                    "market_name": "Paris 2023 Challengers Sticker Capsule",
                    "price": 0.198,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 13,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Krakow%202017%20Cobblestone%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Krakow%202017%20Cobblestone%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Krakow%202017%20Cobblestone%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Krakow%202017%20Cobblestone%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Krakow 2017 Cobblestone Souvenir Package",
                    "market_name": "Krakow 2017 Cobblestone Souvenir Package",
                    "price": 1465.979,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3436,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 28,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Legends%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Legends%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Legends%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Legends%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Legends Sticker Capsule",
                    "market_name": "Paris 2023 Legends Sticker Capsule",
                    "price": 0.18,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 280,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 12,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Mirage%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Mirage%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Mirage%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Mirage%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Mirage Souvenir Package",
                    "market_name": "Paris 2023 Mirage Souvenir Package",
                    "price": 2.474,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 49,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 19,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Paris%202023%20Nuke%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Paris%202023%20Nuke%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Paris%202023%20Nuke%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Paris%202023%20Nuke%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Paris 2023 Nuke Souvenir Package",
                    "market_name": "Paris 2023 Nuke Souvenir Package",
                    "price": 2.06,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 102,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 30,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Operation%20Vanguard%20Weapon%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Operation%20Vanguard%20Weapon%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Operation%20Vanguard%20Weapon%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Operation%20Vanguard%20Weapon%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Operation Vanguard Weapon Case",
                    "market_name": "Operation Vanguard Weapon Case",
                    "price": 2.015,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 25,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Boston%202018%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Boston%202018%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Boston%202018%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Boston%202018%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Boston 2018 Inferno Souvenir Package",
                    "market_name": "Boston 2018 Inferno Souvenir Package",
                    "price": 10.388,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 55,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Perfect%20World%20Sticker%20Capsule%201/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Perfect%20World%20Sticker%20Capsule%201/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Perfect%20World%20Sticker%20Capsule%201/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Perfect%20World%20Sticker%20Capsule%201/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Perfect World Sticker Capsule 1",
                    "market_name": "Perfect World Sticker Capsule 1",
                    "price": 1.084,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1372,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 25,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/CS20%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/CS20%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/CS20%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/CS20%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "CS20 Case",
                    "market_name": "CS20 Case",
                    "price": 0.46,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1354,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 24,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Falchion%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Falchion%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Falchion%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Falchion%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Falchion Case",
                    "market_name": "Falchion Case",
                    "price": 0.703,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 10,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Cobblestone%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Cobblestone%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Cobblestone%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/MLG%20Columbus%202016%20Cobblestone%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "MLG Columbus 2016 Cobblestone Souvenir Package",
                    "market_name": "MLG Columbus 2016 Cobblestone Souvenir Package",
                    "price": 1430,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 1,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Challengers%20%28Foil%29%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Challengers (Foil) | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Challengers (Foil) | MLG Columbus 2016",
                    "price": 41.807,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 13,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Counter%20Logic%20Gaming%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Counter Logic Gaming | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Counter Logic Gaming | MLG Columbus 2016",
                    "price": 4.847,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 18,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20FaZe%20Clan%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | FaZe Clan | Cologne 2016",
                    "market_name": "Autograph Capsule | FaZe Clan | Cologne 2016",
                    "price": 8.59,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Flipsid3%20Tactics%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Flipsid3 Tactics | Cologne 2015",
                    "market_name": "Autograph Capsule | Flipsid3 Tactics | Cologne 2015",
                    "price": 12.002,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 1,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 32,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Fnatic | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Fnatic | Cluj-Napoca 2015",
                    "price": 3.56,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 24,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 29,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cologne%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cologne%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cologne%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Fnatic%20%7C%20Cologne%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Fnatic | Cologne 2015",
                    "market_name": "Autograph Capsule | Fnatic | Cologne 2015",
                    "price": 2.452,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 22,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20G2%20Esports%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | G2 Esports | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | G2 Esports | MLG Columbus 2016",
                    "price": 9.547,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 11,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Gambit%20Gaming%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Gambit%20Gaming%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Gambit%20Gaming%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Gambit%20Gaming%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Gambit Gaming | Atlanta 2017",
                    "market_name": "Autograph Capsule | Gambit Gaming | Atlanta 2017",
                    "price": 7.37,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20GODSENT%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20GODSENT%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20GODSENT%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20GODSENT%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | GODSENT | Atlanta 2017",
                    "market_name": "Autograph Capsule | GODSENT | Atlanta 2017",
                    "price": 5.308,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20mousesports%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | mousesports | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | mousesports | Cluj-Napoca 2015",
                    "price": 42.463,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Natus%20Vincere%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Natus Vincere | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Natus Vincere | MLG Columbus 2016",
                    "price": 7.662,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 30,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Ninjas%20in%20Pyjamas%20%7C%20MLG%20Columbus%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Ninjas%20in%20Pyjamas%20%7C%20MLG%20Columbus%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Ninjas%20in%20Pyjamas%20%7C%20MLG%20Columbus%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Ninjas%20in%20Pyjamas%20%7C%20MLG%20Columbus%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Ninjas in Pyjamas | MLG Columbus 2016",
                    "market_name": "Autograph Capsule | Ninjas in Pyjamas | MLG Columbus 2016",
                    "price": 3.584,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20OpTic%20Gaming%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20OpTic%20Gaming%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20OpTic%20Gaming%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20OpTic%20Gaming%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | OpTic Gaming | Atlanta 2017",
                    "market_name": "Autograph Capsule | OpTic Gaming | Atlanta 2017",
                    "price": 16.68,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20SK%20Gaming%20%7C%20Atlanta%202017/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20SK%20Gaming%20%7C%20Atlanta%202017/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20SK%20Gaming%20%7C%20Atlanta%202017/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20SK%20Gaming%20%7C%20Atlanta%202017/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | SK Gaming | Atlanta 2017",
                    "market_name": "Autograph Capsule | SK Gaming | Atlanta 2017",
                    "price": 8.573,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Cologne%202016/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Cologne%202016/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Cologne%202016/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20Liquid%20%7C%20Cologne%202016/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team Liquid | Cologne 2016",
                    "market_name": "Autograph Capsule | Team Liquid | Cologne 2016",
                    "price": 10.435,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 29,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20SoloMid%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20SoloMid%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20SoloMid%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Team%20SoloMid%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Team SoloMid | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Team SoloMid | Cluj-Napoca 2015",
                    "price": 3.79,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 9,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Titan%20%7C%20Cluj-Napoca%202015/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Titan%20%7C%20Cluj-Napoca%202015/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Titan%20%7C%20Cluj-Napoca%202015/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Autograph%20Capsule%20%7C%20Titan%20%7C%20Cluj-Napoca%202015/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Autograph Capsule | Titan | Cluj-Napoca 2015",
                    "market_name": "Autograph Capsule | Titan | Cluj-Napoca 2015",
                    "price": 14.538,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 288,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 19,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Contenders%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Contenders%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Contenders%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Contenders%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Contenders Sticker Capsule",
                    "market_name": "Stockholm 2021 Contenders Sticker Capsule",
                    "price": 3.547,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 276,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 20,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Finalists%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Finalists%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Finalists%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Finalists%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Finalists Autograph Capsule",
                    "market_name": "Stockholm 2021 Finalists Autograph Capsule",
                    "price": 0.601,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 12,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Inferno%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Inferno%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Inferno%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Inferno%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Inferno Souvenir Package",
                    "market_name": "Stockholm 2021 Inferno Souvenir Package",
                    "price": 3.638,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 72,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Mirage%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Mirage%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Mirage%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Mirage%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Mirage Souvenir Package",
                    "market_name": "Stockholm 2021 Mirage Souvenir Package",
                    "price": 2.78,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 5,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 18,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Nuke%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Nuke%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Nuke%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Nuke%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Nuke Souvenir Package",
                    "market_name": "Stockholm 2021 Nuke Souvenir Package",
                    "price": 2.95,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 72,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 9,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Vertigo%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Vertigo%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Vertigo%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Vertigo%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Vertigo Souvenir Package",
                    "market_name": "Stockholm 2021 Vertigo Souvenir Package",
                    "price": 3.999,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 4,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 6,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/X-Ray%20P250%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/X-Ray%20P250%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/X-Ray%20P250%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/X-Ray%20P250%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "X-Ray P250 Package",
                    "market_name": "X-Ray P250 Package",
                    "price": 2.421,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 91,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/The%20Boardroom%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/The%20Boardroom%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/The%20Boardroom%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/The%20Boardroom%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "The Boardroom Sticker Capsule",
                    "market_name": "The Boardroom Sticker Capsule",
                    "price": 1.106,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": true,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 0,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Radicals%20Box/512.png",
                    "image_100": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Radicals%20Box/100.png",
                    "image_150": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Radicals%20Box/150.png",
                    "image_300": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Radicals%20Box/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "StatTrak™ Radicals Box",
                    "market_name": "StatTrak™ Radicals Box",
                    "price": 8.2,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 100,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 22,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Sticker Capsule",
                    "market_name": "Sticker Capsule",
                    "price": 0.599,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 20,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Ancient%20Souvenir%20Package/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Ancient%20Souvenir%20Package/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Ancient%20Souvenir%20Package/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Ancient%20Souvenir%20Package/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Ancient Souvenir Package",
                    "market_name": "Stockholm 2021 Ancient Souvenir Package",
                    "price": 2.916,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 43,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 31,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Tacticians%20Music%20Kit%20Box/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Tacticians%20Music%20Kit%20Box/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Tacticians%20Music%20Kit%20Box/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Tacticians%20Music%20Kit%20Box/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Tacticians Music Kit Box",
                    "market_name": "Tacticians Music Kit Box",
                    "price": 2.63,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 86,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 25,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Warhammer%2040%2C000%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Warhammer%2040%2C000%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Warhammer%2040%2C000%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Warhammer%2040%2C000%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Warhammer 40,000 Sticker Capsule",
                    "market_name": "Warhammer 40,000 Sticker Capsule",
                    "price": 0.96,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 3579,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 29,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Spectrum%202%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Spectrum%202%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Spectrum%202%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Spectrum%202%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Spectrum 2 Case",
                    "market_name": "Spectrum 2 Case",
                    "price": 1.243,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2035,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 25,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Spectrum%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Spectrum%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Spectrum%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Spectrum%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Spectrum Case",
                    "market_name": "Spectrum Case",
                    "price": 1.839,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 14893,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 29,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Snakebite%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Snakebite%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Snakebite%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Snakebite%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Snakebite Case",
                    "market_name": "Snakebite Case",
                    "price": 0.169,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 2190,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 30,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Shadow%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Shadow%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Shadow%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Shadow%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Shadow Case",
                    "market_name": "Shadow Case",
                    "price": 0.656,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 256,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Shattered%20Web%20Case/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Shattered%20Web%20Case/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Shattered%20Web%20Case/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Shattered%20Web%20Case/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Shattered Web Case",
                    "market_name": "Shattered Web Case",
                    "price": 2.864,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 299,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 23,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Champions%20Autograph%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Champions%20Autograph%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Champions%20Autograph%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Champions%20Autograph%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Champions Autograph Capsule",
                    "market_name": "Stockholm 2021 Champions Autograph Capsule",
                    "price": 0.537,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 228,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 22,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Stockholm%202021%20Legends%20Sticker%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Stockholm%202021%20Legends%20Sticker%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Stockholm%202021%20Legends%20Sticker%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Stockholm%202021%20Legends%20Sticker%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Stockholm 2021 Legends Sticker Capsule",
                    "market_name": "Stockholm 2021 Legends Sticker Capsule",
                    "price": 1.282,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 47,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 9,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Sugarface%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Sugarface%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Sugarface%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Sugarface%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Sugarface Capsule",
                    "market_name": "Sugarface Capsule",
                    "price": 1.085,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 63,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 17,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Team%20Roles%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Team%20Roles%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Team%20Roles%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Team%20Roles%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Team Roles Capsule",
                    "market_name": "Team Roles Capsule",
                    "price": 0.91,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": false,
                    "slot": "",
                    "popularity": 64,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 7,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/Skill%20Groups%20Capsule/512.png",
                    "image_100": "https://cdn2.csgo.com/item/Skill%20Groups%20Capsule/100.png",
                    "image_150": "https://cdn2.csgo.com/item/Skill%20Groups%20Capsule/150.png",
                    "image_300": "https://cdn2.csgo.com/item/Skill%20Groups%20Capsule/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "Skill Groups Capsule",
                    "market_name": "Skill Groups Capsule",
                    "price": 0.923,
                    "stickers": [],
                    "__typename": "ItemType"
                },
                {
                    "color": "D2D2D2",
                    "id": null,
                    "currency": "USD",
                    "stattrak": true,
                    "slot": "",
                    "popularity": 0,
                    "features": null,
                    "rarity": "Base Grade",
                    "rarity_ext": {
                        "id": "Base Grade",
                        "name": "Base Grade",
                        "__typename": "RarityExtraType"
                    },
                    "ctp": 26,
                    "quality": null,
                    "phase": "",
                    "descriptions": null,
                    "type": [
                        "Container"
                    ],
                    "tags": null,
                    "image_512": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Tacticians%20Music%20Kit%20Box/512.png",
                    "image_100": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Tacticians%20Music%20Kit%20Box/100.png",
                    "image_150": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Tacticians%20Music%20Kit%20Box/150.png",
                    "image_300": "https://cdn2.csgo.com/item/StatTrak%E2%84%A2%20Tacticians%20Music%20Kit%20Box/300.png",
                    "seo": {
                        "category": "Container",
                        "type": "",
                        "__typename": "SeoType"
                    },
                    "market_hash_name": "StatTrak™ Tacticians Music Kit Box",
                    "market_name": "StatTrak™ Tacticians Music Kit Box",
                    "price": 5.08,
                    "stickers": [],
                    "__typename": "ItemType"
                }
            ],
            "__typename": "ItemsType"
        }
    }
}
```
