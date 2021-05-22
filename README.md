# CoWin Slot Checker
CoWin Slot Checker is an Android app designed to check Covid-19 Vaccine availabity on https://cowin.gov.in website - hosted, managed and updated by Government of India.Features and Limitations of the same is mentioned below. Source code is not shared here at the moment, as there is a risk of missuse.

## Features
- It starts a foreground service which will be operational even if you are not on the app or the phone is in sleep mode.
- Check Status / Details will be visible in a undestroyable Notification.
- Time interval can be set for Automatic slot checking
- The slot finding operation can be filterd by Minimum age (18 or 45)
- Can set minimum number of dose(s) to find the availability
- Most Importent filter is PIN code and District. PIN code or District code must be mentined.
- For District code, A district code finder feature is also included.
- If no Filters set, the app will run with it's won default filteres.
- Wenever it finds a slot. it will trigger a loude SIREN.

## Limitations
- Minimum Time interval limit is 5 Miniuts.
- This App is build for Android 8(O) and above.
- **The Big Limitation,**  As Android 8 and above has it's self power-saving feature, due to that it makes the service temporarily inactive while the screen of the phone goes off and not connected to charger.
- To overcome the above issue, someone can keep the screen on by doing stuffs on the phone (Which is Impractical) or the best  solution is to keep the phone connected to a charger.
