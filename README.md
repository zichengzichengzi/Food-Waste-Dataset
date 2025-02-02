# Food Waste 131
a new food waste dataset(rgb+depth) "Food Waste 131" for food waste Semantic segmentation and quantification. The dataset has been collected in real college canteen in China. Depth images are raw data that can be used for food volume calculation or other downstream tasks.
![image](https://github.com/user-attachments/assets/17b90801-69d6-47ac-98e7-7fbe92c488b1)



|Name|Address|
|:---|:---|
|CC-FOOD-100|[https://pan.baidu.com/s/1Cb4AULANrZSCKgsg10XFaQ password:9ucz](https://pan.baidu.com/s/1o7ZDwkd4oUFui5UZMmIvPw?pwd=pfav)|

## Dataset structure

```
|-- <CC-FOOD-100>
    |-- <json> //Store label files
        0.json
        1.json
        ...
    |-- <depth> //Store depth images
        0.npy
        1.npy
        ...
    |-- <rgb> //Store color images
        0.png
        1.png
        ...
    |-- <xml> //Store voc xml
        0.xml
        1.xml
        ...
        
```
        

