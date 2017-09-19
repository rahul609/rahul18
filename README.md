# rahul18

ANS 3- let m = document.querySelector(".item-page__main-title");
undefined
m
<h1 title=?"Java Programming:? A Comprehensive Introduction" data-a8n=?"item-page__main-title" class=?"item-page__main-title is-truncated" style=?"word-wrap:? break-word;?">?Java Programming: A Comprehensive... ?</h1>?
m.text
undefined
m.textContent="Dominos pizza";
"Dominos pizza"

ANS 4-let hardy = document.querySelector(".product-image__image--single");
undefined
hardy
<img class=?"product-image__image--single" src=?"https:?/?/?dynamic.indigoimages.ca/?books/?007802207x.jpg?altimages=false&scaleup=true&maxheight=515&width=380&quality=85&sale=4&lang=en" data-a8n=?"product-image__image" alt=?"Java Programming:? A Comprehensive Introduction by Herbert Schildt">?
hardy.src
"https://dynamic.indigoimages.ca/books/007802207x.jpg?altimages=false&scaleup=true&maxheight=515&width=380&quality=85&sale=4&lang=en"
hardy.src="http://findthemoat.com/wp-content/uploads/2017/02/dominospizze.jpg";
9780078022074-item.html?ikwid=java+programming&ikwsec=Home&ikwidx=1:1 [Report Only] Refused to load the image 'http://findthemoat.com/wp-content/uploads/2017/02/dominospizze.jpg' because it violates the following Content Security Policy directive: "img-src 'self' data: blob: *.indigo.ca *.indigoimages.ca *.bazaarvoice.com *.nr-data.net https://*.cloudfront.net https://*.doubleclick.net https://*.facebook.com https://*.googleapis.com https://*.google-analytics.com https://*.google.com https://*.google.ca https://*.gstatic.com https://*.pinimg.com https://*.twimg.com https://*.twitter.com https://*.webtype.com *.omtrdc.net https://t.co https://notify.bugsnag.com https://s3.amazonaws.com https://*.checkout.visa.com https://tracker.marinsm.com https://kbimages1-a.akamaihd.net www.paypalobjects.com https://*.paypal.com https://*.piwikpro.com https://secure.adnxs.com https://www.offlinx.com https://gtrk.s3.amazonaws.com https://heapanalytics.com".

9780078022074-item.html?ikwid=java+programming&ikwsec=Home&ikwidx=1:1 Mixed Content: The page at 'https://www.chapters.indigo.ca/en-ca/books/java-programming-a-comprehensive-introduction/9780078022074-item.html?ikwid=java+programming&ikwsec=Home&ikwidx=1' was loaded over HTTPS, but requested an insecure image 'http://findthemoat.com/wp-content/uploads/2017/02/dominospizze.jpg'. This content should also be served over HTTPS.
"http://findthemoat.com/wp-content/uploads/2017/02/dominospizze.jpg"




ANS 5- let navigation =["The" , "Noblest" , "Pleasure" , "Is" , "The" , "Joy" , "Of" , "Pizza"];
undefined
let o = document.querySelectorAll(".top-nav__list-link");
undefined
o = document.querySelectorAll("[class^=top-nav__list-link]");

o = Array.from(document.querySelectorAll("[class^=top-nav__list-link]"));

o.map( (navitem , idx) => navitem.textcontent = o[idx]);



ANS 6-let l = document.querySelector("[data-a8n]");
undefined
l
l = document.querySelector("[data-a8n=indigo-logo]");
let pel =document.createElement("img"); 
undefined
pel
<img>?
pel.src = "http://www.logodesignworkz.com/images/Best%20logos/1.jpg"

pel
<img src=?"http:?/?/?www.logodesignworkz.com/?images/?Best%20logos/?1.jpg">?
l

let ppEl = document.querySelector("[data-a8n=indigo-logo] svg");
undefined
ppEl
<svg xmlns=?"http:?/?/?www.w3.org/?2000/?svg" width=?"130" height=?"66" viewBox=?"0 0 130 66">?…?</svg>?
l.replaceChild(pel , ppEl);

