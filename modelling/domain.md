---
title: Prova titolo TITOLO
---

# What is this?
This document shows an overview of what is the application's reference domain and what are the sub-domains. It is useful in the very first steps (*and also in the following ones*) to identify wich are the area of interest, this enables the identification of distinct areas of functionality within the application.

The main domain is: **Energy Optimization**

The identified (*macro*) sub-domains are:
- [⚡ Energy Production](#-energy-production)
- [🏡​ Home Energy](#-home-energy)
- [📈​ Forecast](#-forecast)
- [⛏️​ Mining](#-mining)

## ⚡ Energy Production
This subdomain takes care of the aspects of energy production, whether from a photovoltaic, wind or hydroelectric plant. Here elements are taken into consideration that concern the quantity of energy produced, the state of the batteries (if there are any), the power of the plant, total energy supplied, etc.

### Needs
- For *Off-Grid systems*, the cells must be able to reach the balancing point to ensure a long battery life.
- For *On-Grid systems*, the presence of the national electrical grid is required for the system to works correctly.

### Processes
- The battery is charged until the input current drops below a certain value (for example 1A).
- The battery is discharged until a safety threshold is reached, usually up to 20% of the battery capacity.
- When the battery reaches 100% of the SoC level the battery is charged.

## 🏡​ Home Energy
This subdomain groups together all the elements concerning domestic loads, their operating dynamics and their priorities.

### Needs
- Turn on appliances, even energy-hungry ones, when necessary (washing machine, dishwasher, hot water boiler).
- Reduce electricity waste.
- Reduce electricity costs.
- Heating the home.

### Processes
- Enable electric vehicle charging when the vehicle battery is at 20%.
- Turn on a stove when the temperature drops below 18 degrees.
- Turn on the washing machine every 2 days.

## 📈​ Forecast
This subdomain is concerned with providing forecasts, both for energy production forecasts and for energy usage forecasts by loads.

### Needs
- Predicting the amount of energy that will be produced tomorrow (or next hour).
- Predict how much energy the home will require tomorrow (or next hour).

### Processes
- Use forecasted weather conditions, the characteristics of the power plant and its geographic location to predict the energy that will be produced.
- Analyze historical consumption to predict future consumption of the home

## ⛏️​ Mining
This subdomain is intended to group together the elements that concern mining process and its dynamics.

### Needs
- Maintain a constant hashrate.
- Cool the miner due to high temperatures.
- Stable and constant internet connection.
- Track the profitability.

### Processes
- To be completed...

