# Fall-Detection-System-With-Simulation-MATLAB
A MATLAB-based fall detection and emergency alerting system. Simulates real-time fall monitoring algorithms and integrates with the Twilio API to automatically send SMS notifications to designated emergency contacts.

---

## Key Features

* **Real-Time Motion Tracking:** Continuous monitoring of real-time accelerometer and gyroscope data to detect fall events using custom threshold algorithms.
* **Instant Emergency SMS Alerts:** Automatic dispatch of SMS alerts via Twilio upon fall detection, complete with a direct Google Maps link to the user's location.
* **Interactive MATLAB GUI:** Built-in graphical user interface to easily trigger or stop monitoring while visualizing real-time sensor streams.

---

## Prerequisites & Requirements

### Software Dependencies
* MATLAB (configured for Mobile Sensor Connectivity)
* MATLAB Mobile Application (installed on target mobile device)
* Twilio Account (for automated SMS gateway integration)

### Hardware Dependencies
* Mobile device equipped with functioning Accelerometer, Gyroscope, and GPS hardware sensors.

---

## System Configuration & Thresholds

### Fall Detection Criteria
The algorithm flags a fall event when motion metrics exceed these specific limits (configurable within `fallDetectionSystem.m`):
* **Acceleration Threshold:** $19.6 \text{ m/s}^2$ (approx. $2g$)
* **Gyroscope Threshold:** $100^\circ/\text{s}$

### SMS Gateway Requirements
Emergency messaging relies on the Twilio API. Ensure active GPS access on your mobile device to ensure precise coordinate generation in the broadcasted link.

---

## Setup & Installation

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/Dhorajiya-Kenil/Fall-Detection-System-With-Simulation-MATLAB/tree/main])

## Limitations

* The system depends on accurate sensor data from the mobile device, and poor sensor quality or lack of GPS signal might affect its performance.
* The fall detection logic is based on simple thresholding; more advanced algorithms can be implemented for improved accuracy.

---

## Documentation

For detailed information on system architecture, V-Model XT methodology, UML diagrams, and STAMP analysis, check out the [Project Report](https://github.com/Dhorajiya-Kenil/Fall-Detection-System-With-Simulation-MATLAB/blob/main/Documentation.pdf).


---

## License & Contribution

* **License:** This project is licensed under the MIT License. See the [LICENSE](https://github.com/Dhorajiya-Kenil/Fall-Detection-System-With-Simulation-MATLAB/blob/main/LICENSE). file for more details.
* **Contribution:** Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## Contact

For any inquiries, please reach out to: **dhorajiyakenil@gmail.com**
