| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Makeover Monday for Reliable Cars!
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization
![Makeover Monday Pick](Most-Dependable-Car-Brands-in-the-US_Web.jpg)
**Source:** https://www.visualcapitalist.com/ranked-the-most-reliable-car-brands-in-the-u-s/#google_vignette

I chose this data visualization because I’m planning to buy a car after I graduate, and I’ve come across many similar rankings that feel unreliable or lacking in transparency. This is the first one I’ve seen that actually provides a clear metric—problems per 100 vehicles—to explain how reliability is measured.

## Step two: the critique
I found this visualization really useful because it clearly states the metric used—problems per 100 vehicles—which is something I haven’t seen in other rankings. Most just list the rankings without explaining the methodology. That said, I was initially confused by the numbers being over 100, and I think there might be a more intuitive way to present that information.  

I’m not sure how I feel about the use of both brand logos and names. It seems redundant, but I know a lot of visualizations do this. The bar graph itself is easy to read, but it took me a while to notice the “average” bar, which I think is actually really helpful but doesn’t stand out enough.  

Visually, I found the blue-to-red color gradient unnecessary and even a little distracting. Since the data is simple, a clean bar chart would be just as effective—maybe even better. I’d also be interested in trying a unit chart to see if it makes the information more engaging without overcomplicating it.  

I think the primary audience for this tool is people looking for a reliable car, and in that sense, it does its job well. I could quickly find the top-ranked cars and adjust my search accordingly.  

If I were to make changes, I’d focus on aesthetics—reducing unnecessary color and using it more intentionally to highlight important details, like the “average” bar. I’d also reconsider how the problems-per-100-vehicles metric is presented since it wasn’t immediately intuitive to me. Maybe showing problems per vehicle would be easier to grasp, but I’d want to test that with others to see if it’s just a personal preference.

## Step three: Sketch a solution
<div class='tableauPlaceholder' id='viz1739221692712' style='position: relative'><noscript><a href='#'><img alt='Typical number of problems your vehicle will have over a three year period.Sorted from most reliable to least reliable brand. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;MostReliableCar_17392216659440&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MostReliableCar_17392216659440&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;MostReliableCar_17392216659440&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1739221692712');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Step four: Test the solution

### Interview Questions

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

**Results:**

| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|   Can you tell me what you think this is?       |     Comparing typical car problems to average number of car problems        |  Comparing typical car problems to average number of car problems           |
|   Can you describe to me what this is telling you?       |  Most cars have above the average number of problems           |    Most cars have above the average number of problems         |
|  Is there anything you find surprising or confusing?        |  The average seems high           |   The average seems high          |
| Who do you think is the intended audience for this?         |    People looking to buy cars         |    People looking to buy cars         |
|Is there anything you would change or do differently?          |  There's a lot going on, maybe you could break up the brands by country or include a hover-over feature to display the average price of cars          |    I think maybe you could make the brands more obvious, there's a lot of them they kind of get lost         |

**Synthesis:**

The first interviewee, an MSPPM student in their mid-20s with no previous professional experience in data visualization, understood the visualization as comparing the number of car problems a specific car has to the average and interpreted it as showing that most cars have more than the average number of problems. They found the average surprisingly high. They identified the intended audience as people looking to buy a car and suggested sorting the data by cost, adding a hover-over feature to display the average price or data source, and breaking up the information to reduce visual overload.

The second interviewee, a MEIM student in their mid-20s with no previous professional experience in data visualization, interpreted the visualization as comparing the number of car problems a specific car has to the average. They understood it as showing that most cars have more than the average number of problems and found the average surprisingly high. They identified the intended audience as people looking to buy a car and suggested making car brands more obvious to improve clarity. They also noted that the title and subtitle were the most helpful elements. 


## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

<div class='tableauPlaceholder' id='viz1739223067932' style='position: relative'><noscript><a href='#'><img alt='Typical number of problems your vehicle will have over a three year period.Sorted from most reliable to least reliable brand. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;MostReliableCarRedesign&#47;Sheet12&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MostReliableCarRedesign&#47;Sheet12' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;MostReliableCarRedesign&#47;Sheet12&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1739223067932');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

After receiving feedback, I realized that the number of car options may have been overwhelming. One interviewee mentioned that a hover-over feature displaying prices would be helpful, which made me think about ways to simplify the selection. I decided to narrow down the brands by focusing on affordability—since people looking for reliable cars likely aren’t considering luxury brands. I looked up the most affordable cars and reduced the list to the top 15, but I also included Nissan because, while it wasn’t in the top 15, it’s generally known for being budget-friendly (though I could be wrong). After making these changes and increasing the label sizes, the chart felt much more digestible.

This assignment was interesting—when I first chose the chart, I wasn’t sure how much I could change since it already seemed simple. But I was drawn to it because I’ve spent the past few weeks searching for affordable cars on the internet. In fact, I’ve been using this data to guide my own car search and have set my Carvana filters to show only cars priced above this average (though, of course, the sample size may not be entirely representative). That said, I do feel like I’ve significantly improved the visualization by making the numbers clearer and using colors that naturally guide the reader’s focus.

## References
Source for most affordable cars: (https://caredge.com/ranks/costs/30k/least-expensive#models)

