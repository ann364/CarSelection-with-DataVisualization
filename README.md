# CarSelection with DataVisualization

##Objective:

The goal of the project was to help an employee purchase a car , based on his company and personal criteria. The company provided four different car models to choose from. The car choice had to be cost effective, maintenance efficient and needed to have best safety features. While the employee’s personal criteria were: to have best insurance coverage, cost effective fuel usage and best resale value.

## Data Retrieval and Cleaning:
Data on car price, safety scores and costs on maintenance, fuel usage, insurance coverage , resale/depreciation value were retrieved from different websites (kbb.com, cars.com, edmunds.com). The data was retrieved by web scraping using python. Some data had missing values. For example, price for some cars were missing. That was fixed by imputing the value with average price.
Scores and Weighted Scores:
The values were averaged for each car types. Then the minimum and maximum range for every measure were calculated. Based on favorability, I came up with scores between 1 through 5 for each of these measures where 5 was the most favorable score point.

The company had given weights (out of 10) for the company criterion measures. That meant some measures had high preference over the other. I came up with similar weights for the personal criteria measures. Based on these weights, I calculated new weighted scores for all different car types. 

## Plotting:
Once I had the weighted scores, it was easier to plot them into charts.  The charts were plotted against measure values vs car types or car types vs measure names. I came up with at least three types of charts: circle view, stacked bar view and regular bar charts. 
Different charts were created for company criteria vs car types. The charts were combined into one dashboard.  The step was repeated for personal criteria vs car types.

## CompanyCriteria_Combined_Dashboard.pdf: 
The stacked bar chart where safety measure scores displayed in the salmon pink color are almost of the same height for all the car types. If you look at the whole bars, Honda and Ford are of similar height. The grand total score is the same (85) for both Ford and Honda. In the circle and bar charts, individual measures like price, maintenance, and safety are easily viewed because they have their individual sections. From the charts we can see Ford wins on price score, i.e. Ford is more affordable to buy. But Honda wins on maintenance and safety.
However, we must see the overall picture and not just one or two factors. In this light, I would choose the Ford Escape or the Honda CRV for company criteria. Both of their total weighted scores (85) are higher than the other two cars. Ford leads in the price score, i.e. affordability rather than the other three cars but Honda leads in maintainability and safety. But since both have the same total weighted score, it is quite difficult to make only one choice.

## PersonalCriteria_Combined_Dashboard.pdf:
You can observe in the stacked bar chart that the bar for the Honda CRV is tallest among all. We can see that the total weighted score for Honda is about 97 which is the highest among all the cars. 
If you look at each of the color stacks, we can see that Honda has higher scores for insurance and fuel. That means it is more economical to have Honda in terms of the fuel usage and the insurance cost. The resale score for Honda is the same as Toyota (35) but higher than the other two. 
If you see the circle and bar views, in the same dashboard, we can see the same holds  true. Honda beats all cars if we take every measure into consideration -one at a time. 
Based on Criteria 2, the clear winner is the Honda CRV because its total weighted score is greater than other cars and it has higher individual scores for all personal measures.

## Dashboard_AllCombinedCriteria.pdf:
 We can see at a glance on the stacked chart that, Honda CRV’s bar is the tallest. If we look at the table view, we can observe that it has the highest grand total weighted score: 182. By no doubt, Honda CRV would be the first choice for the purchase if all factors are taken into consideration.

We can also see that the individual weighted scores for cars in side-by-side bars, stacked bars, and circle view charts. Except for safety and price, scores for other measures are high for Honda. 

In this light, Honda CRV would be my choice of purchase!

Data Sources

https://www.kbb.com/cars-for-sale/cars/?p=1&year=2018&distance=50&atcmakecode=ford&searchtype=new&atcmodelcode=escape&nr=100&s=kbbrank
https://www.edmunds.com/ford/escape/2017/st-401628717/cost-to-own/
https://cars.usnews.com/cars-trucks/ford/escape/2018/safety




