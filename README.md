#README

The Custom CNN script is ran with randomized weights which could output different final values as written in my report.

When I was running my code, it was done on A100 GPU with high ram. 
When the code is initialized, the images from the dataset are resized to 120 x 120
If the script is ran on a CPU, the code will face performance issues with the ram causing the code to break.
To fix this, change this line to resize to 64 x 64 instead of 120 x 120

image_size = (120, 120)

The results should not change significantly but final performance of the model might drop compared to what was written in the report. 
The final images will also look different.

In one test with 64x64, the results are:

Training Accuracy: 0.7286
#0.3 ~ 0.4 decrease

Training Loss: 1.0195
#0.1 ~ 0.2 increase

Validation Accuracy: 0.7252 
#0.2 ~ 0.3 decrease

Validation Loss: 1.0216 
#0.1 ~ 0.2 increase

Test Accuracy: 0.72 
#0.3 ~ 0.4 decrease

Test Loss: 1.04
#0.1 ~ 0.2 decrease


