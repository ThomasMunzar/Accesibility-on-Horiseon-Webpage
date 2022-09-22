# Accesibility-on-Horiseon-Webpage

## Description

The goal of this project was to take a website that already had .HTML and .CSS code and make it follow accessibility standards as well has basic HTML and CSS formating. I did this following these next few steps;


    1. Take existing code and make it follow accessibility standards.
    2. Add semantic HTML elements to the code.
    3. Add Alt attributes to Icons and Images
    4. Make sure heading attributes fell in sequential order
    5. Make sure code does not unnecessarily repeat itself.


I did stuggle to read through the code on this project. I am not used to reading code at all but I am happy that I was able to find things in the code that did not make sense to me.  For instance, alot of the elements were labeled 'div'.  This worked fine with the linked css folder and look of the website but it did not make the code easy to read.  I went through the code and swapped out 'div' elements with : 'header, nav, article, footer' and other semantic HTML elements that make HTML easier to read.

### Challenges

I had a few challenges with this project. For instance, I was able to locate all the images that I saw on the website in the HTML and give them Alt values except for the largest picture on the website. It wasnt until I looked in the .CSS that I saw the main image was embeded in the CSS file as a background image. I did not know this was possible and I did not know how to add an Alt to it.

After research and asking for help I found out that you can if a CSS background image an Alt using '<title>'

My code for that looked like this:

'<main class="hero">
        <div class="hero" title="Photo of co-workers working at a table"></div>'


Another issue I did not know right away was how to solved repeated code in the CSS folder.  This code had so many components with the same attributes. After some research I was able to consolodate most the the CSS file.

My code finally looked a bit cleaner:

'.benefit-lead,.benefit-brand,.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-lead h3,.benefit-brand h3,.benefit-cost h3{
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img,.benefit-brand img,.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.search-engine-optimization,.online-reputation-management,.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.search-engine-optimization img,.online-reputation-management img,
.social-media-marketing img {
    max-height: 200px;
}

.search-engine-optimization h2,
.online-reputation-management h2,
.social-media-marketing h2{
    margin-bottom: 20px;
    font-size: 36px;
}
.footer,.footer h2 {
    padding: 30px;
    clear: both;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
    font-size: 20px;
}'


It looks long hear but it was much longer before.


