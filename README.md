# Cosmetic_business_study
A large multi-category online store in the US was looking for more insights about one of its business categories, Cosmetic. They wanted to understand customer behavior, so they could optimize conversions at each stage of the process. They sell only cosmetic products in the Cosmetic sub-shop.

# What this project has: 

1. Introduction
    <br> 1.1.Key Study
    <br> 1.2.Problem defined
    <br> 1.3. Steps of the key study analysis
 
 2. Preparing environment and data
 3. Exploratory Analysis & Business Questions
 4. Conclusion & recommendations
 5. Reference
 6. Html link for my assignment
 
## Introduction
More and more, brands have enlisted digital technologies to scale their businesses at the center of what we’d like to call a 
new era of online shopping.  eCommerce is bigger than ever before, especially now that new tools exist to improve platform 
efficiencies across the board. 

Today, an eCommerce store is the primary retail growth engine for any business. In fact, eCommerce is expected to claim 17%
of the industry by the end of 2022. The meteoric growth witnessed by digital commerce over the last decade has also given 
rise to several eCommerce challenges. With the increasing size and demand for online business, riding the digital commerce
wave is not easy.

A demanding majority of shoppers (nearly 81%) begin their journey with online research. Further, 71% of the customers say 
that a fast and highly responsive online marketplace is essential for a pleasant shopping experience.

The leaders of the business need to strengthen their tools and capabilities for better reach and visibility amongst the 
consumers. Retailers should use additional customer data strategically to better understand individual customer behavior
and create a personalized customer experience that should start by analyzing their eCommerce trends.

## 1.1. Key Study
A large multi-category online store in the US was looking for more insights about one of its business categories, Cosmetic. 
They wanted to understand customer behavior, so they could optimize conversions at each stage of the process. They sell only cosmetic products in the Cosmetic sub-shop.

## 1.2. Problem defined

This sub-shop is going to be my client. In order to help him with his request, I will analyze the file they have shared with
me to give recommendations on performance improvements and strategies. 

The client has collected data (5 months: Oct 2019- Feb 2019) regarding the behavior of their customers.

  A. The structure of the data is as follows:
    
    1.Event_time: Time when event happened at (in UTC).
    2.Event_type: The type of the event   
    3.product_iD: ID of a product
    4.category_id: Product's category ID
    5.category_code: Product's category taxonomy (code name) if it was possible to make it.
                     Usually present for meaningful categories and skipped for different kinds of accessories.
    6.brand: Downcased string of brand name. Can be missed.
    7.price: Float price of a product. Present.
    8.user_id: Permanent user ID.
    9.user_session: Temporary user's session ID. Each session will change every time user come back to online store
                    from a long pause.
        
 
  B. Event types: events can be
          
   - view : a user viewed a product
   + cart : a user added a product to shopping cart
   - remove_from_cart : a user removed a product from shopping cart
   + purchase : a user purchased a product

                
  C. Multiple purchases per session
    A session can have multiple purchase events.                  

This study focus is identifying key insights across every stage of the buying process, from viewing a
product to adding or removing it from the shopping cart to making a purchase, in order to optimize conversion rates by 
providing critical recommendations and performance improvements.

 ### 1.3. Steps of the key study Analysis  
    
    1. Upload the required modules
    2. Load the data  
    3. Preparing Data 
    4. Exploratory Analysis & Recommendations
    5. Conclusion
    6. Reference
    
## Conclusion & Recommendations
The client is already doing a good job, but there is still alwaya a window for improvement. I have already mentioned few 
recommnedations in the previous step.

Added to that I would like to highlight Order abandonment one more time which is an ongoing issue for all multichannel
retail brands. However, because of the nature of cosmetics, which many shoppers prefer to try on first, this is an especially 
challenging issue for beauty retailers.

As a way to decrease the potential for abandonment, brands are encouraged to use personalization tactics that encourage 
shoppers to try new products, along with delivering a shopping experience that engages the customer and lets them know how 
much we value their business. And for the marketing tactics, I would suggest:

+ Offering a pop-up discount may encourage a shopper to reconsider leaving their items behind when they exhibit behaviors 
  that indicate they will leave, such as a sudden click to a different page. This approach will work best if it is tailored
  to the user. 

+ Recommend regular product replenishments: As beauty brands fully understand the average replenishment times of items such
  as foundation, lipstick, or eyeshadow, this data can be used to reengage customers who had added an item to their cart but
  then left the site.

+ Notifying them via email that it's time to restock on a previous purchase will increase their likelihood of returning to
  purchase both items

+ The fear of missing out (FOMO) can be a major motivating factor for customers who are unsure about whether they want to
  purchase a specific item. Notifying customers that stock is low may help them decide to purchase, since they may not get
  a chance to later.

+ Retarget returning visitors: Often, shoppers add items to their cart, leave the website, and then come back at a later date.
  When the customer returns, deliver a message that reminds them of their basket details and encourages them to checkout 
  (or continue shopping).
    
+ Add an email to your email service provider (ESP) to remind customers to come back: If a customer has left items in their
  cart and has left the site entirely, trigger an email to remind them to come back. Ensure that you have rules that govern
  email opt-outs (or opt-ins), email frequency, and other factors that will ensure a "light touch" and avoid irritating your
  customers.

One more thing, in this document I didnot go through the customer analysis so I don't have a lot of insights there, but I would 
definitely recommand to check that as well, because it is really important part of the puzzle. And the more data we have about
our customers, the more we can understand them. In this case, I would encourage my client to collect more customer data, or, 
if he already has it, he should share it with me since that would help me to better understand the audience.
    
# Dataset
Kaggle.com. 2022. eCommerce Events History in Cosmetics Shop. [online] Available at:
<https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-cosmetics-shop?select=2020-Jan.csv>


