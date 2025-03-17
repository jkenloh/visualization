> What software did you use to create your data visualization?

I used Python in Visual Studio Code to create my visualization.

> Who is your intended audience? 

My intended audiences are diners at restaurants/takeout places, government food safety regulators, and restaurant/franchise owners.
    
> What information or message are you trying to convey with your visualization? 

I am trying to convey which food establishments in Toronto have the most number of significant/crucial food infractions based on year.
    
> What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 

I wanted the visualization to be aesthetically pleasing to look at, so I opted for a minimilistic design. The visualization is substantive as it accurately and honestly presents the data with no hidden bias, as it simply ranks the establishments based on the number of significant/crucial infractions. I believe that the message of the visualization would also be clear, as the title reflects what the data is showing. I used accessible colours for the bars to ensure that the information is understandable to everyone, including individuals with colour vision deficiencies or other sensitivites. I also made sure the background and bar colours were not clashing, making it easy to read. I wanted to make sure to minimize the mental load for whoever was looking at my visualization, which meant keeping everything clear and simple. I did this by making sure the title was related to the data being shown, and that the labels, y-axis, and x-axis were clearly visible and easy to read/understand.

I wanted to include an interactive slider to change the year instead of a dropdown, just so it minimizes the amount of clicking while making it easy to navigate without having to read any additional instructions. I also highlighted the top 5 establishments to give a clear distinction to them compared to the rest, so that it was easy to find the top 5 with the most infractions quickly in each year.
    
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

I ensured my data visualization was reproducible by making the file accessible on GitHub, so that you can incorporate the link in the code immediately without having to download it. The python code can also be used to create the same visualization using the same dataset, as all the data cleaning and modifying were done through the code. 
    
> How did you ensure that your data visualization is accessible?  

I used a minimalistic design and accessible colours, including highlighting the top 5 to make it stand out even more. I also made sure the font size and type were easy to read. 
    
> Who are the individuals and communities who might be impacted by your visualization?  

The individuals who dine out often may be impacted as they may see some of the establishments they regularly visit on the list of most infractions. If there are immuno-compromised individuals, they may also want to avoid the names consistently being listed at the top. For businesses and franchise owners finding themselves on the list, they may want to invest time and resources to prevent future infractions from happening. The government food safety regulators may also want to focus their attention on the establishments that are consistently ranked at the top of the list, as these places are clearly having some issues regarding following food safety practices.
    
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 

I chose to include the features that were relevant to my analysis, which were date, infraction details (for the count), severity of the infraction to categorize significant/crucial infractions, and establishment name for identifying purposes. Date was also important as I wanted to make sure the number of infractions were showing per year figures, so we could see the list of establishments change depending on the year, and see whether or not some were still on the list as time went on. 
    
> What ‘underwater labour’ contributed to your final data visualization product?

Deciding which columns to use, preprocessing (handling missing values, deciding how to make the count), running the code blocks multiple times to make sure it worked as expected, creating many iterations, debugging, and ensuring it was accessible (colours, font, sizing, layout). There was lots of trial and error as well, often modifying something then running it to test it out. Also, deciding which dataset to use, including what to show and how to show it.