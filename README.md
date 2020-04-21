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
Try Search Engine Optimization (SEOs) and product recommendation engines.
2. Decrease the bounce rate.
Try adding a navigation button, a clear Call-To-Action (CTA), and better visual design.
3. Bring traffic to the high page-value pages.
Try internal links within the website or external links such as social media or email.
4. Utilize the seasonal shopping trend.
Try sending promotional emails (with promo codes) and launching ads on certain traffic source to reach potential visitors
5. Advertising on sources of traffic.
In this specific case, Youtube and Twitter are good sources though companies should be cautious when allocating resources to paid-ads due to budget.
6. Improve customer loyalty. 
Customize, Personalize, Make them feel special!
