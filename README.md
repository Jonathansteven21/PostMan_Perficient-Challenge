# PostMan_Perficient-Challenge
BootCamp QA  Challenge Postman

## Challenge
Using the following API Definition: https://petstore.swagger.io/#/ to verify through tests by postman if the information was saved correctly

## Tutorial to run Postman

### 1. Install Node.js
Use versions greater than 16, preferably LTS versions

### 2. Install newman
```
npm install -g newman 
```
(Windows) Can also be installed with the executable ``` Install newman.bat ```

### 3. Install newman-reporter-htmlextra
```
npm install -g newman-reporter-htmlextra 
```
(Windows) Can also be installed with the executable ``` Install newman-reporter-htmlextra.bat ```

## Run the project by console command

### 1. Open the console in the folder where the file is located: ``` SwaggerPetstoreAPI.Boot-Camp.json ```

### 2. Enter the following command from there to run the report
```
newman run SwaggerPetstoreAPI.Boot-Camp.json -r htmlextra --reporter-htmlextra-browserTitle "SwaggerPetstoreAPI.Boot-Camp" --reporter-htmlextra-export ./SwaggerPetstoreAPI_Reports/SwaggerPetStoreAPI_Report.html
```

## Run the project by ``` .bat ``` executable

### 1. Open file ``` Executable.bat ```

## Tutorial to open the report

### 1. Open the folder created in the same location of the file ``` .json ``` named ``` SwaggerPetstoreAPI_Reports ```

### 2. Open file HTML ``` SwaggerPetStoreAPI_Report ``` in your browser


