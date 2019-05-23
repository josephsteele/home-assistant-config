#**Home Assistant Config**

**Front End**
![alt text](https://github.com/josephsteele/home-assistant-config/blob/master/Front%20End%20Snapshot.PNG)

**Components**  
* Konnected - 5 IR sensors, door sensor, siren  
* Alarm Panel - Day and nighttime alarm settings  
* Hive thermostat - heating control  
* Darksky Weather  
* Tesla - battery charge, plugged in state, climate, locked/unlocked, etc.  
* Waze travel time - gives the time for commute to work based on current traffic  
* Person and device tracker - who is at home tracked using wifi router connection and bluetooth pi detection 
* Coinmarketcap - current bitcoin price  
* Timezone - time in other country of interest 
* Telegram and lannouncer for notifications

**Automations**
* Automatic Arming and disarming of house alarm at night  
* Automatic Disarming of house alarm when arriving home
* Silent alarm (notification only) for when devices not detected at home but movement detected (silent to avoid false alarms e.g. battery died)
* Siren and notification if alarm tripped  
* Hive Heating on and off using presence detection  
* Notification if bad traffic on commute via waze    
* Notification if Tesla in not plugged in by 21:30 and the battery charge is below 60% 
* Notification when home assistant system boots


