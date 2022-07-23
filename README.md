# 10Task

Changes:
1.Creation of two buttons in the body index html(March 2020,July 2020).
2.Creating stats interface in stats.ts, creating const with the initial stats and creating const with the current stats.
3.In index.ts the initial and current stats as well as the stats interface of stats.ts are imported.
4.In index.ts we pass maxaffected to fixed value and to calculateradiusbasedonaffectedcases we put it in function of the set of 
data instead of being static to one set of data.We update calculateradiusbasedonaffectedcases arguments where the function is called.
5.In index.ts We create an updatechart function to update the chart according to the dataset we select.This function calls to calculateradiusbasedonaffectedcases.
6.In index.ts Creating two functions that by clicking on the buttons call the update chart function with the selected dataset 
according to the selected button.


To execute the code first you have to download this full repository and unzip the file.Then load the unzipped file to VSC and loading the full file there.
Once we have the file in VSC, running npm install and npm start in a terminal window will open our chart.
