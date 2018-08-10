## Data Available From USPs

This document outlines the data that will become available from the Urban Sharing Platforms in the lifetime of the Sharing Cities Task 2.4 - The Dashboard (aka service layer). It first focuses on the data available through **Sharing Cities Specific Services**. It then focuses on data avaialble from other sources (e.g. datastores) in the relevant cities.

More details relating to the API's will be added when available. 

---


### Lisbon

For more information on anticipated dates and the data available, see the [Lisbon USP Folder](https://drive.google.com/drive/folders/0B-BYSa5GDvhZekdhZFJYR05iVDQ). This is managed by Telma mota. The spreadsheet in this folder has more information on availability dates. 

#### `Digital Social Market - UNCERTAIN`

- We might be recieving data that relate to the Digital Social Market in Lisbon and we may be able to receive aggregate data relating to:
    - Energy Consumption (per group of people in kWh) (get 15 minutely data once a month)
    - Personal Energy Production (per group of people in kWh) (get 15 minutely data once a month)
    - Run and e-bike Distance per person in Km (per 0.5 day likely once a month)
    - Steps per person	Nbr of steps (real time)
    - EV Charging energy per person	kWh

#### `General Services - MORE CERTAIN`

- `Energy consumption and production` (kWh) for two public buildings and potentially three private buildings. The private building data might be aggregated.
- `Energy management data` from the City Hall 'virtual building' in Lisbon and a series of 'Pilot area buildings'. This includes data from the:
    - HVAC system
    - EV Charging (near the building)
    - Photo Voltaics (as shown in the previous major bullet)
    - Other energy consimption
    - Public lighting energy consumption (kWh/section)
- `Ebike docking station` data
    - Ebike docking station energy consumption
    - Ebike docking station status - free or charging (hourly data)
    - We could compare this to the energy generated by the building to see if it's sufficient to power the Ebikes. 
    - Potentially, the distance travelled on the ebikes. 
- `EV Car Charging Point` Data
    - Energy consumption of docks (kWh)
    - Charge level of docks
    - Max power and curren  of charging docks
    - State of charging station (charging / not / offline...)
    - Current energy costs (euros / kWh)
- `EV Car data` - __may be private__
    - Vehicle speed
        - Average
        - Instantaneous
    - Driving / Charging State
    - Location
    - Distance Covered
    - Emissions saved
- `Parking Sensor Data`
    - Parking sensor status (free / occupied)
    - Type of space (charging or just parking)
    - Should map and show timeseries (see Greenwich notes)
- `Lamp post sensor` data
    - NOx & No2, O3, CO, PM10, PM2.5, Temperature, Humidity, Atmospheric pressure
    - Should map and show timeseries when clicked on. 
### Greenwich

For more information on anticipated dates, see the [Greenwich USP plan](https://docs.google.com/spreadsheets/d/1mWTsh-IIZ8ZosO-Tm_hDV8RSGFfA8Br8RMQUUti-PEE/edit?ts=5b616ddb#gid=0).

- Kiwi Power (KP) `Plant room / estate level electricity consumption`
    - Could look into getting a floor plan of the estate. Should be mapped at least. Likely to require some custom visualisation. 
- KP `Dwelling level electricity consumption`
    - Could look into getting a floor plan of the estate. Should be mapped at least. Likely to require some custom visualisation. 
- KP `Dwelling level environmental condition (temp, humid)`
    - Could look into getting a floor plan of the estate. Should be mapped at least. Likely to require some custom visualisation. Could also use this to generate some details about the relationships between the previous two and the existing environment. 
- `Smart parking - aka Parking Sensor`
    - At least a map of where the parking spaces are with some sort of indicator of which ones are free and which ones are not. 
    - Potentially something that plots the number of free spaces through time.
    - Potentially something that predicts when it is least busy. 
- `Weather`
    - Need to check if this is easier to use than the data from another open source / free weather api. 
- `Wholesale Energy Prices`
    - Need to develop use case around this - any good ideas? Perhaps something like *its cheaper to charge an EV now people should plug in!*
- `Blue Point EV charging API`
    - At least a map of where the parking spaces are with some sort of indicator of which ones are free and which ones are not. 
    - A map that shows the state of charge of the vehicles in real time. Flagging which charger is freely available next (based on state of charge).
    - Potentially something that plots the number of free spaces through time.
    - Potentially something that predicts when it is least busy. 
- `eBike GPS`
    - These will be static data and are unlikely to change fequently. Current understanding is that they are likely to be updated every 6 months or so. Despite this, it might be useful to have the tracks on a map where possible. 
- `eLogistics impact`
    - These will be static data and are unlikely to change fequently. Current understanding is that they are likely to be updated every 6 months or so. We're in consultation with Greenwich about how to best use this information. 

### Milan

Awaiting feedback. 