# Group M Mindshare Summary
## The Challenge
You are an agency team (Mindshare) consulting on a project for a small but profitable eyewear company with 3 main products, all with different target demographics and at different stages in the market. 

Golden Finch
- Product Type: Luxury Sunglasses
- Target Demographic: Female 18-36
- Price: $650

Timber
- Product Type: Luxury Sunglasses
- Target Demographic: Male 18-36
- Price: $600

Avalanche
- Product Type: Winter Sports Goggles
- Target Demographic: Unisex 24-34
- Price: $850

As a consultant, you must discover the underlying ties between consumer and consumption and determine their impact. Your goal is to build an executable media plan to achieve the client objectives below:

Sales Objectives:
- Maintain media budget below $70MM
- Increase sales volume by 15%

Audience Engagement:
- How does our audience interact with and consume media? Does this align with our previous strategy? If not, how can we adapt our media plan to better reach our target demographic.
Brand Impact
- We want to understand the long-term impact that brand consideration has on our sales volume.

## Case Objective
Brand:
Use audience listening data to determine the characteristics of the target audience to inform your media plan and creative strategy.

Analytical Methodology:
Quantify the relationship between brand consideration, media, and sales performance across each product.

Plan & Engagement:
Create a detailed media plan for the year across all 3 products.
Use your creativity to provide visual examples of an engaging ad.

Measurement Framework:
Detail how you would monitor the success of your plan.

## The Datasets
Audience Measurement Dataset
- Demographic segments
- Consumer behaviors and characteristics
- Media consumption habits

Two years historical data for products lines:
- Sales Volume
- Media Spend
- Media Activity
- Brand Consideration

## Our Solution
For further detail (including the code), see: https://github.com/kly2110/Mindshare/blob/master/Final%20Recommendations%20Report.pdf

Based on the audience dataset given, my team and I segmented our consumers into 4 groups using k-means clustering, and chose to focus two of the four clusters when marketing our products. Afterwards, we developed a Markov chain mixed channel attribute model (with several major assumptions) to help us allocate the media spend to different channels specified in the problem. We then forecasted the future sales for the three products. We also developed various marketing strategy material and social media content that the company could use to advertise their products.

Note: While we used an ARIMA model during the forecasting process, we should not have done so since the model builds upon past history to forecast the future and does not incorporate new additional information.


