# Raspberry-Pi-5-Waveshare-UPS-3S
Raspberry Pi 5 - GUI Battery Monitor for Waveshare UPS 3S

mkdir -p /home/pi/UPS/

    copy here UPS.py

mkdir -p /home/pi/.config/autostart
nano /home/pi/.config/autostart/UPS.desktop

    [Desktop Entry]
    Type=Application
    Name=UPS
    Exec=python3 /home/pi/UPS/UPS.py
    Icon=python3
    Terminal=true
    Categories=Utility;

chmod +x /home/pi/.config/autostart/UPS.desktop



## UPS.py
![immagine](https://github.com/user-attachments/assets/8abe3309-0420-4b2e-bba5-7f998f03d1b3)

Waveshare-UPS-3S
Uninterruptible Power Supply (UPS) Module, Supports charging And Power output at the same time, 3S & 5V 5A Output
3S indicates that powered by 3x 18650 Li batteries in series, the output range is about 9V~12.6V

Suitable for Raspberry Pi 5 or Pi 4B

![UPS-Module-3S-details-5](https://github.com/user-attachments/assets/814511a3-e416-4e03-a880-e0bd091f6d83)


![UPS-Module-3S-details-2-1](https://github.com/user-attachments/assets/0d272a04-2cd4-4704-a86b-93f40dc13d91)

SAFETY CAUTIONS

    Li-ion and Li-po batteries are quite unstable. They may cause fire, personal injury, or property damage, if they're not properly recharged or used.
    Do not reversely connect the polarities when recharging or discharging the battery. Do not use inferior charger/charging panel to recharge the battery.
    Do not mix use old batteries with new ones, avoid using batteries of different brands.
    When buying Lithium battery, should always make sure the battery specification is compatible with the expansion board. Choose batteries from formal manufacturer, and ensure the batteries will work stably and safely by aging test.
    Lithium batteries have limited cycle life, they will also deteriorate as time goes by. Should be replaced with new ones when the batteries reaching their max cycle life, or working over two years, whichever comes first.
    Should be placed carefully and properly, keep it away from inflammables and explosives articles, away from children, avoid any safety accident caused by careless storage.

![UPS-Module-3S-details-7](https://github.com/user-attachments/assets/e6310363-f96d-4183-a9ab-41e1d1fc40a8)


Features at a glance

    Adapting various interfaces via cables, easy to integrate into mobile robots or industrial control equipment
    I2C bus communication, monitoring the batteries voltage, current, power in real time
    Multi battery protection circuits: over charge/discharge protection, over current protection, short circuit protection, and reverse protection, along with the equalizing charge feature, more safe and stable
    Onboard 5V regulator, up to 5A continuous output current, more sufficient power source for Raspberry Pi and Jetson Nano
    Batteries warning indicators, easy to check if the battery is connected correctly
    Comes with online development resources and manual


![UPS-Module-3S-details-9](https://github.com/user-attachments/assets/bf80515f-0ef3-4d5b-bcf3-19d246b99c26)

Specifications
Output voltage: 	Batteries series voltage; 5V 5A; 3.3V 300mA
Control interface: 	I2C
Battery support: 	3 x 18650 Li batteries (in series, NOT included)
Charger: 	12.6V 2A
Dimensions: 	60 × 93mm
Mounting hole size: 	3.0mm



Adapting various interfaces via cables


![UPS-Module-3S-details-11](https://github.com/user-attachments/assets/65640932-3ff3-43e3-8139-60992fe42d31)


It is able to charge the batteries and provide power output at the same time from external power supply
Automatically switch over to batteries output if external power supply is unavailable, keeps the system running without any trouble

![UPS-Module-3S-details-inter](https://github.com/user-attachments/assets/90971504-3957-40ad-ac7a-69ca58e2aa81)


Real time monitoring the batteries voltage, current and power via I2C
for reference only, the Raspberry Pi 4B and the batteries are NOT included.


![UPS-Module-3S-details-15](https://github.com/user-attachments/assets/c1f14dfc-a5d3-4832-8732-ccc2618dd496)

Protection circuits for over charge/discharge, over current, short circuit, and reverse
along with the equalizing charge feature, more safe and stable

![UPS-Module-3S-details-intro](https://github.com/user-attachments/assets/f19c00d7-9845-4608-81b9-2b0566ddf23d)



Chips

    S-8254AA     Li battery protection
    SY8286       5V voltage regulator
    HY2213       Equalizing charge
    INA219       Voltage/current monitoring
    RT9193       3.3V voltage regulator
    NDC7002N     Voltage translator

Others

    AO4407A     Battery protection MOS tube
    Power port   12.6 2A power input
    Power output switch
    Batteries series power output
    5V power output     
    Reverse warning indicators
    Multi-functional expansion header
    I2C level selection
    3.3V (default) / 5V




Battery warning indicators: easy to check if the battery is connected correctly

