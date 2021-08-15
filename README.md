## 项目结构梳理

* camera.h——可以调整视角和位置的相机
* color.h——着色处理
* hittable.h和hittable_list.h——记录物体信息
* material.h——实现材质
* ray.h——发射光线采样
* rtweekend.h——util函数
* sphere.h——几何物体相关
* vec3.h——向量的相关函数



## 不足之处

* 该渲染效果目前还是静态的，是离线渲染的结果，渲染一张图要好几分钟，可以考虑使用OpenVM来进行多线程加速



### 效果展示

![图片展示](https://github.com/hiki-long/SimpleRayTrace/raw/master/image.jpg)

