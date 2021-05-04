### Introducción

- [x] Intro a Producto 

- [x] Levantar Producto en local 

- [x] Acceso a los Servers 

- [x] Onboarding de algún Dev.

- [x] Tomar Owner de los Servers de Producto (y ni bien tenga todo ordenado en Producto, también sumar a Academy en esta gestión).

### Organizar rápidamente algunos temas

- [ ] Configurar un servidor de Test (sería la previa a Staging) + Evitar que sea indexable + Ponerle capa de Auth

- [ ] Evitar que Staging sea indexable + Ponerle capa de Auth

- [ ] En la medida de lo posible, asegurar que todos los entornos (Test, Staging y Prod) sea iguales en características y configs para disminuir la posibilidad de sorpresas al deployar en cada Stage

- [ ] Optimizar las estrategias de deploy

- [ ] Un tema que no está vinculado a Producto pero que deberíamos darle prioridad en algún momento, es el de hacer una revisión de todos los Servers viejos que están en marcha (ejemplo: checkinapp). Hay que ver si algo que se puede eliminar o juntar todos en un mismo droplet, ya que en su mayoría son Servers no Productivos (se puede analizar el tráfico y ver qué se puede compactar - a.k.a. poner muchos proyectos de poco tráfico en un único droplet para pagar menos ![:rat:](https://a.slack-edge.com/production-standard-emoji-assets/13.0/apple-medium/1f400.png) ).

- [ ] Implementar ELK + Tener idea de programación Backend con JS (stack Producto) y PHP (para ayudarlo a Bomber con la config de ElasticSearch + stack Academy).

- [ ] Analytics

- [ ] Amplitude

- [ ] Grafana

- [ ] Terraform

- [ ] UI Tests con tools como Selenium

- [ ] Implementación de sistema de Tickets con Slack y Jira

### Algunas aclaraciones:

> - Ni bien estabilicemos las configs de Producto, también sumar a Academy en esta gestión.
> - Cuando hablamos de Servers de Producto, nos referimos a los del Site, Dashboard, MindHunter y la Webapp para ventas y comunidad que está haciendo Ema Aguirre
