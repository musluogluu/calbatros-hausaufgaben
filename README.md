#  YOLOv4 Image Detection Ödevi

##  Ödev Tanımı

Bu ödevde, `ai/` klasöründe bulunan **YOLOv4 model dosyaları** ile `img/` klasöründeki görsellerde **nesne tespiti (object detection)** yapılacaktır. Her bir görsel için:

- YOLOv4 kullanılarak **bounding box** çizilecek,  
- Görsel **popup olarak gösterilecek**,  
- Ve her tespit için **bounding box koordinatları terminale yazdırılacaktır.**

---

## 🗂 Klasör Yapısı

```bash
.
├── ai/
│   ├── yolov4.weights
│   ├── yolov4.cfg
│   └── coco.names
├── img/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
├── main.py
└── README.md
