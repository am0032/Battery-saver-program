# Battery-saver-program
This program helps save the battery lifespan of devices  via a software and hardware solution.


This application is designed to enhance the battery lifespan of devices through a  software and hardware approach.

The lithium batteries commonly found in mobile devices exhibit optimal performance when charged and discharged within a specific range, typically between 20% and 80%. Charging and discharging to the extremes (0% to 100%) can negatively impact battery longevity. Unfortunately, many manufacturers neglect to incorporate this optimization feature into their devices, and third-party software solutions often struggle to implement it effectively.

This program provides a solution by integrating both software and hardware components. It introduces an external hardware module, utilizing an Arduino and a relay system, which can be installed between the power source and the device. This hardware component acts as a safeguard by interrupting the power supply when the charging level reaches a user-defined upper limit. Additionally, it initiates the charging process when the battery level drops to a lower threshold set by the user. This proactive control mechanism ensures that the battery operates within the recommended range, ultimately extending its lifespan.

Requirements:
Software:
1)Python installed(download and install from official site)
2)Pyserial installed (pip install pyserial If pip is installed)

Hardware:
1)Arduino
2)Relay module
