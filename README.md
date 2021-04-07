# UNT_Aerial_Dataset

## The UNT Aerial Dataset project

* Provides standardised image data sets for object classification and recognition.



## UNT Aerial Dataset

* The dataset is available in this repository. [The rar file will be uploaded later.]
* The dataset contains 5000 images with carefully labeled annotation file for each image. 
* The annotation files are XMLs and label format follows the standard of [PASCAL VOC](http://host.robots.ox.ac.uk/pascal/VOC/).



## Structure

```
UNT Aerial Dataset
    ├── test
    |    └──Annotations (500 XMLs)
    |    └──JPEGImages  (500 images)
    └── train
    |    └──Annotations (4500 XMLs)
    |    └──JPEGImages	(4500 images)
    └── README.md
    └── UNT_Aerial_Dataset.rar(Upload later)
```

* This dataset is randomly splitted into two sub-datasets, test (500 images) and train (4500 images). You can merge them together and then split according your requirement easily.

- [ ] Try to upload a rar file containing all images and annotations.



## Summary

* There are 6 classes in this dataset: person, boat, car, bicycle, truck, bus. The statistic information is in following tables.

| UNT Aerial Dataset | Person | Boat | Car   | Bicycle | Truck | Bus  |
| ------------------ | ------ | ---- | ----- | ------- | ----- | ---- |
| No. of Images      | 4394   | 90   | 3324  | 296     | 267   | 26   |
| No. of Objects     | 26921  | 797  | 14225 | 583     | 272   | 27   |

| Scenes             | No. of Images | No. of Objects per Image | No. of Images | Angle of View     | No. of Images |
| ------------------ | ------------- | :------------------------: | ------------- | ----------------- | ------------- |
| **Parking Lot**    | 552           | **1~10**                 | 3967          | **Vertical View** | 1335          |
| **Action Test**    | 2108          | **11~20**                | 608           | **Side View**     | 3665          |
| **Routine Life**   | 414           | **21~50**                | 378           |                   |               |
| **Outdoor Living** | 626           | **51~100**               | 25            |                   |               |
| **Harbour**        | 50            | **101~150**              | 8             |                   |               |
| **Social Party**   | 1251          | **151~200**              | 14            |                   |               |



## Support

- [ ] Support info