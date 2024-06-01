## Minefield Evacuation Proximity Drift Safety Alert

**Abstract** - Safety remains of utmost importance across all industries, with mining particularly prioritizing the well-being of all involved with the mining sector placing particular emphasis on the well-being of its workforce. The unique and hazardous conditions within mining operations present significant challenges in real-time monitoring and data collection at various points. This paper presents the development of a monitoring system aimed at enhancing safety in coal mines, utilizing AM2560 Rev3 and NRF2401 technologies. Precisely tracking miners' locations e u-blox NEO-M8N GPS module. Additionally, it utilizes the Haversine distance formula to calculate the shortest distance between two points on the sphere's surface, based on their respective latitudes and longitudes. Moreover, the system integrates the ESP32 Wi-Fi module for high-speed, low-power wireless communication, ensuring secure data transfer and continuously monitoring environmental conditions are critical tasks that demand immediate attention from coal mining enterprises. Within the labourers area of the mine, air contamination primarily arises from emissions of particulate matter and gases such as Sulphur dioxide (SO2), Nitrogen dioxide (NO2), and Carbon monoxide (CO). To address this issue, two smoke sensors are employed to monitor different smoke levels in the mine, while semiconductor gas sensors monitor the concentration levels of unsafe gases. If any smoke sensor value exceeds the threshold range, the microcontroller triggers an alert to notify personnel. The system's sophistication extends to result analysis, as demonstrated by its comprehensive control panel functionality.

**Introduction** - The mining industry is inherently hazardous, with various risks to miners' safety, including collapses, explosions, and exposure to toxic gases. In response to these risks, mining companies continuously seek innovative solutions to enhance safety measures and mitigate potential hazards. This paper presents the design and implementation of a comprehensive safety monitoring system specifically tailored for coal mines, addressing the unique challenges associated with underground mining operations.

**System Architecture** - The safety monitoring system comprises several key components, including sensor nodes, a central processing unit, wireless communication modules, and a centralized monitoring dashboard. Sensor nodes are strategically deployed throughout the mine to monitor environmental parameters such as air quality, temperature, humidity, and gas concentrations. These nodes transmit real-time data to the central processing unit, which processes the information and triggers alerts or alarms in case of abnormal conditions. Wireless communication modules facilitate seamless data transmission between sensor nodes and the central processing unit, enabling rapid response to safety incidents. The centralized monitoring dashboard provides mine operators and safety personnel with a comprehensive overview of the mine's safety status, including live sensor data, historical trends, and actionable insights.

![image](https://github.com/Aaditiiipatil/Safe-Drift-Proximity/assets/143029253/74e1b8fa-6ea4-4e3d-b23d-8d176c918ca6)


**Sensor Node Design** - Each sensor node is equipped with an array of sensors designed to detect specific environmental parameters relevant to mine safety. For example, gas sensors detect the presence of harmful gases such as carbon monoxide (CO), methane (CH4), and hydrogen sulfide (H2S), while smoke sensors detect the onset of fires or smoldering incidents. Additionally, environmental sensors measure ambient conditions such as temperature, humidity, and air pressure, providing valuable context for assessing safety risks. Sensor nodes are ruggedized and intrinsically safe, ensuring reliable operation in harsh mining environments.

![image](https://github.com/Aaditiiipatil/Safe-Drift-Proximity/assets/143029253/2f761acf-b6c7-45ee-a292-a686ab9a5c1d)

![image](https://github.com/Aaditiiipatil/Safe-Drift-Proximity/assets/143029253/c424a3fe-aa64-42cf-8b46-561af2b041e9)

**Data Analysis and Alerting** - The central processing unit continuously monitors incoming sensor data, applying machine learning algorithms to identify patterns indicative of potential safety hazards. For example, anomaly detection algorithms can flag sudden increases in gas concentrations or temperature spikes that may indicate equipment malfunction or environmental hazards. When abnormal conditions are detected, the system triggers appropriate alerts, notifying mine personnel and initiating predefined safety protocols. Alert notifications are sent via various communication channels, including SMS, email, and audible alarms, ensuring timely response to safety incidents.

**Conclusion** - The safety monitoring system presented in this paper represents a significant advancement in mine safety technology, offering real-time monitoring, predictive analytics, and proactive alerting capabilities to enhance worker safety in coal mines. By leveraging state-of-the-art sensor technology, wireless communication protocols, and data analysis techniques, mining companies can mitigate safety risks, improve emergency response times, and ensure the well-being of their workforce in hazardous mining environments.

**Screenshots** - 
![image](https://github.com/Aaditiiipatil/Safe-Drift-Proximity/assets/143029253/b4cb38cf-7789-4e68-8056-62abc42395aa)

![image](https://github.com/Aaditiiipatil/Safe-Drift-Proximity/assets/143029253/06c3eb13-b5d5-4c5e-a34d-1e17246fffaa)

![image](https://github.com/Aaditiiipatil/Safe-Drift-Proximity/assets/143029253/a8d2cfa7-6198-4cc1-a61e-a2d85d95f929)

![image](https://github.com/Aaditiiipatil/Safe-Drift-Proximity/assets/143029253/1b702dac-9368-4011-8c97-f5cb2c285ae1)

![image](https://github.com/Aaditiiipatil/Safe-Drift-Proximity/assets/143029253/44697d3e-3952-419d-a0ae-b35983424e04)

![image](https://github.com/Aaditiiipatil/Safe-Drift-Proximity/assets/143029253/885bba2e-ac7c-46a6-bb83-010e34410eba)

![image](https://github.com/Aaditiiipatil/Safe-Drift-Proximity/assets/143029253/6e2ad49f-6b0e-4501-802b-c0927f5d36df)

