# Techlabs_Project_Covid-19
Project solution for Techlabs' #codeathome challenge week

## Title of the project

Covid-19 interactive & intuitive visualization & forecasting


## Which is the problem the solution solves?

For many of us, the current development of Covid-19 resembles a big black-box which we cannot access intuitively. Reliable information is scarce, especially regarding smaller countries with a lower media coverage. Furthermore, in a more and more globalized and connected world, people are also interested into being able to oversee the Covid-19 development for different countries of the world without having to access local media. 
Social media could be one of those possibilities, but information there often lacks reliability. The websites of governments or (inter-)national organizations could be another option, but many of those sources lack interactivity, forecasts or seem overloaded with different kinds of information. 
Therefore, people are often not able to interpret their home country’s exposure to Covid-19 correctly and may not understand why their country has chosen certain measures to limit the spread of the disease. This might lead to public criticism and rejection against current strategies which could – in the end – worsen Covid-19 development worldwide.


## Solution Pitch

Our goal was it to build an intuitive application that plots the Covid-19 development interactively and can be accessed by everyone, even by those people that might not understand the disease itself or are not able to interpret raw case numbers. Therefore, we created a python notebook that can also be operated by people without a programming or machine learning background. The main features of the notebook are a world map that gives the user an overview about the spread of the disease and the corresponding case numbers, starting from 22nd January, 2020 and an interactive plot that shows official up-to-date confirmed, active, death and recovered case numbers for a total of more than 180 countries worldwide. Furthermore, the user can plot different kinds of forecasts for each type of case number, which were build on multiple machine learning algorithms.


## The solution

Our Solution consists of three chapters in total. The first chapter is all about visualizing the global impact and the current development of Covid-19 case numbers. Therefore, we built an interactive world map that gives the user the possibility to see when and where the disease had an impact by using intuitively understandable bubbles for every country and an interactive time axis. 
The second chapter focuses on the country-wise development of Covid-19. The user can access official up-to-date case numbers from the Johns Hopkins University and gets an overview over confirmed, active, recovered and death case numbers for a total of over 180 countries. Furthermore, different kinds of projections are presented, based on a certain country’s virus reproduction rate and four ML algorithms. Those are a polynomial regression, an AdaBoost regression, a Support Vector Machine and Facebook’s Open Source Forecasting Tool Prophet. 
The third chapter extends the focus of the first two chapters on case numbers with a holistic view on the differences in the structure and capabilities of countries to successfully combat the virus. A clustering approach is used to cluster all countries into three separate groups, according to the reproduction rate, the mortality rate and the recovery rate.


## Impact on the crisis

The impact on the crisis mainly refers to informing the population about the current development of Covid-19. We want to prevent disinformation and, as a possible  result, resistance against (necessary) country- or worldwide measures to contain the spread of the disease. Limiting free movement and social contacts is not easy and requires each of us to give up on something. Nevertheless, we think that this can be made easier for each individual if he or she understands why such measures are ordered or recommended to the general public and to what successes the enforcement of such measures has already led to in some countries. Even if we are just able to inform and handful of people and can convince them to e.g. stay at home, we think that our solution already had a powerful impact on the crisis, because what really counts is that everyone of us knows his responsibility and takes part into combatting the spread of Covid-19.
