# Star Alignment
Align several astronomy / nightscape images by star points in images. Apply to wide angle lens
as well as tele-lens.

A detailed blog describing the motivation and algorithm can be found at [This Site](https://zhuanlan.zhihu.com/p/25311770) 
(which is my special column at zhihu.com, of course, in Chinese)

## matlab code

Check `star_align_average_main.m` as the main script.

## python code

Check `imgprc.py` and run it. Need OpenCV, NumPy, SciPy, pywt, piexif, matplotlib (optional), tiffile be installed. Matplotlib
is used for debug, and there is no affect if you remove relevent lines.


# 星点对齐叠加
对多张星空图片进行星点对齐并叠加，适用于深空、星野图片，适用于长焦、广角拍摄的图片，改正了常见叠加方法无法对齐广角星空的缺点。

在我的知乎专栏[星野摄影降噪（2）：对齐叠加](https://zhuanlan.zhihu.com/p/25311770)中，对算法思路和细节有详细描述，欢迎讨论。

## matlab 代码

脚本 `star_align_average_main.m` 为主脚本。

## python 代码

所有算法都在 `imgprc.py` 文件中，依赖的第三方包：OpenCV, NumPy, SciPy, pywt, piexif, matplatlib（可选）, tiffile。其中 matplotlib
主要用于调试输出中间图，去掉相关代码对实际功能没有影响。
