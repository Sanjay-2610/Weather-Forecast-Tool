# Weather-Forecast-Tool
This project is done for the Microsoft's Fastest Coder Hackathon for the Problem statement Python - Weather Forecast Tool in Command Line

**NOTE** - Enter your API Key of OpenWeather in the Line 7 of weather.py file
## >_ INTRODUCTION
- Displays the weather forecast using Open Weather API
- Can be used in command line
- Gets the input from the user as
   - City name
   - Latitude and Longitude
   - Automated using Public IP Address
- Gets the input as Parse(switches)
- Checks for errors and returns appropriate exceptions

## >_ USAGE
- Finds weather using city name
```bash
reaper@kali[~/weather-tool]$ python weather.py chennai
 ```

- [ `-lat -long` ] Finds the weather latitude and longitude
```bash
reaper@kali[~/weather-tool]$ python weather.py chennai -lat 65.876 -long 76.865
```

- [ `no-arguments` ]Finds the weather using Automated IP Address
```bash
reaper@kali[~/weather-tool]$ python weather.py 
```

- [ `-v -verbose` ]Finds the weather using verbose mode
```bash
reaper@kali[~/weather-tool]$ python weather.py chennai -v 
```

- [ `-h --help` ]Help Menu
```bash
reaper@kali[~/weather-tool]$ python weather.py -h
```
- [ `-lat` or `-long` ] Automates if there is no arguments given or not valid arguments
```bash
reaper@kali[~/weather-tool]$ python weather.py -lat 65.876
```
```bash
reaper@kali[~/weather-tool]$ python weather.py -long 76.865
```
## >_ARCHITECTURE 
![Architecture](https://github.com/Sanjay-2610/Weather-Forecast-Tool/assets/91368803/7300a3a5-0814-45d6-9570-2225d2b19d6d)

## >_ SCREENSHOTS
### USING CITY NAME
![City](https://github.com/Harishspice/Microsoft-Git-Copilot/assets/117935868/5e350eec-b2fc-46f8-afa3-0c6359265c16)

### IN VERBOSE MODE 
![Verbose](https://github.com/Harishspice/Microsoft-Git-Copilot/assets/117935868/cb279cc1-0f3d-4fbe-95c9-e81c6550497a)

### IN AUTOMATED MODE
![Automated](https://github.com/Harishspice/Microsoft-Git-Copilot/assets/117935868/715be4f8-188e-4207-9286-8f8bbb443024)

### HELP MENU
![Help](https://github.com/Harishspice/Microsoft-Git-Copilot/assets/117935868/638e2878-f035-4a05-a502-b4a91e6b9125)

### WITH NOT SUFFICIENT DATA
![not sufficient data](https://github.com/Sanjay-2610/Weather-Forecast-Tool/assets/91368803/9929cac6-de2e-42d0-a70e-cbe6220cf97b)

## PREREQUISITIES
They will be using the following libraries
```bash
pip install requests
pip install argparse
pip install termcolor
```
