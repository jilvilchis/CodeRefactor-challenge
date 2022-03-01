# This markdown summarizes the findings and changes to the original code

## HTML

I.Changed the html attribute from class to id for "search-engine-optimzation", so the a tag can work properly

II. Added this meta tag into the head tag to make it more friendly to other devices

< meta name="viewport" content="width=device-width, initial-scale=1.0">

III. Change the title tag and add a favicon to 
< title>Horiseon< /title>

IV. alt text were added to img tags

V. Semantics were incorporated to make the code easier to read, i.e. we modified the overuse of div tags to a semantics html

## CSS

I. add a missing class selector

.seo{
    color: rgb(109,109,109);
}

II. Comments were added to facilitate reading

III. CSS selectors and properties were consolidated and organized in accordance to semantics structure

.benefit-lead,
.benefit-brand,
.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-lead h3,
.benefit-brand h3,
.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img,
.benefit-brand img,
.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.search-engine-optimization,
.online-reputation-management,
.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.search-engine-optimization img, 
.online-reputation-management img,
.social-media-marketing img {
    max-height: 200px;
}

.search-engine-optimization h2,
.online-reputation-management h2,
.social-media-marketing h2  {
    margin-bottom: 20px;
    font-size: 36px;
}

IV. some CSS selectors were refactored in accordance to the html semantics