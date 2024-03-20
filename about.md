---
layout: default
title: About
---

## Sobre {{ site.name }}

<img class="user-avatar" src="{{ site.owner.avatar }}">

Olá, meu nome é Frederico Ferreira Bitencourt, formando em Engenharia Eletrônica e de Telecomunicação. Comecei na base hardware e eletrônica, depois fui
para sistema embarcados e apartir daqui veio a paixão por software. Ver o hardware que você programa fazendo coisas me deixou fascinado!

Hoje sou líder técnico e CTO da LeadSoft® Soluções Web construíndo diversos tipos de software para várias contextos com grandes clientes.

Esse blog é meu diário pessoal que registrarei meu progresso e todas as experiências, aprendizados, conhecimento da minha vida profissional e pessoal.

Espero que o conhecimento compartilhado aqui possa ajudar você. A melhor forma de aprendizado e ensinar/compartilhar conhecimento.

Seja bem vindo!

<div class="pagination">
  {% if site.owner.linkedin %}
    <a href="{{ site.owner.linkedin }}" class="social-media-icons"><i class="fa fa-2x fa-linkedin-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.email %}
    <a href="mailto:{{ site.owner.email }}" class="social-media-icons"><i class="fa fa-2x fa-envelope-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.twitter %}
    <a href="https://twitter.com/{{ site.owner.twitter }}" class="social-media-icons"><i class="fa fa-2x fa-twitter-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.github %}
    <a href="{{ site.owner.github }}" class="social-media-icons"><i class="fa fa-2x fa-github-square" aria-hidden="true"></i></a>
  {% endif %}
</div>
