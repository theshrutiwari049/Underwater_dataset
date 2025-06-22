# Underwater_dataset
Augmented Dataset
Total= 387 frames* 25 features = 9,675 frames
2 files named strong and light is already available with you
387* 27 features =10,449 frames

This folder contains augmented images , augmented from base file - Sharp .

It has folders named color_effect_frames with effects like brightness,contrast,clahe,hsv,invert color ,sepia ,histogram equilization ,saturation.

Folder named gaussian_augmented contains frames with different kernel sizes (3,5,7,9,11) 
After plotting graph with respect to sharpness and (kernel size with sigma value)
The kernel size 3*3 with sigma size 0.5 resulted to have best sharpness
figure : ![image](https://github.com/user-attachments/assets/6bdc05e4-6356-4b10-9593-18e863e3c596)


Folder named motion_blur_augmented contains blur_bilateral,blur directional,diagonal,horizontal_light, horizontal_strong ,reverse_diagonal ,vertical blur frames

Folder named reflected_frames contains horizonal,vertical,both reflections

Folder named salt-pepper conatins frames with value 1 and 0.5 





