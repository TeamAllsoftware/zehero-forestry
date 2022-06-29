---

---
# Editing a blog post

ZE HERO website uses this CMS called Forestry to edit our content easily.

Our theme uses a lot of templating to simplify edition and we add component periodicly.

### Using Forestry

Forestry's [editing docs](https://forestry.io/docs/editing/) provide a good overview of how to use the editor.

### Using our CMS to edit blog post

In the left sidebar, go to the section related to blog posts in the appropriate language and add or edit a post.

Once you have been introduce to our system, you might want to use the block component to compose your post with style.

## LASTEST UPDATES

#### update 29.06.2022 : Gérer les départements de la carte

La carte se gère depuis la page "carte" dans le menu. C'est une page de code assez simple à gérer.

A partir de la ligne 39, chaque département est présenté, et encodé, comme suis:

    {
    	"department-59": {
         value: "0",
         href: "#",
         tooltip: {content: "<span style=\"font-weight:bold;\">Nord (59)</span>"}
       },

Tu peux modifier les 2 champs suivants c'est tout :

* value = "0" le département est gris, "1" le département est vert
* href = "#" le département n'a pas de lien, ou alors tu colles le lien vers la page (ex: "/fr/ete/destinations/savoie")

#### update 29.06.2022 : Ajouter la carte dans une page

un "snippet" pour coller automatiquement le code qui affiche la carte. TU peux prendre ce snippet dans le composant "TEXT PARAGRAPH WITH OPTION TITLE"

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1656493223/website/admin%20forestry/snippet-carte.png)

et bien sur tu peux changer le texte à afficher dans la colonne de gauche

#### update 11.03.2022 : Add new components

* video2colImgTxt
* heroImageFull
* blogPostList
* 4col2imgTxtImg
* 2colTitreTxt
* ZEHEROintro
* 2colimgtxt
* 2col2tiers1tiers

#### update 7.03.2022 : New fields BUTTON ZE-HERO

New option to add personnalize the always on page "Réserver" green button. This link will supercharge the generic link

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1646652428/website/admin%20forestry/button_ze-hero_hs53kb.png)

#### update 16.02.2022 : New fields META TITLE and META DESCRIPTION

These 2 fields are for SEO and are very important. META TITLE should express what the page is about. The most important keyword of the page should be in the META TITLE but should not be repeated in the title. It must appear once. META TITLE is between 35 to 65 characters long.

**How to Write Title Meta Tags for SEO**

Here are some best practices to write title meta tags for your web pages.

* Do not write title meta tags longer than 65 characters.
* Add modifiers—such as how-to, tips, buy, find, top, etc.—to your title tag.
* Titles with numbers work better, same is true for title tags as well.
* Insert your primary keyword in the title tag, preferably right at the beginning.
* Write a unique title tag for each page.

#### update 31.01.2022 : Add a new component: 2col txt + img

it is a new component that faces the other **2col img + txt**  
this way it is possible to make a page with alternate section img+txt and the section txt+img (ex: https://www.ze-hero.com/fr/qui-sommes-nous)

#### update 31.01.2022 : Add Forestry sidebar FR Various pages

Possibility to create and update various pages not in any categories and then add a link in menu or page or hidden from menu (ex: contact page, qui sommes nous page

#### update 21.01.2022 : Add a new component: cta

#### update 06.01.2022 : Resort template

**The resort template was updated with introduction text to personalize each resort like this capture represent it :**

![](https://res.cloudinary.com/deddrj0yb/image/upload/c_fill,w_800/v1641486201/website/admin%20forestry/resort-introduction-1_hcflwh.png)

**In the admin resort page, look for the "introduction" block :**

![](https://res.cloudinary.com/deddrj0yb/image/upload/c_fill,w_800/v1641486200/website/admin%20forestry/resort-introduction-3_i696c9.png)

**and you enter the "Introduction" block to edit :**

![](https://res.cloudinary.com/deddrj0yb/image/upload/c_fill,w_800/v1641486200/website/admin%20forestry/resort-introduction-2_iz1pl8.png)

## For now we use the following components

block name: **2-col-img-txt**

![](https://res.cloudinary.com/deddrj0yb/image/upload/c_fill,w_800/v1639669858/website/admin%20forestry/2-col-img-txt_gvhzo2.png)

block name: **2-col-txt-img**

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1647006061/website/admin%20forestry/2colimgtxt.png)

block name: **txt-paragraph**

![](https://res.cloudinary.com/deddrj0yb/image/upload/c_fill,w_800/v1639669858/website/admin%20forestry/txt-paragraph_c9oxb2.png)

block name: **list-bullet-style01**

![](https://res.cloudinary.com/deddrj0yb/image/upload/c_fill,w_800/v1639669858/website/admin%20forestry/list-bullet-style01_unsgfq.png)

block name: **list-numbered-style01**

![](https://res.cloudinary.com/deddrj0yb/image/upload/c_fill,w_800/v1639669859/website/admin%20forestry/list-numbered-style01_fb66im.png)

block name: **3-col-txt-img-txt**

![](https://res.cloudinary.com/deddrj0yb/image/upload/c_fill,w_800/v1639669859/website/admin%20forestry/3-col-txt-img-txt_thmzmt.png)

block name: **2col2tiers1tiers**

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1647006062/website/admin%20forestry/2col2tiers1tiers.png)

block name: **image-gallery-style-02**

![](https://res.cloudinary.com/deddrj0yb/image/upload/c_fill,w_800/v1639669861/website/admin%20forestry/image-gallery-style-02_vqcfpv.png)

block name: **2-lines-grid-txt-img**

![](https://res.cloudinary.com/deddrj0yb/image/upload/c_fill,w_800/v1639669860/website/admin%20forestry/2-lines-grid-txt-img_h5t9fy.png)

block name: **counter + headline + content**

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1640094001/website/admin%20forestry/numberInfo_bbihcs.png)

block name: **cta** (= Call To Action) means, un block to add a button

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1642758086/website/admin%20forestry/cta-block_xk4oqk.png)

block name: **imageHeroFull**

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1647005695/website/admin%20forestry/heroImageFull.png)

block name: **4col2imgTxtImg**

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1647005692/website/admin%20forestry/4col2imgTxtImg.png)

block name: **video2colImgTxt**

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1647005692/website/admin%20forestry/video2colImgTxt.png)

block name: **blogPostList**

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1647005692/website/admin%20forestry/blogPostList.png)

block name: **newsletter**

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1647005691/website/admin%20forestry/newsletter.png)

block name: **ZEHEROintro**

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1647005692/website/admin%20forestry/ZEHEROintro.png)

block name: **2colTitreTxt**

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1647005691/website/admin%20forestry/2colTitreTxt.png)

block name: **heroBreadcrumb**

to use right under the the menu bar. To use with "various page template"

![](https://res.cloudinary.com/deddrj0yb/image/upload/v1647006482/website/admin%20forestry/heroBreadcrumb.png)

This is it for now