---
layout: layout_generic_plus
language: fr
season: summer
type: B2B
menu: seminaire
topnav_color_text: 
title: Liste des destinations des séminaires hiver
permalink: "/fr/seminaires-ete/destinations-seminaires"
meta-title: Liste des destinations des séminaires été
meta-description: Connaissez-vous Ze Hero, la référence de l'Outdoor ? Découvrez l'équipe
  Ze Hero, notre histoire et les valeurs qui nous animent
baseline: Découvrez ZE HERO
redirection_from:
page_sections:
- template: 2colTitreTxt
  title: Destination Côte d'Azur et Vallée de l'Arve autour de Chamonix
  content: |-
    ZE HERO Séminaires vous invite à découvrir une variété de paysages, nature, stations balnéaires, villages, vecteurs d'image et de notoriété pour l'entreprise.

---

 <!-- start section -->
<section class="p-0 wow animate__fadeIn">
    <div class="container">
        <div class="row row-cols-1 row-cols-lg-3 row-cols-md-2 justify-content-center margin-9-rem-bottom lg-margin-7-rem-bottom">
            {% assign items = site.data.content.seminaire_destinations.ete %}
            {% assign stations = items.resort.stations %}
            {% assign imgsize = site.data.config.img %}
            {% for item in items %}
            <!-- start testimonial item -->
            <div class="col margin-30px-bottom xs-margin-15px-bottom wow animate__fadeIn" data-wow-delay="0.2s">
                <div class="testimonials-style-02 border-radius-5px overflow-hidden">
                    <img class="d-inline-block" loading="lazy" src="{{ imgsize.url }}{{ imgsize.blogpostlist }}{{ item.image_href | remove: 'https://res.cloudinary.com/deddrj0yb/image/upload' }}" alt="{{ item.image_alt }}"  width="600px" height="450px" />
                    <div class="testimonials-content padding-3-half-rem-all bg-light-gray  lg-padding-2-half-rem-lr">
                        <h3 class="h-70px h3 alt-font font-weight-500 text-extra-dark-gray text-uppercase d-block">{{ item.title }}</h3>
                        <p class="h-250px">{{ item.content }}</p>
                        <a href="/fr/seminaire-devis/" class="btn btn-large btn-{{ site.data.config[page.type].site-color }} btn-round-edge-small" title="Demande de devis pour {{ item.title }}">Demander un devis</a>                        
                    </div>
                </div>
            </div>
            <!-- end testimonial item -->
            {% endfor %}
        </div>
    </div>
</section>
<!-- end section -->