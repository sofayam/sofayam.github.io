---
layout: default
---

# Diversas dúvidas 



<ul>
  {% for duvida in site.duvidas %}
    <li>
      <a href="{{ duvida.url }}">{{ duvida.title }}</a> 
    </li>
  {% endfor %}
</ul>

## ainda a fazer

- frases hipotéticas (o subjuntivo)



# Verbos
 
- verbos super-irregulares (ver, vir, ser etc.) <a href="/verbs"> Lista aqui </a> 
 

# Notas de aulas

 <ul>
  {% for aula in site.aulas %}
    <li>
      <a href="{{ aula.url }}">{{ aula.url }}</a> 
    </li>
  {% endfor %}
</ul>
