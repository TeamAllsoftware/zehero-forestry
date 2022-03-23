---
layout: layout_generic_plus
title: Plan du site, toutes les pages à visiter
meta-title: Plan du site, toutes les pages à visiter en accès rapide.
meta-description: Plan du site. Retrouvez toutes les pages du site internet de ZE HERO. Un accès rapide et facile à toutes les pages.

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
            <div class="row">
                <div class="col-12 col-lg-6">
                    {% assign collectionFr = site.collections | where: 'label', "fr" %}
                    <h2 class="h4">HIVER</h2>
                    <div class="margin-20px-tb">
                        {% assign catList = site[page.collection] | where_exp: 'item', "item.path contains 'hiver/racine' "  %}
                        {% assign service = catList %}
                        {% for collection in collectionFr %}
                        <h3 class="h5">Pages racine</h3>
                        <ol class="text-start">
                            {% for item in service %}
                            <li><a href="{{ item.url }}">{{ item.title }}</a></li>
                            {% endfor %}
                        </ol>
                        {% endfor %}
                    </div>
                    <div class="margin-20px-tb">
                    {% assign catList = site[page.collection] | where_exp: 'item', "item.path contains 'hiver/activity' "  %}
                    {% assign service = catList %}
                    {% for collection in collectionFr %}
                      <h3 class="h5">Pages activités</h3>
                      <ol class="text-start">
                        {% for item in service %}
                          <li><a href="{{ item.url }}">{{ item.title }}</a></li>
                        {% endfor %}
                      </ol>
                    {% endfor %}
                    </div>
                    <div class="margin-20px-tb">
                    {% assign catList = site[page.collection] | where_exp: 'item', "item.path contains 'hiver/advice' "  %}
                    {% assign service = catList %}
                    {% for collection in collectionFr %}
                      <h3 class="h5">Pages conseils</h3>
                      <ol class="text-start">
                        {% for item in service %}
                          <li><a href="{{ item.url }}">{{ item.title }}</a></li>
                        {% endfor %}
                      </ol>
                    {% endfor %}
                    </div>
                    <div class="margin-20px-tb">
                    {% assign catList = site[page.collection] | where_exp: 'item', "item.path contains 'hiver/resort' "  %}
                    {% assign service = catList %}
                    {% for collection in collectionFr %}
                      <h3 class="h5">Pages destinations</h3>
                      <ol class="text-start">
                        {% for item in service %}
                          <li><a href="{{ item.url }}">{{ item.title }}</a></li>
                        {% endfor %}
                      </ol>
                    {% endfor %}
                    </div>
                </div>
                <div class="col-12 col-lg-6">
                    {% assign collectionFr = site.collections | where: 'label', "fr" %}
                    <h2 class="h4">ETE</h2>
                    <div class="margin-20px-tb">
                    {% assign catList = site[page.collection] | where_exp: 'item', "item.path contains 'ete/racine' "  %}
                    {% assign service = catList %}
                    {% for collection in collectionFr %}
                      <h3 class="h5">Pages racine</h3>
                      <ol class="text-start">
                        {% for item in service %}
                          <li><a href="{{ item.url }}">{{ item.title }}</a></li>
                        {% endfor %}
                      </ol>
                    {% endfor %}
                    </div>
                    <div class="margin-20px-tb">
                    {% assign catList = site[page.collection] | where_exp: 'item', "item.path contains 'ete/activity' "  %}
                    {% assign service = catList %}
                    {% for collection in collectionFr %}
                      <h3 class="h5">Pages activités</h3>
                      <ol class="text-start">
                        {% for item in service %}
                          <li><a href="{{ item.url }}">{{ item.title }}</a></li>
                        {% endfor %}
                      </ol>
                    {% endfor %}
                    </div>
                    <div class="margin-20px-tb">
                    {% assign catList = site[page.collection] | where_exp: 'item', "item.path contains 'ete/advice' "  %}
                    {% assign service = catList %}
                    {% for collection in collectionFr %}
                      <h3 class="h5">Pages conseils</h3>
                      <ol class="text-start">
                        {% for item in service %}
                          <li><a href="{{ item.url }}">{{ item.title }}</a></li>
                        {% endfor %}
                      </ol>
                    {% endfor %}
                    </div>
                    <div class="margin-20px-tb">
                    {% assign catList = site[page.collection] | where_exp: 'item', "item.path contains 'ete/resort' "  %}
                    {% assign service = catList %}
                    {% for collection in collectionFr %}
                      <h3 class="h5">Pages destinations</h3>
                      <ol class="text-start">
                        {% for item in service %}
                          <li><a href="{{ item.url }}">{{ item.title }}</a></li>
                        {% endfor %}
                      </ol>
                    {% endfor %}
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
<!-- end section -->