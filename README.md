# Human-Activity-Recognition-using-Smartphones

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKINGUPSTAIRS, WALKINGDOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

## How I tackle this Question?
I applied a artificial neural network (ANN) model and got training accuracy of about 99% and validation accuracy of about 95% and predicted accuracy of about 93%.

## Some plots

Loss over Epoches
![image](https://user-images.githubusercontent.com/92180055/190886961-fa70e8ff-00fc-4dc3-b6fa-0063b27fb4f9.png)

Accuracy over Epoches
![image](https://user-images.githubusercontent.com/92180055/190886968-895edbe0-ba20-4dbf-b67f-aee0885b9231.png)

