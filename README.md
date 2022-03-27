# Engineering Log

## Goals: model world population growth since 1950, generate predictions for the next 50-100 years. Depict prediction on world map?
### Sunday March 27, 2022

    - [X] Wikipedia article on world population, table with estimates of world population (https://modsimpy.com/worldpop)
    - [X] Use pandas to read the web page, extract data 
    - [X] Extracted 5 useful tables as pandas DataFrame objects

#### What is today's overall strategy?
    - [X] Get the tables from Wikipedia web page
        - [X] Replace the column labels with shorter strings
        - [X] Get the Census estimates, store in variable called census
        -
    - [X] Plot the estimates
        - [ ] ISSUE with getting the decorate() to work properly
        - [X] SOLVED needed to import another library
    - [X] Calculate the absolute and relative errors
    - [ ] Fit the model to the data
    - [ ] Model the poulation growth
        - [X] Model with constant growth 
            - [X] Compute the average annual growth
              - [X] Instead of hard coding, programmatically get the ends of the table
              - [X] calculate elapsted time, total growth, and annual growth
    - [X] Simulate the population growth
    
