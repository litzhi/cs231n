### challenge
* different camera from the same thing can present different data point
![alt text](images/image.png)
* illumination（光照）
![alt text](images/image-1.png)
光照影响
* background clutter(杂物)
![alt text](images/image-2.png)
* occulution (隐藏)
![alt text](images/image-3.png)
* deformaion(变形)
![alt text](images/image-4.png)
* intraclass variaion(同一个种类多种多样)
![alt text](images/image-5.png)
* context
识别的物体会因为周围环境的变化而导致不同的结果

### linear classify
* l1 distance
使用最简单的l1 distance来实现分类
![alt text](images/image-6.png)
![alt text](images/image-7.png)
其中np.sum利用了numpy的广播机制来实现相加