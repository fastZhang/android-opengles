### b612 大图像*泛文娱：（持续）
图形图像处理会涉及：
   * 数字图像处理
   * 各平台api编程，opengl cv
   * AI处理能力，代表cnn
   * 音视频相关ffmpeg openglsl codec

应用领域：
   * 相机
   * 后编辑
   * 音视频
   * 短视频
   * 美颜
   ......


#### opengl
* cpu/gpu：简单印象：
        cpu计算处理能力强，但是是顺序执行业务逻辑，我们在编码后的执行一般都在cpu上。gpu相反，一般开启硬件加速之类的说法都会掉用gpu处理，如view的绘制，和opengles编程。
        对于一张图像，用cpu的方式去for遍历修改像素点，和gpu并行，同时修改数据点，由于gpu计算能力较弱，所以不适合做复杂运算如大量if else和循环
        《其他百度补充》

* 编程接口：jni层 java层 RenderScript 。 opengles可以在ndk和java层编写 。ndk层写的话就可以跨平台和相对加密了
