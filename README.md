Automated Irrigation System with HMI Interface

This repository contains the code and documentation for an automatic irrigation system equipped with a Human-Machine Interface (HMI), developed using Siemens TIA Portal v18. Designed to efficiently manage watering for two distinct plant lines in a garden, the system utilizes a combination of float switches and moisture sensors to tailor watering schedules to the specific requirements of each plant type.

System Description:

In the garden, two different plant lines coexist, each with unique water demands. To ensure optimal growth conditions, water provision is customized for each plant type. The system employs two different methods to address the watering needs of the plants:

1. Float Switch Control: 
   - The first plant line requires precise control over water levels in the pool. To achieve this, float switches are employed to regulate water levels between a designated minimum and maximum threshold.

2. Moisture Sensor Integration:
   - For the second plant line, moisture sensors are utilized to determine soil moisture levels. Watering is triggered based on the detected moisture levels, ensuring that the plants receive adequate hydration tailored to their specific needs.

List of Inputs:
- I1: Minimum water level threshold.
- I2: Auto on/off switch for automated watering.
- I3: Moisture sensor input for monitoring soil moisture levels.
- I4: Maximum water level threshold.

List of Outputs:
- Q1: Water pump control for plant line A.
- Q2: Water pump control for plant line B.

This system not only streamlines the watering process but also promotes water conservation by delivering water precisely where and when it's needed. The integration of an HMI interface enhances user interaction and provides real-time monitoring and control capabilities for efficient garden management.

Feel free to explore the code and documentation provided in this repository to learn more about the implementation and functionality of this automatic irrigation system with HMI interface developed using Siemens TIA Portal v18. Your feedback and contributions are highly appreciated!
