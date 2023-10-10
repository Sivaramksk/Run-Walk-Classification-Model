# Run-Walk-Classification-Model
Developing a Run/Walk Classification Model
Problem Statement
To develop a machine learning classification model that accurately distinguishes between running and walking activities based on sensor data. Multi-layer neural networks will be trained and evaluated based on data from Run or Walk Reduced dataset.

Tasks
Task 1: Prepare a complete data analysis report on the given data.
Task 2:-Create a predictive model to classify whether a person is running or walking based on the given predictor variables.

### In this dataset, we have 11 columns of parameters for RunWalk Classification and 88588 rows of data.
******

#### Input Variable

   **Date:** 
    
        This column typically represents the date on which the activity  data was recorded.
   **Time:** 
    
        This column represents the time of day when the activity or motion data was recorded.
   **Username:** 

        This column may contain the usernames or identifiers of individuals or users associated with the recorded data.
   **Wrist:** 
   
        This column indicates the specific wrist where the wearable device or sensor was placed. It can be "left,"
        "right," or some other identifier to indicate the location of the sensor on the body.
   **Acceleration_x:**
   
        These columns typically contain numerical values representing the acceleration of motion along the x-axis. 
        Acceleration measures how quickly an object is changing its velocity. In the context of a wearable sensor,
        this could represent acceleration in a horizontal direction.
   **Acceleration_y:** 
   
        Similar to the previous column, this one represents the acceleration along the y-axis. It may indicate motion
        in a vertical direction or another orientation, depending on how the wearable device is positioned.
   **Acceleration_z:** 
   
        This column represents the acceleration along the z-axis. It typically measures motion in a depth or 
        front-to-back direction.
   **Gyro_x:** 
   
        These columns contain numerical values representing the angular velocity (rate of rotation) around the x-axis.
        Gyroscopic sensors measure the rate of change of orientation or rotation.
   **Gyro_y:**
   
        Similar to the previous column, this one represents angular velocity around the y-axis.
   **Gyro_z:**

        This column represents angular velocity around the z-axis. It measures rotational motion around a 
        vertical axis.
        
#### Output Variable

   **Activity:**
   
        This column contains labels or descriptions of the physical activities being performed, such as "walking,"
        "running". 
        Walking = 0
        Running = 1
