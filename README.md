# data6-project

 <img src="./IMG_1649.jpeg" style="width:50%; margin:auto; display:block">


 import plotly
 print(plotly.offline.plot(px.scatter_geo(regional_restaurants.to_df(), 
               lat = 'latitude', 
               lon = 'longitude', 
               color = 'name',
               locationmode='USA-states',
               scope = 'usa',
               title = 'Regional Fast Food Chains Across the US'
              ), include_plotlyjs=False, output_type='div'))
