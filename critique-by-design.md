| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Price of pizza slices in NYC 


## Step one: the visualization

The data chosen to visulaize was [NYC Pizza Slice](https://elkue.com/nyc-slice/)

The reason I chose to work on the redesign for this data was just because of how interesting this was. While I understand that overall, NYC has a LOT of pizza joints, there are so many things I am curious about - why the author chose to do this, why did he only try two specific kinds of pizzas, well at least majority of the time, and most importantly how he was consistent with it for more than 8 years! While looking at the data and analyzing it, I felt that there was something more that can be shown through this. Not just about pizza slices and their prices but also something about the economy as a whole. 

[Link](https://data.world/makeovermonday/2023w5) to the raw data sets and maps.  

### The Original Visualization 
Mapping the Pizza joints tried in NYC 

![Pizza joints in NYC](PizzaViz1.jpeg).

Visualizing the changes in price from 2014 to 2023 - specifically for plan and pepperoni.

![Prices of plain and pepperoni](PizzaViz2.jpeg).

Tabulating the pizza joints tried and the price - arranged from heighest to lowest price per slice.

![Tabulation of pizza slice prices](PizzaViz3.jpeg).



## Step two: the critique

NYC Pizza Slice by Liam Quigley represents his journey of trying out pizza slices in New York City from 2014 to 2022. He also has a baseline for the price, which starts at $2.50, which is considered cheap, and goes up to approximately $6 a slice, which is expensive. What works great here is that the data only focuses on the pizza slices he has tried and includes the necessary attributes like where, when, and how much each slice costs. 

Apart from being curious and surprised about the number of pizza slices Liam has tried since 2014, what stood out to me was the map. I was able to instantly see parts of NYC that might have the greatest number of pizza joints to try from. This also gave me a sense of the kind of urban development that place might have. 
Liam also represents the trend in the price change with the years, which when observed can be seen that the base price of $2.50 went up to $3, and because the trend is represented with the years it becomes easy to understand that it might have been because of the inflation. The chart representing the trend of prices focuses only on two major types of pizzas (plain and pepperoni) that he has tried. While this might have been a choice made by the author, limiting price trends for only two of the pizza types; the ones that he tried most of the time, makes it easier for the audience to draw a comparison without creating distractions. 
A few things that I thought did not necessarily work – even though not mapped the data includes the time. While the date of when the pizza slice was tried could be important the time when it was tried may not be required, especially when showing it to a larger group of people. The heading may also be misleading in some cases, it does not say “what” about NYC pizza slices is being explored. Having a title that says something about the core of the data could be helpful, this eliminates the need to go through the article/data set to understand what is being visualized. While Liam categorizes pizza based on the topping, the ‘plain’ type is a little confusing – does plain mean with cheese or without it? This may not be confusing to people who are from America and understand the norms of pizza toppings, but it could be confusing to people who are not originally from the USA. 

What I would probably do differently is create a map that is symbolized by the price of the slice rather than the type of slice. That way people know the pizza joint that has the cheapest slice of pizza regardless of the type of pizza. Another thing that I would map is probably the list of places that Liam recommends – it has not been mapped, but because he provides a list creating a map of it might also help people choose a pizza joint that is cheap but also tastes good. 


## Step three: Sketch a solution

While the idea was to give people an idea about where they could possibly get the cheapest slice of pizza, I also thought it would be interesting to see if I could also show the pattern of inflation through it. While the author depicts a line graph with the prices of plain and pepperoni pizza from 2014 to 2023, during the time of inflation, around 2020 we see that there is a rise in the price of pizza slices. I thought this could be an interesting layer to add to the redeisgn. 

![Solution](Pizza1.jpeg)

![Solution](Pizza2.jpeg)


## Step four: Test the solution

Questions I asked to my peer reviewers:

- What do you think you are learning from this data?

- Who do you think this data might be useful for?

- Is there anything I could change or make clearer?


Results: 

| Question | Interview 1 | Interview 2 |  Interview 3 |
|----------|-------------|-------------|------------- |
| What do you think you are learning from this data? | Where people can get cheap pizza in NYC and which borough has the cheapest pizza | Which area in NYC has the most options for pizza joints and comparison between plain and pepperoni pizza slice prices |        
|          |             |             |              |
|          |             |             |              |

Synthesis: 

While the participants during the interview overall appreciated the sketch of the solution, a common question was "What do you mean by plain pizza?". This one was tricky because the author of the data itself has not specified what plain pizza might be, so this was a question I was also having. But for this assignmnet i am assuming that a plain pizza might just be the same as margherita.

Another suggestion was - if in case I was choosing to depict inflation, I could probably have the line graph in the begining of the data visualization. 

## Step five: build the solution

Like I had mentioned in my critique of the original data, I chose to map the pizza joints around NYC by the price. I feel like this is a much better way o give people - studets, working class, tourists, a better sense of where you can get cheap pizza. The map also specifices the name of the Pizza joint, but not its address. 

<div class='tableauPlaceholder' id='viz1739715676841' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Sheet 1' src='https://public.tableau.com/static/images/C9/C9M3GJDCC/1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='path' value='shared/C9M3GJDCC' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/C9/C9M3GJDCC/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1739715676841');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script> 


While the map abouve shows the specifics of where in NYC you can get cheap pizza slices, I wanted to see if I could visualize the average pice of pizza slices by NYC boroughs. This gives a larger picture in terms of understanding which borough overall has expensive pizza slices.


<div class='tableauPlaceholder' id='viz1739719187584' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Average price of pizza slice by NYC borough' 
           src='https://public.tableau.com/static/images/Pi/PizzaSlice_17397154445730/Sheet3/1_rss.png' 
           style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='PizzaSlice_17397154445730/Sheet3' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' 
           value='https://public.tableau.com/static/images/Pi/PizzaSlice_17397154445730/Sheet3/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1739719187584');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

I chose to filter out only plain and pepperoni pizza styles, because even though the author does try different pizza styles the majority is plain and pepperoni. By doing this the amount of information a viewer might have to comprehend also reduces - making it easier to understand the chart. This chart compares the average price of pepperoni and plain pizza silces in each borough. I also visulized them with a colour that I think represents them the best - red for pepperoni and yellow for plain. 

<div class='tableauPlaceholder' id='viz1739720966017' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Average pizza slice price by borough' 
           src='https://public.tableau.com/static/images/Pi/PizzaSlice_17397154445730/Sheet4/1_rss.png' 
           style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='PizzaSlice_17397154445730/Sheet4' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' 
           value='https://public.tableau.com/static/images/Pi/PizzaSlice_17397154445730/Sheet4/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1739720966017');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>




I went ahead and tried to see if I could visulaize the increase in prices from 2014 to 2023 only for plain and perpperoni style pizzas - though the outcome of the interview was to see if I could put this chart in the beginning, but I felt that even though I am trying to show inflation my main focus is to give people an idea as to where you can get cheap pizza in NYC. But this was also a process of experimentation for me. 



<div class='tableauPlaceholder' id='viz1739718160863' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Average pizza prices by year' 
           src='https://public.tableau.com/static/images/Pi/PizzaSlice_17397154445730/Sheet2/1_rss.png' 
           style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='PizzaSlice_17397154445730/Sheet2' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' 
           value='https://public.tableau.com/static/images/Pi/PizzaSlice_17397154445730/Sheet2/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1739718160863');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

