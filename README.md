# EKF assignment -

All of the code relevant to EKF/UKF is in the odomshi package, with imu and odom being the dummy publishers, while relay being the relay node for using the gazebosimulation data. 
For switching between dummy to simulation data you need to edit the topics from which the EKF/UKF nodes are picking up data in the config file. 
the launch file used is the launch file in the rover_gazebosim package only. 
even when using the dummy nodes for EKF the simulation needs to start before the topics start publishing(idk why). 
