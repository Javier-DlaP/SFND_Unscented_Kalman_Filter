The implementation it's based on the code we previously created in the lesson 4 (UKF).

To have the RMSE less than the values [0.3, 0.16, 0.95, 0.7] I have use the NIS on both the radar and lidar to get the 95% of the value under 7.815 and 5.991 as we see on "Parameters and Consistency".
After trying different values of std_a_ and std_yawdd_ I ended up with no excess of the RMSE values using std_a_=5, std_yawdd_=5.

(The code for calculating the percentage of NIS is on the tool.cpp file and the results can be seeing setting the variable percentage to true).