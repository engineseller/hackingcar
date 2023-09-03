# HackingCar

HackingCar is a comprehensive collection of scripts designed to facilitate car research and potentially car hacking activities. This project aims to provide a valuable resource for individuals
interested in exploring the intricacies of automotive systems and uncovering vulnerabilities within them.

The scripts included in HackingCar cover various aspects of car research, providing users with a jump start in their exploration. These tools can assist researchers in analyzing different components
of vehicles, such as the infotainment system, electronic control units (ECUs), communication protocols, and more. By leveraging these scripts, users can gain insights into how cars operate, identify
potential security weaknesses, and contribute to improving the overall security of automotive systems.

HackingCar serves as a platform for knowledge sharing and collaboration among car enthusiasts, security researchers, and developers interested in the field of car hacking. It encourages users to
experiment responsibly and ethically by adhering to legal guidelines while conducting their research.

With its wide range of scripts and resources, HackingCar aims to foster innovation in the automotive industry by encouraging proactive identification and resolution of security issues. By providing an
accessible starting point for car research endeavors, this project contributes to enhancing the safety and security of modern vehicles.

## Run car_info.py

A start of a terminal dashboard.

Usage Example:  
`python car_info.py /dev/ttyUSB0`

## Run obd_info.py

Pulls All Responding OBD2 PIDS off of the car.

Usage Example:  
`python obd_info.py /dev/ttyUSB0`

Example Output:

```
[obd.decoders] Failed to parse ELM voltage
Supported commands
------------------
O2_S1_WR_CURRENT: -0.00390625 milliampere
WARMUPS_SINCE_DTC_CLEAR: 2 count
DISTANCE_SINCE_DTC_CLEAR: 124 kilometer
EVAP_VAPOR_PRESSURE: 89.5 pascal
BAROMETRIC_PRESSURE: 97 kilopascal
DTC_BAROMETRIC_PRESSURE: None
DTC_EVAP_VAPOR_PRESSURE: None
DTC_DISTANCE_SINCE_DTC_CLEAR: None
DTC_WARMUPS_SINCE_DTC_CLEAR: None
DTC_O2_S1_WR_CURRENT: None
STATUS_DRIVE_CYCLE: <obd.OBDResponse.Status instance at 0x7fa5b8a53488>
PIDS_C: 11111110110111000000110000000000
ABSOLUTE_LOAD: 26.6666666667 percent
CONTROL_MODULE_VOLTAGE: 13.968 volt
RELATIVE_THROTTLE_POS: 3.92156862745 percent
COMMANDED_EQUIV_RATIO: 0.999424 ratio
THROTTLE_POS_B: 12.5490196078 percent
AMBIANT_AIR_TEMP: 24 degC
ACCELERATOR_POS_D: 14.9019607843 percent
MONITOR_EVAP_150: Unknown : -1511.0 pascal [PASSED]
ACCELERATOR_POS_E: 14.9019607843 percent
THROTTLE_ACTUATOR: 4.3137254902 percent
MONITOR_PURGE_FLOW: Unknown : 32.5 pascal [PASSED]
TIME_SINCE_DTC_CLEARED: 167 minute
RUN_TIME_MIL: 0 minute
DISTANCE_W_MIL: 0 kilometer
PIDS_B: 10000000000001111111000000010101
MONITOR_MISFIRE_CYLINDER_4: Average misfire counts for last ten driving cycles : 0 count [PASSED]
Misfire counts for last/current driving cycles : 0 count [PASSED]
MONITOR_MISFIRE_CYLINDER_3: Average misfire counts for last ten driving cycles : 0 count [PASSED]
Misfire counts for last/current driving cycles : 0 count [PASSED]
MIDS_E: 00000000000000000000000000000001
MONITOR_MISFIRE_GENERAL: Misfire counts for last/current driving cycles : 0 count [PASSED]
MIDS_F: 11111000000000000000000000000000
MONITOR_MISFIRE_CYLINDER_2: Average misfire counts for last ten driving cycles : 0 count [PASSED]
Misfire counts for last/current driving cycles : 0 count [PASSED]
MONITOR_MISFIRE_CYLINDER_1: Average misfire counts for last ten driving cycles : 0 count [PASSED]
Misfire counts for last/current driving cycles : 0 count [PASSED]
MONITOR_O2_B1S2: Unknown : 8842 millivolt / second [PASSED]
Unknown : 0.0 millivolt [PASSED]
Unknown : 0.0546875 ratio [PASSED]
CATALYST_TEMP_B1S2: 408.4 degC
MIDS_A: 11000000000000000000000000000001
MONITOR_O2_B1S1: Unknown : 32.767 count [PASSED]
Unknown : 0.0 count [PASSED]
Unknown : 0.011 count [PASSED]
CATALYST_TEMP_B1S1: 509.2 degC
DTC_CATALYST_TEMP_B1S1: None
DTC_CATALYST_TEMP_B1S2: None
O2_SENSORS: ((), (False, False, False, False), (False, False, True, True))
DTC_OBD_COMPLIANCE: None
THROTTLE_POS: 12.9411764706 percent
O2_B1S2: 0.75 volt
GET_DTC: []
GET_CURRENT_DTC: [('U0001', 'High Speed CAN Communication Bus')]
CLEAR_DTC: None
DTC_SHORT_FUEL_TRIM_1: None
DTC_LONG_FUEL_TRIM_1: None
DTC_ENGINE_LOAD: None
DTC_COOLANT_TEMP: None
DTC_FUEL_STATUS: None
DTC_STATUS: None
TIMING_ADVANCE: 1.5 degree
SPEED: 0 kph
INTAKE_TEMP: 60 degC
RPM: 670.0 revolutions_per_minute
INTAKE_PRESSURE: 44 kilopascal
DTC_INTAKE_TEMP: None
DTC_SPEED: None
DTC_TIMING_ADVANCE: None
DTC_INTAKE_PRESSURE: None
DTC_RPM: None
MONITOR_VVT_B1: Unknown : 19.5 degree [PASSED]
Unknown : 0.0 count [PASSED]
Unknown : 0.0 count [PASSED]
Unknown : 0.0 count [PASSED]
Unknown : 14.25 degree [PASSED]
Unknown : 0.0 count [PASSED]
COOLANT_TEMP: 91 degC
ENGINE_LOAD: 45.8823529412 percent
LONG_FUEL_TRIM_1: 0.0 percent
SHORT_FUEL_TRIM_1: 0.0 percent
STATUS: <obd.OBDResponse.Status instance at 0x7fa5b8a53560>
PIDS_A: 10111110001111101010100000010011
FUEL_STATUS: ('Closed loop, using oxygen sensor feedback to determine fuel mix', '')
DTC_THROTTLE_POS: None
OBD_COMPLIANCE: OBD-II as defined by the CARB
DTC_O2_SENSORS: None
DTC_O2_B1S2: None
MIDS_D: 00000000000000000000000000000001
ELM_VERSION: ELM327 v1.5
FUEL_LEVEL: 54.9019607843 percent
DTC_RUN_TIME: None
EVAPORATIVE_PURGE: 0.0 percent
DTC_THROTTLE_ACTUATOR: None
DTC_ACCELERATOR_POS_E: None
DTC_RUN_TIME_MIL: None
DTC_TIME_SINCE_DTC_CLEARED: None
DTC_CONTROL_MODULE_VOLTAGE: None
DTC_ABSOLUTE_LOAD: None
DTC_PIDS_C: None
DTC_STATUS_DRIVE_CYCLE: None
DTC_AMBIANT_AIR_TEMP: None
DTC_THROTTLE_POS_B: None
DTC_COMMANDED_EQUIV_RATIO: None
DTC_RELATIVE_THROTTLE_POS: None
DTC_ACCELERATOR_POS_D: None
ELM_VOLTAGE: None
MONITOR_O2_HEATER_B1S2: Unknown : 269 ohm [PASSED]
MIDS_C: 11000000000000000000000000000001
MONITOR_O2_HEATER_B1S1: Unknown : 780.0 degC [PASSED]
DTC_SHORT_O2_TRIM_B1: None
DTC_LONG_O2_TRIM_B1: None
MONITOR_EVAP_020: Unknown : 0.0 count [PASSED]
MONITOR_EVAP_040: Unknown : 0.0 count [PASSED]
MONITOR_EVAP_090: Unknown : -1511.0 pascal [PASSED]
RUN_TIME: 916 second
DTC_EVAPORATIVE_PURGE: None
DTC_FUEL_LEVEL: None
DTC_PIDS_B: None
DTC_DISTANCE_W_MIL: None
LONG_O2_TRIM_B1: 0.0 percent
SHORT_O2_TRIM_B1: 0.0 percent
MIDS_B: 10000000000000000000100011111001
MONITOR_CATALYST_B1: Unknown : 0.07 count [PASSED] 
```

## OBDII Adapters

To get started, you will need an OBDII adapter. Here are three of my favorite adapters that I own and have tested:

| Tool Name         | Link                                                                                                       | Notes                                                         |
|-------------------|------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| USB ELM327        | [http://a.co/7YrtPui](http://a.co/7YrtPui)                                                                 | Best for getting started and using with virtual environments. |
| Veepeak Bluetooth | [http://a.co/80FLIMV](http://a.co/80FLIMV)                                                                 | Great for permanent installs and using with your phone.       |
| Cantact           | [https://hackerwarehouse.com/product/cantact-bundle/](https://hackerwarehouse.com/product/cantact-bundle/) | An amazing open-source project for advanced users.            |
| Veepeak Bluetooth | [http://a.co/ajFbcZ4](http://a.co/ajFbcZ4)                                                                 | Great for getting started but has some limitations.           |

## Included Tools

The following tools are automatically installed and configured:

| Tool Name       | Link                                                                                             | Notes                                                                              |
|-----------------|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| Can-Utils       | [https://github.com/linux-can/can-utils](https://github.com/linux-can/can-utils)                 | Basic CAN tool.                                                                    |
| Canbus-Utils    | [https://github.com/digitalbond/canbus-utils](https://github.com/digitalbond/canbus-utils)       | Basic CAN tool.                                                                    |
| Cantact-App     | [https://github.com/linklayer/cantact-app/](https://github.com/linklayer/cantact-app/)           | Built to work with the Cantact Hardware. I have not got it to work yet.            |
| Caringcaribou 	 | [https://github.com/CaringCaribou/caringcaribou](https://github.com/CaringCaribou/caringcaribou) |                                                                                    |
| GNUradio        | [https://www.gnuradio.org/](https://www.gnuradio.org/)                                           | If you want to look at door locks and TPM modules.                                 |
| c0f             | [https://github.com/zombieCraig/c0f](https://github.com/zombieCraig/c0f)                         |                                                                                    |
| ICSim           | [https://github.com/zombieCraig/ICSim](https://github.com/zombieCraig/ICSim)                     | Basic simulator for testing without a car.                                         |
| KatyOBD         | [https://github.com/YangChuan80/KatyOBD](https://github.com/YangChuan80/KatyOBD)                 | A really neat project that provides a GUI. I want to fork this and make it better. |
| Kayak           | [https://github.com/dschanoeh/Kayak](https://github.com/dschanoeh/Kayak)                         |                                                                                    |
| OBD-Monitor     | [https://github.com/dchad/OBD-Monitor](https://github.com/dchad/OBD-Monitor)              		     | A rally neat project that provides a GUI. Needs some documentation work.           |
| PyOBD           | [http://www.obdtester.com/pyobd](http://www.obdtester.com/pyobd)                          		     | Super old tool, still works, kinda.                                                |
| Python-OBD      | [https://github.com/brendan-w/python-OBD](https://github.com/brendan-w/python-OBD)       	 	     | Use over PIP install.                                                              |
| SavvyCAN        | [http://www.savvycan.com/](http://www.savvycan.com/)                                    	        | Basic CAN tool.                                                                    |
| Scantool        | [https://www.scantool.net/](https://www.scantool.net/)                                      	    | Super old tool but still works.                                                    |
| UDSim           | [https://github.com/zombieCraig/UDSim](https://github.com/zombieCraig/UDSim)             		      | Basic simulator for testing without a car.                                         |
| Wireshark       | [https://www.wireshark.org/](https://www.wireshark.org/)                                  	      | Great for capturing OBDII data just like you would capture ethernet data.          |

#### THIS TOOL MUST BE RUN AS ROOT !

```bash
git clone https://github.com/engineseller/hackingcar.git
chmod -R 755 hackingcar
cd hackingcar
bash install.sh
```

![engineseller's github stats](https://github-readme-stats.vercel.app/api?username=engineseller&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)
