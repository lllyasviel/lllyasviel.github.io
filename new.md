[中文版](https://lllyasviel.github.io/chinese)

![image](https://user-images.githubusercontent.com/19834515/31306645-c9971bc2-ab86-11e7-915f-0dad0b1f9c58.png)

This is a screenshot of the web APP. If you are a beginner, we recommend you to download the *default_refernces.zip*. You can get this file by clicking the link marked in red arror.

![image](https://user-images.githubusercontent.com/19834515/30780911-3577021a-a148-11e7-85fd-b76eeea8a31a.png)

Then decompress the zip file and you will get some illustrations like this.

![image](https://user-images.githubusercontent.com/19834515/30780936-83e1c46c-a148-11e7-9e68-2eea4ad4639c.png)

There are 15 illustations in the default package with different color. These illustrations are well-suited for AI to learn and you can deal with nearly all sketches with these 15 images.

<img src="https://user-images.githubusercontent.com/19834515/30780973-55764520-a149-11e7-8539-a6ff758be8bf.jpg" height = "512"/>

We will use this sketch as an example. This sketch is rich in detailed features and it is very suitable for AI colorization. We will describe some usages of our web APP in the colorization procedure.

*The AI is also good at deal with simple sketches without detailed features, check [here](https://github.com/lllyasviel/style2paints/blob/master/README.md) and find the example 5.*

![image](https://user-images.githubusercontent.com/19834515/31306675-6cc3daf6-ab87-11e7-854a-8de39c30af69.png)

Now upload our sketche and reference. We use a reference illustration with blue hair and gray background. You can select any reference images with any color. You can improve the colorization quality via trying more references and find a best one. There are nearly no trick to find the best reference in a single time. The more, the better. We highly recommend you use the images in *default_refernces.zip* and these images are selected by the author, well-suited for AI to read.

![image](https://user-images.githubusercontent.com/19834515/31306681-9b12ea6e-ab87-11e7-8299-3fb54188ec42.png)

You can one of the two buttons to colorize your sketch.

![image](https://user-images.githubusercontent.com/19834515/30781146-a850f95e-a14c-11e7-8f6d-ea45159979f1.png)

This four toggles are important for AI painting. We now list the V1-V4 results below.

![image](https://user-images.githubusercontent.com/19834515/30781175-f61130f0-a14c-11e7-90bc-e0643b830052.png)

![image](https://user-images.githubusercontent.com/19834515/30781183-17ca6f18-a14d-11e7-8975-78f79b22226a.png)

![image](https://user-images.githubusercontent.com/19834515/30781210-64efe372-a14d-11e7-9c69-7d213ad0f573.png)

![image](https://user-images.githubusercontent.com/19834515/30781221-950d49d2-a14d-11e7-8e4c-4a3a138ed9ac.png)

Here is the comparison between V1-V4.

![image](https://user-images.githubusercontent.com/19834515/30781245-1ebc5240-a14e-11e7-9c92-c70eae744af8.png)

Here is the detailed comparison.

In this example, I think V4 is best, so lets continue with V4.

![image](https://user-images.githubusercontent.com/19834515/30781636-81939cf0-a155-11e7-8f5f-b023cff12ad4.png)

When we move our mouse to the reference image, the cursor will becomes a cross. In fact, the reference image is a color picker and you can select any color in it. Now we select the skin color on the face. A tiny square is left to the reference image and the selected color will be shown here. In the screenshot above, the skin color is selected and the selected color is shown on the tiny square.

![image](https://user-images.githubusercontent.com/19834515/30781698-5bf1aec8-a156-11e7-9ee5-01ada5f5b7b4.png)

After the skin color is selected, you can move your mouse to the sketch and add hints for the AI by clicking where should be skin. You can click *colorize* to get new result and then add some additional hints and then click *colorize* and then add hints......But keep in mind that **small and pointed hints are fine and you do not need to full fill some color blocks**.

![image](https://user-images.githubusercontent.com/19834515/30781714-b948f3a6-a156-11e7-9e3c-1562bd6a33e1.png)

Now we add black hints to the tail.

![image](https://user-images.githubusercontent.com/19834515/30781725-f1555a50-a156-11e7-97ad-2c39fe5236cc.png)

Now the ears.

![sep2401000426812 fin](https://user-images.githubusercontent.com/19834515/30781737-1599bf00-a157-11e7-8ddb-00de5416fe13.png)

After about 5 minutes, we get a good result. After this example, some may think of that V4 is always the best and we do not need V1-V3, but in fact V4 has its own drawbacks.

![image](https://user-images.githubusercontent.com/19834515/30924534-95c6cff6-a3e1-11e7-897b-b8871267489d.png)

![image](https://user-images.githubusercontent.com/19834515/30924506-811735dc-a3e1-11e7-88af-78dc2eeeedf6.png)

![image](https://user-images.githubusercontent.com/19834515/30924716-2981f64e-a3e2-11e7-9d51-ea2b67a8cda6.png)

Each of V1, v2, V3, V4 has advantages and disadvantages, and V2 is the best in the example above.

![image](https://user-images.githubusercontent.com/19834515/31159367-189d7d4e-a8fb-11e7-92ae-6e0c9b6f3913.png)

*FSAA* toggles are important. The *D0* and *D1* can denoise the results and the *SX* can do style transfer for illustrations.

![image](https://user-images.githubusercontent.com/19834515/31159475-f3dd5096-a8fb-11e7-80db-6fb61555c09f.png)

![image](https://user-images.githubusercontent.com/19834515/31159580-aca5c37e-a8fc-11e7-85c0-4393d88873e9.png)

![image](https://user-images.githubusercontent.com/19834515/31159449-c253b452-a8fb-11e7-8697-a75f6d588a6b.png)

The 3 screenshots above show how *D1* improves the result by denoising.

![image](https://user-images.githubusercontent.com/19834515/31159516-412bd214-a8fc-11e7-8772-e5b479bf4027.png)

![image](https://user-images.githubusercontent.com/19834515/31159525-587f8c62-a8fc-11e7-82bb-0f3a64cd0775.png)

The 2 screenshots above show how *SX* do style transfer for illustations.

PS: You can add any color hints, but the AI will sometimes resist to the hints in some cases.

PSS: The secret of a good result is trying more reference images, and the *default_refernces.zip* is recommended.
