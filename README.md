# Diashield

To develop a context-sensing application like Project 1 using the Health-Dev framework, you should provide the following specifications:

Sensor specifications:
Types of sensors (e.g. ECG, temperature, accelerometer)
Sampling frequencies for each sensor
Sensor platform (e.g. TelosB, Shimmer)
Signal processing algorithms to run on sensor data (e.g. peak detection, FFT)
Execution sequence of algorithms
Communication protocol (Bluetooth or ZigBee)
Data to be transmitted to smartphone

Network specifications:
Network topology
Routing information
Radio duty cycling parameters for energy management

Smartphone specifications:
UI elements (buttons, text views, graphs)
Sensor data to display
Algorithms to run on received sensor data
Control commands to send to sensors


Overall system requirements:
Energy consumption limits
Reliability/packet error rate requirements

Providing these high-level specifications to Health-Dev would allow it to automatically generate the sensor and smartphone code for your context-sensing application, without requiring in-depth programming knowledge.

Using the bHealthy application suite, you could provide feedback and improve context sensing in the following ways:

Use bHealthy's physiological signal monitoring (ECG, EEG, accelerometer) to collect more comprehensive health data beyond just symptoms.
Leverage bHealthy's suite of assessment applications to detect the user's mental and physical state. This provides additional context beyond self-reported symptoms.
Use bHealthy's suggestion module to recommend wellness activities to the user based on their physiological and mental state.
Track the user's performance and engagement with the suggested wellness activities over time.
Generate wellness reports for the user showing trends in their physiological data, mental state assessments, symptom reports, and activity engagement.
Use machine learning techniques to analyze the comprehensive longitudinal data collected to generate a personalized model of the user's health patterns and responses to interventions.
Provide personalized feedback and suggestions to the user based on their evolving health model.
Continuously refine the user model as more data is collected, creating a feedback loop of improved context sensing and more targeted interventions.

This approach would provide richer context sensing, actionable feedback to users, and enable development of personalized health models - going beyond just storing symptom data locally.

After completing Project 1 and reading the papers, my view of mobile computing has expanded beyond just app development. I now see mobile computing as encompassing:


Sensor networks and body sensor networks for collecting contextual and physiological data
Energy-efficient hardware and software design for resource-constrained mobile devices
Wireless communication protocols optimized for mobile/wearable scenarios
Context-aware and adaptive systems that respond to user state and environment
Novel interaction paradigms suited for mobile/wearable form factors
Privacy and security considerations for sensitive mobile data
Integration of mobile devices with cloud computing and big data analytics
Model-driven development approaches to abstract hardware/software complexities
Physiological signal processing and health monitoring algorithms
