# RosProject
This project is done by:
        -BOUTALLOUST Mohammed Amine (n°6 ISEIA1)
        -DERKAOUI Yahia (n°10 ISEIA1)
        -ELAMIRI Youssef (n°21 ISEIA1)
This project is an HVAC System Control which consiste of 3 packages:
    -hvac_actuators: have 3 nodes ACU , Heater and Ventilator:
        +ACU: represente the Air Conditionning Unit which provide 2 services: one for setting the status of the ACU(On/Off) and the other service is for getting a constante of the ACU.
        +Heater: represente the Heatting system which provide 2 services: one for setting the status of the Heater(On/Off) and the other service is for getting a constante of the Heater.
        +Ventilator: represente the Ventilation system which provide 2 services: one for setting the status of the Ventilator(On/Off) and the other service is for getting a constante of the Ventilator.
    -hvac_control: have 2 nodes UI , and Controller
        +UI: represente the User Interface (QT UI) which provide an interactive interface to control the hvac_system.
        +Controller: represente the Controler which control all of the heating, AC, and ventilation systems as you want.
    -temp_sensor: have 1 nodes TempSensor: represente the Temperature Sensors Controller which Assemble all the temperature readings from the sensors and send them to the Controller for processing.
