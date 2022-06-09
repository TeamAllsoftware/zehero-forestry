---
layout: layout_generic_plus
title: Carte de France
meta-title: Activités outdoor et boutique en ligne pour l'été
meta-description: Toutes les activités outdoor de l'été à partager en famille ou entre amis où que vous soyez en France et quelque soit votre niveau
permalink: "/fr/map/"
language: fr
season: summer
type: generic
topnav_color_text: light
page_sections:
- template: heroBreadcrumb
  title: Carte de notre présence en France
author: geoffreyarduini
baseline: ''
button_to_link_to_ze_hero_shop:
  button_text: ''
  url_to_shop_zehero: https://shop.ze-hero.com/fr/activites-Outdoor/

---
 <script type="text/javascript" src="http://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="/js/jquery.vmap.js"></script>
<script src="/js/jquery.vmap.france.js"></script>

<script>
    jQuery(document).ready(function () {
      jQuery('#vmap').vectorMap({
        map: 'france_fr',
        enableZoom: true,
        showTooltip: true
      });
    });
  </script>

 <div id="vmap" style="width: 680px; height: 520px;"></div>