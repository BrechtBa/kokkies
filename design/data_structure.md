# Data structures


```
{
    "userhash": {
        "products": {
            "prkey1": {
                "name": "",
                "store": "",
                "price": 0,
                "unit": ""
            },
            "prkey2": {
                "name": "",
                "store": "",
                "price": 0,
                "unit": ""
            }
        },
        "productgroups": {
            "pgkey1": {
                "name": "",
                "products": {
                    "prkey1": {
                        "order": 0,
                        "quantity": 0
                    },
                    "prkey2": {
                        "order": 1,
                        "quantity": 0
                    }
                }
            }
        },
        "periods": {
            "pdkey1": {
                "name": "",
                "startdate": 0,
                "days": {
                    "dakey1": 1,
                    "dakey2": 2,
                }
            },
            "pdkey2": {
                "name": "",
                "startdate": 0,
                "days": {
                }
            }
        },
        "days": {
            "dakey1": {
                "date": 0,
                "productgroups": {
                    "pgkey1": 1,
                    "pgkey2": 2,
                }
            }
        },
        "daygroductgroups": {
            "dakey1":{
                "pgkey1": {
                    "quantity": 0,
                },
                "pgkey2": {
                    "quantity": 0,
                }
            }
        },
        "dayproductgroupproducts": {
            "dakey1":{
                "pgkey1": {
                    "prkey1": {
                        "shoppinglist": "slkey1",
                        "used": 0
                    }
                },
                "pgkey2": {
                    "prkey2": {
                        "shoppinglist": "slkey2",
                        "used": 0
                    }
                }
            }
        },
        "shoppinglists": {
            "pdkey1": {
                "slkey1": {
                    "name": "",
                    "date": 0,
                    "products": {
                        "prkey1": {
                            "quantity": 0
                        },
                        "prkey2": {
                            "quantity": 0
                        }
                    }
                }
            }
        }
        
    }
}
```


