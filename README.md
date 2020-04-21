# E-commerce-Converstion-Rate-Model

The analysis was conducted by estimating a linear logistic regression model based on a dataset on online shopper’s browsing behavior. 

```
mylogit <- glm(Revenue ~ Administrative + Administrative_Duration + Informational + Informational_Duration + ProductRelated + ProductRelated_Duration + BounceRates + PageValues + SpecialDay + Month + OperatingSystems + Browser + Region + TrafficType + VisitorType + Weekend, data = reg_data, family = binomial(link="logit"))
summary(mylogit)
```

## Main Findings
1. The number of product-related pages visited and page value positively affect the conversion rate. 
2. The bounce rate massively induces web abandonment. 
3. The conversion rate are highly subject to seasonality and sources of the traffic.
4. The returning customers contributed lower conversion rate than the first-time visitors. 

## Managerial Implications 
1. Raise visibility of product-relevant pages.
2. Decrease the bounce rate.
3. Bring traffic to the high page-value pages.
4. Utilize the seasonal shopping trend,
5. Advertising on sources of traffic
6. Improve customer loyalty. 
