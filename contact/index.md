---
layout: default
---

<main class="mw7-ns center pa3 ph5-ns lh-copy">

  <h1>Contact</h1>

  <p>N'hésitez pas à nous contacter pour toute information!</p>

  <form action="https://formspree.io/mvggaejx" method="POST" accept-charset="utf-8">
    <input type="text" name="_gotcha" style="display: none">
    <input type="hidden" name="_next" value="http://educa-international.com/merci/" />
    <fieldset id="form-message" class="ba b--transparent ph0 mh0">
      <div class="mt3">
        <label class="db fw4 lh-copy f6" for="name">Nom, Prénom</label>
        <input class="pa2 input-reset ba bg-transparent w-100 measure" type="text" name="name" id="name">
      </div>
      <div class="mt3">
        <label class="db fw4 lh-copy f6" for="email-address">E-mail</label>
        <input class="pa2 input-reset ba bg-transparent w-100 measure" type="email" name="email" id="email-address">
      </div>
      <div class="mt3">
        <label class="db fw4 lh-copy f6" for="subject">Sujet</label>
        <input class="pa2 input-reset ba bg-transparent w-100 measure" type="text" name="_subject" id="subject">
      </div>
      <div class="mt3">
        <label class="db fw4 lh-copy f6" for="message">Message</label>
        <textarea class="pa2 input-reset ba bg-transparent w-100 measure" rows="4" cols="50" name="message" id="message"></textarea>
      </div>
    </fieldset>
    <div class="mt3">
      <input class="b ph3 pv2 input-reset ba b--black bg-transparent grow pointer f6" type="submit" value="Envoyer">
    </div>
  </form>

  {% include contact.html %}

</main>
