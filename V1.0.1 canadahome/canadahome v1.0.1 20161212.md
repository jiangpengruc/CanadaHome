## canadahome v1.0.1 第一次迭代

**20161212** 

网站做了第一次迭代更新，主要体现如下：

1. 图片做了自适应，通过设置height和width为100%实现
2. 加入了超链的跳转链接，“阅读更多”可以跳到其他页面
3. 页面右下角插入了一个“返回顶部”的按钮，通过JS实现
4. 删除多余代码


**遗留问题**

1. 使用**@media**进行屏幕适配的时候发现没有效果，可能原因是页面使用**position**,**float**进行定位，导致失效，后续考虑使用**flex**重新布局
2. 超链外部路径，如果是内部页面跳转，是否需要重新开发一个网页，开发的话怎么上传？解决方式是做一个新的Html,上传到和原来html相同位置，然后通过<a href="目标链接"></a>实现
3. “返回顶部”完全是照搬网上的代码，只不过是自己修改了position和size，并没有完全掌握，再研究下，搞个“小火箭返回顶部”

**下次迭代功能 v1.0.2**

1. 完成移动端适配，布局重构
2. 仿Linkedin，zhihu两栏布局
3. 相对路径进行内部跳转
4. 加入JS，或是jQuery


