## _Task number 2: Critique by Design_

### Here, we choose, review and critique a visualization!

> ## Step 1: The original visualization
### The visual chosen is as shown below:
The link for the same is given here: https://blog.datawrapper.de/weekly-chart-scatterplot-lifeexpectancy-rutger-bregman/

<img width="700" alt="OGImg" src="https://user-images.githubusercontent.com/43436738/152729852-10e60d12-fe5a-4b9e-be79-2daddfde1108.png">


> ## Step 2: My process for re-visualization

1. **Changing the title**
The current heading 'Every country has a higher life expectancy than in 1800' fails to correlate the two important measured values used here for comparison: The GDP and Life-expectancy. Currently, the only interpretation that can come out of this title refers to the life-expectancy. 

2. **Choosing the correct visual**
Personally, I thought there could be some other way in comparing the two measured values of GDP and life expectancy other than the scatter plot. The visual I chose was the geographical map. Personally, I thought it is important for the reader to easily map the countries and compare their values across the two years. Since, it's a map spotting the required countries to compare would be easy. 

3. **Representation of the GDP: The Bubbles on the Geo-graph**
The Bubbles of on the graph would be a similar representation of the scatter-plot. The bubble size would indicate the GDP across the years, hence as assumed the year 1800 would have smaller sizes as compared to the year 2015. 

4. **Representation of the Life-Expectancy: The colors of the Bubbles**
My approach was the divide the life-expectancy in hyeras in terms of age buckets, with each bucket being representated by a seperate colour. My aim was to represent different age brackets as colours, so that visually interpretation becomes easy, and comparison of years lived across the two years can be visually mapped easily.

5. **Representation of population: The background colour of the map**
In the scatter pot, the represntation of the population was indicated with a colour, which blocked other countries and dominated the chart. I thought that a use of a single gradient colour as a background for the map will also be a simple and good indicator. A deeper hue could be an indicator of higher population and subsequently a lighter hue 
represents lesser population. This way, the reader wouldn't be confused and distracted from the visual.


> ## Step 3: A summary of my wireframes
<img width="700" alt="OGImg" src="https://user-images.githubusercontent.com/43436738/152732244-77f82008-b9b5-4572-95f4-30d880d79f07.png">


> ## Step 4: User Feedback

### Interview 1
Can you tell me what you think this is? 
>  Yes, the map shows the relation between the GDP and average life expectancy as specified. 

Can you describe what it is telling you?
> Sure! I can see the mapping of different countries and I see it indicates the relation between the GDP and life expectancy. I guess that the bubble size indicates a higher GDP? Yes, I can see that countries have a higher GDP have a higher life expectancy. 

Is there anything you find surprising or confusing.
> Umm..the bubble size across the maps are assumed to have a higher GDP, a specification for the same would be good. Also, the background colours of the map, the blue gradients aren’t specified what they actually represent. 


Who do you think is the intended audience for this?
> The intended audience for this seems to be economists or researchers, that are interested in correlating these factors. It seems to be interesting to compare the two years and understanding how it has changed.


Is there anything you would change or do differently?
> I would like to see the bubble size and map hues to be explicitly defined so that it can be interpreted better. Additionally, incorporating filters relating to the population size and or continents would be better. 



What did you like?
> I like how we can compare and contrast the relation between health and wealth across the two years: 1800 & 2015. Additionally the geographic map can easily allow to  me to find and know about a particular country if I wish. 


### Interview 2

Can you tell me what you think this is? 
> So, what I can see is the mapping of different countries over the map. It is said that is shows a correlation between health and the wealth.

Can you describe what it is telling you?
> Looking at the visualisation, I can see that the higher GDP, the higher is the life expectancy. I can also see the difference in the Avg life expectancy across the 2 years, 2015 people did live longer and I see the massive increase in their GDPs too, depending on the bubble size. I see the age bracket differentiation based on the colours which seems interesting.

Is there anything you find surprising or confusing.
> The visual comparison between the two years looks good, but the blue background for the map is darker for India and China, but what does that indicate, I guess population? That’s confusing. The bubble sizes are also not mentioned to be indicating anything. 


Who do you think is the intended audience for this?
> Audience for this visualisation could be anyone in the field of economy, science or even officials working in government organisations. Additionally, it could be of a great use in any academic institutions pertaining to geo-economy.


Is there anything you would change or do differently?
> The visualisation looks great for interpretation. I would like the something that could avoid the visualisation to look cluttering (Assuming all the countries would be plotted, which could make the visual look busy)


What did you like?
> The visual allows me to perform comparison across years and countries, and clearly see the relation between wealth and health. The use of colours seem really good. Also, I feel that the age buckets is a good way to compare these visuals. 

#### Feedback review/ My take-aways! :D

### The responses that I received above helped to me make the following changes:

Specifications (Bubbles & Map colours)
- I added the bubble size and map blue gradient references as legends, making the visualisations even more clearer and easier to interpret.

De-cluttering the visualisation
- I decided to filter out the visualisation so that it remained de-cluttered. And added the criteria as a filter that the audience can play with.


> ## Step 5: My re-design/Data visual

Using Tableau, I tried encorportating all the above factors in creating this:

<div class='tableauPlaceholder' id='viz1644253961593' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DoesWealthaffectHealth&#47;DoesWealthaffectHealth' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1644253961593');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
if ( divElement.offsetWidth > 800 ) { vizElement.style.width='800px';vizElement.style.height='500px';} 
else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='800px';vizElement.style.height='500px';}
else { vizElement.style.width='100%';vizElement.style.height='500px';}                     
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


<div class='tableauPlaceholder' id='viz1644258699993' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DoesWealthaffectHealth&#47;DoesWealthaffectHealth' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                  
var divElement = document.getElementById('viz1644258699993');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.maxWidth='1704px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';vizElement.style.maxHeight='945px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.maxWidth='1704px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';vizElement.style.maxHeight='945px';} else { vizElement.style.width='100%';vizElement.style.height='1027px';}                     
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);               
</script>


<div class='tableauPlaceholder' id='viz1644261130238' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DoesWealthaffectHealth&#47;DoesWealthaffectHealth' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1644261130238');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1004px';vizElement.style.height='745px';} 
else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1004px';vizElement.style.height='745px';} else { vizElement.style.width='100%';vizElement.style.height='745px';}                     
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
