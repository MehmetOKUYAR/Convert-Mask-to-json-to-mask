# Convert Mask-to-json-to-mask

If you are developing a segmentation model, you may need to convert your tags from json format to mask format.
Thanks to the interface we have developed, you will be able to easily turn your labels into masks.
Also, if you have masks and want to convert them to json format, you can easily do this with our application.
This conversion comes to you in Mask R-CNN format, so if you have mask photos, you can easily convert them to .json files suitable for Mask R-CNN format.
This convenience will allow you to convert the labels you have as you wish, even if they do not fit your format.

## How to Run
you need to run `python main.py`

Then you will see the following window

## 1 ) Convert JSON to Mask

![](https://github.com/g180900073/Mask-to-json-to-mask/blob/main/images/jsontomask.jpg)

___
 **Load Json :**  Upload the json file you labeled for segmentation 

 **Save Path :**  Specify the folder path you want to save 

 **Mask Height :**  enter image height 

 **Mask Width :**  enter image width 

After filling in the relevant fields, you can easily perform the conversion by pressing the **start** button.

## 2 ) Convert Mask to JSON

![](https://github.com/g180900073/Mask-to-json-to-mask/blob/main/images/masktojson.jpg)

___
 **Mask Path :**  Specify path to pre-created mask photos 

 **JSON Path :**  Specify the path of the json file format to be generated 

After filling in the relevant fields, you can easily perform the conversion by pressing the **start** button.
