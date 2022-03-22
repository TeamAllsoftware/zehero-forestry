---
layout: layout_generic_plus
title: Plan du site, toutes les pages à visiter
meta-title: Plan du site, toutes les pages à visiter
meta-description: ZE HERO est la boutique en ligne été / hiver pour commander vos activités de plein air, louer ou acheter du matériel; et un site web de conseils et d'articles.

permalink: /fr/plan-du-site
language: fr
season: winter
topnav_color_text: light
page_sections:
- template: heroBreadcrumb
  title: Conditions générales d'utilisation
---

<!-- start section -->
<section class="bg-light-gray pt-0">
    <div class="container">
        <div class="row">
            <div class="row show-grid">
                <div class="col-12 col-lg-6">
                    <!-- start activités -->
                    {% assign collection = site[page.collection] %}
                    {% assign serviceType = activity %}
                    {% assign servicePath = season_language | prepend:'/' | append: '/' | append: serviceType | append: '/' %}
                    {% assign catList = site[page.collection] | where_exp: 'item', "item.path contains servicePath "  %}
                    {% assign service = catList %}
                    <ul>
                    {% for service in collection %}
                    {% if service.path contains servicePath %}
                    <!-- start portfolio item -->
                    <li> <a href="{{ service.url }}" class="btn btn-fancy btn-small btn-green margin-35px-top">{{ service.title }}</a></li>
                    <!-- end portfolio item -->
                    {% endif %}
                    {% endfor %}
                    </ul>
                    <!-- fin activités section -->
                </div>
                <div class="col-12 col-lg-6">
                .col-lg-6</div>
            </div>
        </div>
    </div>
</section>
<!-- end section -->