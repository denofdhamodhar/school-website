### CODER CODER | SCHOOL WEBSITE 
**Live Link:-** [coder coder school website](https://school-website-seven-phi.vercel.app/)

<hr>

> [!IMPORTANT]
> On the first commit, I commited wrong font version. So clone the second commit.

* Clone the second commit.
* Start the project.
* Read/Check the css code ( In boilerplate css added default css code )

```
Basic Folder structure

.
├── assets
├── css ➡️ Styles were created in subfolders but connected in style.css
│   ├── global
│   │   └── boilerplate.css
│   └── style.css
├── fonts
│   ├── plus-jakarta-sans-v8-latin-500.woff2
│   ├── plus-jakarta-sans-v8-latin-700.woff2
│   └── plus-jakarta-sans-v8-latin-800.woff2
├── index.html
└── README.md

```
```
CSS Folders 

Root folder
Root folder holds "style.css", It imports styles from subfolders.

Global folder
boilerplate.css -> website purpose added styles (like default styles, colors)
fonts.css -> fonts for website (500, 700, 800)
button.css -> for buttons
layout.css -> contain one main wrapper it sets padding left and right of sections. 
( one the desktop screen we fixed width of the wrapper to 75em = 1200px, if we use max-width then we need to use marign:auto)

Components folder
header.css -> header styles
hero.css -> hero styles
courses.css -> courses styles
footer.css -> footer styles

```
```
Fontography

Google font: Plus Jakarta Sans
Extra Bold -> 800
Bold -> 700
Medium -> 500
```

## Steps followed
1. Added common default css code in " boilerplate.css " .
2. Added color for the website in boilerplate css.
3. Added fonts and its font-weight in body, heading css elements. 
4. Completed whole website HTML SKELETON. - 40:13 

After skeleton completed, Now targeting each semantic tags
> [!IMPORTANT]
> For every website, Starts to develop from small, medium and desktop.

5. Now at header in small screen while creating a button. we saw custom fontsizes on mobile to tablet, and desktop.
6. Header section completed. - 1:12:52
7. What I learnt from hero section
```
a. If we use margin-block it affects overflow the content into inline elements.
- To fix this, change inline elements to inline-block elements.
- Use the padding properties is the best pratices.

b. Suppose if a hero section have a left text, right image, The image should use position:absoulte and we need to responsive to all the screens. "Picture" tag is very much useful to change across very screen sizes.

c. To decrease size of the image and fixed use "max-width".

d. Left text box, The middle element fixes the space between upper element and bottom elements. The middle is a "p" tag, max-width: "character_size" ch very much helpful.

e. Mainly design eye-catch is important.
```
8. Hero section completed. - 2:11:00
9. What I learnt from courses section
```
a. Grid gap plays a major role for responsive along with padding for the blocks.

b. Gird block again takes as a grid to the maintain the content of the block box good. so here to spacing the content used "Grid template rows": min-content 1fr min-content. For the middle content takes 1fr. For the "Get started" anchor tag acts as self end.
```
10. Courses section completed. - 2:48:33
11. Footer section as same as the header section.
