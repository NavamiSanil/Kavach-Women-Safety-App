1. Introduction
1.1 Description
Kavach is a cutting-edge mobile application designed specifically to address women's safety concerns. The app integrates real-time safety features like Emergency SOS, Hidden Camera Detection, and a Siren Alarm, complemented by tools like Safety Tips, Emergency Speed Dial, and Emergency Contact Management.

1.2 Purpose
The purpose of this app is to enhance safety and empower women by providing a reliable lifeline in emergencies and offering precautionary tools for day-to-day use. Kavach aims to reduce response times during crises, increase awareness, and create a safer environment for women.
1.3 Intended Audience and Reading Suggestions
This report is intended for:
•	Developers: To understand the technical details and features.
•	Testers: To create test cases based on system features.
•	End-users: To explore app functionalities and usability.
•	Managers: To monitor project progress and ensure compliance with requirements.

1.4 Product Scope
Kavach offers a robust set of features:
•	Emergency SOS alerts that share real-time GPS locations with trusted contacts.
•	Tools for detecting hidden surveillance cameras.
•	A customizable siren alarm for immediate public attention.
•	Safety tips for personal security awareness.
•	Instant access to emergency numbers like police, ambulance, and women’s protection helplines.

1.5 References
•	Android Developer Documentation
•	Magnetometer Sensor API Documentation
•	News API Documentation
________________________________________

2. Overall Description
2.1 Product Perspective
Kavach integrates multiple safety and empowerment features into a single mobile application. It leverages smartphone capabilities like GPS, accelerometer, and magnetometer sensors to deliver reliable and efficient responses in emergencies.

2.2 Product Functions
The core functionalities include:
•	Emergency SOS with GPS tracking.
•	Hidden Camera Detection using sensors.
•	Customizable emergency contacts for alerts.
•	Direct dialing to emergency numbers.
•	Daily safety tips for users.

2.3 User Classes and Characteristics
1.	Primary Users: Women (ages 13–60) who need a simple and intuitive safety app.
2.	Secondary Users: Authorities and family members who receive alerts.
3.	NGOs: Collaborate for content related to women’s rights and safety.

2.4 Operating Environment
•	Android: Versions 8.0 (Oreo) and above.
•	Hardware Requirements: GPS, magnetometer, accelerometer, and internet connection.

2.5 Design and Implementation Constraints
•	Continuous GPS tracking may drain battery life.
•	Some features require specific sensors (e.g., magnetometer).

2.6 User Documentation
The app includes an interactive tutorial and a detailed help section for setting up and using features.

2.7 Assumptions and Dependencies
•	Users have smartphones with basic hardware requirements.
•	An active internet connection for emergency speed dial and SOS updates.
________________________________________

3. System Features
3.1 Emergency SOS
Description: Sends the user’s real-time location to predefined contacts via SMS or in-app notifications.
Priority: High.

Stimulus/Response Sequence:
•	Stimulus: User presses the SOS button.
•	Response: App sends an alert with location data and triggers a loud alarm.
________________________________________

3.5 Safety Tips
Description: Displays daily personal safety guidelines for users.
Priority: Medium.
Stimulus/Response Sequence:
•	Stimulus: User selects "Safety Tips".
•	Response: App displays curated tips, such as staying vigilant in public spaces or sharing trip details with trusted contacts.
________________________________________

3.6 Emergency Speed Dial
Description: Provides one-tap access to dial emergency services like police, ambulance, or women’s protection helplines.
Priority: High.
Stimulus/Response Sequence:
•	Stimulus: User taps an emergency speed dial button.
•	Response: App directly dials the selected service.
________________________________________
3.7 Emergency Contact Management
Description: Allows users to add, update, or delete emergency contacts.
Priority: High.
Stimulus/Response Sequence:
•	Stimulus: User edits the contact list in settings.
•	Response: App saves and verifies the changes.
________________________________________

4. Nonfunctional Requirements
4.1 Performance Requirements
•	SOS alerts must send within 3 seconds.
•	The app should work efficiently on low data networks.
________________________________________

5. Future Enhancements
1.	Integration with Wearable Devices.
2.	AI-powered Risk Detection.
3.	Multi-language Support for better accessibility.
________________________________________
6. Design of Mobile App
•	Splash Screen: Welcomes users and displays the app logo.
•	Main Dashboard: Includes SOS, Hidden Camera Detection, Siren Alarm, and Safety Tips.
•	Settings: For managing emergency contacts, language preferences, and app tutorials.
