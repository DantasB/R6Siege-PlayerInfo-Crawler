# R6Siege Crawler Made With C# 

A simples Crawler that get's every match info of any Rainbow Six Siege player.

## Information:
- This Crawler access the [R6Stats](https://r6stats.com/) and reproduce every get and post necessary to reach the user information.
- The class [PlayerData](PlayerData.cs) will be used to compare the stored data with the data gotten in the above url.
- The [Utils](Utils.cs) is a group of functions used to treat the Date information.
- The [R6StatsData](R6StatsData.cs) is a class that stores every R6Stats data gotten.
- The [Worker](Worker.cs) is where the main function is located and the other group of functions necessaries to parse the url data.

## How to Use:
- Please Open the release Session: [Click Here](https://github.com/DantasB/R6Siege-PlayerInfo-Crawler/releases)

## Example:
- Here's an example in how the Temporary Data is stored: [Click Here](https://github.com/DantasB/R6Siege-PlayerInfo-Crawler/blob/master/R6SCrawler/WorkFolder/Alekz%20211dc9a3-3c48-4bd5-ab5b-1055b675f965.json)
- Here's an example in how the Result Data is Stored: [Click Here](https://github.com/DantasB/R6Siege-PlayerInfo-Crawler/blob/master/R6SCrawler/ResultFolder/Alekz.json)
