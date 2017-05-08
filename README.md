# pir-to-pet-tutor
This code is used to demonstrate how the Seeed PIR can be used to detect a person and trigger a Smart Animal Training Systems Pet Tutor to dispense kibbles.

The hardware required this software to function includes:

* Seeed PIR with Grove connector
** http://wiki.seeed.cc/Grove-PIR_Motion_Sensor/
*** The cost to buy from Seeed is too much because of international shipping and import duties
*** so buy them here instead: http://www.robotshop.com/en/seeedstudio-grove-pir-motion-sensor.html 

* LightBlue Bean+ by PunchThrough Design
** https://store.punchthrough.com/collections/bean-family/products/lightblue-bean-plus

* Pet Tutor Pro with Bluetooth
** https://smartanimaltraining.com/products/feeder-only

The code (arduino sketch) is used to allow the Bean+ to use the Seeed PIR, or passive infra red, motion detector to detect motion and request the Pet Tutor Blu iOS app (https://itunes.apple.com/us/app/pettutor-blu/id934260904 ) to trigger the Pet Tutor Blu feeder to dispense kibbles.

