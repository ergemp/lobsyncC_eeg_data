# Head Movements 

This task has the wrist movements for left, right, up and down events. All movements are handled with right hand. Each session has five set of Training recording and three set of Test recording. Each file (recording) consists of three seconds of EEG recording with 250hz sample size, this gives 750 samples (lines) for each file. 

## Resting Position:
Right arm, wrist and hand start with rested state on a table with 90 degree elbow angle. 

## Data Collection:
While resting the the desk, subject is informed with a written message that data collection is going to start. After the alert, daha acquisition starts and waits for 500 miliseconds before the corresponding acquisitions. Total 2 acquisition comes true with 1000 miliseconds each, and the last message to the subject comes as the data collection is going to end. After the last message, procedure waits for another 500 miliseconds. Acquisition ends and data is saved to csv file. 

## Left Movement: 
Starts with resting, straight natural position of the the head. Starting from the first notification subject start the movement of bending the head to the left and ends the movement with the last notification. 

## Right Movement 
Starts with resting, straight natural position of the the head. Starting from the first notification subject start the movement of bending the head to the right and ends the movement with the last notification. 

## Up Movement 
Starts with resting, straight natural position of the the head. Starting from the first notification subject start the movement of bending the head to the back and ends the movement with the last notification. 

## Down Movement 
Starts with resting, straight natural position of the the head. Starting from the first notification subject start the movement of bending the head to the front and ends the movement with the last notification. 

## Headers:

Recording are done via a [10-20 system](https://en.wikipedia.org/wiki/10%E2%80%9320_system_(EEG)) positioned [Brainaccess Kit](https://www.brainaccess.ai/products/brainaccess-standard-kit/) EEG device.

### F3
Left Frontal Cortex F3.

### F4
Right Frontal Cortex F4.

### C3
Motor Imagery Region C3.

### C4
Motor Imagery Region C4.

### P3 
Left Peripheral Region P3.

### P4
Right Peripheral Region P4.

### Cz
Center Zenith Location Cz.

### Pz
Peripheral Zenith Location Pz.

### Accel_x
EEG headset supports 3-axis accelerometer that can be used to detect head and other movements. Accel_x represents the X axis movements of the subjects head. 

### Accel_y
EEG headset supports 3-axis accelerometer that can be used to detect head and other movements. Accel_y represents the Y axis movements of the subjects head. 

### Accel_z
EEG headset supports 3-axis accelerometer that can be used to detect head and other movements. Accel_z represents the Z axis movements of the subjects head. 

### Sample
Sample is the timeseries column of each measurement which increments for each measurement for time keeping. 




