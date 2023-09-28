
# Food Calories from the Images of Junk foods 


## [Yash Adhiya]([https://www.linkedin.com/in/vinayak-sable-675502131](https://www.linkedin.com/feed/)) 

+ ###  Problem
 The problem can be simply stated as, given a set of food images and the idea is to estimate the calories. 
+ ### Objectives
 1.	To detect food type by using Convolutional Neural Network (CNN)
 2.	To estimate calories of food
 

+ ### Data collection

Please Note that I have not used the data that was provided to me DL_1 problem statement. I have rather used the following pre-trained data. The only reason was that I have tries a lot to preprocess the coma-separated src link but had some unsolvable errors. 

For this project, I used the following datasets:
1. ECUST Food Dataset (ECUSTFD)


  
  
## Food type

![image](https://github.com/Yash-Adhiya/SmartSense_DL/assets/76459878/d71dc497-e4f1-412c-9a4e-d84aa86a0b18)








### Recognition method
Food Recognition deals with the recognition of food items when given an image. For this problem, I used a Convolutional Neural Network (CNN). The Architecture of  CNN given below figure 
![image](https://github.com/Yash-Adhiya/SmartSense_DL/assets/76459878/a2108d06-2f61-4541-85f9-13551926b53a)

> **all this work done in ```cnn.py``` file
change the directory to ```food-calories-estimation-using-Image-processing-master``` folder and give sufficient information to ```cnn.py``` python file and run**



### Accuracy 
![image](https://github.com/Yash-Adhiya/SmartSense_DL/assets/76459878/d4a07f8f-35d2-4c16-9afa-befaef6f189d)


### Loss
![image](https://github.com/Yash-Adhiya/SmartSense_DL/assets/76459878/fcff59fc-6908-48fd-b475-afcfd6718f94)






### Requirements
+ Python
+ Tensorflow 
+ tflearn


### Testing
Google colab link for testing [click here](https://colab.research.google.com/drive/1dRVXXVfX5vQ0Re1kW_yX4zwJBNzSezoa?usp=sharing)
for testing our model run
```
python demo.py
```

### Training
Download data from above FOODD link and create forlder in repo FOODD and run
```
python train.py
```


> *all this done ```image_segment.py``` and ```calorie.py```*



## Result

 | Fruits  | Calorie | Estimated Calories|
 | ------- | ------- | -----------------| 
 | Apple   |  53.96  |   40.42          |
 | Burger  |  170.88 |   188.81         |  
 | Pizza  |  31.16  |   26.28          |
 | Cake|  29.44  |   37.65          |
 | Noodles   |  44.88  |   37.13          |  
 | Dosa  |  69.09  |   71.92          |
 | Biryani  |  17.46  |   13.82          |

 These are the random images tried out and they worked really well on the vegetables and fruits dataset. However I may not be able to serve the purpuse of the given dataset in the prob statment but using the pre-trained data, I got really good results


+ #### Limitations:
    1. Due to image quality, it is impossible to find actual weight and calories.
    2. It's challenging to get the right fruit-camera angle.
    3. Pixel changes in relation to lighting conditions
  
    





