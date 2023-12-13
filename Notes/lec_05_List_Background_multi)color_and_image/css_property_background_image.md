<!-- for single-color background -->

body{
background-color: red;
}

<!-- for multi-color background -->

body{
background-image: linear-gradient( color1, color2, color3);
}

<!-- full page cover background image -->

step1:
body{
background-image : url(file_path);
}

step 2: if image repeats

body{
background-repeat : no-repeat;
}

step 3: if image size is very small
body{
background-size : cover;
}

note : for better background image, always download images with more horizontal width rather than vertical length

interview question ---> difference between global/universal selector \* and body selector ??

body ---> body's properties will affect in tags only.

\*\* ---> universal/global's properties will affect the tags including content which is having no tags
