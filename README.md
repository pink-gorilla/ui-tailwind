# ui-tailwind [![GitHub Actions status |pink-gorilla/ui-tailwind](https://github.com/pink-gorilla/ui-tailwind/workflows/CI/badge.svg)](https://github.com/pink-gorilla/ui-tailwind/actions?workflow=CI)[![Clojars Project](https://img.shields.io/clojars/v/org.pinkgorilla/ui-tailwind.svg)](https://clojars.org/org.pinkgorilla/ui-tailwind)

**End Users** this project is not for you.


Tailwind css themes, wrapped to work with css-loader


```
cd ui-tailwind
clj -X:goldly:npm-install
clj -X:goldly:compile
clj -X:goldly
```
# Tailwind CSS

Tailwind css (https://tailwindcss.com) makes it really easy to build custom ui.

## Template sites

Publicly available templates are written in html. To convert them to hiccup,
you can use this converter:  http://html2hiccup.buttercloud.com/

Differences to html: 
- Reagent does not support style strings; it is necessary to convert style from
string to map.
- svg viewbox has to be :view-box
- html comments need to be commented out with ;

- https://tailwindcss.com/components/cards/
- https://umeshmk.github.io/Tailwindcss-cheatsheet/
- https://mertjf.github.io/tailblocks/
- https://merakiui.com/
- https://www.creative-tim.com/learning-lab/tailwind-starter-kit/presentation
- https://tailwindcomponents.com/
- https://tailwindcomponents.com/components/Cards SAU GEIL
- http://www.heropatterns.com/
- https://kitwind.io/products/kometa/components/headers
- https://github.com/aniftyco/awesome-tailwindcss#ui-libraries-components--templates
- https://emortlock.github.io/tailwind-react-ui/#navmenu
- https://tailwindui.com/


## tailwind optimization 

https://www.pollen.style/addons/grid


Tw
84 colors 3600kb
25 colors 2200kb

5 breakpoints 3600
1 breakpoint 1100 


https://tailwindui.com/components/application-ui/lists/tables



