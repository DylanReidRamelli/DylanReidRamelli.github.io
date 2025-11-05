---
date: '2025-11-01'
draft: true
title: 'Turning Paragliding pilots into a Mobile Atmospheric Sensor Network'
categories: [Apps]
---

### Overview

Paragliding is a popular activity across the world and particularly in Switzerland, where thousands of flights are logged each year — from short, recreational glides to extended cross-country (XC) journeys. For example, during summer alone, XC contests regularly log over 150 flights. These pilots naturally cover a wide range of altitudes and geographical areas, especially in and around the Alps.

Paragliding pilots typically carry a set of instruments to monitor flight parameters such as altitude, vertical speed, and GPS location. A core instrument is the **variometer**, which audibly indicates whether a pilot is climbing or sinking. Most pilots also carry smartphones or safety trackers, often used for flight tracking (e.g. XContest).

This natural, widespread presence of equipped pilots opens the door to a novel concept: **using paragliders as distributed, low-altitude atmospheric sensors**.

### Concept

By equipping paragliding pilots with additional sensors — such as thermometers, humidity sensors, and barometers — we can capture high-resolution, real-time atmospheric data at low to mid altitudes (roughly from ground level up to 1500–2000m AGL). In essence, pilots would function similarly to **mobile, human-launched radiosondes**.

This data could be highly valuable for:

- **Improving local weather forecasting models**
    
- **Enhancing thermal prediction for free flight**
    
- **Studying microclimates and alpine meteorology**
    
- **Contributing to long-term climate research**
    
- **Maybe Filling  gap in low-altitude atmospheric data**
    

### Key Requirements

- **Ease of Use**: Data collection must be seamless and non-intrusive for pilots.
    
- **Reliability**: Sensor accuracy and data quality are crucial.
    
- **Scalability**: The system should work across many pilots without requiring complex setup.
    

---

## Implementation Options

### Option 1: Embedded Device with Local Storage

Design a self-contained sensor device that pilots carry during flights. It records data locally and is retrieved after a flying season or after each flight. Pros: simplicity and no need for real-time transmission. Cons: delayed data access and possible data loss.

### Option 2: App + Embedded Sensor System

Develop a mobile app that connects to an external sensor module. The app handles transmission of data to a central server. The sensor could be an off-the-shelf product or custom-made for this project. This balances real-time access with broader sensing capabilities.

### Option 3: Smartphone-Only (Limited)

Use only a smartphone to collect and transmit data. While convenient (since every pilot probably already has one), phones typically lack key sensors such as external temperature and humidity, limiting the usefulness of this approach unless paired with external devices.

---

## Final Thoughts

The most practical path forward seems to be **a hybrid system**: using smartphones for communication and positioning, paired with lightweight, external sensor modules for environmental data collection. These modules could either leverage existing hardware or be custom-designed for pilot-specific use.

By crowdsourcing environmental sensing through the paragliding community, this project could create a unique and rich atmospheric dataset — gathered not by expensive balloons or aircraft, but by everyday adventurers already in the sky.



### Acquired data list:
- Time
- Latitude
- Longitude
- Altitude
- Speed
- g-force
- Temperature
- Humidity
- ...



