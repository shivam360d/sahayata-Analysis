# Sahayata Analysis-
Data Analysis project to gain insights of future prices of rice crop in North Indian wholesale markets.
Gathered data by scrapping open-source government website using Selenium scripts.
Government website from which the data for wholesale market prices is scrapped: https://fcainfoweb.nic.in/Reports/Report_Menu_Web.aspx.

### Data
>> Market rates data is gathered by scrapping the above mentioned website's resources. Other features of the data are: Rainfall, Inflation, Production, Export rate, MSP.

### nn.ipynb:
>>In this file, the prepared data is transformed and scaled to be used for model input
>>I have created a ANN model for the priction of the crop price.

### lstmWeeklyData.ipynb:
>>In this file, I have transformed the data and made it suitable for a time series model.
>>Created the time series model using LSTM. Plotted its performance using Matplotlib in the same code.
>>persistence_model file is the maximum extent of accuracy the model can touch.

### Tablue
>>This folder contains the tablue charts created for analyzing relationships between different features of the data.
