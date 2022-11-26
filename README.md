The most important thing to understand is that color-scheme exclusively determines the default appearance, 
whereas prefers-color-scheme determines the stylable appearance.

color-scheme CSS property

1. CSS property.
2. Honoring the color-scheme CSS property requires the CSS to be first downloaded and to be parsed. To aid user agents in rendering the page background with the desired color scheme immediately, a color-scheme value can also be provided in a <meta name="color-scheme"> element.
3. :root{color-scheme:dark light} default write first.

prefers-color-scheme

1. user preference media feature.
2. while styles can be styled in main.css file with 
@media(prefers-color-scheme:dark), can also load which css file with <link media="(prefers-color-scheme:no-preference),(prefers-color-scheme:light)">