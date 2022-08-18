# ESPN-API

"Youtube video goes here"

## Objective
Pull matchup data from your fantasy football league using the ESPN API, Python, and pandas.

## Details
This is the first code repository related to a series of videos on pulling, manipulating, and plotting fantasy football data. If all you want is the data, the **main.py** file can be run in the terminal and it will output a csv of the matchup data for your league in the specified year. 

1. Git clone the repository to your machine.
2. In terminal, *cd Pull-Matchup-Data-w-ESPN-API*:
<img width="573" alt="Screen Shot 2022-08-18 at 1 59 13 PM" src="https://user-images.githubusercontent.com/29851231/185473271-6894aa8b-1f9d-4692-a507-b28d5aed4c35.png">
3. Run the main.py file
4. Enter your ESPN league id (how to find this is below) and the year you want to pull:
<img width="573" alt="Screen Shot 2022-08-18 at 2 02 40 PM" src="https://user-images.githubusercontent.com/29851231/185473930-0473d368-a97a-4e76-b0e4-897885eb8973.png">
5. All done! The csv with matchup data will be in your directory
<img width="924" alt="Screen Shot 2022-08-18 at 2 03 40 PM" src="https://user-images.githubusercontent.com/29851231/185474104-9457db2d-0791-4414-9532-122f3a0428a6.png">

To find your ESPN league id, go to your ESPN fantasy football league page and look in the url for where it says leagueid=******
<img width="507" alt="Screen Shot 2022-08-18 at 2 05 22 PM" src="https://user-images.githubusercontent.com/29851231/185474391-777c13c6-d29a-48c5-a559-15fe680d0bf0.png">

There's also a Python notebook **MatchupsExportESPNAPI.ipynb** where the code is broken down into blocks and explained, in detail, in the Youtube video. It's key to understand this first set of code in order to progress with the ESPN API.

### Dependencies
The only dependencies beyond having Python installed are the *requests* library and pandas - both can be installed via pip in the terminal.
