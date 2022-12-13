# Course Track

{% embed url="https://www.loom.com/share/7d21602f13e64a83ac7acbf307cec170" %}

### How to add a Course Track

* [ ] Add a "Course Track' to your Student Dashboard&#x20;
* [ ] Select a course to be shown inside the course settings
* [ ] Add a block setting for each lesson providing an image thumbnail and lesson description
  * [ ] To quickly get an image thumbnail for your lesson, head over to the Video library and right click on your video thumbnail to save it to your laptop. You may also need to rename the file so that Thinkific's image uploader accepts it.
* [ ] Optionally change the Visibility & Upsell settings to control if the track is shown when the user is not enrolled in the course

### Settings

#### Course Settings

![](<../.gitbook/assets/Screen Shot 2021-07-19 at 4.05.53 PM.png>)

* **Course** - specify the course to be used for the track
* **Heading -** This will be the track heading. \[AUTO] will use the course name
* **Sub Heading** - This will be the track subheading. \[AUTO] will use the course description



#### Visibility & Upsell

This group of settings controls how the track is shown if the student is not enrolled in course. It also allows you to control where you want the student to be sent to in the case of showing a course that they are not enrolled in.

![](<../.gitbook/assets/Screen Shot 2021-05-04 at 9.09.48 PM.png>)

* **When not enrolled:** Decide what happens when they are not enrolled
  * _Hide (track)_ - this will hide the track completely when they are not enrolled in the bundle.&#x20;
  * _Always show_ - (Default) - this will show the track at all times.&#x20;
* **Upsell Options:** Decide what happens when the student clicks on a course that they are not enrolled in.
  * _Upsell (Course Purchase)_ - **`Default`** - this will bring them to the course checkout page
  * _Upsell (Course Landing)_ - this will bring them to the course landing page
  * _Upsell (Custom Page)_ - this will bring them to the custom page you specify&#x20;
* **Custom Upsell Page:** to be used when the Upsell Option is set to _`Upsell (Custom Page)`_

#### Display Settings

* **Show Content Name (Track)** - when checked it will show the lesson name right under the image in the track
* **Show Course Name (Hover)** - when checked, it will show the lesson name on the hover card
* **Number to show at a time** - this will determine how many course to show on the track at once. The less number shown, the larger in height the track will appear.



#### Style Options

![](<../.gitbook/assets/Screen Shot 2021-05-04 at 9.21.56 PM.png>)

* **Normal** - this will be a standard size card (Default)
* **Tall -** this is intended for a more "featured' track. The image dimensions are not the same as the standard card size. So you may want to select images that do not contain text so that they are not cut off. The intention is to draw interest, but not be the main attraction.

#### Lesson Info (Blocks)

You need to specify a lesson block for each lesson that you would like to show a different image and description.

![](<../.gitbook/assets/Screen Shot 2021-07-19 at 4.13.39 PM.png>)

* **Lesson Name** - Be sure to match the lesson name exactly how it appears in the course curriculumn. if the lesson name does not match, then it will use the default settings (course image, chapter name as the description)
* **Description** - Enter a brief description for the lesson. It will appear on hover (Desktop) and on the course card (Mobile). Using _\[CHAPTER NAME]_ SmartText will use the chapter name that the lesson is in.
* **Image** - Upload an image to be used as the Thumbnail. The image will "fill" the background and be auto cropped (center). To quickly create an image for the lesson, locate the video inside the Thinkific Video Library. Then right click on the video thumbnail image in the video listing and save it to your desktop. Rename the image file to be a simple name and then use that image in the lesson info settings.

{% hint style="info" %}
The course track will automatically add new items for each lesson and will use the course image as the default image thumbnail. To specify a different image to be used for each lesson, you will need to add a Lesson info block for each lesson and provide the image and description.
{% endhint %}



