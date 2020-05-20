# Title Of The Project 						
IOT based Accident Alert System

# Group Members					
Kunal Kale(16104027) 
Viranchee Patil(16104044) 
Chinmay Kubal(16104023)


# Brief Description About Project Implementation
The working of IOT Based Accident Alert System begins with the accelerometer which is constantly monitoring the vehicle’s acceleration with respect to the 3 axes. This data that is generated is constantly being uploaded to the cloud. The vibration sensor is also monitoring data such as displacement, change in temperature,etc. This is because at the time of crash, the values of displacement and temperature also change abruptly along with the change in acceleration. So, to check for false alarms, the vibration sensor is essential.When a crash occurs, and it is conﬁrmed by the accelerometer as well as the vibration sensor, the geographical coordinates of the location are mapped and uploaded to the cloud via the MQTT Cloud service provided by Amazon AWS. These coordinates are then sent to the emergency services via an email notiﬁcation using the AWS Simple Notiﬁcation Service. For the emergency services to receive an alert regarding the crash, they should be subscribed to the SNS service.