# Aegis-UI

The public user interface prototype for **Aegis: A Context-Aware Safety App**, developed as a Final Year Project.

This repository contains the HTML-based design mock-up used to demonstrate the application's user interface and user experience. The production application, backend services, and monitoring algorithms remain private and are not included in this repository.

**Live Demo:** https://aegis-design.vercel.app

---

## Overview

Personal safety applications have become increasingly common for individuals who travel alone, live independently, or wish to stay connected with family members and trusted contacts. However, many existing solutions primarily focus on location sharing and basic geofencing, requiring users or guardians to manually monitor locations and status updates.

Aegis aims to address these limitations by introducing a context-aware approach to personal safety. Instead of relying solely on reactive emergency actions, the application uses user-defined behavioural baselines and contextual information to identify unusual situations proactively.

The system is designed to understand a user's expected routines, schedules, locations, and behaviours, allowing it to recognise anomalies and notify trusted guardians when necessary.

---

## Key Features

### Context-Aware Monitoring

Aegis analyses user-defined behavioural baselines and contextual information such as frequently visited locations, daily schedules, curfews, movement patterns, and device status indicators. By comparing real-time observations against these expected behaviours, the system can identify anomalies and generate safety alerts when unusual situations are detected.

### Guardian-Based Safety Network

Aegis enables users to connect with trusted guardians who can receive safety notifications, view shared locations, request user check-ins, and monitor safety-related events. This allows guardians to remain informed of a user's wellbeing without requiring continuous manual observation.

### Emergency SOS System

The application provides multiple methods of requesting assistance, including manual SOS activation and voice-triggered emergency alerts using custom user-defined phrases. These capabilities are designed to support both direct and discreet emergency activation when conventional interaction with the application may not be possible.

### Activity History

Aegis maintains a historical record of safety-related events, including geofence transitions, location-based activities, check-in responses, and generated alerts. This information enables users and guardians to review past events and better understand behavioural trends over time.

### Safety Map

The application incorporates a shared safety map that allows users and guardians to create and view safety reports, recommendations, and location-based safety pins. This feature promotes situational awareness by providing relevant information about locations that may require additional caution or attention.

### IoT Device Integration

Aegis extends traditional mobile safety monitoring through integration with Internet of Things (IoT) devices. Linked devices can be associated with user-defined routines and monitored for expected activity patterns. Deviations from these routines may be incorporated into the application's contextual reasoning process, providing additional insight into a user's wellbeing and daily activities.

### Automated Check-Ins and Notifications

The application supports automated check-in requests and real-time notifications to facilitate proactive monitoring. Guardians may request check-ins from monitored users, while the system can deliver alerts and status updates when behavioural anomalies or safety-related events are detected.

---

## Technology Stack

### UI Prototype

* HTML5
* CSS3
* JavaScript
* Material Design Components

### Production Application

* Kotlin (Android)
* Supabase
* Firebase Cloud Messaging
* Google Maps and Places
* Vosk Speech Recognition
* Tuya IoT Platform
* Android Geofencing
  
---

## Repository Scope

This repository contains only the user interface prototype and design implementation.

The following components are **not included**:

* Mobile application source code
* Backend services
* Database schemas
* Contextual reasoning engine
* Monitoring algorithms
* Authentication implementation
* Production APIs

---

## Academic Context

This project was developed as part of a Final Year Project focused on exploring how context-awareness, behavioural baselines, and automated monitoring can improve personal safety applications while maintaining user privacy through local processing.

The work investigates the use of contextual reasoning to move beyond traditional location-sharing systems and towards proactive safety monitoring.

---

## Disclaimer

This repository is provided for educational and portfolio purposes only. The interfaces presented here demonstrate the visual design and intended functionality of the Aegis project and do not represent the complete production system.
