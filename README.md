# README
# FloodRunnerATX_api

FloodRunnerATX_api

FloodRunnerATX is a live-updated resourse for looking at current water levels at flood gauges in the Austin, TX area using the USGS API.  

- clone repository and cd into newly created folder. 
- run 'bundle install' 
- run 'CREATE DATABASE' from the terminal to create a new postgresql database. 
- run 'rake db:seed' to run the inital calls to third party APIs. 
- To start a local server, run `rails s -p 3001` from your terminal.
- Access the api using your own client, or use the React client I built for this project at "https://github.com/Josh-Gotro/FloodRunnerATX_client"

Third Party API's:
- USGS water records
https://waterservices.usgs.gov/rest/IV-Test-Tool.html
# live water gauge data

- Google Maps API
https://developers.google.com/maps/documentation
# maps data

- DarkSky
https://darksky.net/dev
# weather information

Rails 6 API created using
 `rails new floodrunneratx_api --api  --database=postgresql`
