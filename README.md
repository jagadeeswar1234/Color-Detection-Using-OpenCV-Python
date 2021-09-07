# Color-Detection-Using-OpenCV-Python
What is Colour Detection?

Colour detection is the process of detecting the name of any color. Simple isn’t it? Well, for humans this is an extremely easy task but for computers, it is not straightforward. Human eyes and brains work together to translate light into color. Light receptors that are present in our eyes transmit the signal to the brain. Our brain then recognizes the color. Since childhood, we have mapped certain lights with their color names. We will be using the somewhat same strategy to detect color names.

The Dataset

Colors are made up of 3 primary colors; red, green, and blue. In computers, we define each color value within a range of 0 to 255. So in how many ways we can define a color? The answer is 256*256*256 = 16,581,375. There are approximately 16.5 million different ways to represent a color. In our dataset, we need to map each color’s values with their corresponding names. But don’t worry, we don’t need to map all the values. We will be using a dataset that contains RGB values with their corresponding names.

The colors.csv file includes 865 color names along with their RGB and hex values.

Steps Involved:
1) Take an image from the user

Ex:

![image](https://user-images.githubusercontent.com/86997363/132298278-dc9a0a94-1e96-421e-ad89-2a9a7a4cd1e8.png)

3) Read Csv file
4) Set a mouse call back event
5) Calculate distance to get color Name
6) Display image on window.

OUTPUT:


![image](https://user-images.githubusercontent.com/86997363/132298359-67a1a25c-8a66-4d69-a79b-8e17ea83c95f.png)


![image](https://user-images.githubusercontent.com/86997363/132298409-1ae07929-e730-4a83-9509-20dca1ada94a.png)
