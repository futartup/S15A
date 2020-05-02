# EVA Assignment Submissions ( S15A and S15 )

This is an original submission of assignments from S15A and S15. The goal is to segment and create a bounding box around the object detected as well as monocular depth estimation. I have created my own dataset.

## Acknowledgements

I would like to thanks all the EVA4 telegram batch members who has helped me to implement the code whenever i am stuck.

I would also like to thank www.theschoolofai.in to give me this opporthunity to get hands on AI. 

## Prerequisites
- Python 3.6+
- PyTorch 1.0+

## Creation of dataset
### Choosing of background images
For choosing background images i have choosen the natural scenery images. The scenery images are choosen in such a way that there are very less subjects in the image. I will overlay foreground images on top of these scene images on randon positions. 

The number of these backgroud images are 100 of size 224 * 224.
The scene images are as follows-
![alt-text-1](https://github.com/futartup/S15A/blob/master/raw_images/background_images_224/16ms-17c-sardar-petal-road-adyar-ARJ.png) 
![alt-text-2](https://github.com/futartup/S15A/blob/master/raw_images/background_images_224/464250.png ) 
![alt-text-1](https://github.com/futartup/S15A/blob/master/raw_images/background_images_224/empty-road-1.png) 
![alt-text-2](https://github.com/futartup/S15A/blob/master/raw_images/background_images_224/images150.png)

### Choosing of foreground images
For foreground images the size is 100 * 100. All the images are of cars. The images are made transparent using GIMP software. Some of the transparent png images of car is downloaded from various sources in internet.

The number of these foreground images are 100 of size 100 * 100. The images are as follows-
![alt-text-1](https://github.com/futartup/S15A/blob/master/raw_images/foreground_images_100/image24.png) 
![alt-text-2](https://github.com/futartup/S15A/blob/master/raw_images/foreground_images_100/images10.png ) 
![alt-text-1](https://github.com/futartup/S15A/blob/master/raw_images/foreground_images_100/maruti-suzuki-car-india-car.png) 
![alt-text-2](https://github.com/futartup/S15A/blob/master/raw_images/foreground_images_100/24-249294_ktm-1290-super-duke-r-motorcycle-bike-png.png)

## Approach



### Results and some observations S15A submission


### Accuracy
| Model             | Acc.        |
| ----------------- | ----------- |
|       |      |

## File Structure


## About me
My name is Anup Gogoi and i am an computer vision and AI enthusiast. My dream is to develop products which actually augment the intelligence of mankind in specially medical domain. Human brain can do very complex things, But still it will take some time to figure out the best medicine for Coronavirus pandemic, whereas a combined effort of human and artificial intelligence can do that in very less time.

My github repo is public and collaborators, suggestions are always welcomed.





