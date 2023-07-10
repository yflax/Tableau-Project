# Final-Project-Tableau

## Project/Goals
> For this project I chose to work with option 2 and gain insight into trends and patters of the NYC Airbnb rentals market through visualizations. My goal is to draw insights from the trends and correlations in the data through the lense of a potential airbnb property buyer (individual rental property investor) and  find the most appropriate visualization to answer  questions that the invesotr may ask. I want the  visualization itself to explain the data .  
I hope that once I've completed this project I will become knowledgeable about Tableau visualizations and the New York City airbnb rental market  .

## Process
### 1) EXPLORING & UPLOADING THE DATA  
> After downloading the airbnb files locally , I read them to familiarize myself with the various fields. I then uploaded them to Tableau.

### 2) CLEANING  
> Performed basic cleaning by excluding null values and filtering out non-New-York zipcodes . Did not delete anything because I reasoned those flawed data points may come to use in a future , broader airbnb analysis 

### 3) VISUALIZATIONS
> Experimented with different visualizations to represents different relationships and comparisons , taking heed of Dr. Andrew Abela's chart suggestions. Narrowed it down to five visualizations to present - as instructed . Throughout this process I focused heavily on what the user experience would be like for a rental-property-investor who wants a brief overview of metrics of NYC airbnb rentals. I was mindful of limiting the number of colours I used  and allowing the user customization by creating a price parameter, show/hide button, and displaying filters so the user can isolate specific data points to analyze.  
> Before tackling the dashboard , I sketched a plan for the layout of each sheet in the dashboard so when I added the containers I knew how to structure them and placing the sheets was easy. When I was creating the dashboard  my priority continued to be a clean and accessible interface . My plan was to embed an article about the airbnb-rental landscape in NYC , but when the dashboard looked too cluttered with it , I chose to remove it . 
Lastly , I created my story in Tableau , choosing to present in Tableau so that I can interact with the data  while explaining.
### 4) 


## Results
> I chose option 2 , 'Airbnb Rentals in NYC'. The following were some of the questions I asked from the perspective of a private investor interested in buying individual properties to rent on Airbnb.

>>> "Does number of beds affect price and rating?" - number of beds affected price and the reference line showed a high R-squared value and a low P-value , but the average rating remained consistent even as bed count increased.

>>> " Which zipcodes have higher review counts ? " - created clusters to group by review count (amount of reviews not rating score) for each area and found the localities with high review counts were not limited to one zipcode , which makes sense because it is unlikely that certain localities  would influence a higher review count.

>>> "Does a higher rating score cause hosts to raise prices ?" - no , there was no clear relationship between rating score and price as seen in the scatter plot and reference line with low R_Squared value

>>> " Do more years as a host  = higher avg. price and rating in New York City?" - no , hosts that have registered with airbnb earlier on did not have higer prices and ratings than hosts who signed up later on.

>>> "Most expensive neighbourhood in NYC on average?" - Manhattan.


### Chanllenge 
> This project was really enjoyable to me , I loved the way that bright visuals explained the data in a universal and inclusive format , requiring no background in data science and statistics to understand it. My biggest challenge was that the dataset was dated , ranging from 2008 through 2016 ,and is likely not representative of the current AirBnb market in NYC.

## Future Goals
> If I had more time I would analyze the data from the angle of a Airbnb guest and find relevant trends and relationships that would be relevant to a guest. I would also like to work with a larger dataset because I found that my lines of regression may have been imbalanced due to insufficient data points. Ideally my dataset would be current , and I would love to perform forecasting with it. 
