# 界面介绍

![image-20200909091002796](https://gitee.com/zr001/writeimges/raw/master/images/image-20200909091002796.png)

# 基础设置

![image-20200909105110264](https://gitee.com/zr001/writeimges/raw/master/images/image-20200909105110264.png)

正视于：`ctrl+shift+A`

## 导出为`stl`格式

- 无法直接导出
- ![image-20200909100307167](https://gitee.com/zr001/writeimges/raw/master/images/image-20200909100307167.png)

# 建模思路

## 1.构建建模思路

- STL模型导入，六面体坐标系建立；
- 主体：合理地将曲面划分，利用面片创建自由曲面，将所有曲面创建完成后合并为实体；
- 特征结构：倒圆角；
- 数据导出。
- ![image-20200909092508552](https://gitee.com/zr001/writeimges/raw/master/images/image-20200909092508552.png)

> 领域的划分非常重要，决定曲面的平滑程度以及与实体之间的偏差

![image-20200909092845097](https://gitee.com/zr001/writeimges/raw/master/images/image-20200909092845097.png)

## 2.划分领域

### 自动划分领域

> ![image-20200909093538411](https://gitee.com/zr001/writeimges/raw/master/images/image-20200909093538411.png)
>
> 自动分割有时可能划分的区域不是很准确
>
> 工作中不常用



### 手动划分领域

> ![image-20200909093637305](https://gitee.com/zr001/writeimges/raw/master/images/image-20200909093637305.png)
>
> 按住`alt`左右拖动可以调节画笔大小，按住鼠标左键拖动即可，正常情况需要一次性拖动，不然前面的选择会消失，按住`shift`拖动叠加选择，按住`ctrl`撤销选择。
>
> 点击插入
>
> ![image-20200909093912093](https://gitee.com/zr001/writeimges/raw/master/images/image-20200909093912093.png)
>
> 面片拟合
>
> ![image-20200909094150315](https://gitee.com/zr001/writeimges/raw/master/images/image-20200909094150315.png)

