---
layout: layout_generic_plus
language: fr
season: winter
type: B2B
menu: seminaire
topnav_color_text: 
title: Liste des destinations des séminaires hiver
permalink: "/fr/seminaires-hiver/destinations-seminaires"
meta-title: Liste des destinations des séminaires hiver
meta-description: Connaissez-vous Ze Hero, la référence de l'Outdoor ? Découvrez l'équipe
  Ze Hero, notre histoire et les valeurs qui nous animent
baseline: Découvrez ZE HERO
redirection_from:
page_sections:
- template: 2colTitreTxt
  title: Liste des destinations de nos séminaires d'hiver
  content: |-
    ZE HERO Séminaires organise votre événement d’entreprise entre Savoies, Mont Blanc et Jura, au cœur d’une nature généreuse, de massifs enneigés, de villages charmants et de lacs étincelants... un cadre unique à moins de 4h de Paris, qui sera apprécié par tous.

---

 <!-- start section -->
<section class="p-0 wow animate__fadeIn">
    <div class="container">
        <div class="row row-cols-1 row-cols-lg-3 row-cols-md-2 justify-content-center margin-9-rem-bottom lg-margin-7-rem-bottom">
            {% assign items = site.data.content.seminaire_destinations.hiver %}
            {% assign stations = items.resort.stations %}
            {% assign imgsize = site.data.config.img %}
            {% for item in items %}
            <!-- start testimonial item -->
            <div class="col margin-30px-bottom xs-margin-15px-bottom wow animate__fadeIn" data-wow-delay="0.2s">
                <div class="testimonials-style-02 border-radius-5px overflow-hidden">
                    <img class="d-inline-block" loading="lazy" src="{{ imgsize.url }}{{ imgsize.blogpostlist }}{{ item.image_href | remove: 'https://res.cloudinary.com/deddrj0yb/image/upload' }}" alt="{{ item.image_alt }}"  width="600px" height="450px" />
                    <div class="testimonials-content padding-3-half-rem-all bg-light-gray  lg-padding-2-half-rem-lr">
                        <h3 class="h-70px h3 alt-font font-weight-500 text-extra-dark-gray text-uppercase d-block">{{ item.title }}</h3>
                        <p class="h-200px">{{ item.content }}</p>
                        <span class="h-50px alt-font font-weight-300 text-small text-uppercase d-block">Ski: {{ item.ski-pistes }} pistes / {{ item.ski-km }} km</span>
                        <span class="h-70px alt-font font-weight-300 text-small text-uppercase d-block">Les stations:  {{ item.stations | array_to_sentence_string: "et" }} </span>
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