# Why This?

This masking technique can be used on wide number of applications.Dont limit this algorithm to only the field of agriculture.....It works for anything which requires efficient masking on particular type of images/snaps.I have applied this particular alorithm so as to remove the external parts in image other than crops so that i can perform image detection algorithm on it efficiently  and measure the temperature around each part of the fields.This is just one application........dont get me wrong but this can be and should be applied to larger scale applications on different fields

# How it Works


i)First, the color image in RGB format is changed to the Grayscale format. This brings about a significant distinction between the desired and unwanted elements.

![image](https://user-images.githubusercontent.com/59787095/140626557-5cf20d56-16a3-42cf-b1fc-2abc71f1b04e.png)  

ii)It is followed by applying threshold values to each of the color components. This would lead to a binary image displaying the selected canopy fraction as logical 'one' and the rest of the pixels as binary 'zero'. 

iii)Consequently, the fraction of the image with logical 'zero' is mapped on to the thermal image frame and masked out.

![image](https://user-images.githubusercontent.com/59787095/140626616-a39565f1-5c1e-44fa-8a74-9fadda86a3e0.png)  ![image](https://user-images.githubusercontent.com/59787095/140626618-e3b9eb8b-6457-4020-aa92-78461e414d0e.png)


