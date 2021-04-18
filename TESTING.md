# Test Cases and Execution Report

![test result screenshot](x)
![test result screenshot](x)
![test result screenshot](x)
![test result screenshot](x)

Full downloadable excel document can be found [here](assets/images/testResults/testResults.xlsx).

Please note these results are a .xlsx file and will require excel, google docs or a compatible program to open the file.

# Issues and Resolutions

## Navigation Scroll-spy:

**Issue:**
The sizing was not consistent, so instead of setting individual margins and paddings on each ID I added the same class to each of them. For instance in #aboutme, #projects and #contact it was padding: 6% 5% 6% 5%; in #aboutme and #projects margin: 5% 0;  and in #contact margin: 0;

**Resolution:**
* Add a class of:  mt-5 and mb-5 to container-fluid elements
* Add a class of container-padding to each container fluid
* Set your padding to: 5% 5% 5% 5%;
* Remove the padding and margins from the individual id rules in css.

## Responsiveness:

**Issue:**
Had issues with the site not being fully responsive since I had target specific platforms. 

**Resolution:**
* Add new media quieres/screens: @media (min-width: 640px), @media (min-width:960px), @media (min-width:1100px), 
@media only screen and (min-width: 100px), @media only screen and (min-width: 768px), @media only screen and (min-width: 992px), 
and @media only screen and (min-width: 1500px).

## Main Logo:

**Issue:**
The Hero image/logo and circle animation jumped to the header. 

**Resolution:**
Fixed this by removing the top property on css style for both outer and inner circle class, and adding media quieres/screens.

## Slogan: 

**Issue:**
Slogan overflow logo.

**Resolution:**
Add margin-top: 300px, and changed px in media quieres to make it look good on different sizes/platforms.

## Images:

**Issue:**
The Images was not responsive and project hover animation was owerflowing.

**Resolution:**
Add: img-fluid img-responsive and image rounded mx-auto d-block classes. And specify different .image height and width, .image:after height and width in media quieres/screens.

# Lighthouse Report

![lighthouse report](xxxx)

# Validator Results

### HTML
![html results](xxx)

### CSS 
![css results](xxx)