# Wrist Movements 

This task has the wrist movements for left, right, up and down events. All movements are handled with right hand. Each session has five set of Training recording and three set of Test recording. Each file (recording) consists of three seconds of EEG recording with 250hz sample size, this gives 750 samples (lines) for each file. 

## Resting Position:
Right arm, wrist and hand start with rested state on a table with 90 degree elbow angle. 

## Data Collection:
While resting the the desk, subject is informed with a written message that data collection is going to start. After the alert, daha acquisition starts and waits for 500 miliseconds before the corresponding acquisitions. Total 2 acquisition comes true with 1000 miliseconds each, and the last message to the subject comes as the data collection is going to end. After the last message, procedure waits for another 500 miliseconds. Acquisition ends and data is saved to csv file. 

## Left Movement: 
Starts with resting position of the the right arm, elbow and hand on a desk with 90 degree elbow angle and strait wrist. Starting from the first notification subject start the movement of the right hand wrist to the left and ends the movement with the last notification. 

## Right Movement 
Starts with resting position of the the right arm, elbow and hand on a desk with 90 degree elbow angle and strait wrist. Starting from the first notification subject start the movement of the right hand wrist to the right and ends the movement with the last notification. 

## Up Movement 
Starts with resting position of the the right arm, elbow and hand on a desk with 90 degree elbow angle and strait wrist. Starting from the first notification subject start the movement of the right hand wrist to up as if the finger tips are showing the ceiling and ends the movement with the last notification. 

## Down Movement 
Starts with resting position of the the right arm, elbow and hand on a desk with 90 degree elbow angle and strait wrist. Starting from the first notification subject start the movement of the right hand wrist to the down as if the fingers are showing the desk and ends the movement with the last notification. Since there is no room for down movement for the hand, movement is defined with the pressing the desk with finger tips and raising the wrist from the desk. 

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

### Accel_y

### Accel_z

### Sample
