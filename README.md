# Canny-Operator-with-morphological-completion
Edge detection using canny operator using canny operator and edge enhancement with morphology

Lets try edge detection over this image
![alt text](https://raw.githubusercontent.com/tbharathchandra/Canny-Operator-with-morphological-completion/master/si.jpg)

After de-noising using Gaussian filter
![alt text](https://raw.githubusercontent.com/tbharathchandra/Canny-Operator-with-morphological-completion/master/img_guassian_filter.jpg)

Derivatives in x and y directions
![alt text](https://raw.githubusercontent.com/tbharathchandra/Canny-Operator-with-morphological-completion/master/gx.jpg)
![alt text](https://raw.githubusercontent.com/tbharathchandra/Canny-Operator-with-morphological-completion/master/gy.jpg)

final magnitude 
![alt text](https://raw.githubusercontent.com/tbharathchandra/Canny-Operator-with-morphological-completion/master/Mag.jpg)

After Non Maxima suppression
![alt text](https://raw.githubusercontent.com/tbharathchandra/Canny-Operator-with-morphological-completion/master/NMS.jpg)

To enhance the above image i have used morphological operations  

After dilation 
![alt text](https://raw.githubusercontent.com/tbharathchandra/Canny-Operator-with-morphological-completion/master/img_dilation.jpg)


After eroding the final image is
![alt text](https://raw.githubusercontent.com/tbharathchandra/Canny-Operator-with-morphological-completion/master/img_erode.jpg)

With these technique we can detect edges more efficiently than just applying canny operator

This code is under MIT License.
