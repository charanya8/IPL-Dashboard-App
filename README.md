# IPL-Dashboard-App

Functionality to be added

The app must have the following functionalities

When the app is opened, Home Route should be displayed
When the Home Route is opened,
Make HTTP GET request to the teamsApiUrl
loader should be displayed while fetching the data
After fetching the data, the list of teams should be displayed
When a team card in Home Route is clicked,
Page should be navigated to the Team Matches Route with the URL /team-matches/:id
When the Team Matches Route is opened,
Make HTTP GET request to the teamMatchesApiUrl with the team id to get the recent matches data of the team
Example: https://apis.ccbp.in/ipl/KKR
loader should be displayed while fetching the data
After fetching the data, the team banner, latest match, and list of recent matches should be displayed
