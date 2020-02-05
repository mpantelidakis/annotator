
## Installation

### Windows

 Download and install Anaconda for Python 2.7 64-bit https://www.anaconda.com/distribution/
 
 Open an Anaconda2 terminal
 
 ```
 $ cd path/to/your/project
 ```
 
 ```
 $ pip install -r requeriments.txt
 ```

### How to use

Put all the images assigned to you inside data/train

Once you are in the project's root folder

```
 $ cd src
```

```
 $ python main.py
```


 Once the UI is initialized go to File -> Open an Image and select one image from the "train" folder
 
  Segmentation -> Execute (You can play around with the different segmentators or configurations to see what happens, but i suggest   using the preconfigured ones)

After the segmentation finishes, you will see that the image is now split and each segment has a border around it.

### Annotation steps

1.  Pick a class (located on the left of the panel)
2.  Click on the segments that correspond to this class

**Make sure to annotate all the segments in the image**

**If you missclick by accident, pick the correct class and click again**

**Finally, if you open an already annotated image, the annotation will be reset, so keep track of your completed images**

You can find the generated mask for your image inside data/train_labels


