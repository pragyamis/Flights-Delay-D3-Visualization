# Flights-Delay-D3-Visualization
 
<h1>CS 498: Data Visualization Project Report Air Flights Delays  </h1>
<h2>Submitted By: Pragya Mishra </h2>
 
<b>What is the message you are trying to communicate with the narrative visualization? </b>

This project provided great opportunity to learn new aspects of data visualization. This narrative visualization is about answering few questions about US Flights delays:

  What is concern about flight delays? 
  What is “Flight delay” trend over last 10 years?  
  Which airports causes most delays? 
  Which airlines causes most delays? 
  
<b>Data Source:  </b>
The dataset “US Flights Delays and Cancellation” from Kaggle and latest years data from US Transportation website. 
Narrative Structure: 
An interactive slideshow, where user exploration is allowed at some or all the steps of the story. Tooltips are provided in all charts for more details. 
 
<b>Visual Structure and Scenes  </b>
Narration opens with a question “Do you know as per US Department of Transportation 18.8% flights delayed this year”. Same font-color, background color has been used in all slides for minimum distraction from topic. 

Slide One: Introduction with a question: Do you know as per US Department of Transportation, how many flights delayed in 2019 already? 
Bold and Red color text give viewer sense of concern and has been increased from last year. 

Second slide “Has it always been like this, what is the trend across last 10 years” 
  
Slide Third: Airports causing most delays: 
This slide opens a map that has overlay of Flights delays by airports data. This gives better idea to user about “Which airports has most delays or less delays? 
 
Circle size represents airport size (number of flights) and opacity shows its' delay rate (counting only delays that were longer than 10 minutes).  
 
This map uses bigger scale to reduce circle sizes and overlapping, however it's still presents in some cases. 
 
Viewer will know after exploring this chart that Delays are not always related to airport size.  
 
Small but Dark Red circle airport like Wilmington Airport, Wilmington, DE, has 40% delayed (40 of 100 flights)  

 
Scene/Slide Four: Airline with Most or least flight delays: 
 
Circle size represents airline size (number of flights) and Y axis shows its' delay rate (counting only delays that were longer than 10 minutes).  
 
Circle size and y value shows maximum number of flights were delayed by WN South West Airlines Co and least number of delayed flights by HA Hawaiian Airlines Inc. 

<b>Annotations/Tooltips  </b>

Bar Chart shows annotation for 2019 Flight delays from Jan-May period and indicates to users that it is already exceeding 2018 total delays. 
Bar Chart also shows tool tips showing % of flight delays that year out of total flights and changes color of bar red. 

“Airport with most and least delays” shows map and circles on airports. Viewer can click on airport to know more about that airport.  
 
Airlines causing more or least delays 
 
<b>Parameters: </b>

Radio buttons have been used to toggle between Flight delays by arrival and departure. THis is passed as parameter. 

<b>Triggers:</b>

Third slide "Airport causing most or least delays"  has mouse click event that shows annotations in a leaflet that opens on clicking on any airport circle. 

<b>Future Work: </b>
Explore Reasons for delay and evaluate revenue loss due to flight delays. 
