# Tableau

Tableau is a data visualization software great for conducting visual analysis and displaying findings with visual aid.  

Tableau Public makes use of hybrid cloud/local computing.  Your data is stored on the cloud and workbooks you make on your account can be accessed anywhere there is a Tableau Desktop or Tableau Public application.  

**Bonus**: You get a sweet profile to display all your visualizations.

**Drawback**: Public is not recommended for sensitive data.
	Tableau Public can also demand a lot of your local resources as large data transformations and calculations will quickly eat up much of your local resources and leave your computer lagging around. I've also noticed an issue with it interpretting the 'Pages' aspects of visualizations.

Importing data is very simple and can come from a variety of formats such as csv, excel or json.  Be mindful of excel files because they have a mind of their own and tend to ‘interpret’ data and assign them best guess data types.  These best guesses can sometimes change the data.  Tableau is also smart and can interpret datatypes and assign a best guess, but it also takes into consideration Excel when reading in an Excel file.

### Data In

#### Tableau Datatypes
- Integer (Decimol & Whole)
- Bolean
- Date & Time: 2016:12:05 09:30:00 
- Date: 2016:05 or January 2016 or 01:2017:01
- String
- Geographic - These can be anything from Longitude and Latitude Coordinates, Zip codes, City names, Counties, States, Countries. (*Very, Very Helpful.  We will bring this all home during TimeSeries week*) 

#### Tableau Data Cleaning
- Hide unwanted features
- Rename columns
- Adjust recognized datatype
- Quick Table Sorts

#### Joins
Very simple drag and drop
- Inner, Outer Left & Right.

### Tableau Creative Spaces

**Sheets** - workspace to build and finalize visualizations and for presenting results or exploratory analysis.

**Dashboards** - Combinations of 1 or more finalized visualizations.  Very useful is you want to combined different graphs/visualizations that utilize similar filtering/sorting.

**Stories** - Collection of finalized visualizations or dashboards.  Dashboards are made of one or more pages, with each page being an individual sheet or dashboard.  These are great for presenting several visualizations, ideally of a related topic.  You can even go as far as make full presentations out of these stories.

### Visualization 

#### Pills (Those Draggy-Droppy bits)
- **Measures** - Any feature that is described quantitatively.
- **Dimensions** - Any feature that is described qualitatively.



#### Columns and rows - These are pretty self explanatory.  They show the direction in which data is going to be

### Filters, Marks and Pages
**Filters** - Allow us to take a feature and use it as a means to hone in on specific data aspects.

**Marks** -  Allow for us to show depth and add additional dimensions by creating visual changes in the chart that show meaningful relations.  We can use either dimensions or measures for these.

**Pages** - Allow us to take a feature or a measure that ideally has a continuous relationship (i.e Time) and create almost a flip book that shows how the information depicted changes and the page feature changes. 

**Quicktable Calculations** - 
These are great for Timeseries data or data where observations that come before and after are closely related or influenced.
These are simple ways to get things like ‘Running Total”, “Percent of Total”, Moving Averages”, and “Moving Differences”

*Once we get to the Time Series week, we will be doing some more work with these Quicktable Calcs, as well as Pages.*

**Table Calculations**
Table Calculations are similar in offerings to the Quick Table Calculations, however they contain more customization options.

**Calculated Fields** - 
Calculate Fields are basically a way to Engineer Features in Tableau.  They function very similar to Excel table Calculations.

**Aggregate Measures.** - 
When plotting measures against measures Tableau has a Tendency to Aggregate measures, or collectively summarize all observations as a single point.   A lot of times you are going to create a viz and it will end up as a single observation.  If this ever happens check the ‘Aggregate Measures’ option in the Analysis tab.


### Tableau Activities
- I Left some clues as to the routes I went about to solve these.

** Load in the NYC-Leading-Causes-of-Death dataset **

**1. What are the leading causes of death in New York (according to our data)?**
> - a. BONUS:  Research what is the common description of the second leading cause of death.  
    
**2. What is the Second leading cause of death in New York in 2010?**
> - a. Filters or Pages may help
    
**3. What percent of all deaths recorded are attributed to the leading cause of deaths?**
> - a. Use a Quick Table Calculation
    
***By Now you have probably noticed that there are two very-high, across the board contributors.  ***

**4. Investigate and see if there are any years, races or sex combinations where these two are not so prevalent.**
> - a. Filters may help
> - b. Feel free to filter these two contributors for the remainder of the exercise following.

**5. What are the top 5 causes of death for “NON-HISPANIC BLACK” (You can do this with or without having filtered out the distinct top 2. **
> - a. Do these Top 5 change on a year to year basis?
    
**6. Not all races have records for all types of deaths.  Make a visualization that shows which races do not have records for which cause of death.**
> - a. It may be counter intuative, but a table could be useful.  
    
**7. Which Causes of Death are Males more at risk for as opposed to females and vise versa?**




## **Part two **Tableau is great for easily viewing geographic data. Try connecting to the **Drinks.csv file**

**8. Try to show a map of world beer consumption where the shade of color in a specific country corresponds to their beer consumption.** 

**9. Try focusing on just a single continent with you map.** 
>- a. Filters will help here 

**10 Customise your geographic map with tooltips and labels.**


**11. By Now there should have been some insight that peaked your curiosity.**
> - a. Explore them.
> - b. Build a Story of at least 4 Sheets or Dashboards to show your findings through your thought process.  