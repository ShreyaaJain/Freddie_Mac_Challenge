# Freddie_Mac_Challenge
### Part1 deals with Exploratory Data Analysis and scraping data  from Freddiemac website
### Part2 has Prediction and Classification alogorithms to predict an interest rate of a mortgage, and to classify a whether a loan is delinquent or not 
### Instruction to pull and Run the Image:

- To get the images in the local execute: 
  - docker pull sumedh11/midtermads4:latest
- Image can be run in three different ways.
  - To run part1 alone execute the command mentioned in next line by entering username and password,image will login into Freddiemac website,using the cookies and scrape the data
  - docker run sumedh11/midtermads4:latest username password
  
  
  
  - To run part2 alone execute the command mentioned in next line by entering username,password and Quarter Name for which interest rate has to be predicted
  - docker run sumedh11/midtermads4:latest username password Quartername
    To get data for 3rd quarter of 2007.Quartername will be Q32007 and the corresponding next quarter data will be test data.
    
    

  - To run both parts execute following command mentioned in next line.Default values of username,password and Quarter Name(Q12005) will be used for executing part1 and part2
  - docker run sumedh11/midtermads4:latest
   
