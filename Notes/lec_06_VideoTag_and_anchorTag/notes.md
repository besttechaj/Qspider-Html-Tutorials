Totally there are 4 media tags available :

a) < img src="" alt="" > : image tag, it is the only empty tag in the media tag

b) video tag

<!--  <video attributes></video> -->

attributes are :
controls : Video / audio will not play until "controls" attribute are not mention.

    autoplay : To play file directly whenever someone open it. "Autoplay" will not work until muted is applied.

    muted : It is important to apply muted after autoplay because while visiting a website if suddenly audio play which is not referred as a good website like In YOUTUBE, While opening the youtube only video will play but audio are muted.

    loop : If you want to play video automatically again after video ends you have to pass loop attribute.
    <video src="video_path_file" controls autoplay muted loop></video>

c) audio tag : <!-- controls : to view audio file it is mandatory to provide control -->

    <audio src="audio_path_file" controls></audio>

d) iframe tag

    <!-- iframe : stands for inline frame. To display any website or your previous locally created website on your current webpage, you need to provide iframe tag followed by its path   -->

    <iframe src="http://testfreshers.com" frameborder="0"></iframe>

    <iframe src=". ./lec_03_Tables/table_type01/table1.html"></iframe>

> > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > >

ANCHOR TAG

<!--
      To navigate some one to any other website we use "Anchor Tag"
       anchor tag : <a href="" target="_blanket"></a>
       href means hypertext reference

       Inside href = "", Here we need to provide other website link or any previous locally created website path

       target = "_blank" is used to open the other website in a new tab
     -->

    <a
      href="https://www.google.com/search?q=news&oq=news&gs_lcrp=EgZjaHJvbWUqEggAEEUYOxiDARixAxjJAxiABDISCAAQRRg7GIMBGLEDGMkDGIAEMg0IARAAGIMBGLEDGIAEMgYIAhBFGDsyBggDEEUYPDIGCAQQRRg8Mg0IBRAAGIMBGLEDGIAEMg0IBhAAGIMBGLEDGIAEMgoIBxAAGJIDGIAEMg0ICBAAGJIDGIAEGIoFMg0ICRAAGIMBGLEDGIAE0gEIMTk1MWowajmoAgCwAgA&client=ms-android-samsung-gj-rev1&sourceid=chrome-mobile&ie=UTF-8"
      id="nn"
      >news</a
    >
    <a href="../list/list.html" target="_blank">Table</a>

    <!-- To directly jump to mail application  need to give attribute like href="mailto: your_mail_id"  -->

    <a href="mailto:asap2656@gmail.com">Mail-Us</a>

    <!-- To directly jump to call option need to give attribute like href="tel:any_number"  -->

    <a href="tel:8445334702">Contact_Us</a>

    <a href="fb.com">
      <img src="../list/vv.jpeg" />
    </a>

INTERVIEW QUESTION :

 <!-- To navigate someone to any other website while clicking on the image  -->

    <a href="website_link" target="_blank">
      <img src="image_source" alt="any alternate image name" />
    </a>

4 types of attribute we can use with anchor tag <a></a> are :
a) To jump to any live website

<!-- <a
      href="website_url"
      id="nn"
      >news</a> -->

b) To jump to locally created website

<!-- <a href="../list/list.html" target="_blank">Table</a> -->

c) to mail some one directly while clicking on a text/ button

<!-- <a href="mailto:asap2656@gmail.com">Mail-Us</a> -->

d) to call some one while clicking on text/ button

<!-- <a href="tel:8445334702">Contact_Us</a> -->
