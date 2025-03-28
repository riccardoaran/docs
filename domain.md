# What is this?
This document shows an overview of what is the application's reference domain and what are the sub-domains

The main domain is: **Energy Optimization**

The identified sub-domains are:
- [⚡ Energy Production](#energy-production)
- [🏡​ Home Energy](#home-energy)
- [📈​ Forecast](#forecast)
- [⛏️​ Mining](#mining)

## ⚡ Energy Production
This subdomain takes care of the aspects of energy production, whether from a photovoltaic, wind or hydroelectric plant. Here elements are taken into consideration that concern the quantity of energy produced, the state of the batteries (if there are any), the power of the plant, total energy supplied, etc.

### Needs
- For *Off-Grid systems*, the cells must be able to reach the balancing point to ensure a long battery life.
- For *On-Grid systems*, the presence of the national electrical grid is required for the system to works correctly.

### Processes
- The battery is charged until the input current drops below a certain value (for example 1A).
- The battery is discharged until a safety threshold is reached, usually up to 20% of the battery capacity.
- When the battery reaches 100% of the SoC level the battery is charged

## 🏡​ Home Energy
This subdomain groups together all the elements concerning domestic loads, their operating dynamics and their priorities.

### Needs
- Turn on appliances, even energy-hungry ones, when necessary (washing machine, dishwasher, hot water boiler)
- Reduce electricity waste
- Reduce electricity costs

### Processes
- To be completed...

## 📈​ Forecast
This subdomain is concerned with providing forecasts, both for energy production forecasts and for energy usage forecasts by loads.

### Needs
- To be completed...

### Processes
- To be completed...

## ⛏️​ Mining
This subdomain is intended to group together the elements that concern mining process and its dynamics.

### Needs
- Maintain a constant hashrate.
- Cool the miner due to high temperatures.
- Stable and constant internet connection

### Processes
- To be completed...

