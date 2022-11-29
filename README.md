# Challenge-1

## Criteria 1: Semantic HTML Elements

The innitial html code given uses `<div>` tags instead of proper html semantics like `<header>`, `<aside>`, `<section>` and `<article>` which consist of the basic elements. In order to have a proper semantic structure, I replace every tag with `<div>` for the proper semantic equivalent, results shown in the following image:

<img width="638" alt="Captura de pantalla 2022-11-28 a la(s) 20 08 33" src="https://user-images.githubusercontent.com/118247139/204421048-33514c98-1e3f-449c-b8c5-f988cdce3655.png">

> ###### Note: The tag `<span>` wasn´t changed as it was necessary for the divison and conexion in the css.style file and did not interrupt a proper semantic flow.

## Criteria 2: Logical HTML Structure

Another problem presented by the innitial html code is the structure of the document, where the file is not only wrongly distributed but also has problems in funcionallity that directly affected the website. For this, a semantic logical structure was placed and comments where made inside the file that detail the process and explain the changes made.

<img width="668" alt="Captura de pantalla 2022-11-29 a la(s) 0 14 33" src="https://user-images.githubusercontent.com/118247139/204452959-f52112e8-a32e-4514-add2-8f4739711cd0.png">

## Criteria 3: Alt Attributes in Images

As both a user and a programmer, I want to be able to see a detailed description of the image I'm going to position so that I don´t have to keep accessing this file whenever I want to remember what it is. From this, and from the criteria given in the initial file, a brief description of the images used within the website is given, appended with `alt` format within the `<img>` tag.

<img width="760" alt="Captura de pantalla 2022-11-28 a la(s) 17 15 50" src="https://user-images.githubusercontent.com/118247139/204400658-f5ed04d1-f280-4997-bc73-436d0b1151a8.png">

## Criteria 4: Sequential Order

In order to have easier accessibility when editing the website, a sequential structure must be made where the CSS file is directly related to the HTML file. For this case most of the variables in the CSS file are out of order and therefore it is necessary to make corrections as follows.

<img width="944" alt="Captura de pantalla 2022-11-28 a la(s) 17 14 07" src="https://user-images.githubusercontent.com/118247139/204400460-864b2014-fcf9-468f-b128-1bfcdd9a82f9.png">
<img width="987" alt="Captura de pantalla 2022-11-28 a la(s) 17 14 20" src="https://user-images.githubusercontent.com/118247139/204400474-2c16d665-20e5-4c61-94a9-3f74f22d58ff.png">
<img width="912" alt="Captura de pantalla 2022-11-28 a la(s) 17 14 33" src="https://user-images.githubusercontent.com/118247139/204400496-ce23880d-81ce-4945-9a2b-2ac1ef780b53.png">

## Fixing Bugs

In order not to affect the functionality of the website for users, corrections were made related to failures in the use of links within the same page found in the navigation menu. This is because the id element was not linked properly, so the corrections are made to have a functional and complete site.

```
<article id="search-engine-optimization" class="search-engine-optimization">
        <!-- id missing in order to proper link functionality-->
```

<img width="884" alt="Captura de pantalla 2022-11-28 a la(s) 17 15 21" src="https://user-images.githubusercontent.com/118247139/204400582-344514ad-1d83-4687-ab20-49ff1ee89473.png">

## Recommendations

Within the file there are different comments both in the HTML file and in the CSS of possible code configurations that can allow the page to have the best performance. Among these comments is the possibility of anchoring the header so that the user can access the menu whenever they need it, changing the title to have a more suitable one that matches the website, joining multiple elements in CSS to save code, etc.

Example (extraction of code):
```
.search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2   {
    /* joined the 3 categories in order to reduce space in code as all share the same characteristics*/
    margin-bottom: 20px;
    font-size: 36px;
}
```

> Visualize the final page [here](https://drums180.github.io/Challenge-1/#social-media-marketing)

