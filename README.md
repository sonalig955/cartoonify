# cartoonify
<h1>Lets give our photos some cartoonize efffect </h1>
<h4>To convert an image to a cartoon, multiple transformations are done. Firstly, an image is converted to a Grayscale image. Yes, similar to the old day’s pictures!. Then, the Grayscale image is smoothened, and we try to extract the edges in the image. Finally, we form a color image and mask it with edges. This creates a beautiful cartoon image with edges and lightened color of the original image. </h4>
<h3>To show this process we have made an application using GUI window and also provided a save button. So, that the cartoonized image must get saved at a particular folder.</h3>
<h1>LIBRARIES USED</h1>
<h4>
1. cv2  # for image processing
2. easygui  # to open the filebox
3. numpy   # to store image
4. imageio  # to read image stored at particular path
5. sys
6. matplotlib.pyplot 
7. os
8. tkinter 
9. PIL
</h4>