# Climate-Data-Scraping
## This is using data scraping skill to collect climate data from NOAA. After collecting yearly climate data from NOAA, I assigned the climate data to the nearest census based on census' center coordinates and the coordinates of the weather stations.

## Steps to collect climate data from NOAA and assign the climate record of the weather stations to the nearest census
### Step 1. Load the census geometry dataset:
<img src="https://github.com/Wenhuan2516/Climate-Data-Scraping/blob/main/step1.png" alt="step" title="step">

### Step 2. find the centriod of each census:
<img src="https://github.com/Wenhuan2516/Climate-Data-Scraping/blob/main/step2.png" alt="step" title="step">

### Step 3. scraping the climate data from NOAA:
<img src="https://github.com/Wenhuan2516/Climate-Data-Scraping/blob/main/step3.png" alt="step" title="step">

### Step 4. create a funtion to clear the NONE values:
<img src="https://github.com/Wenhuan2516/Climate-Data-Scraping/blob/main/step4.png" alt="step" title="step">

### Step 5. change the FRSHTT column to be Fog, Rain, Snow, Hail, Thunder, Tornado:
<img src="https://github.com/Wenhuan2516/Climate-Data-Scraping/blob/main/step5.png" alt="step" title="step">

### Step 6. calculate the relative humidity and heat index based on temperature and dew point and their definitions:
<img src="https://github.com/Wenhuan2516/Climate-Data-Scraping/blob/main/step7.png" alt="step" title="step">

### Step 7. create a function to find the nearest weather station for each census tract:
<img src="https://github.com/Wenhuan2516/Climate-Data-Scraping/blob/main/step8.png" alt="step" title="step">

### Step 8. the final dataset:
<img src="https://github.com/Wenhuan2516/Climate-Data-Scraping/blob/main/step9.png" alt="step" title="step">
