---
title: Desolation Cafe
tags: april
date: 2020-04-01
---
<style>
 body {  
    color:var(--wp--preset--color--base);
    font-family:var(--wp--preset--font-family--system-font);
    font-size:var(--wp--preset--font-size--medium);
    line-height:1.6;
  }  
body { 
/* CSS Variables that may have been missed get put on body */ 
    --wp--style--root--padding-top:  0px;  
    --wp--preset--spacing--30: clamp(1.5rem, 5vw, 2rem); 
    --wp--style--root--padding-right:  var(--wp--preset--spacing--30);  
    --wp--style--root--padding-bottom:  0px;  
    --wp--style--root--padding-left:  var(--wp--preset--spacing--30); 
    --wp--style--unstable-gallery-gap:  var( --wp--style--gallery-gap-default, var( --gallery-block--gutter-size, var( --wp--style--block-gap, 0.5em ) ) );  
    --wp--style--unstable-gallery-gap:  var( --wp--style--gallery-gap-default, var( --gallery-block--gutter-size, var( --wp--style--block-gap, 0.5em ) ) );  
} 

:where(body) { 
    background-color: var(--wp--preset--color--cyan-bluish-gray); 
    color: var(--wp--preset--color--base); 
    font-family: var(--wp--preset--font-family--system-font); 
    font-size: var(--wp--preset--font-size--medium); 
    line-height: 1.6; 
    --wp--style--root--padding-top: 0px; 
    --wp--style--root--padding-right: var(--wp--preset--spacing--30); 
    --wp--style--root--padding-bottom: 0px; 
    --wp--style--root--padding-left: var(--wp--preset--spacing--30);
} 

body { 
    margin: 0;
} 

@media all{ 
  html { 
    --wp-admin--admin-bar--height: 32px; 
    scroll-padding-top: var(--wp-admin--admin-bar--height);
  } 
}     


:root { 
    --wp--preset--color--black: #000000; 
    --wp--preset--color--cyan-bluish-gray: #abb8c3; 
    --wp--preset--color--base: #ffffff; 
    --wp--preset--color--secondary: #345C00; 
    --wp--preset--font-size--medium: clamp(1rem, 1rem + ((1vw - 0.2rem) * 0.227), 1.125rem); 
    --wp--preset--font-size--x-large: 2.25rem; 
    --wp--preset--font-family--system-font: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif; 
    --wp--preset--spacing--30: clamp(1.5rem, 5vw, 2rem); 
} 

:root { 
    --wp--style--global--content-size: 650px; 
} 

:root { 
    --wp--style--block-gap: 1.5rem;
} 

.wp-site-blocks { 
    padding-top: var(--wp--style--root--padding-top); 
    padding-bottom: var(--wp--style--root--padding-bottom);
} 

:where(.wp-site-blocks) > *  { 
    margin-block-start: 1.5rem; 
    margin-block-end: 0;
} 

.has-global-padding { 
    padding-right: var(--wp--style--root--padding-right); 
    padding-left: var(--wp--style--root--padding-left);
} 

:where(.wp-site-blocks) > :first-child:first-child  { 
    margin-block-start: 0;
} 

:where(.wp-site-blocks) > :last-child:last-child  { 
    margin-block-end: 0;
} 

@media all{ 
  :where(.wp-block-cover-image, .wp-block-cover) { 
    min-height: 430px; 
    padding: 1em;
  } 

  :where(.wp-block-cover:not(.has-text-color)) { 
    color: #fff;
  } 
}     

:where(body .is-layout-constrained) > *  { 
    margin-block-start: 1.5rem; 
    margin-block-end: 0;
} 

@media all{ 
  .wp-block-cover { 
    align-items: center; 
    background-position: 50%; 
    box-sizing: border-box; 
    display: flex; 
    justify-content: center; 
    overflow: clip; 
    position: relative;
  } 
}     

.has-global-padding > .alignfull  { 
    margin-right: calc(var(--wp--style--root--padding-right) * -1); 
    margin-left: calc(var(--wp--style--root--padding-left) * -1);
} 

:where(body .is-layout-constrained) > :first-child:first-child  { 
    margin-block-start: 0;
} 

@media all{ 
  .wp-block-cover-image:after,.wp-block-cover:after { 
    content: ""; 
    display: block; 
    font-size: 0; 
    min-height: inherit;
  } 

  .wp-block-cover-image:after,.wp-block-cover:after { 
    content: none;
  } 
}     

.has-text-align-center { 
    text-align: center;
} 

.has-black-color { 
    color: var(--wp--preset--color--black) !important;
} 

body .is-layout-constrained > :where(:not(.alignleft):not(.alignright):not(.alignfull))  { 
    max-width: var(--wp--style--global--content-size); 
    margin-left: auto !important; 
    margin-right: auto !important;
} 

:where(h1, h2, h3, h4, h5, h6) { 
    color: #ffffff; 
    font-weight: 400; 
    line-height: 1.4;
} 

:where(h2) { 
    color: #ffffff; 
    font-size: var(--wp--preset--font-size--medium); 
    line-height: 1.1;
} 

:where(figure) { 
    margin: 0 0 1em;
} 

:where(body .is-layout-flex) { 
    gap: 1.5rem;
} 

.is-layout-flex  { 
    display: flex;
} 

.is-layout-flex  { 
    flex-wrap: wrap; 
    align-items: center;
} 

.wp-block-gallery.wp-block-gallery-2 { 
    --wp--style--unstable-gallery-gap: var( --wp--style--gallery-gap-default, var( --gallery-block--gutter-size, var( --wp--style--block-gap, 0.5em ) ) ); 
    gap: var( --wp--style--gallery-gap-default, var( --gallery-block--gutter-size, var( --wp--style--block-gap, 0.5em ) ) );
} 

@media all{ 
  figure.wp-block-gallery.has-nested-images { 
    align-items: normal;
  } 
}     

.wp-block-media-text { 
    box-sizing: border-box; 
    direction: ltr; 
    display: grid; 
    grid-template-columns: 50% 1fr; 
    grid-template-rows: auto;
} 

.wp-block-media-text.has-media-on-the-right { 
    grid-template-columns: 1fr 50%;
} 

.wp-block-gallery.wp-block-gallery-4 { 
    --wp--style--unstable-gallery-gap: var( --wp--style--gallery-gap-default, var( --gallery-block--gutter-size, var( --wp--style--block-gap, 0.5em ) ) ); 
    gap: var( --wp--style--gallery-gap-default, var( --gallery-block--gutter-size, var( --wp--style--block-gap, 0.5em ) ) );
} 

.has-text-align-left { 
    text-align: left;
} 

ul { 
    box-sizing: border-box;
} 

:where(body .is-layout-constrained) > :last-child:last-child  { 
    margin-block-end: 0;
} 

@media all{ 
  .wp-block-cover .wp-block-cover__background  { 
    bottom: 0; 
    left: 0; 
    opacity: .5; 
    position: absolute; 
    right: 0; 
    top: 0; 
    z-index: 1;
  } 

  .wp-block-cover .has-background-dim:not([class*="-background-color"])  { 
    background-color: #000;
  } 

  .wp-block-cover__image-background { 
    z-index: 0;
  } 

  .wp-block-cover .wp-block-cover__image-background  { 
    border: none; 
    bottom: 0; 
    box-shadow: none; 
    height: 100%; 
    left: 0; 
    margin: 0; 
    max-height: none; 
    max-width: none; 
    object-fit: cover; 
    outline: none; 
    padding: 0; 
    position: absolute; 
    right: 0; 
    top: 0; 
    width: 100%;
  } 

  .wp-block-cover .wp-block-cover__inner-container  { 
    color: inherit; 
    width: 100%; 
    z-index: 1;
  } 
}     

body .is-layout-flex > *  { 
    margin: 0;
} 

@media all{ 
  .wp-block-gallery.has-nested-images figure.wp-block-image  { 
    box-sizing: border-box; 
    display: flex; 
    flex-direction: column; 
    flex-grow: 1; 
    justify-content: center; 
    max-width: 100%; 
    position: relative;
  } 

  .wp-block-gallery.has-nested-images figure.wp-block-image:not(#individual-image)  { 
    margin: 0; 
    width: calc(50% - var(--wp--style--unstable-gallery-gap, 16px)/2);
  } 

  .wp-block-gallery.has-nested-images.is-cropped figure.wp-block-image:not(#individual-image)  { 
    align-self: inherit;
  } 
}     

@media (min-width: 600px){ 
  .wp-block-gallery.has-nested-images.columns-default figure.wp-block-image:not(#individual-image)  { 
    width: calc(33.33% - var(--wp--style--unstable-gallery-gap, 16px)*.66667);
  } 
}     

.wp-block-media-text .wp-block-media-text__content  { 
    align-self: center;
} 

.wp-block-media-text .wp-block-media-text__content  { 
    direction: ltr; 
    grid-column: 2; 
    grid-row: 1; 
    padding: 0 8%; 
    word-break: break-word;
} 

.wp-block-media-text.has-media-on-the-right .wp-block-media-text__content  { 
    grid-column: 1; 
    grid-row: 1;
} 

.wp-block-media-text .wp-block-media-text__media  { 
    align-self: center;
} 

.wp-block-media-text .wp-block-media-text__media  { 
    grid-column: 1; 
    grid-row: 1; 
    margin: 0;
} 

.wp-block-media-text.has-media-on-the-right .wp-block-media-text__media  { 
    grid-column: 2; 
    grid-row: 1;
} 

.wp-block-media-text.is-image-fill .wp-block-media-text__media  { 
    background-size: cover; 
    height: 100%; 
    min-height: 250px;
} 

.wp-block-media-text .wp-block-media-text__content ,.wp-block-media-text.is-vertically-aligned-center .wp-block-media-text__content  { 
    align-self: center;
} 

.wp-block-media-text .wp-block-media-text__media ,.wp-block-media-text.is-vertically-aligned-center .wp-block-media-text__media  { 
    align-self: center;
} 

:where(a:where(:not(.wp-element-button))) { 
    color: var(--wp--preset--color--base); 
    text-decoration: underline;
} 

:where(.wp-block-post-content a:where(:not(.wp-element-button)))  { 
    color: var(--wp--preset--color--secondary);
} 

:where(p.has-text-color:not(.has-link-color)) a  { 
    color: inherit;
} 

:where(a:where(:not(.wp-element-button)):hover) { 
    text-decoration: none;
} 

:where(body .is-layout-flow) > *  { 
    margin-block-start: 1.5rem; 
    margin-block-end: 0;
} 

:where(body .is-layout-flow) > :first-child:first-child  { 
    margin-block-start: 0;
} 

:where(body .is-layout-flow) > :last-child:last-child  { 
    margin-block-end: 0;
} 

@media all{ 
  .entry-content .wp-block-kadence-rowlayout.alignfull  { 
    text-align: inherit; 
    margin-bottom: 0;
  } 

  .wp-block-gallery.has-nested-images figure.wp-block-image > a  { 
    flex-direction: column; 
    flex-grow: 1; 
    margin: 0;
  } 

  .wp-block-gallery.has-nested-images.is-cropped figure.wp-block-image:not(#individual-image) > a  { 
    display: flex;
  } 

  .wp-block-gallery.has-nested-images.is-cropped figure.wp-block-image:not(#individual-image) a  { 
    flex: 1 0 0%; 
    height: 100%; 
    object-fit: cover; 
    width: 100%;
  } 
}     

:where(h3) { 
    font-size: var(--wp--preset--font-size--x-large);
} 

:where(img[class*="wp-image-"])  { 
    height: auto; 
    max-width: 100%;
} 

.wp-block-media-text__media img  { 
    height: auto; 
    max-width: unset; 
    vertical-align: middle; 
    width: 100%;
} 

.wp-block-media-text.is-image-fill .wp-block-media-text__media img  { 
    clip: rect(0,0,0,0); 
    border: 0; 
    height: 1px; 
    margin: -1px; 
    overflow: hidden; 
    padding: 0; 
    position: absolute; 
    width: 1px;
} 

.wp-block-image img  { 
    box-sizing: border-box; 
    height: auto; 
    max-width: 100%; 
    vertical-align: bottom;
} 

@media all{ 
  .wp-block-gallery.has-nested-images figure.wp-block-image img  { 
    display: block; 
    height: auto; 
    max-width: 100%!important; 
    width: auto;
  } 

  .wp-block-gallery.has-nested-images.is-cropped figure.wp-block-image:not(#individual-image) img  { 
    flex: 1 0 0%; 
    height: 100%; 
    object-fit: cover; 
    width: 100%;
  } 

  .kt-row-layout-inner { 
    position: relative; 
    border: 0 solid rgba(0,0,0,0);
  } 

  .kt-row-layout-inner:before,.kb-row-layout-wrap:before { 
    clear: both; 
    display: table; 
    content: "";
  } 

  .kt-row-column-wrap { 
    display: grid; 
    grid-template-columns: minmax(0, 1fr); 
    gap: var(--global-row-gutter-md, 2rem) var(--global-row-gutter-md, 2rem); 
    grid-auto-rows: minmax(min-content, max-content); 
    z-index: 1; 
    position: relative;
  } 

  .alignfull > .kt-row-layout-inner > .kt-row-column-wrap  { 
    padding-left: var(--global-content-edge-padding, 15px); 
    padding-right: var(--global-content-edge-padding, 15px);
  } 
}     

#kt-layout-id_a807f8-d8 > .kt-row-column-wrap  { 
    align-content: start;
} 

#kt-layout-id_a807f8-d8 > .kt-row-column-wrap  { 
    column-gap: var(--global-kb-gap-none, 0rem ); 
    row-gap: var(--global-kb-gap-md, 2rem); 
    max-width: 99%; 
    margin-left: auto; 
    margin-right: auto; 
    padding-top: var( --global-kb-row-default-top, 25px ); 
    padding-bottom: var( --global-kb-row-default-bottom, 25px ); 
    padding-top: 0px; 
    grid-template-columns: repeat(3, minmax(0, 1fr));
} 

@media all{ 
  .wp-block-kadence-column { 
    display: flex; 
    flex-direction: column; 
    z-index: 1; 
    min-width: 0; 
    min-height: 0;
  } 
}     

.kadence-column_e944e5-d4 { 
    position: relative;
} 

:where(#kt-layout-id_a807f8-d8 > .kt-row-column-wrap) > .wp-block-kadence-column  { 
    justify-content: start;
} 

.kadence-column_c2299a-9c { 
    position: relative;
} 

.kadence-column_7af36b-c2 { 
    position: relative;
} 

@media all{ 
  .kt-inside-inner-col { 
    flex-direction: column; 
    border: 0 solid rgba(0,0,0,0); 
    position: relative; 
    transition: all .3s ease;
  } 
}     

.kadence-column_e944e5-d4 > .kt-inside-inner-col  { 
    border-top-width: 0px; 
    border-right-width: 0px; 
    border-bottom-width: 0px; 
    border-left-width: 0px;
} 

.kadence-column_e944e5-d4 > .kt-inside-inner-col  { 
    border-top-left-radius: 0px; 
    border-top-right-radius: 0px; 
    border-bottom-right-radius: 0px; 
    border-bottom-left-radius: 0px;
} 

.kadence-column_e944e5-d4 > .kt-inside-inner-col  { 
    column-gap: var(--global-kb-gap-sm, 1rem);
} 

.kadence-column_e944e5-d4 > .kt-inside-inner-col  { 
    flex-direction: column;
} 

.kadence-column_e944e5-d4 > .kt-inside-inner-col , .kadence-column_e944e5-d4 > .kt-inside-inner-col::before { 
    border-top-left-radius: 0px; 
    border-top-right-radius: 0px; 
    border-bottom-right-radius: 0px; 
    border-bottom-left-radius: 0px;
} 

.kadence-column_e944e5-d4 > .kt-inside-inner-col::before { 
    opacity: 0.3;
} 

.kadence-column_c2299a-9c > .kt-inside-inner-col  { 
    border-top-width: 0px; 
    border-right-width: 0px; 
    border-bottom-width: 0px; 
    border-left-width: 0px;
} 

.kadence-column_c2299a-9c > .kt-inside-inner-col  { 
    border-top-left-radius: 0px; 
    border-top-right-radius: 0px; 
    border-bottom-right-radius: 0px; 
    border-bottom-left-radius: 0px;
} 

.kadence-column_c2299a-9c > .kt-inside-inner-col  { 
    column-gap: var(--global-kb-gap-sm, 1rem);
} 

.kadence-column_c2299a-9c > .kt-inside-inner-col  { 
    flex-direction: column;
} 

.kadence-column_c2299a-9c > .kt-inside-inner-col , .kadence-column_c2299a-9c > .kt-inside-inner-col::before { 
    border-top-left-radius: 0px; 
    border-top-right-radius: 0px; 
    border-bottom-right-radius: 0px; 
    border-bottom-left-radius: 0px;
} 

.kadence-column_c2299a-9c > .kt-inside-inner-col::before { 
    opacity: 0.3;
} 

.kadence-column_7af36b-c2 > .kt-inside-inner-col  { 
    border-top-width: 0px; 
    border-right-width: 0px; 
    border-bottom-width: 0px; 
    border-left-width: 0px;
} 

.kadence-column_7af36b-c2 > .kt-inside-inner-col  { 
    border-top-left-radius: 0px; 
    border-top-right-radius: 0px; 
    border-bottom-right-radius: 0px; 
    border-bottom-left-radius: 0px;
} 

.kadence-column_7af36b-c2 > .kt-inside-inner-col  { 
    column-gap: var(--global-kb-gap-sm, 1rem);
} 

.kadence-column_7af36b-c2 > .kt-inside-inner-col  { 
    flex-direction: column;
} 

.kadence-column_7af36b-c2 > .kt-inside-inner-col , .kadence-column_7af36b-c2 > .kt-inside-inner-col::before { 
    border-top-left-radius: 0px; 
    border-top-right-radius: 0px; 
    border-bottom-right-radius: 0px; 
    border-bottom-left-radius: 0px;
} 

.kadence-column_7af36b-c2 > .kt-inside-inner-col::before { 
    opacity: 0.3;
} 

.kadence-column_c2299a-9c > .kt-inside-inner-col, .kadence-column_c2299a-9c > .kt-inside-inner-col::before { 
    border-top-left-radius: 0px; 
    border-top-right-radius: 0px; 
    border-bottom-right-radius: 0px; 
    border-bottom-left-radius: 0px;
} 

.aligncenter { 
    clear: both;
} 

.wp-block-image.aligncenter { 
    text-align: center;
} 

.wp-block-image.aligncenter { 
    display: table;
} 

.kadence-column_c2299a-9c > .kt-inside-inner-col > .aligncenter  { 
    width: 100%;
} 


/* These were inline style tags. Uses id+class to override almost everything */
#style-4F4pR.style-4F4pR {  
   min-height:400px;  
   aspect-ratio:unset;  
   aspect-ratio:unset;  
}  
#style-DONgS.style-DONgS {  
   background-image:url(/img/april/cafe/foodiesfeed.com_homemade-waffles-with-coffee-150x150.jpg);  
   background-position:50% 50%;  
}  
#style-Se7sb.style-Se7sb {  
   background-image:url(/img/april/cafe/10693918384_9aefe2bf94_coffee-270x250@2x.jpg);  
   background-position:50% 50%;  
}  
#style-w53ln.style-w53ln {  
   background-image:url(/img/april/cafe/LA-captains-table-1024x550.png);  
   background-position:50% 50%;  
}  

    </style>
<div class="wp-site-blocks snipcss-oyRNp">
    <div class="entry-content wp-block-post-content has-global-padding is-layout-constrained wp-block-post-content-is-layout-constrained">
        <div class="wp-block-cover alignfull style-4F4pR" id="style-4F4pR"><span aria-hidden="true" class="wp-block-cover__background has-background-dim"></span><img fetchpriority="high" decoding="async" width="1500" height="686" src="/img/april/cafe/foodiesfeed.com_meanwhile-in-the-kitchen-1.jpg" class="wp-block-cover__image-background wp-post-image" alt="" data-object-fit="cover" data-object-position="50% 50%" style="object-position: 50% 50%">
            <div class="wp-block-cover__inner-container is-layout-flow wp-block-cover-is-layout-flow">
                <div class="wp-block-kadence-rowlayout alignfull">
                    <div id="kt-layout-id_a807f8-d8" class="kt-row-layout-inner kt-layout-id_a807f8-d8">
                        <div class="kt-row-column-wrap kt-has-3-columns kt-gutter-none kt-v-gutter-default kt-row-valign-top kt-row-layout-equal kt-tab-layout-inherit kt-m-colapse-left-to-right kt-mobile-layout-row">
                            <div class="wp-block-kadence-column inner-column-1 kadence-column_e944e5-d4">
                                <div class="kt-inside-inner-col"></div>
                            </div>
                            <div class="wp-block-kadence-column inner-column-2 kadence-column_c2299a-9c">
                                <div class="kt-inside-inner-col">
                                    <figure class="wp-block-image aligncenter is-resized"><img decoding="async" src="/img/april/cafe/Desolation-Cafe.png" alt="" width="200" height="200"></figure>
                                </div>
                            </div>
                            <div class="wp-block-kadence-column inner-column-3 kadence-column_7af36b-c2">
                                <div class="kt-inside-inner-col"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <p class="has-text-align-center has-black-color has-text-color">Handcrafted ascended delights that instantly brighten up your WvW raid. Whether it’s peppercorn, Mint or Magic Find, we use the finest ingredients to produce these mouth-watering feasts.</p>
        <h2 class="wp-block-heading has-black-color has-text-color">Our Sweets</h2>
        <figure class="wp-block-gallery has-nested-images columns-default is-cropped wp-block-gallery-2 is-layout-flex wp-block-gallery-is-layout-flex">
            <figure class="wp-block-image size-large"><a href="/img/april/cafe/foodiesfeed.com_Your-Sunny-Side-Up-2.jpg"><img decoding="async" width="1024" height="683" data-id="3598" src="/img/april/cafe/foodiesfeed.com_Your-Sunny-Side-Up-2.jpg" alt="" class="wp-image-3598"></a></figure>
            <figure class="wp-block-image size-large"><a href="/img/april/cafe/foodiesfeed.com_traditional-czech-honey-cake-caffee-latte.jpg"><img decoding="async" width="1024" height="683" data-id="3599" src="/img/april/cafe/foodiesfeed.com_traditional-czech-honey-cake-caffee-latte.jpg" alt="" class="wp-image-3599"></a></figure>
            <figure class="wp-block-image size-large"><a href="/img/april/cafe/foodiesfeed.com_homemade-waffles-with-coffee.jpg"><img decoding="async" width="1024" height="1024" data-id="3600" src="/img/april/cafe/foodiesfeed.com_homemade-waffles-with-coffee-1024x1024.jpg" alt="" class="wp-image-3600"></a></figure>
            <figure class="wp-block-image size-large"><a href="/img/april/cafe/foodiesfeed.com_homemade-pizza.jpg"><img decoding="async" width="1024" height="683" data-id="3602" src="/img/april/cafe/foodiesfeed.com_homemade-pizza.jpg" alt="" class="wp-image-3602"></a></figure>
            <figure class="wp-block-image size-large"><a href="/img/april/cafe/foodiesfeed.com_Wedding_15.jpg"><img decoding="async" width="1024" height="683" data-id="3603" src="/img/april/cafe/foodiesfeed.com_Wedding_15.jpg" alt="" class="wp-image-3603"></a></figure>
            <figure class="wp-block-image size-large"><a href="/img/april/cafe/foodiesfeed.com_get-ready-for-your-espresso.jpg"><img decoding="async" width="1024" height="683" data-id="3605" src="/img/april/cafe/foodiesfeed.com_get-ready-for-your-espresso.jpg" alt="" class="wp-image-3605"></a></figure>
        </figure>
        <div class="wp-block-media-text has-media-on-the-right is-stacked-on-mobile is-image-fill has-black-color has-text-color" style="grid-template-columns:auto 40%">
            <div class="wp-block-media-text__content">
                <h3 class="wp-block-heading has-black-color has-text-color">Tasty Breakfast</h3>
                <p class="has-black-color has-text-color">Something with Magic Find? 66% chance to life steal?</p>
                <p class="has-black-color has-text-color">Something exotic with Omnomberries?</p>
            </div>
            <figure class="wp-block-media-text__media style-DONgS" id="style-DONgS"><img decoding="async" width="150" height="150" src="/img/april/cafe/foodiesfeed.com_homemade-waffles-with-coffee-150x150.jpg" alt="" class="wp-image-3600 size-thumbnail"></figure>
        </div>
        <div class="wp-block-media-text is-stacked-on-mobile is-image-fill has-black-color has-text-color" style="grid-template-columns:40% auto">
            <figure class="wp-block-media-text__media style-Se7sb" id="style-Se7sb"><img decoding="async" src="/img/april/cafe/10693918384_9aefe2bf94_coffee-270x250@2x.jpg" alt=""></figure>
            <div class="wp-block-media-text__content">
                <h3 class="wp-block-heading has-black-color has-text-color">Fresh Coffee</h3>
                <p class="has-black-color has-text-color">Refuel for the battlefield with our newly built WarClaw-Thru!</p>
            </div>
        </div>
        <div class="wp-block-media-text has-media-on-the-right is-stacked-on-mobile is-vertically-aligned-center is-image-fill has-black-color has-text-color">
            <div class="wp-block-media-text__content">
                <h3 class="wp-block-heading">Birthdays &amp; Events</h3>
                <p>Celebrate getting your Gift of Battle in style with our in-house bakery and fireworks.</p>
                <p>Hero Banners are available.</p>
            </div>
            <figure class="wp-block-media-text__media style-w53ln" id="style-w53ln"><img decoding="async" src="/img/april/cafe/LA-captains-table-1024x550.png" alt=""></figure>
        </div>
        <h2 class="wp-block-heading">Our Sweets Collection</h2>
        <p>The best way to experience our wide collection of sweets is to visit the store. Follow the aromas and choose the most enticing sweets to satisfy your palate.</p>
        <figure class="wp-block-gallery has-nested-images columns-default is-cropped wp-block-gallery-4 is-layout-flex wp-block-gallery-is-layout-flex">
            <figure class="wp-block-image"><img decoding="async" src="/img/april/cafe/foodiesfeed.com_Wedding_15-on460zt49bmazoudd2s1a6tctekt0x0xw11h5eh6mc.jpg" alt="foodiesfeed.com_Wedding_15.jpg"></figure>
            <figure class="wp-block-image"><img decoding="async" src="/img/april/cafe/foodiesfeed.com_Your-Sunny-Side-Up-2-on4612mmttq5yiq9wlzwzo3qlk6wo0c4wezxl8d03o.jpg" alt="foodiesfeed.com_Your-Sunny-Side-Up-2.jpg"></figure>
            <figure class="wp-block-image"><img decoding="async" src="/img/april/cafe/foodiesfeed.com_homemade-pizza-on460zt49bmazoudd2s1a6tctekt0x0xw11h5eh6mc.jpg" alt="foodiesfeed.com_homemade-pizza.jpg"></figure>
            <figure class="wp-block-image"><img decoding="async" src="/img/april/cafe/foodiesfeed.com_homemade-waffles-with-coffee-on4611osmzovmwrn23laf6ca06bjgb8ekacg3yee9w.jpg" alt="foodiesfeed.com_homemade-waffles-with-coffee.jpg"></figure>
            <figure class="wp-block-image"><img decoding="async" src="/img/april/cafe/foodiesfeed.com_traditional-czech-honey-cake-caffee-latte-on4611osmzovmwrn23laf6ca06bjgb8ekacg3yee9w.jpg" alt="foodiesfeed.com_traditional-czech-honey-cake-caffee-latte.jpg"></figure>
        </figure>
        <h2 class="wp-block-heading has-text-align-left has-black-color has-text-color">Visit Us</h2>
        <ul class="has-black-color has-text-color">
            <li>Western Ward, Lions Arch</li>
            <li>Tier 3 StoneMist Castle (opening soon!)</li>
        </ul>
        <p class="has-black-color has-text-color">Image Sources: <a href="https://foodiesfeed.com" target="_blank" rel="noopener">foodiesfeed</a>, <a href="http://www.wocintechchat.com" target="_blank" rel="noopener">WOCinTechChat</a>, <a href="http://www.graphberry.com/item/3-vintage-vector-logo-insignias" target="_blank" rel="noopener">GraphBerry</a></p>
    </div>
</div>