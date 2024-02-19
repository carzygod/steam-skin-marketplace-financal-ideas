```
https://api.dmarket.com/exchange/v1/market/items?side=market&orderBy=personal&orderDir=desc&title=&priceFrom=0&priceTo=0&treeFilters=categoryPath%5B%5D=misc/container&gameId=a8db&types=dmarket&cursor=&limit=100&currency=USD&platform=browser&isLoggedIn=true
```

Authorization

```
eyJhbGciOiJFUzI1NiIsInR5cCI6IkpXVCJ9.eyJqdGkiOiJlOTU0YjBhMy01MDRiLTQzOTgtOTk2NC1iMGI4NmNlYjVhY2QiLCJleHAiOjE3MTA4MzgxNDMsImlhdCI6MTcwODI0NjE0Mywic2lkIjoiMGtZTA0MS00ZDI4LWEyMTItYTU5MGE1YjYwNDlhIiwidHlwIjoiYWNjZXNzIiwiaWQiOiJhMDc4OGNkOC1mNTliLTRjOTAtYTI3Yy00ZTYyMjgyNGUzNTAiLCJwdmQiOiJtcCIsInBydCI6IjI0MDIiLCJhdHRyaWJ1dGVzIjp7ImFjY291bnRfaWQiOiI2MzMzYTljYS01ZWVmLTQ2ZTMtYWUxMS0wNTVhNjdhZmEwMmYiiOiJlOWQxYjU1OGYyMzE0MWY2ODhjMmIwZTdkYjE4YTM1ZDA3OTJiZTVjZDdhYjQzNWFiZDlkZjc4NGQ2NTcwYTBmIiwic2FnYV93YWxsZXRfYWRkcmVzcyI6IjB4NmZBNDZGQzkzOGZhYjM4NUUwRjJmN0YwQzhjMDg5NTZjNDU3NWUyQSJ9fQ.joy8A0bFbfuRv1q2LlcaLn6Sr3W2Bv9QjFQ6HtFVzZ1Zvc_peDmFTL_pR2Fo3kUfbQjcs9qQ
```



Response

```
{
 "objects": [
  {
   "itemId": "78d230c8-b6c6-5d57-823e-fdbaf149b83d",
   "type": "offer",
   "amount": 1,
   "classId": "143865972:5709717927",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "EMS Katowice 2014 Challengers",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsQEl9Jg9SpIW1KgRr7PjJZW8SvYiJxNHFxaajauOClG1SucYo3bqQotWl21Xm_hE5Mjv1Io6QdANvNVzR_QToyfCv28GZlomvBA",
   "slug": "ems-katowice-2014-challengers",
   "owner": "b9034955-65a2-4127-8b4a-044c03dbd1c4",
   "ownersBlockchainId": "f6496a752b424b37959cf6760eb1454ab4b021379eff84c611d32f79ea2b613d",
   "ownerDetails": {
    "id": "b9034955-65a2-4127-8b4a-044c03dbd1c4",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "f6496a752b424b37959cf6760eb1454ab4b021379eff84c611d32f79ea2b613d"
   },
   "status": "active",
   "discount": 1,
   "price": {
    "DMC": "",
    "USD": "3750000"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "3792507"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "7cafc52d-ef19-4a53-a827-b251a8fdd59c",
    "isNew": false,
    "gameId": "a8db",
    "name": "EMS Katowice 2014 Challengers",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199508183402/inventory/#730_2_35840744387",
    "groupId": "76561199508183402",
    "linkId": "fe457160-9ce9-567f-b683-d47319a2c32f",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 4,
    "tradeLockDuration": 396452,
    "itemType": "container",
    "collection": [
     ""
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cccc6ab2c803caaa0af760",
    "emissionSerial": "65cccc6ab2c803caaa0af760",
    "sagaAddress": "0x087C9577AC3B5ef6d76A259De144C7fe3A20575c"
   },
   "createdAt": 1707920528,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:66110e138ea9a79a1cecc615b9ac9323"
  },
  {
   "itemId": "7432eb6c-f155-54b4-b24f-10e23d635a3f",
   "type": "offer",
   "amount": 1,
   "classId": "236997301:1646559767",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "MLG Columbus 2016 Nuke Souvenir Package",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsUFJ4MAlVo6n3e1Y27OPafjBN09izq46enPK6ZLqDxTpQ7Z100uvEpIjw3gW3qEpuNjz2cIDGJwBqZguE8wS9lOe8g4j84spg8K8xSw",
   "slug": "mlg-columbus-2016-nuke-package",
   "owner": "1c562492-b785-4e4d-8b9b-c00052bdc402",
   "ownersBlockchainId": "f39d8ac507484161a59567bfa0937e602d2c624c98ae43129f8e92d1f26cfffb",
   "ownerDetails": {
    "id": "1c562492-b785-4e4d-8b9b-c00052bdc402",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "f39d8ac507484161a59567bfa0937e602d2c624c98ae43129f8e92d1f26cfffb"
   },
   "status": "active",
   "discount": 10,
   "price": {
    "DMC": "",
    "USD": "20575"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "23071"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "530f6ee4-53bc-4534-b7da-b2de89007e43",
    "isNew": false,
    "gameId": "a8db",
    "name": "MLG Columbus 2016 Nuke Package",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199302141668/inventory/#730_2_35291896562",
    "groupId": "76561199302141668",
    "withdrawable": true,
    "linkId": "179844e9-446d-5ffe-97a9-7c8c697aef43",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "nuke"
    ],
    "saleRestricted": false,
    "inGameAssetID": "659c732184c193354e243df6",
    "emissionSerial": "659c732184c193354e243df6",
    "sagaAddress": "0xf6CC2B519c995dd1EB905098F231E4FcCe80939D"
   },
   "createdAt": 1704751908,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:ad6ecb8ce08a4db243440f12ea527a01"
  },
  {
   "itemId": "138073f7-820b-5ea8-b9a9-11c183819d85",
   "type": "offer",
   "amount": 1,
   "classId": "143865972:823285422",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "ESL One Katowice 2015 Challengers (Holo-Foil)",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsQEl9Jg9SpIW1KgRr7PbbfTZD-NOhnYOOxaelZoSBxCUGvpcn277EptXz0VDi_kdpMG33IoSWIwQ5YF_YrlbvwOft08O0u86a1zI97ZiV9vtb",
   "slug": "esl-one-katowice-2015-challengers-holofoil",
   "owner": "4bf9e242-b2d7-4bbd-a300-64e1b0c4c93c",
   "ownersBlockchainId": "76db417bee27901d007e5bd0d7b22beeb2caf0d172eb2bdb8a577527c6bd1c64",
   "ownerDetails": {
    "id": "4bf9e242-b2d7-4bbd-a300-64e1b0c4c93c",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "76db417bee27901d007e5bd0d7b22beeb2caf0d172eb2bdb8a577527c6bd1c64"
   },
   "status": "active",
   "discount": 2,
   "price": {
    "DMC": "",
    "USD": "57900"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "59569"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "65902acf-9772-47cb-80fc-fe9c2dc5e826",
    "isNew": false,
    "gameId": "a8db",
    "name": "ESL One Katowice 2015 Challengers (Holo/Foil)",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199492159409/inventory/#730_2_34982426650",
    "groupId": "76561199492159409",
    "withdrawable": true,
    "linkId": "8227f142-62a3-540a-8087-7ebf9ce62320",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     ""
    ],
    "saleRestricted": false,
    "inGameAssetID": "657dca5ede5da69c2497ff26",
    "emissionSerial": "657dca5ede5da69c2497ff26",
    "sagaAddress": "0xeC7443baB32D649e7e6D804ff2448d317fb580cC"
   },
   "createdAt": 1707740563,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:17dfaae50d1822d4973628fc3ab6e048"
  },
  {
   "itemId": "7bb8f5a1-a6e3-5dd6-bb9c-a43526fb30a1",
   "type": "offer",
   "amount": 1,
   "classId": "143865972:1817233797",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Autograph Capsule | Challengers (Foil) | Cologne 2016",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsQEl9Jg9SpIW1KgRr7PDHfTJF4tnkxNHdqPDmPK7BqTof6pIpjL_HodmljAO28kNrNjr3ctWVIAJoaAzVr1S-xr_ngsft7s7Oy2wj5HcBWC3V3Q",
   "slug": "autograph-capsule-challengers-foil-cologne-2016",
   "owner": "68f2a1e8-114e-4324-b467-0d2414a50169",
   "ownersBlockchainId": "f1575fe58d263773e37140756760c412c4993c1e816bd630219e139ce47c8ca6",
   "ownerDetails": {
    "id": "68f2a1e8-114e-4324-b467-0d2414a50169",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "f1575fe58d263773e37140756760c412c4993c1e816bd630219e139ce47c8ca6"
   },
   "status": "active",
   "discount": 19,
   "price": {
    "DMC": "",
    "USD": "5986"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "7426"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "22ed49cd-039a-45bb-aa36-9cd9423f6385",
    "isNew": false,
    "gameId": "a8db",
    "name": "Autograph Capsule | Challengers (Foil) | Cologne 2016",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199489767925/inventory/#730_2_35766345904",
    "groupId": "76561199489767925",
    "linkId": "f6f6c9d6-cc2b-50f3-ad5a-f8fe9954a792",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 59140,
    "itemType": "container",
    "collection": [
     ""
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c760d9b2c803caaa9a6870",
    "emissionSerial": "65c760d9b2c803caaa9a6870",
    "sagaAddress": "0x41D1a1038a8E0cf6f6E2e19aEd6Fcef0191cf38a"
   },
   "createdAt": 1707616349,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:556fe30cc282bc4d533f1ffd5008f7ec"
  },
  {
   "itemId": "52260789-4809-5d96-8515-09aa20d89a40",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "5642eed7-1ee3-4956-a11b-29eec6a5aa74",
   "ownersBlockchainId": "1ff36ea46c5f48f4b01737bc20dea0149204dc9485e2469299a4cfa422f47982",
   "ownerDetails": {
    "id": "5642eed7-1ee3-4956-a11b-29eec6a5aa74",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "1ff36ea46c5f48f4b01737bc20dea0149204dc9485e2469299a4cfa422f47982"
   },
   "status": "active",
   "discount": 14,
   "price": {
    "DMC": "",
    "USD": "7445"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "3162aac8-c718-4ec0-b6e4-f8594f4b1de3",
    "isNew": true,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199258422103/inventory/#730_2_35889274579",
    "groupId": "76561199258422103",
    "linkId": "f7c6c70b-7b94-52b0-97ea-ff0c0434cbec",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 520514,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cfb4317664a50f5e0329f9",
    "emissionSerial": "65cfb4317664a50f5e0329f9",
    "sagaAddress": "0x3EDA16a19701C335C5cb490E01358520FcD4dCA9"
   },
   "createdAt": 1708241086,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "7d50016c-0791-561e-b136-e96a95b7ed30",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "66bd37cb-6048-4b8d-b6bb-d9d8174636be",
   "ownersBlockchainId": "a9df371c0373e9da2bcb872f1791ba0eebe0a907092868b0198b78b4680e579f",
   "ownerDetails": {
    "id": "66bd37cb-6048-4b8d-b6bb-d9d8174636be",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "a9df371c0373e9da2bcb872f1791ba0eebe0a907092868b0198b78b4680e579f"
   },
   "status": "active",
   "discount": 14,
   "price": {
    "DMC": "",
    "USD": "7447"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "9db83b5a-b9a5-47ed-96f3-7e7d8f118c7c",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199253701116/inventory/#730_2_35865246254",
    "groupId": "76561199253701116",
    "linkId": "f7d468c1-0827-5249-986f-a1b607ce5947",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 5,
    "tradeLockDuration": 448359,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ce2869b2c803caaa1d0fa6",
    "emissionSerial": "65ce2869b2c803caaa1d0fa6",
    "sagaAddress": "0x860F81750dC37102a2D047a29a946D370142C3a2"
   },
   "createdAt": 1708210805,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "f9d91efa-e9f7-5fc1-a06e-a283aa80831d",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "8fcd7e9c-8758-4710-9366-c751709f685d",
   "ownersBlockchainId": "387584222d1934f862dd8f2533cca84b1bcad30c8e3a145488d44d250f025e6f",
   "ownerDetails": {
    "id": "8fcd7e9c-8758-4710-9366-c751709f685d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "387584222d1934f862dd8f2533cca84b1bcad30c8e3a145488d44d250f025e6f"
   },
   "status": "active",
   "discount": 14,
   "price": {
    "DMC": "",
    "USD": "7449"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "830cb00a-0dee-4824-aae4-cd50439d42ad",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199501205242/inventory/#730_2_35906947470",
    "groupId": "76561199501205242",
    "linkId": "a2eae8b4-5429-5173-b31d-0c4083d9cf14",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 604113,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65d0eae47664a50f5ed1fe5e",
    "emissionSerial": "65d0eae47664a50f5ed1fe5e",
    "sagaAddress": "0x1E64aF05D07A86d6C2098b2B92EFB4f9C0350D46"
   },
   "createdAt": 1708202587,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "a582ed5e-6adf-5e2c-a406-5d65285517bc",
   "type": "offer",
   "amount": 1,
   "classId": "236997301:652707302",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "DreamHack 2014 Mirage Souvenir Package",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsV1VjdFBopqiqJghf1_b3fDRQ7duz2obckfOgYr3QwT5Xu5wp3byYoNSsiwC1_0Fla2igIoGTewU5YlCG-VGggbC4PrNReKs",
   "slug": "dreamhack-2014-mirage-package",
   "owner": "bd56d707-4294-408d-bf7b-adfc967e0ca7",
   "ownersBlockchainId": "592f6df8675246e0831248ea4ca21da647a96296a2f64191867bb52cceebc990",
   "ownerDetails": {
    "id": "bd56d707-4294-408d-bf7b-adfc967e0ca7",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "592f6df8675246e0831248ea4ca21da647a96296a2f64191867bb52cceebc990"
   },
   "status": "active",
   "discount": 2,
   "price": {
    "DMC": "",
    "USD": "50216"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "51429"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "8ea6b509-a8f1-4913-a125-2439d406b3d1",
    "isNew": false,
    "gameId": "a8db",
    "name": "DreamHack 2014 Mirage Package",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199513954537/inventory/#730_2_35214486195",
    "groupId": "76561199513954537",
    "withdrawable": true,
    "linkId": "6577d339-0c42-5751-afc3-e8dfe328635a",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "mirage"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65952fa884c193354e37cfac",
    "emissionSerial": "65952fa884c193354e37cfac",
    "sagaAddress": "0x3e6CC4709F7E80757C37F0B68b4355f73F7A7427"
   },
   "createdAt": 1704276160,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f65ba847df1e8dc85bdcbda4b93be509"
  },
  {
   "itemId": "a89ddb28-7123-5de1-926b-2553743ef28a",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "d9b20bdb-2158-416f-8f82-fd48329243a1",
   "ownersBlockchainId": "66b83306234042b2b237473398931056ce58531e7f8443db9108435ca8c0da97",
   "ownerDetails": {
    "id": "d9b20bdb-2158-416f-8f82-fd48329243a1",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "66b83306234042b2b237473398931056ce58531e7f8443db9108435ca8c0da97"
   },
   "status": "active",
   "discount": 13,
   "price": {
    "DMC": "",
    "USD": "7498"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "79dcb5ff-7709-4865-b963-6cecb8416214",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199495928050/inventory/#730_2_35886266464",
    "groupId": "76561199495928050",
    "linkId": "80aa8aa9-ac5a-573c-bc66-ec9b1ec20503",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 535005,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cf89ae7664a50f5e1600ff",
    "emissionSerial": "65cf89ae7664a50f5e1600ff",
    "sagaAddress": "0xD169A623C20f3b7fF65b3F6509B9fb958461C6ac"
   },
   "createdAt": 1708194927,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "714ab46a-827a-508d-99a9-b0fce9958ba9",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "ed59a510-cfa8-45d6-947c-bc54b366aec3",
   "ownersBlockchainId": "ee2b4eff32cabf48f8b7b185808430e3125e6e1e67ae10dc85bb7b272536bf0e",
   "ownerDetails": {
    "id": "ed59a510-cfa8-45d6-947c-bc54b366aec3",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ee2b4eff32cabf48f8b7b185808430e3125e6e1e67ae10dc85bb7b272536bf0e"
   },
   "status": "active",
   "discount": 11,
   "price": {
    "DMC": "",
    "USD": "7640"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "010c54de-2c7a-4740-9bf6-578167d6fe1c",
    "isNew": true,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199507139324/inventory/#730_2_35882813709",
    "groupId": "76561199507139324",
    "linkId": "19f2206c-e32e-5a50-a7bf-4258ee46af58",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 520412,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cf5b057664a50f5e845570",
    "emissionSerial": "65cf5b057664a50f5e845570",
    "sagaAddress": "0xd57E5e310c555A72d10106fac2CcA1eE63d6F1fF"
   },
   "createdAt": 1708241188,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "22a367e8-6131-5ec3-adf9-d41423ddba83",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "ed59a510-cfa8-45d6-947c-bc54b366aec3",
   "ownersBlockchainId": "ee2b4eff32cabf48f8b7b185808430e3125e6e1e67ae10dc85bb7b272536bf0e",
   "ownerDetails": {
    "id": "ed59a510-cfa8-45d6-947c-bc54b366aec3",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ee2b4eff32cabf48f8b7b185808430e3125e6e1e67ae10dc85bb7b272536bf0e"
   },
   "status": "active",
   "discount": 11,
   "price": {
    "DMC": "",
    "USD": "7640"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "dc79b60b-3c1c-40b1-ac38-b900cde97be6",
    "isNew": true,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199475274377/inventory/#730_2_35891687487",
    "groupId": "76561199475274377",
    "linkId": "dfe81d73-46dc-5720-92a2-8a7d64fc68fa",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 520412,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cfda4b7664a50f5ea63432",
    "emissionSerial": "65cfda4b7664a50f5ea63432",
    "sagaAddress": "0xd57E5e310c555A72d10106fac2CcA1eE63d6F1fF"
   },
   "createdAt": 1708241188,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "906438b0-3315-581f-abc0-f89053848fee",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:5712343610",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "19720480-7f18-4393-8986-18f5f33c4c2b",
   "ownersBlockchainId": "736535c8ce5e0a45594f1bcdd0139fa9f4e8fb6d0a6c65648aac8cfa02869965",
   "ownerDetails": {
    "id": "19720480-7f18-4393-8986-18f5f33c4c2b",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "736535c8ce5e0a45594f1bcdd0139fa9f4e8fb6d0a6c65648aac8cfa02869965"
   },
   "status": "active",
   "discount": 11,
   "price": {
    "DMC": "",
    "USD": "7649"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "415b5135-a7dd-4bdf-a55a-58ab5aafe88b",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199279390992/inventory/#730_2_35883025388",
    "groupId": "76561199279390992",
    "linkId": "0de3e06b-5cd8-5fca-9e62-33254bb421c8",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 535370,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cf5d527664a50f5e8b9b3e",
    "emissionSerial": "65cf5d527664a50f5e8b9b3e",
    "sagaAddress": "0xDCaf188bE2611a657F56a4F4ec17FFCC94A7b3e8"
   },
   "createdAt": 1708164195,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "56c9cc03-727d-5906-8025-d4d6e3563de0",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:5712343610",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "19720480-7f18-4393-8986-18f5f33c4c2b",
   "ownersBlockchainId": "736535c8ce5e0a45594f1bcdd0139fa9f4e8fb6d0a6c65648aac8cfa02869965",
   "ownerDetails": {
    "id": "19720480-7f18-4393-8986-18f5f33c4c2b",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "736535c8ce5e0a45594f1bcdd0139fa9f4e8fb6d0a6c65648aac8cfa02869965"
   },
   "status": "active",
   "discount": 11,
   "price": {
    "DMC": "",
    "USD": "7649"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "c20a867e-bd95-4543-ad2b-736319d56cbf",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199279390992/inventory/#730_2_35883025371",
    "groupId": "76561199279390992",
    "linkId": "3f925fe8-80f1-5bc2-a351-2515d7c5f420",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 534453,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cf5d517664a50f5e8b9a51",
    "emissionSerial": "65cf5d517664a50f5e8b9a51",
    "sagaAddress": "0xDCaf188bE2611a657F56a4F4ec17FFCC94A7b3e8"
   },
   "createdAt": 1708164195,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "5022cafe-f808-5b0a-a769-0b4dbb68a1bf",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:5712343610",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "19720480-7f18-4393-8986-18f5f33c4c2b",
   "ownersBlockchainId": "736535c8ce5e0a45594f1bcdd0139fa9f4e8fb6d0a6c65648aac8cfa02869965",
   "ownerDetails": {
    "id": "19720480-7f18-4393-8986-18f5f33c4c2b",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "736535c8ce5e0a45594f1bcdd0139fa9f4e8fb6d0a6c65648aac8cfa02869965"
   },
   "status": "active",
   "discount": 11,
   "price": {
    "DMC": "",
    "USD": "7649"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "f12528ea-28e1-456d-b270-d14c4ebd035a",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199279390992/inventory/#730_2_35883025345",
    "groupId": "76561199279390992",
    "linkId": "3692e994-7e05-5e67-9f7d-4a467cb65e6f",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 534083,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cf5d517664a50f5e8b99a7",
    "emissionSerial": "65cf5d517664a50f5e8b99a7",
    "sagaAddress": "0xDCaf188bE2611a657F56a4F4ec17FFCC94A7b3e8"
   },
   "createdAt": 1708164195,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "62efc292-efcf-597a-89d2-0d2a3d55e5e8",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
   "ownersBlockchainId": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe",
   "ownerDetails": {
    "id": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe"
   },
   "status": "active",
   "discount": 11,
   "price": {
    "DMC": "",
    "USD": "7650"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "b0b0fb29-187b-44fa-bc00-c70860d71066",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199487893549/inventory/#730_2_35899415531",
    "groupId": "76561199487893549",
    "linkId": "26eb4848-4c25-5959-9282-3664573e27cd",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 7,
    "tradeLockDuration": 620996,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65d07e777664a50f5eb4c2d7",
    "emissionSerial": "65d07e777664a50f5eb4c2d7",
    "sagaAddress": "0x2456BbAdEFD1AdBDf636D401F8Ebb97c8310aE45"
   },
   "createdAt": 1708162688,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "b6c05bce-80d4-5a64-b38f-6445f4cb56f8",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
   "ownersBlockchainId": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe",
   "ownerDetails": {
    "id": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe"
   },
   "status": "active",
   "discount": 11,
   "price": {
    "DMC": "",
    "USD": "7650"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "02bc6e75-84a4-4675-beb9-c3cc941aa620",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199487893549/inventory/#730_2_35899415500",
    "groupId": "76561199487893549",
    "linkId": "fcee057c-6b00-5b21-b0f6-6ad7b9e75eba",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 7,
    "tradeLockDuration": 622171,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65d07e577664a50f5eb46135",
    "emissionSerial": "65d07e577664a50f5eb46135",
    "sagaAddress": "0x2456BbAdEFD1AdBDf636D401F8Ebb97c8310aE45"
   },
   "createdAt": 1708162687,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "c5cdb23b-b046-5754-a236-5ea85a24fc88",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
   "ownersBlockchainId": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe",
   "ownerDetails": {
    "id": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe"
   },
   "status": "active",
   "discount": 11,
   "price": {
    "DMC": "",
    "USD": "7650"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "974d1792-1e89-4405-99ec-3cf217271161",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199487893549/inventory/#730_2_35899415507",
    "groupId": "76561199487893549",
    "linkId": "5586a4aa-f164-5e14-a120-3d2e2ef6dfda",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 7,
    "tradeLockDuration": 621198,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65d07e587664a50f5eb4623a",
    "emissionSerial": "65d07e587664a50f5eb4623a",
    "sagaAddress": "0x2456BbAdEFD1AdBDf636D401F8Ebb97c8310aE45"
   },
   "createdAt": 1708162687,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "b61f0663-fa70-5a05-a6ae-1d8acdc72069",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
   "ownersBlockchainId": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe",
   "ownerDetails": {
    "id": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe"
   },
   "status": "active",
   "discount": 11,
   "price": {
    "DMC": "",
    "USD": "7650"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "5a1f2b6f-eb01-4d02-9c6c-d098a7312cc4",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199487893549/inventory/#730_2_35899415523",
    "groupId": "76561199487893549",
    "linkId": "f9d539df-d2a7-5ced-a40a-f0d7be23172d",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 7,
    "tradeLockDuration": 621611,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65d07e767664a50f5eb4c267",
    "emissionSerial": "65d07e767664a50f5eb4c267",
    "sagaAddress": "0x2456BbAdEFD1AdBDf636D401F8Ebb97c8310aE45"
   },
   "createdAt": 1708162685,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "6d9a8b14-1ef9-5b58-8327-a52df7c3a800",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801297",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "CS:GO Weapon Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT",
   "slug": "csgo-weapon-case",
   "owner": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
   "ownersBlockchainId": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe",
   "ownerDetails": {
    "id": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe"
   },
   "status": "active",
   "discount": 11,
   "price": {
    "DMC": "",
    "USD": "7650"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "8680"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "8fe7b6a1-b703-40e7-8a30-957a2672446f",
    "isNew": false,
    "gameId": "a8db",
    "name": "CS:GO Weapon Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199487893549/inventory/#730_2_35899415517",
    "groupId": "76561199487893549",
    "linkId": "6572a1ee-886e-557f-ad83-5c3c7883ced4",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 7,
    "tradeLockDuration": 621252,
    "itemType": "container",
    "collection": [
     "arms deal"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65d07e767664a50f5eb4c1f2",
    "emissionSerial": "65d07e767664a50f5eb4c1f2",
    "sagaAddress": "0x2456BbAdEFD1AdBDf636D401F8Ebb97c8310aE45"
   },
   "createdAt": 1708162685,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:f96f34ba25aa795856bc7252916279bc"
  },
  {
   "itemId": "410069c5-aecf-5443-8d8b-75a0eefc19de",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "93a19048-cb6d-4188-be33-ae7d533febd3",
   "ownersBlockchainId": "65c224cb00ae564ab49f558c87048bff96ced6caab028a53f66e64cfffa1fa3f",
   "ownerDetails": {
    "id": "93a19048-cb6d-4188-be33-ae7d533febd3",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "65c224cb00ae564ab49f558c87048bff96ced6caab028a53f66e64cfffa1fa3f"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3333"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "68bf99e5-4c16-483e-9157-d553af0dcce9",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199489245485/inventory/#730_2_35818718707",
    "groupId": "76561199489245485",
    "linkId": "0b6f7df3-7e25-5754-bba3-1acaa300e9ea",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 2,
    "tradeLockDuration": 256215,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cb7147b2c803caaa3b860b",
    "emissionSerial": "65cb7147b2c803caaa3b860b",
    "sagaAddress": "0xDfdAD36dD3c4262Bc468b9924163d9FDEd4f5893"
   },
   "createdAt": 1708242196,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "4d20891c-d7a6-55c0-9597-814dd9f92a7e",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "93a19048-cb6d-4188-be33-ae7d533febd3",
   "ownersBlockchainId": "65c224cb00ae564ab49f558c87048bff96ced6caab028a53f66e64cfffa1fa3f",
   "ownerDetails": {
    "id": "93a19048-cb6d-4188-be33-ae7d533febd3",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "65c224cb00ae564ab49f558c87048bff96ced6caab028a53f66e64cfffa1fa3f"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3333"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "7b9709d6-d09d-4cfc-86e0-d23c5a1e6d32",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199497419299/inventory/#730_2_35782382639",
    "groupId": "76561199497419299",
    "linkId": "d5e34366-0c1d-5da8-8e91-753a1c478ab3",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 83415,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c885b0b2c803caaab9b906",
    "emissionSerial": "65c885b0b2c803caaab9b906",
    "sagaAddress": "0xDfdAD36dD3c4262Bc468b9924163d9FDEd4f5893"
   },
   "createdAt": 1708242196,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "179a28b8-ce4d-50f0-9e0a-bbfa9fe94252",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "93a19048-cb6d-4188-be33-ae7d533febd3",
   "ownersBlockchainId": "65c224cb00ae564ab49f558c87048bff96ced6caab028a53f66e64cfffa1fa3f",
   "ownerDetails": {
    "id": "93a19048-cb6d-4188-be33-ae7d533febd3",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "65c224cb00ae564ab49f558c87048bff96ced6caab028a53f66e64cfffa1fa3f"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3333"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "c72adab2-2915-4e46-a7b0-398114b4fd8b",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199497419299/inventory/#730_2_35782382594",
    "groupId": "76561199497419299",
    "linkId": "a3d0cbba-810a-583a-ad38-3edf5356a4a7",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 83415,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c885b0b2c803caaab9b3e1",
    "emissionSerial": "65c885b0b2c803caaab9b3e1",
    "sagaAddress": "0xDfdAD36dD3c4262Bc468b9924163d9FDEd4f5893"
   },
   "createdAt": 1708242196,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "5390224f-4e88-57ac-a886-3c6f6636dfe4",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "93a19048-cb6d-4188-be33-ae7d533febd3",
   "ownersBlockchainId": "65c224cb00ae564ab49f558c87048bff96ced6caab028a53f66e64cfffa1fa3f",
   "ownerDetails": {
    "id": "93a19048-cb6d-4188-be33-ae7d533febd3",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "65c224cb00ae564ab49f558c87048bff96ced6caab028a53f66e64cfffa1fa3f"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3333"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "d304e9c9-e301-4fb7-a504-dddf7de35c71",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199497419299/inventory/#730_2_35782382625",
    "groupId": "76561199497419299",
    "linkId": "f9854853-03f7-59f9-b401-009c63557dc4",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 83415,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c885b0b2c803caaab9b70f",
    "emissionSerial": "65c885b0b2c803caaab9b70f",
    "sagaAddress": "0xDfdAD36dD3c4262Bc468b9924163d9FDEd4f5893"
   },
   "createdAt": 1708242196,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "7706f5b2-8ca9-5cd7-ac1a-895a95ab06cb",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "93a19048-cb6d-4188-be33-ae7d533febd3",
   "ownersBlockchainId": "65c224cb00ae564ab49f558c87048bff96ced6caab028a53f66e64cfffa1fa3f",
   "ownerDetails": {
    "id": "93a19048-cb6d-4188-be33-ae7d533febd3",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "65c224cb00ae564ab49f558c87048bff96ced6caab028a53f66e64cfffa1fa3f"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3333"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "e8586b33-b9e8-494b-b851-62875dfd5a3d",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199497419299/inventory/#730_2_35782382612",
    "groupId": "76561199497419299",
    "linkId": "639ac003-7b75-5596-a059-8ebf0f964f55",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 83415,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c885b0b2c803caaab9b563",
    "emissionSerial": "65c885b0b2c803caaab9b563",
    "sagaAddress": "0xDfdAD36dD3c4262Bc468b9924163d9FDEd4f5893"
   },
   "createdAt": 1708242196,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "ab7bfc77-81ec-5412-b0a1-d8659affb3a3",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "fbe8c99d-0264-4664-89fd-2a4a80721080",
   "ownersBlockchainId": "7db5f205ad896a5362c293bd3b49bb3b03bd44dc865398ed5690d5ddee108e8d",
   "ownerDetails": {
    "id": "fbe8c99d-0264-4664-89fd-2a4a80721080",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7db5f205ad896a5362c293bd3b49bb3b03bd44dc865398ed5690d5ddee108e8d"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3335"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "a5a18ba7-4ea9-4d45-9071-ede7dd8f23b2",
    "isNew": true,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199281382967/inventory/#730_2_35838296781",
    "groupId": "76561199281382967",
    "linkId": "276c90a0-560e-5d4b-953c-f51be0ca2573",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 4,
    "tradeLockDuration": 354089,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ccb551b2c803caaab81b05",
    "emissionSerial": "65ccb551b2c803caaab81b05",
    "sagaAddress": "0x57e045c63CEf7FECED1A017a21C361EC653a7a9c"
   },
   "createdAt": 1708234710,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "f197b177-ba28-5f1e-8c00-04f47af11e7a",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "c3a8fea2-8a36-4b45-a50d-fed06b556de3",
   "ownersBlockchainId": "8e9ece61f482414199e71f6e967e0c4485f2e524cba54f9fbfb200adba322109",
   "ownerDetails": {
    "id": "c3a8fea2-8a36-4b45-a50d-fed06b556de3",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "8e9ece61f482414199e71f6e967e0c4485f2e524cba54f9fbfb200adba322109"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3337"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "7ef7c827-d6ab-47db-8ec5-c9773661f1b8",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199269181907/inventory/#730_2_35890215487",
    "groupId": "76561199269181907",
    "linkId": "4fc44103-44a2-521e-8103-8ec809817644",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 534972,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cfc2337664a50f5e3f4b42",
    "emissionSerial": "65cfc2337664a50f5e3f4b42",
    "sagaAddress": "0x034a2377ac2CFe150A53cF735c47a3586D3b7CB9"
   },
   "createdAt": 1708211447,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "84e3ea70-a805-56a4-a54e-c4fc3ca6bdbe",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
   "ownersBlockchainId": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49",
   "ownerDetails": {
    "id": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "55cdd6e1-3411-4a79-a5f8-5d899ddce741",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199489317939/inventory/#730_2_35722240401",
    "groupId": "76561199489317939",
    "withdrawable": true,
    "linkId": "fb73aeea-cb79-57ba-8cde-b3d657762256",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c4beb0b2c803caaaea9edd",
    "emissionSerial": "65c4beb0b2c803caaaea9edd",
    "sagaAddress": "0x9C163a07308a6E109982Ad8159D0A768BE775467"
   },
   "createdAt": 1708202320,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "6375f065-d809-541c-8075-6f8e2a89b195",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
   "ownersBlockchainId": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49",
   "ownerDetails": {
    "id": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "fd788479-054f-4258-870a-fa8dc7c37093",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199302189996/inventory/#730_2_35722144544",
    "groupId": "76561199302189996",
    "withdrawable": true,
    "linkId": "c6ea9b43-0497-546c-bd84-49c2b338880c",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c4bd94b2c803caaae5c76b",
    "emissionSerial": "65c4bd94b2c803caaae5c76b",
    "sagaAddress": "0x9C163a07308a6E109982Ad8159D0A768BE775467"
   },
   "createdAt": 1708202314,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "a254ae34-4f38-5afd-9bff-679099a51bf5",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
   "ownersBlockchainId": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49",
   "ownerDetails": {
    "id": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "08cc124d-fadd-4e61-b364-c5bff0ec89bb",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199489317939/inventory/#730_2_35722240355",
    "groupId": "76561199489317939",
    "withdrawable": true,
    "linkId": "ed5e27a5-ba20-50da-878f-6522332399e2",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c4beafb2c803caaaea9d27",
    "emissionSerial": "65c4beafb2c803caaaea9d27",
    "sagaAddress": "0x9C163a07308a6E109982Ad8159D0A768BE775467"
   },
   "createdAt": 1708202306,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "614f9fc9-f93b-5fd6-aa54-1446cfdb0cc0",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
   "ownersBlockchainId": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49",
   "ownerDetails": {
    "id": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "7f057ae7-afbe-44c5-b0b3-a82dc3c74e2c",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199296144542/inventory/#730_2_35722180021",
    "groupId": "76561199296144542",
    "withdrawable": true,
    "linkId": "32d7634a-4a91-551d-8a41-26700717f656",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c4bde5b2c803caaae7c472",
    "emissionSerial": "65c4bde5b2c803caaae7c472",
    "sagaAddress": "0x9C163a07308a6E109982Ad8159D0A768BE775467"
   },
   "createdAt": 1708202290,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "1cdf4d38-50c4-5447-9923-9b357421e7e8",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
   "ownersBlockchainId": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49",
   "ownerDetails": {
    "id": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "c2effeb3-2f9a-46ed-b263-167dea81eef7",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199302189996/inventory/#730_2_35722144528",
    "groupId": "76561199302189996",
    "withdrawable": true,
    "linkId": "3a21baf3-e2f6-51d5-8a72-00c364bd52f5",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c4bd93b2c803caaae5c6b3",
    "emissionSerial": "65c4bd93b2c803caaae5c6b3",
    "sagaAddress": "0x9C163a07308a6E109982Ad8159D0A768BE775467"
   },
   "createdAt": 1708202271,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "fc7df598-3219-50eb-84d8-ffc2995f875b",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
   "ownersBlockchainId": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49",
   "ownerDetails": {
    "id": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "a4809f00-ab42-4b15-a69f-db2da11bb253",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199547807249/inventory/#730_2_35722120844",
    "groupId": "76561199547807249",
    "withdrawable": true,
    "linkId": "444ec32d-834b-51ba-bbc3-bc3878d576f9",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c4bd28b2c803caaae42305",
    "emissionSerial": "65c4bd28b2c803caaae42305",
    "sagaAddress": "0x9C163a07308a6E109982Ad8159D0A768BE775467"
   },
   "createdAt": 1708202262,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "75be30ae-0aa5-562e-be04-85b6df97f50f",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
   "ownersBlockchainId": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49",
   "ownerDetails": {
    "id": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "002e2869-4a68-454d-bfdf-1c4408249425",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199296144542/inventory/#730_2_35722180030",
    "groupId": "76561199296144542",
    "withdrawable": true,
    "linkId": "19763a0e-cafb-588a-b919-b2526f6d346e",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c4be08b2c803caaae83085",
    "emissionSerial": "65c4be08b2c803caaae83085",
    "sagaAddress": "0x9C163a07308a6E109982Ad8159D0A768BE775467"
   },
   "createdAt": 1708202255,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "00e2f1a3-8494-56e8-a891-7d784b3a13b8",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:5702370385",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
   "ownersBlockchainId": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49",
   "ownerDetails": {
    "id": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "94d16345-7b91-403e-9c98-191b11b6007d",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199280743121/inventory/#730_2_35721978295",
    "groupId": "76561199280743121",
    "withdrawable": true,
    "linkId": "a0a83008-32ad-531e-810f-2f631a2bfae7",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c4bb4bb2c803caaadc3769",
    "emissionSerial": "65c4bb4bb2c803caaadc3769",
    "sagaAddress": "0x9C163a07308a6E109982Ad8159D0A768BE775467"
   },
   "createdAt": 1708202247,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "fcfa69b2-7bd1-56b1-aa56-fd29710e661e",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
   "ownersBlockchainId": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49",
   "ownerDetails": {
    "id": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "715c3fe2-3745-463b-a1e1-981bfd300ad4",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199296144542/inventory/#730_2_35722180133",
    "groupId": "76561199296144542",
    "withdrawable": true,
    "linkId": "89b4f1a6-0c51-5552-b434-da507c253103",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c4be2cb2c803caaae8baa9",
    "emissionSerial": "65c4be2cb2c803caaae8baa9",
    "sagaAddress": "0x9C163a07308a6E109982Ad8159D0A768BE775467"
   },
   "createdAt": 1708202241,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "ed80e213-e9af-54db-b100-b4c147299cd7",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
   "ownersBlockchainId": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49",
   "ownerDetails": {
    "id": "5e6bd484-c93d-4bf5-b468-7957a63fc389",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "7cf7d409207f4acfac62e50c718ef66440d30bda79964ad48f5f0680a2e9af49"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "a65289ef-c08f-4819-8600-49edc5d9ad0b",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199489317939/inventory/#730_2_35722240384",
    "groupId": "76561199489317939",
    "withdrawable": true,
    "linkId": "24a6c4fc-a4de-5cce-a537-4c78b2b95ccc",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c4beb0b2c803caaaea9e86",
    "emissionSerial": "65c4beb0b2c803caaaea9e86",
    "sagaAddress": "0x9C163a07308a6E109982Ad8159D0A768BE775467"
   },
   "createdAt": 1708202235,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "bdf2914b-f756-5c91-b9af-e937a23663a1",
   "type": "offer",
   "amount": 1,
   "classId": "0:5703308038",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "8fcd7e9c-8758-4710-9366-c751709f685d",
   "ownersBlockchainId": "387584222d1934f862dd8f2533cca84b1bcad30c8e3a145488d44d250f025e6f",
   "ownerDetails": {
    "id": "8fcd7e9c-8758-4710-9366-c751709f685d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "387584222d1934f862dd8f2533cca84b1bcad30c8e3a145488d44d250f025e6f"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "41fd5b93-aaa3-4347-90d4-1a15ddd39240",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199296108458/inventory/#730_2_35719060590",
    "groupId": "76561199296108458",
    "withdrawable": true,
    "linkId": "3fd33ca9-0d32-522a-88e6-e51752987108",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c492bab2c803caaa397925",
    "emissionSerial": "65c492bab2c803caaa397925",
    "sagaAddress": "0x1E64aF05D07A86d6C2098b2B92EFB4f9C0350D46"
   },
   "createdAt": 1708190526,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "4e1981b3-690b-5df0-be48-43bcaaa43d3d",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:5703308038",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "8fcd7e9c-8758-4710-9366-c751709f685d",
   "ownersBlockchainId": "387584222d1934f862dd8f2533cca84b1bcad30c8e3a145488d44d250f025e6f",
   "ownerDetails": {
    "id": "8fcd7e9c-8758-4710-9366-c751709f685d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "387584222d1934f862dd8f2533cca84b1bcad30c8e3a145488d44d250f025e6f"
   },
   "status": "active",
   "discount": 23,
   "price": {
    "DMC": "",
    "USD": "3339"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "8f0734de-17c8-4df2-b7e4-37216a4a3e2a",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199296108458/inventory/#730_2_35719060579",
    "groupId": "76561199296108458",
    "withdrawable": true,
    "linkId": "c3e4a93e-7dd3-5f87-8b15-ca4617383195",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c492bab2c803caaa39780b",
    "emissionSerial": "65c492bab2c803caaa39780b",
    "sagaAddress": "0x1E64aF05D07A86d6C2098b2B92EFB4f9C0350D46"
   },
   "createdAt": 1708190526,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "12cefa58-c0ec-57e4-b420-2a6447d091d7",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
   "ownersBlockchainId": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d",
   "ownerDetails": {
    "id": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3354"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "05919ab7-44c0-40bf-973a-b3336466dc91",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199253925411/inventory/#730_2_35801790619",
    "groupId": "76561199253925411",
    "linkId": "8b575735-18cb-5bf8-b291-c5eb2681d199",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 2,
    "tradeLockDuration": 190156,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ca059bb2c803caaaa97672",
    "emissionSerial": "65ca059bb2c803caaaa97672",
    "sagaAddress": "0xbE7F16C5d17584ee24b52F1f5058BCe2fa969157"
   },
   "createdAt": 1708121001,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "451a0254-417f-5234-8e5b-8516630a9eaf",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
   "ownersBlockchainId": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d",
   "ownerDetails": {
    "id": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3354"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "0b993d39-37d3-4e68-a010-b38895b3aad5",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199492744890/inventory/#730_2_35789024976",
    "groupId": "76561199492744890",
    "linkId": "3a9a49ba-c6c1-5b52-ab8a-6959c045961f",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 1,
    "tradeLockDuration": 103721,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c8ea5fb2c803caaaa5a559",
    "emissionSerial": "65c8ea5fb2c803caaaa5a559",
    "sagaAddress": "0xbE7F16C5d17584ee24b52F1f5058BCe2fa969157"
   },
   "createdAt": 1708121001,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "d7c733b1-a6d3-5852-b679-7264e5206412",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
   "ownersBlockchainId": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d",
   "ownerDetails": {
    "id": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3354"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "188f1de5-db2d-4c7f-9227-aecb0401e597",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199253925411/inventory/#730_2_35801790603",
    "groupId": "76561199253925411",
    "linkId": "d256a590-ff1d-559a-a0fd-d172b9c4ed5f",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 2,
    "tradeLockDuration": 190027,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ca0555b2c803caaaa87165",
    "emissionSerial": "65ca0555b2c803caaaa87165",
    "sagaAddress": "0xbE7F16C5d17584ee24b52F1f5058BCe2fa969157"
   },
   "createdAt": 1708121001,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "3ea44fde-9f7d-58df-b595-69521201ac77",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
   "ownersBlockchainId": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d",
   "ownerDetails": {
    "id": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3354"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "35ad4af1-ab1c-48ba-9984-ccfa0caf46ea",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199253925411/inventory/#730_2_35801790607",
    "groupId": "76561199253925411",
    "linkId": "35d17efa-49ae-5997-a42a-7135e49d4c63",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 2,
    "tradeLockDuration": 189849,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ca0577b2c803caaaa8e170",
    "emissionSerial": "65ca0577b2c803caaaa8e170",
    "sagaAddress": "0xbE7F16C5d17584ee24b52F1f5058BCe2fa969157"
   },
   "createdAt": 1708121001,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "00f52c00-42ef-55fe-81f2-14128151023e",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
   "ownersBlockchainId": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d",
   "ownerDetails": {
    "id": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3354"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "3f3f5623-7b1c-4132-9a44-d87b71ad0cbe",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199492744890/inventory/#730_2_35789025022",
    "groupId": "76561199492744890",
    "linkId": "3eb43fdd-e62e-5948-b9c9-beffe4cd9e1b",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 1,
    "tradeLockDuration": 103384,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c8ea60b2c803caaaa5a7d7",
    "emissionSerial": "65c8ea60b2c803caaaa5a7d7",
    "sagaAddress": "0xbE7F16C5d17584ee24b52F1f5058BCe2fa969157"
   },
   "createdAt": 1708121001,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "e7f88e44-a56a-52b7-95e0-8912c8cb3950",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
   "ownersBlockchainId": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d",
   "ownerDetails": {
    "id": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3354"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "946dcfc2-ae0d-495d-a060-4856469bc133",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199253925411/inventory/#730_2_35801790562",
    "groupId": "76561199253925411",
    "linkId": "ce1070f4-478a-5380-a5b9-428adcf547f1",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 2,
    "tradeLockDuration": 189217,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ca0554b2c803caaaa86ec9",
    "emissionSerial": "65ca0554b2c803caaaa86ec9",
    "sagaAddress": "0xbE7F16C5d17584ee24b52F1f5058BCe2fa969157"
   },
   "createdAt": 1708121001,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "21ebd592-ad04-5be4-a5ad-5676bda84971",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
   "ownersBlockchainId": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d",
   "ownerDetails": {
    "id": "dbd17ca2-ca4e-413d-ab46-db03d461326d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "86f8f82c55d625bb05460b06c9099550bb22e5d1b6078d91789f7d4a9368951d"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3354"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "9cac9719-2de8-43ee-889b-d15e8fd99809",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199253925411/inventory/#730_2_35801790571",
    "groupId": "76561199253925411",
    "linkId": "7e4419f2-d68e-5630-96c6-4e8cb9796b7a",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 2,
    "tradeLockDuration": 189167,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ca0554b2c803caaaa86fb9",
    "emissionSerial": "65ca0554b2c803caaaa86fb9",
    "sagaAddress": "0xbE7F16C5d17584ee24b52F1f5058BCe2fa969157"
   },
   "createdAt": 1708121001,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "8771253b-e6a9-55a4-9237-f2e293a1d09b",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
   "ownersBlockchainId": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64",
   "ownerDetails": {
    "id": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3355"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "27916e55-89c9-4df2-b7db-22921bd52569",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199302340077/inventory/#730_2_35891122150",
    "groupId": "76561199302340077",
    "linkId": "1707004f-8a71-54ca-970d-46b423042f20",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 535536,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cfd0ca7664a50f5e7d6f05",
    "emissionSerial": "65cfd0ca7664a50f5e7d6f05",
    "sagaAddress": "0x33a7d3375809085CBE6Aa88d0f8B1f00474C3111"
   },
   "createdAt": 1708118259,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "ef5054c3-ce1e-541b-8c6c-596d9ff2c414",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
   "ownersBlockchainId": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64",
   "ownerDetails": {
    "id": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3355"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "2d065be3-e98a-4826-8a34-a35ef96b43f6",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199302340077/inventory/#730_2_35891122123",
    "groupId": "76561199302340077",
    "linkId": "d0a38795-16d0-5614-ac36-ea729c07c6d0",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 535502,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cfd0ca7664a50f5e7d6dc7",
    "emissionSerial": "65cfd0ca7664a50f5e7d6dc7",
    "sagaAddress": "0x33a7d3375809085CBE6Aa88d0f8B1f00474C3111"
   },
   "createdAt": 1708118259,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "3d25967f-40fb-5bcc-bb28-568ad16e24cc",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
   "ownersBlockchainId": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64",
   "ownerDetails": {
    "id": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3355"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "65be8f59-c10b-4f4a-b696-e8e92eed7318",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199302340077/inventory/#730_2_35891122093",
    "groupId": "76561199302340077",
    "linkId": "43cc3cae-6e54-5497-a259-f4e0253e3104",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 531692,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cfd0a97664a50f5e7d19ff",
    "emissionSerial": "65cfd0a97664a50f5e7d19ff",
    "sagaAddress": "0x33a7d3375809085CBE6Aa88d0f8B1f00474C3111"
   },
   "createdAt": 1708118259,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "e71e83cc-dd9b-59be-9d57-0cec76949963",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
   "ownersBlockchainId": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64",
   "ownerDetails": {
    "id": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3355"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "e4848ab9-930e-47bc-9a67-3bcfc52a71e3",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199302340077/inventory/#730_2_35891122137",
    "groupId": "76561199302340077",
    "linkId": "fc136047-1e6a-5ba9-bf42-888562e7c283",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 534183,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cfd0ca7664a50f5e7d6e84",
    "emissionSerial": "65cfd0ca7664a50f5e7d6e84",
    "sagaAddress": "0x33a7d3375809085CBE6Aa88d0f8B1f00474C3111"
   },
   "createdAt": 1708118259,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "d3473361-9e75-5c98-8769-b88a9015feac",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "8707bf54-a90b-4a68-a40a-8b55235d8f5d",
   "ownersBlockchainId": "1245a485b63d77a07f9d5af19d665f1d08ed5669c1f9929a7b99623f681d3610",
   "ownerDetails": {
    "id": "8707bf54-a90b-4a68-a40a-8b55235d8f5d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "1245a485b63d77a07f9d5af19d665f1d08ed5669c1f9929a7b99623f681d3610"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3359"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "98618619-53d8-42f8-b537-baa3df5aff81",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199257988493/inventory/#730_2_35879653507",
    "groupId": "76561199257988493",
    "linkId": "ac6fe36e-53c9-57b4-bdff-31f66fcda791",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 534790,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cf25df7664a50f5e58e17b",
    "emissionSerial": "65cf25df7664a50f5e58e17b",
    "sagaAddress": "0xEaD43E4D1c3c32f9cA600B7859cCAbf25FfdeF41"
   },
   "createdAt": 1708074505,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "bce0817c-8f1d-5021-a2d1-21ec0982e658",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "8707bf54-a90b-4a68-a40a-8b55235d8f5d",
   "ownersBlockchainId": "1245a485b63d77a07f9d5af19d665f1d08ed5669c1f9929a7b99623f681d3610",
   "ownerDetails": {
    "id": "8707bf54-a90b-4a68-a40a-8b55235d8f5d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "1245a485b63d77a07f9d5af19d665f1d08ed5669c1f9929a7b99623f681d3610"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3359"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "ec2acebb-d8c8-411c-80df-82d333c561a1",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199257988493/inventory/#730_2_35879653496",
    "groupId": "76561199257988493",
    "linkId": "afe000d8-32c9-562e-8ef0-4f2bd9ed08d0",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 534123,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cf25bd7664a50f5e583fcd",
    "emissionSerial": "65cf25bd7664a50f5e583fcd",
    "sagaAddress": "0xEaD43E4D1c3c32f9cA600B7859cCAbf25FfdeF41"
   },
   "createdAt": 1708074504,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "54f60dc6-299b-508c-83f5-8cd1edd920ae",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "8707bf54-a90b-4a68-a40a-8b55235d8f5d",
   "ownersBlockchainId": "1245a485b63d77a07f9d5af19d665f1d08ed5669c1f9929a7b99623f681d3610",
   "ownerDetails": {
    "id": "8707bf54-a90b-4a68-a40a-8b55235d8f5d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "1245a485b63d77a07f9d5af19d665f1d08ed5669c1f9929a7b99623f681d3610"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3359"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "f8d1dbe4-cf26-48e8-8ee9-12c9badb396e",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199257988493/inventory/#730_2_35879653521",
    "groupId": "76561199257988493",
    "linkId": "682d0b6f-93f3-5ee7-acd1-29c2e16a3bd1",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 534022,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cf25e07664a50f5e58e257",
    "emissionSerial": "65cf25e07664a50f5e58e257",
    "sagaAddress": "0xEaD43E4D1c3c32f9cA600B7859cCAbf25FfdeF41"
   },
   "createdAt": 1708074504,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "1be4425d-94ff-5f6f-8638-8991f928b83a",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801277",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "eSports 2013 Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsVk5kKhZDpYX3e1YznfCcdzkR74vnw9TZwa-sYOOCzzoF6ZJ0jL6Qp9uj3Qbj_Uc6Z2z1I9WLMlhp9VPHu3g",
   "slug": "esports-2013-case",
   "owner": "e0f7f18e-1cfb-457d-b171-621f3d9cfccd",
   "ownersBlockchainId": "59becdf181e584f7751b70e213fd2f0cd1d6c5667f1f046fe0de8dafc78d5310",
   "ownerDetails": {
    "id": "e0f7f18e-1cfb-457d-b171-621f3d9cfccd",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "59becdf181e584f7751b70e213fd2f0cd1d6c5667f1f046fe0de8dafc78d5310"
   },
   "status": "active",
   "discount": 24,
   "price": {
    "DMC": "",
    "USD": "3000"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "3989"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "73234983-73e2-4cac-a177-b4ed3eb30dae",
    "isNew": false,
    "gameId": "a8db",
    "name": "eSports 2013 Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199270928511/inventory/#730_2_34155689921",
    "groupId": "76561199270928511",
    "withdrawable": true,
    "linkId": "028c804a-48ba-5177-9653-20b4888da32d",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "esports 2013"
    ],
    "saleRestricted": false,
    "inGameAssetID": "6533b9ae7856df45af3a6fd4",
    "emissionSerial": "6533b9ae7856df45af3a6fd4",
    "sagaAddress": "0x8C8e07d154a544593F1F37eD07BB13EbdbEA6019"
   },
   "createdAt": 1708029513,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:9a7979bc52cd04383c6232fba1956d6a"
  },
  {
   "itemId": "ade83d14-d37f-5f95-91cd-07366e2930e2",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801277",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "eSports 2013 Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsVk5kKhZDpYX3e1YznfCcdzkR74vnw9TZwa-sYOOCzzoF6ZJ0jL6Qp9uj3Qbj_Uc6Z2z1I9WLMlhp9VPHu3g",
   "slug": "esports-2013-case",
   "owner": "e0f7f18e-1cfb-457d-b171-621f3d9cfccd",
   "ownersBlockchainId": "59becdf181e584f7751b70e213fd2f0cd1d6c5667f1f046fe0de8dafc78d5310",
   "ownerDetails": {
    "id": "e0f7f18e-1cfb-457d-b171-621f3d9cfccd",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "59becdf181e584f7751b70e213fd2f0cd1d6c5667f1f046fe0de8dafc78d5310"
   },
   "status": "active",
   "discount": 24,
   "price": {
    "DMC": "",
    "USD": "3000"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "3989"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "ce0b58a5-ac1e-4533-98ce-694457a4cb24",
    "isNew": false,
    "gameId": "a8db",
    "name": "eSports 2013 Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199508903355/inventory/#730_2_33430559959",
    "groupId": "76561199508903355",
    "withdrawable": true,
    "linkId": "04fb6d60-b1ba-5f07-a861-bd3a751b711a",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "esports 2013"
    ],
    "saleRestricted": false,
    "inGameAssetID": "650d516ee30038fc41a454bf",
    "emissionSerial": "650d516ee30038fc41a454bf",
    "sagaAddress": "0x8C8e07d154a544593F1F37eD07BB13EbdbEA6019"
   },
   "createdAt": 1708029513,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:9a7979bc52cd04383c6232fba1956d6a"
  },
  {
   "itemId": "7159bc11-8c97-540b-b52f-30cca27867b5",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "ba0eab02-8180-402f-9a59-777a38e8639c",
   "ownersBlockchainId": "c307609c831343a3120dce44c52ea5ff31da95c0968562396c2b7ceb698214bf",
   "ownerDetails": {
    "id": "ba0eab02-8180-402f-9a59-777a38e8639c",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "c307609c831343a3120dce44c52ea5ff31da95c0968562396c2b7ceb698214bf"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3363"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "37b7f7a1-2102-4a24-9540-f129054f72b6",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199488148502/inventory/#730_2_35863227985",
    "groupId": "76561199488148502",
    "linkId": "504e79ed-1989-55a2-aa2d-95681919ea2b",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 5,
    "tradeLockDuration": 449036,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ce0fc9b2c803caaad99bb2",
    "emissionSerial": "65ce0fc9b2c803caaad99bb2",
    "sagaAddress": "0x632E5041B46a6Fc6362051DF02096aB64cc19d48"
   },
   "createdAt": 1708003310,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "1e2ed71d-4194-5b3c-84c0-95446ea0e158",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "3ea8c155-5124-4b08-85c0-368fa12e10ec",
   "ownersBlockchainId": "6c5259741a0c44ff817162f07044a1ebf874aaf91ed745958e9c2b38e360d7ad",
   "ownerDetails": {
    "id": "3ea8c155-5124-4b08-85c0-368fa12e10ec",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "6c5259741a0c44ff817162f07044a1ebf874aaf91ed745958e9c2b38e360d7ad"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3368"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "b91a8312-82df-40c4-b013-cd82615a12f9",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199261967748/inventory/#730_2_35632385470",
    "groupId": "76561199261967748",
    "withdrawable": true,
    "linkId": "8f4501e1-6a4a-5e1c-9b5f-583f69ea91e2",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65be08b71e285157a1184c09",
    "emissionSerial": "65be08b71e285157a1184c09",
    "sagaAddress": "0x1FaB2fA2B66eFF78532d3C4f52cC65EAAE2b2D46"
   },
   "createdAt": 1708235227,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "e87b019b-b79c-515d-8468-174a5d2fada7",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801277",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "eSports 2013 Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsVk5kKhZDpYX3e1YznfCcdzkR74vnw9TZwa-sYOOCzzoF6ZJ0jL6Qp9uj3Qbj_Uc6Z2z1I9WLMlhp9VPHu3g",
   "slug": "esports-2013-case",
   "owner": "f511faa3-591f-4197-a539-10a068696579",
   "ownersBlockchainId": "90b2bd776fa9d9377f1ff48afa9f9366a44084c7ddc0a8fd0b87b6cf0778f064",
   "ownerDetails": {
    "id": "f511faa3-591f-4197-a539-10a068696579",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "90b2bd776fa9d9377f1ff48afa9f9366a44084c7ddc0a8fd0b87b6cf0778f064"
   },
   "status": "active",
   "discount": 24,
   "price": {
    "DMC": "",
    "USD": "3007"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "3989"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "88d2668e-71c5-46b0-8096-71fbf443e0ea",
    "isNew": false,
    "gameId": "a8db",
    "name": "eSports 2013 Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199281415715/inventory/#730_2_35805241890",
    "groupId": "76561199281415715",
    "linkId": "13caad25-f2ca-5dbc-a73a-0827de3a3e65",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 2,
    "tradeLockDuration": 189300,
    "itemType": "container",
    "collection": [
     "esports 2013"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ca3fc5b2c803caaac05d2e",
    "emissionSerial": "65ca3fc5b2c803caaac05d2e",
    "sagaAddress": "0x84458a0E963F4Bf1FF81f242Df3bF2FB16e1D0F3"
   },
   "createdAt": 1707753419,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:9a7979bc52cd04383c6232fba1956d6a"
  },
  {
   "itemId": "8aa09c4e-281f-5a57-9a9a-cc41cd0dfe72",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
   "ownersBlockchainId": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64",
   "ownerDetails": {
    "id": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3370"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "3e74a978-73db-4dfd-a879-063962c59e5d",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199277287763/inventory/#730_2_35757485510",
    "groupId": "76561199277287763",
    "withdrawable": true,
    "linkId": "dffd53dd-00c4-5728-be56-cacf7e8965de",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c6bcf0b2c803caaa184b99",
    "emissionSerial": "65c6bcf0b2c803caaa184b99",
    "sagaAddress": "0x33a7d3375809085CBE6Aa88d0f8B1f00474C3111"
   },
   "createdAt": 1707944970,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "14a3f5e8-88ba-5d7f-a5af-4fcd8f19c243",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
   "ownersBlockchainId": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64",
   "ownerDetails": {
    "id": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3370"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "5884d410-8cc5-424a-b234-fbe68fd34e5c",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199277287763/inventory/#730_2_35757485520",
    "groupId": "76561199277287763",
    "withdrawable": true,
    "linkId": "cac2c602-7db8-5cac-972b-acdcc67a5bbd",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c6bcf0b2c803caaa184ded",
    "emissionSerial": "65c6bcf0b2c803caaa184ded",
    "sagaAddress": "0x33a7d3375809085CBE6Aa88d0f8B1f00474C3111"
   },
   "createdAt": 1707944970,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "9ba70c4e-19ea-5fab-9317-24fc6d05b79e",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
   "ownersBlockchainId": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64",
   "ownerDetails": {
    "id": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3370"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "6b5e1109-896f-4a3e-81fc-dcdeb90d65e6",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199277287763/inventory/#730_2_35757485477",
    "groupId": "76561199277287763",
    "withdrawable": true,
    "linkId": "9059586d-c82b-59b5-8ac2-1e34ebea1542",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c6bcefb2c803caaa18479c",
    "emissionSerial": "65c6bcefb2c803caaa18479c",
    "sagaAddress": "0x33a7d3375809085CBE6Aa88d0f8B1f00474C3111"
   },
   "createdAt": 1707944970,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "5ee14348-d534-5029-bcf7-3294573a9b7b",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
   "ownersBlockchainId": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64",
   "ownerDetails": {
    "id": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3370"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "88f21680-0832-41e4-b842-0915feb9acc7",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199502441703/inventory/#730_2_35788529567",
    "groupId": "76561199502441703",
    "linkId": "bb6905d5-450b-5f28-9f29-8ed2f0207b70",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 1,
    "tradeLockDuration": 102899,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c8e39ab2c803caaa8f092a",
    "emissionSerial": "65c8e39ab2c803caaa8f092a",
    "sagaAddress": "0x33a7d3375809085CBE6Aa88d0f8B1f00474C3111"
   },
   "createdAt": 1707944970,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "7fcccc53-d66c-54dd-974f-c61825faca41",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
   "ownersBlockchainId": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64",
   "ownerDetails": {
    "id": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3370"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "8d9d9525-6656-46bb-ba9b-92c10746bacb",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199277287763/inventory/#730_2_35757485495",
    "groupId": "76561199277287763",
    "withdrawable": true,
    "linkId": "8cb94916-ac3f-5088-bb5a-78c55d05b026",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c6bcefb2c803caaa1849ac",
    "emissionSerial": "65c6bcefb2c803caaa1849ac",
    "sagaAddress": "0x33a7d3375809085CBE6Aa88d0f8B1f00474C3111"
   },
   "createdAt": 1707944970,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "efd7dccc-a18b-586b-89b9-14709cd43075",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
   "ownersBlockchainId": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64",
   "ownerDetails": {
    "id": "a88883f2-c3ad-4992-a5be-588ee95ec3db",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "4966f55d8fb308f316f9ccadc0b8ea072f6d6d830b2818b535906e4da1a2ac64"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3370"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "d7ea49a9-6182-4943-94c4-c10392c2945f",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199277287763/inventory/#730_2_35757485461",
    "groupId": "76561199277287763",
    "withdrawable": true,
    "linkId": "9755fb31-a6ff-5e47-b2a1-461768eeb0fb",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c6bccdb2c803caaa16aae0",
    "emissionSerial": "65c6bccdb2c803caaa16aae0",
    "sagaAddress": "0x33a7d3375809085CBE6Aa88d0f8B1f00474C3111"
   },
   "createdAt": 1707944970,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "e292a1b3-4e24-539d-85a7-21a9cc4d26ad",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
   "ownersBlockchainId": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f",
   "ownerDetails": {
    "id": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3374"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "a351bb62-ebe4-4e41-99eb-1ccd72e343bd",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199266888448/inventory/#730_2_35835296367",
    "groupId": "76561199266888448",
    "linkId": "6bff58d8-a861-548b-92fd-4c231ed4e250",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 4,
    "tradeLockDuration": 361916,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cc9464b2c803caaaf26069",
    "emissionSerial": "65cc9464b2c803caaaf26069",
    "sagaAddress": "0x7BCFDc1556708462d38aB87d6855211b8B206B69"
   },
   "createdAt": 1707906341,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "3ad4ddd4-a9af-51aa-9d86-6ed99924236b",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
   "ownersBlockchainId": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f",
   "ownerDetails": {
    "id": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3374"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "e724844b-0fe0-4288-9c79-3fa87d82d0b1",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199266888448/inventory/#730_2_35835296520",
    "groupId": "76561199266888448",
    "linkId": "727f85ec-cbf8-55cd-997c-742c441e71f7",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 4,
    "tradeLockDuration": 361363,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cc94abb2c803caaaf33fa3",
    "emissionSerial": "65cc94abb2c803caaaf33fa3",
    "sagaAddress": "0x7BCFDc1556708462d38aB87d6855211b8B206B69"
   },
   "createdAt": 1707906338,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "43206c4d-712a-5f07-b9d1-f2b1090932fd",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
   "ownersBlockchainId": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f",
   "ownerDetails": {
    "id": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3374"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "3c5ba7ff-59d0-4c22-80ee-4ab83913f86a",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199266888448/inventory/#730_2_35835296414",
    "groupId": "76561199266888448",
    "linkId": "2054439e-6434-5082-a539-dd414b55b0c0",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 4,
    "tradeLockDuration": 362605,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cc9487b2c803caaaf2ade7",
    "emissionSerial": "65cc9487b2c803caaaf2ade7",
    "sagaAddress": "0x7BCFDc1556708462d38aB87d6855211b8B206B69"
   },
   "createdAt": 1707906333,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "03f6dd71-1175-5200-b673-6ece3fa21f38",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "9501fa6e-377b-4603-adf3-295be6a9bc6e",
   "ownersBlockchainId": "41fb3d06c30a4ac59d92a5ad1b7ff37a357e6a003ba0442eae8f2d47be26c077",
   "ownerDetails": {
    "id": "9501fa6e-377b-4603-adf3-295be6a9bc6e",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "41fb3d06c30a4ac59d92a5ad1b7ff37a357e6a003ba0442eae8f2d47be26c077"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3379"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "645e6ace-72eb-41b5-919d-0b9baee8683b",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199518057454/inventory/#730_2_35806816690",
    "groupId": "76561199518057454",
    "linkId": "03026a60-09a6-556f-8774-a039b778d961",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 2,
    "tradeLockDuration": 189548,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ca5a61b2c803caaa1b7fea",
    "emissionSerial": "65ca5a61b2c803caaa1b7fea",
    "sagaAddress": "0x168F07af3a1F54F4026ea6eaAa69a1b641619298"
   },
   "createdAt": 1707762448,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "a775d9dc-7a41-5e73-acb2-0a69bb52ae19",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "1bea3159-e2c4-40ca-bf6a-52a8a7a4ec38",
   "ownersBlockchainId": "e114223163119fc9e719b96eddfb7c9e281603b1203690f35d960f205f3b1e91",
   "ownerDetails": {
    "id": "1bea3159-e2c4-40ca-bf6a-52a8a7a4ec38",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "e114223163119fc9e719b96eddfb7c9e281603b1203690f35d960f205f3b1e91"
   },
   "status": "active",
   "discount": 22,
   "price": {
    "DMC": "",
    "USD": "3380"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "0a73fb9a-51ef-4e24-afb7-87b009e2dc7e",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199255360196/inventory/#730_2_35803614045",
    "groupId": "76561199255360196",
    "linkId": "921442f1-7f85-5897-8700-2cc90e0b6ec5",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 2,
    "tradeLockDuration": 190129,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65ca259db2c803caaa66d753",
    "emissionSerial": "65ca259db2c803caaa66d753",
    "sagaAddress": "0x6Da242721811262B03607D636d702A477178b44c"
   },
   "createdAt": 1707746873,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "1b0cd1a7-b410-5c68-b38e-527ae975f351",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
   "ownersBlockchainId": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c",
   "ownerDetails": {
    "id": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3420"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "1d6c1c9b-ac5d-4ac6-afe0-dba797423d48",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199255532832/inventory/#730_2_35671109070",
    "groupId": "76561199255532832",
    "withdrawable": true,
    "linkId": "b8c65318-0922-59b1-bb93-57fcc690a134",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c25176b2c803caaa0abb4c",
    "emissionSerial": "65c25176b2c803caaa0abb4c",
    "sagaAddress": "0x85aE5529f13812fc2e6FBd734A3E853383E46FBb"
   },
   "createdAt": 1708212468,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "bef89ead-6b83-5034-bea4-5060a31b4d64",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
   "ownersBlockchainId": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c",
   "ownerDetails": {
    "id": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3420"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "31799ede-e406-4318-b997-88f52c6a200f",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199534302627/inventory/#730_2_35757900541",
    "groupId": "76561199534302627",
    "withdrawable": true,
    "linkId": "9eca4ce9-e917-5c65-b03c-e2dc44aac0ed",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c6c548b2c803caaa8804dc",
    "emissionSerial": "65c6c548b2c803caaa8804dc",
    "sagaAddress": "0x85aE5529f13812fc2e6FBd734A3E853383E46FBb"
   },
   "createdAt": 1708212468,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "90dd0b85-61b0-5b7e-9778-672b03e8162d",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:5704295478",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
   "ownersBlockchainId": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c",
   "ownerDetails": {
    "id": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3420"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "54543d75-2ecd-47bc-849f-e8b68d5a3e3e",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199259879216/inventory/#730_2_35742686797",
    "groupId": "76561199259879216",
    "withdrawable": true,
    "linkId": "3a2702e6-1390-5b14-835a-7c9a0ee17fee",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c5efffb2c803caaa3f8301",
    "emissionSerial": "65c5efffb2c803caaa3f8301",
    "sagaAddress": "0x85aE5529f13812fc2e6FBd734A3E853383E46FBb"
   },
   "createdAt": 1708212468,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "eb09d2b8-da19-5872-be21-06c8bab322ff",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
   "ownersBlockchainId": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c",
   "ownerDetails": {
    "id": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3420"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "61997cd0-607c-4b47-ae2a-17b828af43a5",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199496837598/inventory/#730_2_35763138500",
    "groupId": "76561199496837598",
    "linkId": "3201d37a-6de9-563f-b6c2-56ff7f46b1da",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 16765,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c72e7bb2c803caaaa707db",
    "emissionSerial": "65c72e7bb2c803caaaa707db",
    "sagaAddress": "0x85aE5529f13812fc2e6FBd734A3E853383E46FBb"
   },
   "createdAt": 1708212468,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "81c91c81-ad34-5287-a272-02ea9624ea65",
   "type": "offer",
   "amount": 1,
   "classId": "0:5704295478",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
   "ownersBlockchainId": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c",
   "ownerDetails": {
    "id": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3420"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "88efbd7f-dbb1-44a4-9865-6c81b82a2c1e",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199259879216/inventory/#730_2_35742686790",
    "groupId": "76561199259879216",
    "withdrawable": true,
    "linkId": "fd48516a-8fdc-5cd9-861f-d1ce4c2d0cf2",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c5effeb2c803caaa3f7f33",
    "emissionSerial": "65c5effeb2c803caaa3f7f33",
    "sagaAddress": "0x85aE5529f13812fc2e6FBd734A3E853383E46FBb"
   },
   "createdAt": 1708212468,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "b633815f-db14-5ca2-b8e6-4a546b5e1920",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
   "ownersBlockchainId": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c",
   "ownerDetails": {
    "id": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3420"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "c953e380-d8c9-44d0-9d29-35c2ae12fe76",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199309224384/inventory/#730_2_35741624928",
    "groupId": "76561199309224384",
    "withdrawable": true,
    "linkId": "24df1e1e-d302-5854-99e2-36b7a8176784",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c5dd4db2c803caaaf5c7f9",
    "emissionSerial": "65c5dd4db2c803caaaf5c7f9",
    "sagaAddress": "0x85aE5529f13812fc2e6FBd734A3E853383E46FBb"
   },
   "createdAt": 1708212468,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "b69fb899-650a-5792-b0a1-20c8d6507864",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
   "ownersBlockchainId": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c",
   "ownerDetails": {
    "id": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3420"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "e505a82d-016b-44ff-98bb-538d7b61b559",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199262150225/inventory/#730_2_35737318309",
    "groupId": "76561199262150225",
    "withdrawable": true,
    "linkId": "45a09229-f70f-508a-89fb-0d2870428806",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c586a1b2c803caaa3e3e30",
    "emissionSerial": "65c586a1b2c803caaa3e3e30",
    "sagaAddress": "0x85aE5529f13812fc2e6FBd734A3E853383E46FBb"
   },
   "createdAt": 1708212468,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "c5431dab-3cb7-5b65-9282-d033b914f62d",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
   "ownersBlockchainId": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c",
   "ownerDetails": {
    "id": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3420"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "ece8071f-2d16-499e-8cfd-ae6ad97290cc",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199255532832/inventory/#730_2_35671109118",
    "groupId": "76561199255532832",
    "withdrawable": true,
    "linkId": "e250a6fe-3c0d-56d7-aa9b-4587a2ac2cdb",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c251dab2c803caaa0bdd42",
    "emissionSerial": "65c251dab2c803caaa0bdd42",
    "sagaAddress": "0x85aE5529f13812fc2e6FBd734A3E853383E46FBb"
   },
   "createdAt": 1708212468,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "9bc21ff6-a760-51d8-829c-54087ae82af4",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
   "ownersBlockchainId": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c",
   "ownerDetails": {
    "id": "791e749c-e6de-4cd6-9bd0-aa7ab61054f5",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "ac2b27a7d0da4cd0b46dd4a08ff176226c3cf4c58f2f4698a0c4d0755567555c"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3420"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "f3ed6c96-6acc-40d0-a3f9-61ced07fb722",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199500457983/inventory/#730_2_35677939860",
    "groupId": "76561199500457983",
    "withdrawable": true,
    "linkId": "5af97232-391d-54f4-9ba7-4e6127cbc109",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c2f4eab2c803caaa3a9c42",
    "emissionSerial": "65c2f4eab2c803caaa3a9c42",
    "sagaAddress": "0x85aE5529f13812fc2e6FBd734A3E853383E46FBb"
   },
   "createdAt": 1708212468,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "93a94000-d724-5fd4-8d6d-509b772e608e",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5ff94f7a-535a-4713-a9e4-6d32fb880c49",
   "ownersBlockchainId": "c211988c3d2127bc8168d82620d2c221e774041e3a03e7df4902277d0d8190fa",
   "ownerDetails": {
    "id": "5ff94f7a-535a-4713-a9e4-6d32fb880c49",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "c211988c3d2127bc8168d82620d2c221e774041e3a03e7df4902277d0d8190fa"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3427"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "1ae7a7fc-8fa3-42ae-b7ac-cec00847a59d",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199261667880/inventory/#730_2_35506803308",
    "groupId": "76561199261667880",
    "withdrawable": true,
    "linkId": "0252f61c-3b41-5677-879d-c2ca8740c3e8",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65b1b76f8ad6eb102e36353b",
    "emissionSerial": "65b1b76f8ad6eb102e36353b",
    "sagaAddress": "0x653e48Df395e2067DB06de1c7795D76E6AeBf13C"
   },
   "createdAt": 1708191621,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "029bbf69-155b-5548-815b-1e9054fc9216",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "5ff94f7a-535a-4713-a9e4-6d32fb880c49",
   "ownersBlockchainId": "c211988c3d2127bc8168d82620d2c221e774041e3a03e7df4902277d0d8190fa",
   "ownerDetails": {
    "id": "5ff94f7a-535a-4713-a9e4-6d32fb880c49",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "c211988c3d2127bc8168d82620d2c221e774041e3a03e7df4902277d0d8190fa"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3427"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "ab1cd231-bd2a-48fe-bb63-5d2a7f671763",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199503026018/inventory/#730_2_35539506465",
    "groupId": "76561199503026018",
    "withdrawable": true,
    "linkId": "3d17418d-bd29-5853-ad11-b7d61db399fb",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65b4bab68ad6eb102eeb2625",
    "emissionSerial": "65b4bab68ad6eb102eeb2625",
    "sagaAddress": "0x653e48Df395e2067DB06de1c7795D76E6AeBf13C"
   },
   "createdAt": 1708191621,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "71eae0e6-800b-59f6-8a8d-dd85054470fe",
   "type": "offer",
   "amount": 1,
   "classId": "0:5689204898",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a02c19f8-fb96-499e-bd08-3d30b82efea0",
   "ownersBlockchainId": "aab0cff928474167947a7540daf0e39377f20e788bd84b5dafa4db1901a45a02",
   "ownerDetails": {
    "id": "a02c19f8-fb96-499e-bd08-3d30b82efea0",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "aab0cff928474167947a7540daf0e39377f20e788bd84b5dafa4db1901a45a02"
   },
   "status": "active",
   "discount": 21,
   "price": {
    "DMC": "",
    "USD": "3430"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "2db895b7-186d-44ac-ad58-0da8026ab79c",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199540809824/inventory/#730_2_35513766493",
    "groupId": "76561199540809824",
    "withdrawable": true,
    "linkId": "e1ce1ff3-03c4-5f1b-9996-09c6496741fb",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65b260298ad6eb102e46d75a",
    "emissionSerial": "65b260298ad6eb102e46d75a",
    "sagaAddress": "0x7fb57B152A73e0a5401F29618D4cA670E882c5bb"
   },
   "createdAt": 1708155486,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "f39b8d10-52c9-5ea3-a0d3-4143a0204e77",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "712fce42-1ff1-4daf-aee7-6fb0f64822fc",
   "ownersBlockchainId": "70cf0458b810084454c018efdab78250ebaca519362c357b01877edff70e6044",
   "ownerDetails": {
    "id": "712fce42-1ff1-4daf-aee7-6fb0f64822fc",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "70cf0458b810084454c018efdab78250ebaca519362c357b01877edff70e6044"
   },
   "status": "active",
   "discount": 20,
   "price": {
    "DMC": "",
    "USD": "3460"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "090ea5dc-bee5-4b5d-838e-0eb23b302090",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199302006303/inventory/#730_2_35810440256",
    "groupId": "76561199302006303",
    "linkId": "40c708eb-2b84-56b3-b45e-40ae974cdc88",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 2,
    "tradeLockDuration": 190139,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65caaf8db2c803caaab5b572",
    "emissionSerial": "65caaf8db2c803caaab5b572",
    "sagaAddress": "0xe9Ee4Db0E4683A386d24895571C3fFA472A677f8"
   },
   "createdAt": 1707782067,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "39133808-0bc6-5c5c-b999-e59c002d8693",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
   "ownersBlockchainId": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f",
   "ownerDetails": {
    "id": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f"
   },
   "status": "active",
   "discount": 20,
   "price": {
    "DMC": "",
    "USD": "3469"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "de4c0ada-e041-4d32-a1af-948743c7b917",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199496163763/inventory/#730_2_35782878667",
    "groupId": "76561199496163763",
    "linkId": "d8ffe637-7bc5-5db4-af5f-d31e99f71e08",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 1,
    "tradeLockDuration": 102228,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c88f56b2c803caaae1aab0",
    "emissionSerial": "65c88f56b2c803caaae1aab0",
    "sagaAddress": "0x7BCFDc1556708462d38aB87d6855211b8B206B69"
   },
   "createdAt": 1707642731,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "bec099b0-3074-5e02-b4e6-dbc0fc0f99fb",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
   "ownersBlockchainId": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f",
   "ownerDetails": {
    "id": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f"
   },
   "status": "active",
   "discount": 20,
   "price": {
    "DMC": "",
    "USD": "3469"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "1fa3a306-033e-4601-aaf9-01b23522969e",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199492865051/inventory/#730_2_35782740713",
    "groupId": "76561199492865051",
    "linkId": "0f06c2d9-06d8-5931-acf9-8f3d39b4ac86",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 1,
    "tradeLockDuration": 103584,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c88ce7b2c803caaad6e689",
    "emissionSerial": "65c88ce7b2c803caaad6e689",
    "sagaAddress": "0x7BCFDc1556708462d38aB87d6855211b8B206B69"
   },
   "createdAt": 1707642112,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "640d5f06-95c6-5119-a09d-1e62f0f8c466",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
   "ownersBlockchainId": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f",
   "ownerDetails": {
    "id": "e238170e-d9e4-47ec-9456-06ff4ea66d6b",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "bb93d264bb3a43cd8444f8129266aecb0a8a86db6cbe4e419fc0796fbd73944f"
   },
   "status": "active",
   "discount": 20,
   "price": {
    "DMC": "",
    "USD": "3469"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "f9e0fddf-79f0-4e68-88cd-6313b9261409",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199492865051/inventory/#730_2_35782740626",
    "groupId": "76561199492865051",
    "linkId": "111c16bd-5695-5752-bba8-feefa85753bd",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 1,
    "tradeLockDuration": 102013,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c88ca1b2c803caaad5444e",
    "emissionSerial": "65c88ca1b2c803caaad5444e",
    "sagaAddress": "0x7BCFDc1556708462d38aB87d6855211b8B206B69"
   },
   "createdAt": 1707642112,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "bdd984b1-52fc-50c5-9b15-62ba118c5211",
   "type": "offer",
   "amount": 1,
   "classId": "143865972:5700554319",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "ESL One Cologne 2014 Legends",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsQEl9Jg9SpIW1KgRr7PDHfTJF4tnkxNHfqKelfemGxj8Fv5Ai07mY9t6migex_kQ-NW2gLYTBclI2N1nRqFDtx-ju1pSi_MOeXQ8hmeg",
   "slug": "esl-one-cologne-2014-legends",
   "owner": "a3c4e9e5-fe60-4d83-be21-c8f86797a0c2",
   "ownersBlockchainId": "dd949c7ab37650385891cf7be0b14b634e02d61b874d78238b5902e4f97fee8c",
   "ownerDetails": {
    "id": "a3c4e9e5-fe60-4d83-be21-c8f86797a0c2",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "dd949c7ab37650385891cf7be0b14b634e02d61b874d78238b5902e4f97fee8c"
   },
   "status": "active",
   "discount": 9,
   "price": {
    "DMC": "",
    "USD": "8500"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "9363"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "86ed4fcb-ee51-4609-8350-ea272f6b1ce3",
    "isNew": false,
    "gameId": "a8db",
    "name": "ESL One Cologne 2014 Legends",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199495525276/inventory/#730_2_35666923986",
    "groupId": "76561199495525276",
    "withdrawable": true,
    "linkId": "88caec8e-6025-53f8-a4f0-e5763394b737",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     ""
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c1da77b2c803caaa1fed4f",
    "emissionSerial": "65c1da77b2c803caaa1fed4f",
    "sagaAddress": "0xc175e0781579C01b884c0535691F2FD931041829"
   },
   "createdAt": 1707432271,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:0511e696b38e794edc8f17105eb36766"
  },
  {
   "itemId": "3d493dc7-f6b5-56e6-86c6-bd7062747e8b",
   "type": "offer",
   "amount": 1,
   "classId": "143865972:5700554319",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "ESL One Cologne 2014 Legends",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsQEl9Jg9SpIW1KgRr7PDHfTJF4tnkxNHfqKelfemGxj8Fv5Ai07mY9t6migex_kQ-NW2gLYTBclI2N1nRqFDtx-ju1pSi_MOeXQ8hmeg",
   "slug": "esl-one-cologne-2014-legends",
   "owner": "a3c4e9e5-fe60-4d83-be21-c8f86797a0c2",
   "ownersBlockchainId": "dd949c7ab37650385891cf7be0b14b634e02d61b874d78238b5902e4f97fee8c",
   "ownerDetails": {
    "id": "a3c4e9e5-fe60-4d83-be21-c8f86797a0c2",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "dd949c7ab37650385891cf7be0b14b634e02d61b874d78238b5902e4f97fee8c"
   },
   "status": "active",
   "discount": 9,
   "price": {
    "DMC": "",
    "USD": "8500"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "9363"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "0273091b-1fd1-405d-8c0b-2b29f168d535",
    "isNew": false,
    "gameId": "a8db",
    "name": "ESL One Cologne 2014 Legends",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199495525276/inventory/#730_2_35666923983",
    "groupId": "76561199495525276",
    "withdrawable": true,
    "linkId": "0cfcf69c-9e1f-5aaa-b5a1-6dff0d7d1a3b",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     ""
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c1da77b2c803caaa1fec52",
    "emissionSerial": "65c1da77b2c803caaa1fec52",
    "sagaAddress": "0xc175e0781579C01b884c0535691F2FD931041829"
   },
   "createdAt": 1707432256,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:0511e696b38e794edc8f17105eb36766"
  },
  {
   "itemId": "02dbe948-af0e-5651-83b3-a4e0c6484ee1",
   "type": "offer",
   "amount": 1,
   "classId": "143865972:549054327",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "ESL One Cologne 2014 Legends",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsQEl9Jg9SpIW1KgRr7PDHfTJF4tnkxNHfqKelfemGxj8Fv5Ai07mY9t6migex_kQ-NW2gLYTBclI2N1nRqFDtx-ju1pSi_MOeXQ8hmeg",
   "slug": "esl-one-cologne-2014-legends",
   "owner": "a3c4e9e5-fe60-4d83-be21-c8f86797a0c2",
   "ownersBlockchainId": "dd949c7ab37650385891cf7be0b14b634e02d61b874d78238b5902e4f97fee8c",
   "ownerDetails": {
    "id": "a3c4e9e5-fe60-4d83-be21-c8f86797a0c2",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "dd949c7ab37650385891cf7be0b14b634e02d61b874d78238b5902e4f97fee8c"
   },
   "status": "active",
   "discount": 9,
   "price": {
    "DMC": "",
    "USD": "8500"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "9363"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "ec1b8de2-baaf-4653-ae7a-59bcd7f9cc4a",
    "isNew": false,
    "gameId": "a8db",
    "name": "ESL One Cologne 2014 Legends",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199262253592/inventory/#730_2_35709978154",
    "groupId": "76561199262253592",
    "withdrawable": true,
    "linkId": "90b2bcf6-d336-5ec8-a18c-e1a033be426c",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     ""
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c3fa98b2c803caaa37037e",
    "emissionSerial": "65c3fa98b2c803caaa37037e",
    "sagaAddress": "0xc175e0781579C01b884c0535691F2FD931041829"
   },
   "createdAt": 1707342494,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:0511e696b38e794edc8f17105eb36766"
  },
  {
   "itemId": "593c4974-90c0-55dd-a592-f836dadfd70b",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
   "ownersBlockchainId": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe",
   "ownerDetails": {
    "id": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe"
   },
   "status": "active",
   "discount": 19,
   "price": {
    "DMC": "",
    "USD": "3500"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "a3ce8f65-7225-4f5b-b9d7-96241efe758e",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199506574146/inventory/#730_2_35792767359",
    "groupId": "76561199506574146",
    "linkId": "2077a7d7-80eb-5a64-981b-744bd7025741",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 1,
    "tradeLockDuration": 102712,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c92677b2c803caaace8a9d",
    "emissionSerial": "65c92677b2c803caaace8a9d",
    "sagaAddress": "0x2456BbAdEFD1AdBDf636D401F8Ebb97c8310aE45"
   },
   "createdAt": 1707681456,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "1b38be2b-1de0-57a5-be23-b04875577152",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
   "ownersBlockchainId": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe",
   "ownerDetails": {
    "id": "d4fae8d4-ad23-41b6-8e2d-879dfb9ba74e",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "e97b6a26213fc5193ab0ff318b4c95b66d7f5547528edb3ebd6d9fc52163fffe"
   },
   "status": "active",
   "discount": 19,
   "price": {
    "DMC": "",
    "USD": "3500"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "e081042d-0a54-4e9d-be43-47480d338e6f",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199506574146/inventory/#730_2_35792767349",
    "groupId": "76561199506574146",
    "linkId": "635f22d8-4235-5996-92d1-fb984f1a037a",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 1,
    "tradeLockDuration": 102213,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c92677b2c803caaace89f8",
    "emissionSerial": "65c92677b2c803caaace89f8",
    "sagaAddress": "0x2456BbAdEFD1AdBDf636D401F8Ebb97c8310aE45"
   },
   "createdAt": 1707681456,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "370fd26e-ec7d-5ea2-a469-d7060f5b2a84",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:5706307259",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "7520367c-a32f-4351-a325-385641386707",
   "ownersBlockchainId": "5a0e488f5074b6cae4b64f0f499cf623efd6d257e223d679986b8f1aa1ce9961",
   "ownerDetails": {
    "id": "7520367c-a32f-4351-a325-385641386707",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "5a0e488f5074b6cae4b64f0f499cf623efd6d257e223d679986b8f1aa1ce9961"
   },
   "status": "active",
   "discount": 19,
   "price": {
    "DMC": "",
    "USD": "3500"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "24929f71-7a71-431d-905f-9bfcf0e28c53",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199493017150/inventory/#730_2_35788231231",
    "groupId": "76561199493017150",
    "linkId": "c2d885cd-9c9a-536b-a593-eaa09f67a9a4",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 1,
    "tradeLockDuration": 87971,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c8df7eb2c803caaa80a7c6",
    "emissionSerial": "65c8df7eb2c803caaa80a7c6",
    "sagaAddress": "0xb45701FC6F542379866cD0251380047B523EE9eB"
   },
   "createdAt": 1707663263,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "4eaade46-3ad3-53f8-bc42-e39d4d7ebdb9",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "bebb4836-ea13-4e05-820c-56735ad0cdcb",
   "ownersBlockchainId": "e6f1480551fc43eb8bd0280a0bbebef159e44398ad4941ed9462ae18671c3ab4",
   "ownerDetails": {
    "id": "bebb4836-ea13-4e05-820c-56735ad0cdcb",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "e6f1480551fc43eb8bd0280a0bbebef159e44398ad4941ed9462ae18671c3ab4"
   },
   "status": "active",
   "discount": 19,
   "price": {
    "DMC": "",
    "USD": "3500"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "973c930d-9ccb-439c-ab2d-5355787b2ad2",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199479907000/inventory/#730_2_35787158228",
    "groupId": "76561199479907000",
    "linkId": "1decf80e-5ab5-592e-ba31-0bcd58e5690d",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 83781,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c8d10ab2c803caaa4da198",
    "emissionSerial": "65c8d10ab2c803caaa4da198",
    "sagaAddress": "0xde484006C804C0a804203Cd5F7932e122B278261"
   },
   "createdAt": 1707659650,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "bcc20658-02f3-56e2-bdb5-b8aa6d67d389",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "bebb4836-ea13-4e05-820c-56735ad0cdcb",
   "ownersBlockchainId": "e6f1480551fc43eb8bd0280a0bbebef159e44398ad4941ed9462ae18671c3ab4",
   "ownerDetails": {
    "id": "bebb4836-ea13-4e05-820c-56735ad0cdcb",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "e6f1480551fc43eb8bd0280a0bbebef159e44398ad4941ed9462ae18671c3ab4"
   },
   "status": "active",
   "discount": 19,
   "price": {
    "DMC": "",
    "USD": "3500"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "742488ac-97ca-489f-840c-c24eff4b306a",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199479907000/inventory/#730_2_35787158249",
    "groupId": "76561199479907000",
    "linkId": "d28dd323-4229-5e03-a91a-26dbe2bbb018",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 83781,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c8d12eb2c803caaa4e5103",
    "emissionSerial": "65c8d12eb2c803caaa4e5103",
    "sagaAddress": "0xde484006C804C0a804203Cd5F7932e122B278261"
   },
   "createdAt": 1707659649,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "2ef761d7-f5fe-5c38-9185-6f022fb046c0",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "1e4e1048-a721-47f4-833c-0684cbd17874",
   "ownersBlockchainId": "6622557b6f8b7783157360e6031a5eb41626170cfb9554ac8fed680737966214",
   "ownerDetails": {
    "id": "1e4e1048-a721-47f4-833c-0684cbd17874",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "6622557b6f8b7783157360e6031a5eb41626170cfb9554ac8fed680737966214"
   },
   "status": "active",
   "discount": 19,
   "price": {
    "DMC": "",
    "USD": "3500"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "b7c139e5-c036-489c-aa45-0ee20f5f88e4",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199259477239/inventory/#730_2_35782050296",
    "groupId": "76561199259477239",
    "linkId": "8f61933a-19b7-56a0-86b2-fe683c80ba12",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 1,
    "tradeLockDuration": 102538,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c87f7cb2c803caaa9e5f27",
    "emissionSerial": "65c87f7cb2c803caaa9e5f27",
    "sagaAddress": "0xDc658B9144AA95cb4FFF246985E120c677309555"
   },
   "createdAt": 1707638757,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "27f0438f-c275-545f-8a2d-39050a83ca78",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "e5284a5c-b3a7-4252-84d6-36576becdc15",
   "ownersBlockchainId": "72812b6f1207446983e620a9afef45a7b773a4ce9b94488eb68ce36e0c37492c",
   "ownerDetails": {
    "id": "e5284a5c-b3a7-4252-84d6-36576becdc15",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "72812b6f1207446983e620a9afef45a7b773a4ce9b94488eb68ce36e0c37492c"
   },
   "status": "active",
   "discount": 18,
   "price": {
    "DMC": "",
    "USD": "3529"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "adb5c7a4-63d2-4732-b50b-82f19ab9a19a",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199303529699/inventory/#730_2_35749967778",
    "groupId": "76561199303529699",
    "withdrawable": true,
    "linkId": "fc078aba-168a-5122-93d1-ee15d86f2f50",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c6500ab2c803caaa077182",
    "emissionSerial": "65c6500ab2c803caaa077182",
    "sagaAddress": "0x2A839780074A38610eF89A8fd9D1b82e5cAd3a33"
   },
   "createdAt": 1708055488,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "579b0cba-040f-5f16-bd8a-2595c5144ca4",
   "type": "offer",
   "amount": 1,
   "classId": "0:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "e5284a5c-b3a7-4252-84d6-36576becdc15",
   "ownersBlockchainId": "72812b6f1207446983e620a9afef45a7b773a4ce9b94488eb68ce36e0c37492c",
   "ownerDetails": {
    "id": "e5284a5c-b3a7-4252-84d6-36576becdc15",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "72812b6f1207446983e620a9afef45a7b773a4ce9b94488eb68ce36e0c37492c"
   },
   "status": "active",
   "discount": 18,
   "price": {
    "DMC": "",
    "USD": "3529"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "5d746cd6-22ed-4c73-83ce-bd5ea8edb27a",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199256468592/inventory/#730_2_35781826100",
    "groupId": "76561199256468592",
    "linkId": "b072edc8-a2b9-589a-94fc-c3d47e591cf0",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 16790,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c87b21b2c803caaa8f0747",
    "emissionSerial": "65c87b21b2c803caaa8f0747",
    "sagaAddress": "0x2A839780074A38610eF89A8fd9D1b82e5cAd3a33"
   },
   "createdAt": 1708055485,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "fa4cb884-4700-5c4f-9304-7eea4831587f",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "e5284a5c-b3a7-4252-84d6-36576becdc15",
   "ownersBlockchainId": "72812b6f1207446983e620a9afef45a7b773a4ce9b94488eb68ce36e0c37492c",
   "ownerDetails": {
    "id": "e5284a5c-b3a7-4252-84d6-36576becdc15",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "72812b6f1207446983e620a9afef45a7b773a4ce9b94488eb68ce36e0c37492c"
   },
   "status": "active",
   "discount": 18,
   "price": {
    "DMC": "",
    "USD": "3529"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "6a600839-eb87-4fd8-adcf-952a15856ea3",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199303597951/inventory/#730_2_35773625341",
    "groupId": "76561199303597951",
    "linkId": "72497ea9-9ac5-5487-bfdf-3ab513d5e756",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 7570,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65c7c5a8b2c803caaaf6599c",
    "emissionSerial": "65c7c5a8b2c803caaaf6599c",
    "sagaAddress": "0x2A839780074A38610eF89A8fd9D1b82e5cAd3a33"
   },
   "createdAt": 1708055484,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "7e4067cf-141f-59a8-9df6-d09dc6c888a6",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a02c19f8-fb96-499e-bd08-3d30b82efea0",
   "ownersBlockchainId": "aab0cff928474167947a7540daf0e39377f20e788bd84b5dafa4db1901a45a02",
   "ownerDetails": {
    "id": "a02c19f8-fb96-499e-bd08-3d30b82efea0",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "aab0cff928474167947a7540daf0e39377f20e788bd84b5dafa4db1901a45a02"
   },
   "status": "active",
   "discount": 18,
   "price": {
    "DMC": "",
    "USD": "3530"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "9b21b4cd-66b4-4c9c-a5a7-f2ec5866d255",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199502254993/inventory/#730_2_35545354492",
    "groupId": "76561199502254993",
    "withdrawable": true,
    "linkId": "e2dc7e9f-fb3d-5b63-afcd-13fd94ab7cc8",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65b538798ad6eb102e09698b",
    "emissionSerial": "65b538798ad6eb102e09698b",
    "sagaAddress": "0x7fb57B152A73e0a5401F29618D4cA670E882c5bb"
   },
   "createdAt": 1708055379,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "64646a9b-04f1-558b-80a6-5d886b2ef689",
   "type": "offer",
   "amount": 1,
   "classId": "302028390:384801284",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Operation Bravo Case",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsXE1xNwVDv7WrFA5pnabNJGwSuN3gxtnawKOlMO6HzzhQucAm0uvFo4n2iw3h_UM-ZmilJNeLMlhpjfjxEoE",
   "slug": "operation-bravo-case",
   "owner": "a02c19f8-fb96-499e-bd08-3d30b82efea0",
   "ownersBlockchainId": "aab0cff928474167947a7540daf0e39377f20e788bd84b5dafa4db1901a45a02",
   "ownerDetails": {
    "id": "a02c19f8-fb96-499e-bd08-3d30b82efea0",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "aab0cff928474167947a7540daf0e39377f20e788bd84b5dafa4db1901a45a02"
   },
   "status": "active",
   "discount": 18,
   "price": {
    "DMC": "",
    "USD": "3530"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "4350"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": true,
    "offerId": "cb19564f-0b49-4b06-ad7d-4023681d8876",
    "isNew": false,
    "gameId": "a8db",
    "name": "Operation Bravo Case",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199502254993/inventory/#730_2_35545354559",
    "groupId": "76561199502254993",
    "withdrawable": true,
    "linkId": "15056e6a-0b96-5170-9285-2d9cb906a868",
    "quality": "base grade",
    "category": "normal",
    "tradeLockDuration": 0,
    "itemType": "container",
    "collection": [
     "bravo"
    ],
    "saleRestricted": false,
    "inGameAssetID": "65b538bf8ad6eb102e0a6ef3",
    "emissionSerial": "65b538bf8ad6eb102e0a6ef3",
    "sagaAddress": "0x7fb57B152A73e0a5401F29618D4cA670E882c5bb"
   },
   "createdAt": 1708055379,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3eeb9bd42a9b9002060d7082c1c9052"
  },
  {
   "itemId": "9012482e-d850-5c08-9da1-366999d18a50",
   "type": "offer",
   "amount": 1,
   "classId": "143865972:2396554189",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Krakow 2017 Legends Autograph Capsule",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsQEl9Jg9SpIW1KgRr7PjacDZN-47mxde0kOX7JqvuxCVU7JUmjO_C89un0QbjrRU-NWn2doPGIAE8MlGG_gTrlbq705e775ud1zI97TuorcB0",
   "slug": "krakow-2017-legends-autograph-capsule",
   "owner": "64dc4031-75d9-48f5-9fa9-e3defef1ac17",
   "ownersBlockchainId": "d50d74f3b0da4b768e4e773591f819c626f60fbb2f6b4b60950eb4555f17c814",
   "ownerDetails": {
    "id": "64dc4031-75d9-48f5-9fa9-e3defef1ac17",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "d50d74f3b0da4b768e4e773591f819c626f60fbb2f6b4b60950eb4555f17c814"
   },
   "status": "active",
   "discount": 20,
   "price": {
    "DMC": "",
    "USD": "3123"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "3938"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "372a605e-c33b-4bf1-be1e-804622a76c2c",
    "isNew": true,
    "gameId": "a8db",
    "name": "Krakow 2017 Legends Autograph Capsule",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199259467346/inventory/#730_2_35858423847",
    "groupId": "76561199259467346",
    "linkId": "3f5e9f54-9f46-5dbd-b09e-2330aa8cd45f",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 4,
    "tradeLockDuration": 428716,
    "itemType": "container",
    "collection": [
     ""
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cdcd20b2c803caaa83dd1f",
    "emissionSerial": "65cdcd20b2c803caaa83dd1f",
    "sagaAddress": "0xA7bc1FC0d2D5fdf7Bfec591f0B4d53478A6967eF"
   },
   "createdAt": 1708245157,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3ccd0429d11f417cf6e65fa0cfdde82"
  },
  {
   "itemId": "0ef78dee-65a4-55f7-879b-63b8e47d90d8",
   "type": "offer",
   "amount": 1,
   "classId": "143865972:2396554189",
   "gameId": "a8db",
   "gameType": "steam",
   "inMarket": true,
   "lockStatus": false,
   "title": "Krakow 2017 Legends Autograph Capsule",
   "description": "",
   "image": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsQEl9Jg9SpIW1KgRr7PjacDZN-47mxde0kOX7JqvuxCVU7JUmjO_C89un0QbjrRU-NWn2doPGIAE8MlGG_gTrlbq705e775ud1zI97TuorcB0",
   "slug": "krakow-2017-legends-autograph-capsule",
   "owner": "8707bf54-a90b-4a68-a40a-8b55235d8f5d",
   "ownersBlockchainId": "1245a485b63d77a07f9d5af19d665f1d08ed5669c1f9929a7b99623f681d3610",
   "ownerDetails": {
    "id": "8707bf54-a90b-4a68-a40a-8b55235d8f5d",
    "avatar": "https://s3.amazonaws.com/dmarket-images-stage/3a043a13-6f4d-4d15-8257-be01a4bf4138.jpg",
    "wallet": "1245a485b63d77a07f9d5af19d665f1d08ed5669c1f9929a7b99623f681d3610"
   },
   "status": "active",
   "discount": 20,
   "price": {
    "DMC": "",
    "USD": "3124"
   },
   "instantPrice": {
    "DMC": "",
    "USD": ""
   },
   "exchangePrice": {
    "DMC": "",
    "USD": ""
   },
   "instantTargetId": "",
   "suggestedPrice": {
    "DMC": "",
    "USD": "3938"
   },
   "recommendedPrice": {
    "offerPrice": {
     "DMC": "",
     "USD": ""
    },
    "d3": {
     "DMC": "",
     "USD": ""
    },
    "d7": {
     "DMC": "",
     "USD": ""
    },
    "d7Plus": {
     "DMC": "",
     "USD": ""
    }
   },
   "extra": {
    "nameColor": "d2d2d2",
    "backgroundColor": "b0c3d9",
    "tradable": false,
    "offerId": "9c897d52-bb5b-436f-a8d5-f8bdd9eed31b",
    "isNew": false,
    "gameId": "a8db",
    "name": "Krakow 2017 Legends Autograph Capsule",
    "categoryPath": "misc/container",
    "viewAtSteam": "https://steamcommunity.com/profiles/76561199257988493/inventory/#730_2_35879653449",
    "groupId": "76561199257988493",
    "linkId": "ef52beba-79bd-5355-a119-6615b8504ef3",
    "quality": "base grade",
    "category": "normal",
    "tradeLock": 6,
    "tradeLockDuration": 534768,
    "itemType": "container",
    "collection": [
     ""
    ],
    "saleRestricted": false,
    "inGameAssetID": "65cf25bb7664a50f5e583854",
    "emissionSerial": "65cf25bb7664a50f5e583854",
    "sagaAddress": "0xEaD43E4D1c3c32f9cA600B7859cCAbf25FfdeF41"
   },
   "createdAt": 1708074506,
   "deliveryStats": {
    "rate": "",
    "time": ""
   },
   "fees": {
    "f2f": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    },
    "dmarket": {
     "sell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "instantSell": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     },
     "exchange": {
      "default": {
       "percentage": "",
       "minFee": {
        "DMC": "",
        "USD": ""
       }
      }
     }
    }
   },
   "discountPrice": {
    "DMC": "",
    "USD": ""
   },
   "productId": "a8db:e3ccd0429d11f417cf6e65fa0cfdde82"
  }
 ],
 "total": {
  "offers": 0,
  "targets": 0,
  "items": 10000,
  "completedOffers": 0,
  "closedTargets": 0
 },
 "cursor": "WzgxNCwxNzA4MDc0NTA2MDAwLCI5Yzg5N2Q1Mi1iYjViLTQzNmYtYThkNS1mOGJkZDllZWQzMWIiXQ=="
}
```

