# Market-Basket-Analysis-in-Python
This project marks the beginning of my development journey, and I'm excited to share it with you. The primary focus of this project is on Market Basket Analysis, a fundamental concept in data mining that involves analyzing customer purchasing behavior to identify patterns and relationships between different products.

_*Market Basket Analysis*_
Have You Ever Wondered...
While browsing online shopping platforms, have you ever stopped to think about how the system seems to magically know exactly which products to recommend, perfectly complementing your purchases? Then its time to pull up the curtains and introduce you to kits scienece:
Market Basket Analysis is a popular technique used in retail and e-commerce to uncover hidden patterns in customer transactions.
Market Basket Analysis takes data at the transaction level, which lists all items bought by a customer in a single purchase. 
Association Rules are widely used to analyze retail basket or transaction data and are intended to identify strong rules discovered in transaction data using measures of interestingness, based on the concept of strong rules.

“Bought together” → Association

“WIth Profduct A we reccomend you to buy Product B” → Recommendation

These relationships are then used to build profiles containing If-Then rules of the items purchased. for example:

If {A} Then {B} : A => B

 *Support*: Support is an indication of how frequently the item set appears in the data set. 
*Confidence*: The confidence of the rule is the ratio of the number of transactions that include all items in {B} as well as the number of transactions that include all items in {A} to the number of transactions that include all items in {A}.
*Lift*: The third measure called the lift or lift ratio is the ratio of confidence to expected confidence. Expected confidence is the confidence divided by the frequency of B. The Lift tells us how much better a rule is at predicting the result than just assuming the result in the first place. Greater lift values indicate stronger associations. Simply, the lift of a rule is the ratio of the observed support to that expected if X and Y were independent.
By analyzing the items customers purchase together, businesses can gain valuable insights into customer behavior, preferences, and needs. This information can be used to:

*Apriori algorithm*:
The Apriori algorithm is a popular data mining technique used to identify frequent itemsets in transactional databases. It's a fundamental concept in association rule learning, which aims to discover relationships between different items in a dataset.

*Implementation Details*
This project has been implemented using Jupyter Notebook with Python as the programming language. The code is designed to be modular, easy to understand, and modify.

*Applications of Market Basket Analysis*:
*For the retailers*: Market basket analysis (MBA) finds great application for the marketing perspective to the retailers. It helps retailers in optimizing their marketing campaigns and strategize future sales by understanding their customers better. Offering actionable customer patterns and behavior helps in boosting the sales of the store and increases the ROI. Further, it enhances customer engagement and improves the customer experience while shopping from a store.
*Personalized recommendations*: Market basket analysis understands the movie genre an individual likes to watch and recommends movies on OTT platforms like Amazon prime and Netflix.
*Promotions and campaigns*: This analysis helps in understanding the products that go together along with the ones that form keystones in the product line.
*Customer behavior analysis*: Market basket analysis helps you understand the customer behavior that is leveraged from UX/UI design to catalog design.
*In-store operations optimizations*: MBA finds great application in optimizing the inventory by determining the popularity of the products in a store.
*New marketing tactics*: MBA eases the task of discovering new marketing strategies to grow a brand. It analyses the demographic and gentrification data to help you make informed decisions on where to open your next store or target ads.
