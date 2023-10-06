# Steam-Deal-Checker
This is a jupyter Notebook that leverages cheapshark api to find the best deals for steam games. It uses Ipython to display widgets which i have made functional such as the search button, the dropdown sort by menu and the prev and next page buttons. 
![image](https://github.com/LukeGirvan/Steam-Deal-Checker/assets/126108451/bc4e229b-48ad-45a4-b17d-329a4bc0b44d)

![image](https://github.com/LukeGirvan/Steam-Deal-Checker/assets/126108451/6fae1218-3926-4b31-a27e-46792e6e17dc)

## Functionality
- Added functionality to the buttons so instead of having to scroll and find them you can use left or right arrow on your keyboard to achieve the same result and use enter instead of the search button.
- Dynamically displayed buttons. The previous and next page buttons are only visible once you have searched for a game same with the dropdown sort by menu.
- Pagination: I implemented pagination which calulates the amount of pages to be displayed with the max being 6 as the limit from cheapshark api is 60 results, it also calculates when to display the previous and next buttons and when they should be in a disabled state it also displays what page you are currently on.
- Data cleaning: The incoming data from the cheapshark API call is in JSON format so i extracted the results which include the thumbnail price and title of the game ![image](https://github.com/LukeGirvan/Steam-Deal-Checker/assets/126108451/29e490cc-1b3d-4d8b-a376-9e1808d81298)
