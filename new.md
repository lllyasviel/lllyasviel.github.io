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

![image](https://user-images.githubusercontent.com/19834515/31306698-ed00cc6a-ab87-11e7-91ca-ab8d45597c21.png)

This four toggles are important for AI painting. We now list the results below.

![image](https://user-images.githubusercontent.com/19834515/31306706-1b17d918-ab88-11e7-9670-f7b54b9013bd.png)

![image](https://user-images.githubusercontent.com/19834515/31306707-28acc07a-ab88-11e7-98c7-56ddacef264a.png)

![image](https://user-images.githubusercontent.com/19834515/31306709-367de170-ab88-11e7-9ad3-9e5caacc003a.png)

![image](https://user-images.githubusercontent.com/19834515/31306714-462c2b86-ab88-11e7-98b9-9d791a724aef.png)

Here is the comparison between V1-V4.

![image](https://user-images.githubusercontent.com/19834515/30781245-1ebc5240-a14e-11e7-9c92-c70eae744af8.png)

Here is the detailed comparison.

In this example, I think V4 is best, so lets continue with V4.

![image](https://user-images.githubusercontent.com/19834515/31306723-7826e5e0-ab88-11e7-9f79-0c19cee53f91.png)

![image](https://user-images.githubusercontent.com/19834515/31306728-83325500-ab88-11e7-8237-8ef091145f70.png)

![image](https://user-images.githubusercontent.com/19834515/31306730-8b5e3d8e-ab88-11e7-8534-75cfbea93ed6.png)

When we move our mouse to the reference image, the cursor will becomes a cross. In fact, the reference image is a color picker and you can select any color in it. Now we select the skin color on the face. A tiny square is left to the reference image and the selected color will be shown here. In the screenshot above, the skin color is selected and the selected color is shown on the tiny square.

![image](https://user-images.githubusercontent.com/19834515/31306746-d17453e4-ab88-11e7-947c-a3c12ffaae6e.png)

After the skin color is selected, you can move your mouse to the sketch and add hints for the AI by clicking where should be skin. You can click *colorize* to get new result and then add some additional hints and then click *colorize* and then add hints......But keep in mind that **small and pointed hints are fine and you do not need to full fill some color blocks**.

![image](https://user-images.githubusercontent.com/19834515/31306754-f7326abc-ab88-11e7-884a-eb0cb7b88ab5.png)

Now we add black hints to the tail.

![sep2401000426812 fin](https://user-images.githubusercontent.com/19834515/30781737-1599bf00-a157-11e7-8ddb-00de5416fe13.png)

After about 5 minutes, we get a good result. After this example, some may think of that V4 is always the best and we do not need V1-V3, but in fact V4 has its own drawbacks.

![image](https://user-images.githubusercontent.com/19834515/31306776-8169df80-ab89-11e7-906c-19b94eaf9c90.png)

![image](https://user-images.githubusercontent.com/19834515/31306783-951b479e-ab89-11e7-9c7b-f08f095d59b6.png)

![image](https://user-images.githubusercontent.com/19834515/31306786-b1f5ec34-ab89-11e7-99db-c8d20cfcfccb.png)

Each of V1, v2, V3, V4 has advantages and disadvantages, and V2 is the best in the example above.

![image](https://user-images.githubusercontent.com/19834515/31306789-ccc407f8-ab89-11e7-8bf7-a5bded1ca991.png)

These toggles related to inputs are important. 

![image](https://user-images.githubusercontent.com/19834515/31307112-d0e12dc4-ab8f-11e7-9bc5-309148312962.png)

![image](https://user-images.githubusercontent.com/19834515/31159580-aca5c37e-a8fc-11e7-85c0-4393d88873e9.png)

![image](https://user-images.githubusercontent.com/19834515/31306841-5eca8b7c-ab8a-11e7-9412-679380a7b119.png)

The 3 screenshots above show how if improves the result by denoising.

![image](https://user-images.githubusercontent.com/19834515/31307131-0f9352cc-ab90-11e7-9366-e19e2854fac0.png)

![image](https://user-images.githubusercontent.com/19834515/31307142-44e43d06-ab90-11e7-8005-0a8006c71bad.png)

![image](https://user-images.githubusercontent.com/19834515/31306849-941f4a60-ab8a-11e7-890b-88bae54f8495.png)

![image](https://user-images.githubusercontent.com/19834515/31306854-b451d7a8-ab8a-11e7-8390-662559eb4498.png)

The 3 screenshots above show how it do style transfer for illustations.

PS: You can add any color hints, but the AI will sometimes resist to the hints in some cases.

PSS: The secret of a good result is trying more reference images, and the *default_refernces.zip* is recommended.
