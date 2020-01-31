![sample](https://raw.githubusercontent.com/lennox0909/Tree_recognition_project/master/img_sample/P_20191010_135321_yolo_leaf.jpg)

# Taiwanese Tree Recognition Project (Aug - Nov, 2019)

As tree lovers, we were aiming for introducing tree's values and benefits to the public. 

* Collecting tree photos among Taiwan mostly in Taipei metropolois.
* Data released on [kaggle](https://www.kaggle.com/c/whichtree-b/data) to encourage attention.
* Trained `YoloV3` to identify trees.
* Build backend on `Google Cloud Platform`
* Build `Line Chatbot` as frontend for user easy access

---

## Target Trees

| Traditional Chinese | Abbreviation | Wikipedia link                          | Scientific Name           |
|------|----|--------------------------------------------------------------------|-------------------------|
| 臺灣欒樹 | KE | https://zh.wikipedia.org/wiki/%E5%8F%B0%E7%81%A3%E6%AC%92%E6%A8%B9 | Koelreuteria elegans    |
| 苦楝   | MA | https://zh.wikipedia.org/wiki/%E8%8B%A6%E6%A5%9D                   | Melia azedarach         |
| 鳳凰木  | DR | https://zh.wikipedia.org/wiki/%E9%B3%B3%E5%87%B0%E6%9C%A8          | Delonix regia           |
| 盾柱木  | PP | https://zh.wikipedia.org/wiki/%E7%9B%BE%E6%9F%B1%E6%9C%A8          | Peltophorum pterocarpum |
| 楓香   | LF | https://zh.wikipedia.org/wiki/%E6%9E%AB%E9%A6%99                   | Liquidambar formosana   |
| 青楓   | AE | https://zh.wikipedia.org/wiki/%E9%9D%92%E6%A5%93                   | Acer serrulatum         |
| 大葉欖仁 | TC | https://zh.wikipedia.org/wiki/%E6%AC%96%E4%BB%81%E6%A8%B9          | Terminalia catappa      |
| 大葉山欖 | PF | https://zh.wikipedia.org/wiki/%E5%A4%A7%E8%91%89%E5%B1%B1%E6%AC%96 | Palaquium formosanum    |
| 水同木  | FF | https://zh.wikipedia.org/wiki/%E6%B0%B4%E5%90%8C%E6%9C%A8          | Ficus fistulosa         |
| 稜果榕  | FP | https://zh.wikipedia.org/wiki/%E7%A8%9C%E6%9E%9C%E6%A6%95          | Ficus septica           |
| 茄苳   | BJ | https://zh.wikipedia.org/wiki/%E7%A7%8B%E6%9E%AB                   | Bischofia javanica      |
| 樟樹   | CC | https://zh.wikipedia.org/wiki/%E6%A8%9F%E6%A0%91                   | Cinnamomum camphora     |
| 小葉欖仁 | TM | https://zh.wikipedia.org/wiki/%E5%B0%8F%E5%8F%B6%E6%A6%84%E4%BB%81 | Terminalia mantaly      |
| 榕樹   | FM | https://zh.wikipedia.org/wiki/%E7%B4%B0%E8%91%89%E6%A6%95          | Ficus microcarpa        |
| 白千層  | MI | https://zh.wikipedia.org/wiki/%E5%8D%83%E5%B1%82%E6%A0%91          | Melaleuca leucadendra   |
| 水黃皮  | MP | https://zh.wikipedia.org/wiki/%E6%B0%B4%E9%BB%84%E7%9A%AE          | Millettia pinnata       |
| 阿勃勒  | PC | https://zh.wikipedia.org/wiki/%E9%98%BF%E5%8B%92%E5%8B%83          | Cassia fistula          |
| 大王椰子 | RR | https://zh.wikipedia.org/wiki/%E7%8E%8B%E6%A3%95                   | Roystonea regia         |
| 黑板樹  | AS | https://zh.wikipedia.org/wiki/%E9%BB%91%E6%9D%BF%E6%A8%B9          | Alstonia scholaris      |


## Data Collection & Public Released

* 10 members were tree-knowledge trained, then scatter out for photoshooting, where monstly in urban/suburban areas in Taipei.
* Data released on [**kaggle**](https://www.kaggle.com/c/whichtree-b/data) and followed `CC BY 4.0` protocol

## Data Annotation for YOLO training

* [**labelImg**](https://github.com/tzutalin/labelImg) was applied for labeling images before YOLO training

## YOLO Training

* Training process was strongly inspired by [experiencor’s keras-yolo3 project](https://github.com/experiencor/keras-yolo3)
* Revised [**bbox.py**](https://github.com/lennox0909/Tree_recognition_project/blob/master/bbox.py) and [**predict.py**](https://github.com/lennox0909/Tree_recognition_project/blob/master/predict.py) module to **support truetype fonts and Chinese display**

## Backend Map
![Backend Map](https://raw.githubusercontent.com/lennox0909/Tree_recognition_project/master/backend_map.png)

## Line Chatbot Frontend Design

* CSS design [folder](https://github.com/lennox0909/Tree_recognition_project/tree/master/line_chatbot/dynamic_reply) for reference

















