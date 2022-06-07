---
layout: layout_generic_plus
language: fr
season: winter
type: B2B
menu: seminaire
topnav_color_text: 
title: Formulaire de demande de devis pour l'organisation de séminaire d'entreprise
permalink: "/fr/seminaire-devis"
meta-title: Réaliser un devis d'organisation de séminaire d'entreprise
meta-description: Réaliser une demande de devis pour un séminaire d'entreprise. Nous devisons votre séminaire d'hiver ou d'été pour vous simplifier la vie.
baseline: Découvrez ZE HERO
redirection_from:
page_sections:
- template: 2colTitreTxt
  title: Formulaire de demande de devis
  content: |-
    ZE HERO Séminaires organise votre événement d’entreprise entre Savoies, Mont Blanc et Jura, au cœur d’une nature généreuse, de massifs enneigés, de villages charmants et de lacs étincelants... un cadre unique à moins de 4h de Paris, qui sera apprécié par tous.
---

<!-- start section -->
<section class="pt-0  wow animate__fadeIn">
    <div class="container">
        <div class="row align-items-end justify-content-center">
            <div class="col-12 col-lg-6 col-md-8">
                <h3 class="h2 alt-font text-black font-weight-600">Réaliser mon devis de séminaire</h3>
                <form action="/fr/contact-success" name="seminaire-devis-{{ page.language }}" method="POST" data-netlify="true" class="alt-font text-extra-dark-gray">
                    <input class="input-border-bottom border-color-extra-dark-gray bg-transparent placeholder-dark large-input px-0 margin-25px-bottom border-radius-0px required" type="text" name="lastname" placeholder="Quel est votre nom" />
                    <input class="input-border-bottom border-color-extra-dark-gray bg-transparent placeholder-dark large-input px-0 margin-25px-bottom border-radius-0px required" type="text" name="firstname" placeholder="Quel est votre prénom" />
                    <input class="input-border-bottom border-color-extra-dark-gray bg-transparent placeholder-dark large-input px-0 margin-25px-bottom border-radius-0px required" type="text" name="company" placeholder="Pour quelle entreprise souhaitez-vous ce devis" />
                    <input class="input-border-bottom border-color-extra-dark-gray bg-transparent placeholder-dark large-input px-0 margin-25px-bottom border-radius-0px required" type="number" name="howManyPeople" placeholder="Pour combien de personne devons-nous préparer ce séminaire " />
                    <input class="input-border-bottom border-color-extra-dark-gray bg-transparent placeholder-dark large-input px-0 margin-25px-bottom border-radius-0px required" type="number" name="howManyDays" placeholder="Combien de jours et quand débutera-t-il" />
                    <input class="input-border-bottom border-color-extra-dark-gray bg-transparent placeholder-dark large-input px-0 margin-25px-bottom border-radius-0px required" type="date" name="when" placeholder="A quelle date souhaitez-vous débuter votre séminaire" />
                    <input class="input-border-bottom border-color-extra-dark-gray bg-transparent placeholder-dark large-input px-0 margin-25px-bottom border-radius-0px required" type="email" name="email" placeholder="{{ site.data.content.generic_contact.s02.p01[page.language].form_email }}" />
                    <input class="input-border-bottom border-color-extra-dark-gray bg-transparent placeholder-dark large-input px-0 margin-25px-bottom border-radius-0px" type="tel" name="phone" placeholder="{{ site.data.content.generic_contact.s02.p01[page.language].form_phone }}" />
                    <textarea class="input-border-bottom border-color-extra-dark-gray bg-transparent placeholder-dark large-input px-0 margin-35px-bottom border-radius-0px" name="message" rows="5" placeholder="Précisez votre demande (lieu, prestations, etc.)"></textarea>
                    <button class="btn btn-medium btn-dark-gray mb-0" type="submit">Envoyer ma demande de devis</button>
                </form>
            </div>
        </div>
    </div>
</section>
<!-- end section -->