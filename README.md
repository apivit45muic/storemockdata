# storemockdata

better version
```
{
  "discountCodes": [
    {
      "code": "SUMMER21",
      "description": "Summer Sale 2021",
      "validFrom": "2021-06-01T00:00:00Z",
      "validTo": "2021-09-01T23:59:59Z",
      "applicableTo": ["Cart"],
      "discountType": {
        "type": "FixedAmountCoupon",
        "details": {
          "amount": 50
        }
      }
    },
    {
      "code": "WELCOME10",
      "description": "10% off for new customers",
      "validFrom": "2021-01-01T00:00:00Z",
      "validTo": "2021-12-31T23:59:59Z",
      "applicableTo": ["Cart"],
      "discountType": {
        "type": "PercentageCoupon",
        "details": {
          "percentage": 10
        }
      }
    },
    {
      "code": "CLOTH15",
      "description": "15% off on clothing",
      "validFrom": "2021-02-01T00:00:00Z",
      "validTo": "2021-12-31T23:59:59Z",
      "applicableTo": ["Category"],
      "discountType": {
        "type": "CategoryPercentageDiscount",
        "details": {
          "categoryName": "Clothing",
          "percentage": 15
        }
      }
    },
    {
      "code": "POINTS2021",
      "description": "Redeem points for discounts",
      "validFrom": "2021-01-01T00:00:00Z",
      "validTo": "2021-12-31T23:59:59Z",
      "applicableTo": ["Cart"],
      "discountType": {
        "type": "PointsDiscount",
        "details": {
          "pointsToDiscountRatio": 1,
          "maxPercentageCap": 20
        }
      }
    },
    {
      "code": "WINTER40",
      "description": "Winter sale - get 40 THB off for every 300 THB spent",
      "validFrom": "2021-12-01T00:00:00Z",
      "validTo": "2022-02-28T23:59:59Z",
      "applicableTo": ["Cart"],
      "discountType": {
        "type": "SeasonalDiscount",
        "details": {
          "everyXTHB": 300,
          "discountYTHB": 40
        }
      }
    }
  ]
}
```
