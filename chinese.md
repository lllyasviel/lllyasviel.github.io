![image](https://user-images.githubusercontent.com/19834515/30780925-601df226-a148-11e7-9af2-1c3165bdd6f7.png)

首先，你的软件打开之后应该是这个样子的。对于初学者来说应该先点击红框里面的那个下载一个图包。

![image](https://user-images.githubusercontent.com/19834515/30780911-3577021a-a148-11e7-85fd-b76eeea8a31a.png)

下载完成后是这样的。

![image](https://user-images.githubusercontent.com/19834515/30780936-83e1c46c-a148-11e7-9e68-2eea4ad4639c.png)

图包里面有15张色彩跨度比较大，比较适合AI读取的图片，基本上可以处理绝大部分的线稿。

<img src="https://user-images.githubusercontent.com/19834515/30780973-55764520-a149-11e7-8539-a6ff758be8bf.jpg" height = "512"/>

我们使用这张线稿作为一个例子，这张线稿具有较为丰富的纹理信息，比较适合讲解。

*对于纹理信息不丰富的线稿，AI也可以处理的很好，参见[这里](https://github.com/lllyasviel/style2paints/blob/master/README.md)的Example5。*

![image](https://user-images.githubusercontent.com/19834515/30781065-0a56eca0-a14b-11e7-8d9e-c9ca94ebdad5.png)

我们通过*upload sketch*和*upload reference*按钮分别上传了线稿和参考图。这里选择了蓝色发色灰色背景的参考图。参考图片的选择是随意的，结果的好坏也是随机的没有任何规律可循，一般来说需要多试几次。建议使用*default_refernces.zip*里面的参考图片，那些图片是作者筛选出来的成功率比较大的参考图片。

![image](https://user-images.githubusercontent.com/19834515/30781114-d5fe5b5e-a14b-11e7-8d01-2f459a3baccf.png)

由于这张线稿本身的噪点很少，质量较高，所以我们不勾选*denoise*。

![image](https://user-images.githubusercontent.com/19834515/30781146-a850f95e-a14c-11e7-8f6d-ea45159979f1.png)

这四个选项对于上色有重要的意义，现在分别将V1到V4的结果展示出来。

![image](https://user-images.githubusercontent.com/19834515/30781175-f61130f0-a14c-11e7-90bc-e0643b830052.png)

![image](https://user-images.githubusercontent.com/19834515/30781183-17ca6f18-a14d-11e7-8975-78f79b22226a.png)

![image](https://user-images.githubusercontent.com/19834515/30781210-64efe372-a14d-11e7-9c69-7d213ad0f573.png)

![image](https://user-images.githubusercontent.com/19834515/30781221-950d49d2-a14d-11e7-8e4c-4a3a138ed9ac.png)

上面是V1到V4的大致对比。

![image](https://user-images.githubusercontent.com/19834515/30781245-1ebc5240-a14e-11e7-9c92-c70eae744af8.png)

上面是V1到V4的细节对比。

由于笔者认为V4的效果最好，所以我们这里继续使用V4来讲解。

![image](https://user-images.githubusercontent.com/19834515/30781636-81939cf0-a155-11e7-8f5f-b023cff12ad4.png)

首先我们鼠标移动到参考图上，鼠标会变成十字准星。然后我们选取参考图里面的皮肤的颜色。参考图片左下角有一个正方形的小框，里面是你选中的颜色。由于图中选中的是肤色，小正方形预览框中显示的是肤色。（可能有点看不清，但是不妨碍我们讲解。）

![image](https://user-images.githubusercontent.com/19834515/30781698-5bf1aec8-a156-11e7-9ee5-01ada5f5b7b4.png)

接着我们选中颜色后，把鼠标移动到线稿上面，鼠标在应该是肤色的一些部位点击，过程中可以不断点击上色来看效果。

![image](https://user-images.githubusercontent.com/19834515/30781714-b948f3a6-a156-11e7-9e3c-1562bd6a33e1.png)

接着是给尾巴黑色。

![image](https://user-images.githubusercontent.com/19834515/30781725-f1555a50-a156-11e7-97ad-2c39fe5236cc.png)

给耳朵调整颜色。

![sep2401000426812 fin](https://user-images.githubusercontent.com/19834515/30781737-1599bf00-a157-11e7-8ddb-00de5416fe13.png)

五分钟后，这是较为满意的结果。

![image](https://user-images.githubusercontent.com/19834515/30781763-64f90538-a157-11e7-9394-2d32258721b1.png)

*denoise*是一个很有趣的选择。有的时候能够提升质量，有的时候会降低质量。建议用户都试一试。下面是两个例子。

![image](https://user-images.githubusercontent.com/19834515/30781776-dae78986-a157-11e7-9b13-ff99f8e8bd68.png)

![image](https://user-images.githubusercontent.com/19834515/30781779-eac9c666-a157-11e7-8006-392cd0da9782.png)

上面一个例子中，*denoise*效果很明显，把多余的噪点去除了。

![image](https://user-images.githubusercontent.com/19834515/30781819-a2338256-a158-11e7-81ee-ba49b59c2655.png)

![image](https://user-images.githubusercontent.com/19834515/30781800-4a0c909a-a158-11e7-8f7f-0ecc3e516e12.png)

上面一个例子中，*denoise*与否似乎都有优点。

![image](https://user-images.githubusercontent.com/19834515/30781836-f94e5282-a158-11e7-9c0d-de837895a02a.png)

![image](https://user-images.githubusercontent.com/19834515/30781837-fd071e90-a158-11e7-9e7c-43d49bdf3b68.png)

上面是细节对比。
