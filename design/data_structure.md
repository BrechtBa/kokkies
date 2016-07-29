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
                        "quantity": 0
                    },
                    "prkey2": {
                        "quantity": 0
                    }
                }
            }
        },
        "periods": {
            "pdkey1": {
                "name": "",
                "startdate": 0
            },
            "pdkey2": {
                "name": "",
                "startdate": 0
            }
        },
        "days": {
            "pdkey1": {
                "dakey1": {
                    "date": 0,
                    "productgroups": {
                        "pgkey1": {
                            "quantity": 0,
                            "products": {
                                "prkey1": {
                                    "shoppinglist": "slkey1",
                                    "quantity": 0,
                                    "used": 0
                                }
                            }
                        },
                        "pgkey2": {
                            "quantity": 0,
                            "products": {
                                "prkey2": {
                                    "shoppinglist": "slkey2",
                                    "quantity": 0,
                                    "used": 0
                                }
                            }
                        }
                    }
                }
            },
            "pdkey2": {
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