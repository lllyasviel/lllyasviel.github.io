[中文版](https://lllyasviel.github.io/chinese)

**The author of this article is not skilled at color or painting.**

**All the colorization results are obtained by clicking buttons or canvases.**

![image](https://user-images.githubusercontent.com/19834515/30780925-601df226-a148-11e7-9af2-1c3165bdd6f7.png)

This is a screenshot of the web APP. If you are a beginner, we recommend you to download the *default_refernces.zip*. You can get this file by clicking the link marked in red square.

![image](https://user-images.githubusercontent.com/19834515/30780911-3577021a-a148-11e7-85fd-b76eeea8a31a.png)

Then decompress the zip file and you will get some illustrations like this.

![image](https://user-images.githubusercontent.com/19834515/30780936-83e1c46c-a148-11e7-9e68-2eea4ad4639c.png)

There are 15 illustations in the default package with different color. These illustrations are well-suited for AI to learn and you can deal with nearly all sketches with these 15 images.

<img src="https://user-images.githubusercontent.com/19834515/30780973-55764520-a149-11e7-8539-a6ff758be8bf.jpg" height = "512"/>

We will use this sketch as an example. This sketch is rich in detailed features and it is very suitable for AI colorization. We will describe some usages of our web APP in the colorization procedure.

*The AI is also good at deal with simple sketches without detailed features, check [here](https://github.com/lllyasviel/style2paints/blob/master/README.md) and find the example 5.*

![image](https://user-images.githubusercontent.com/19834515/30781065-0a56eca0-a14b-11e7-8d9e-c9ca94ebdad5.png)

Now upload our sketche and reference. We use a reference illustration with blue hair and gray background. You can select any reference images with any color. You can improve the colorization quality via trying more references and find a best one. There are nearly no trick to find the best reference in a single time. The more, the better. We highly recommend you use the images in *default_refernces.zip* and these images are selected by the author, well-suited for AI to read.

![image](https://user-images.githubusercontent.com/19834515/30781114-d5fe5b5e-a14b-11e7-8d01-2f459a3baccf.png)

Because this sketch is sharp and clean, we do not check the *denoise*.

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

![image](https://user-images.githubusercontent.com/19834515/30781763-64f90538-a157-11e7-9394-2d32258721b1.png)

The *denoise* is an interesting toggle and it sometimes improves the results and sometimes do on the contrary.

![image](https://user-images.githubusercontent.com/19834515/30781776-dae78986-a157-11e7-9b13-ff99f8e8bd68.png)

![image](https://user-images.githubusercontent.com/19834515/30781779-eac9c666-a157-11e7-8006-392cd0da9782.png)

In the example above, the *denoise* works well and removes many noisy lines.

![image](https://user-images.githubusercontent.com/19834515/30781819-a2338256-a158-11e7-81ee-ba49b59c2655.png)

![image](https://user-images.githubusercontent.com/19834515/30781800-4a0c909a-a158-11e7-8f7f-0ecc3e516e12.png)

In this example, it seems hard to tell which is better.

![image](https://user-images.githubusercontent.com/19834515/30781836-f94e5282-a158-11e7-9c0d-de837895a02a.png)

![image](https://user-images.githubusercontent.com/19834515/30781837-fd071e90-a158-11e7-9e7c-43d49bdf3b68.png)

The detailed comparison.

PS: You can add any color hints, but the AI will sometimes resist to the hints in some cases.

PSS: The secret of a good result is trying more reference images, and the *default_refernces.zip* is recommended.
