## BGR 轉 HSV
    image = cv.cvtColor(image , cv2.COLOR_BGR2HSV)
    # cv2.COLOR_HSV2BGR :轉回RGB

## 畫矩形
    # (x1,y1)為左上, (x2, y2)為右下, 線寬若-1-->矩形填滿
    cv2.rectangle(image, (x1, y1), (x2, y2), (B,G,R), 線寬)
    
## 文字

