---
title: "YOLOv5와 Dual Kalman Filter 기반의 폐색영역에 강건한 객체 추적 프레임워크"
collection: publications
category: korea_journal
permalink: /publication/2023_YOLO_KM
date: 2023-02-01
excerpt: ''
venue: '한국정보기술학회논문지'
paperurl: 'https://ieeexplore.ieee.org/document/9103002'
citation: '김다솔, 허재석* (2023), YOLOv5와 Dual Kalman Filter 기반의 폐색영역에 강건한 객체 추적 프레임워크, 한국정보기술학회논문지, 21(2), 19-32. (KCI)'
---

Although YOLO(You Only Look Once) is a widely used algorithm in real-time object detection, it has a
limitation in that its performance significantly deteriorates in occlusion areas where a detection target is obscured by
another object or surrounding background. In this study, we propose a robust object tracking framework that utilizes
YOLOv5 and a Dual Kalman Filter(KF) consisting of Detection and Inference KFs to address this issue. The
proposed framework uses the Detection KF updated with a high weight on the detection results of YOLOv5 when
YOLOv5 fails to detect objects. If the object is not detected over successive frames, the proposed framework
attempts to track the object using the Inference KF updated with a high weight on the prediction results of KF.
Through experiments using data with occluded regions, we confirmed that the proposed framework outperformed
existing approaches in terms of detection accuracy while sacrificing less computation speed.

