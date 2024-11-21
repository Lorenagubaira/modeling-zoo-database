---
title: "Modelando una base de datos de Zoológicos"
description: "En base a los requerimientos que se te presentan crea un modelo de base de datos que de respuesta al planteamiento"
tags: ["postgres", "modeling","sql","4geeks"]
authors: ["arnaldoperez"]

---

<onlyfor saas="true" withBanner="true">

## 🌱 ¿Cómo comenzar un proyecto?

Inicia sesión en [quickdatabasediagrams.com/](https://app.quickdatabasediagrams.com/) y crea un nuevo diagrama. Luego podrás empezar a crear tu modelo y posteriormente compartirlo.

</onlyfor>

## 📝Instrucciones

Construya un modelo de base de datos que responda a los requisitos expuestos en el siguiente párrafo.

- Se desea diseñar una base de datos relacional que almacene información sobre los **zoológicos** del mundo y las especies animales que albergan.
- De cada zoológico conocemos el nombre, la ciudad y el país donde está ubicado, el tamaño (en m2) y el presupuesto anual.
- Para cada animal queremos almacenar la **especie**,  el nombre común, el nombre científico, el **género**, la **familia** a la que pertenece y si está en peligro de extinción o no.
- La relación entre especie, género y familia es jerárquica y refleja las relaciones evolutivas entre los organismos. He aquí un resumen de cada nivel y sus relaciones:

>- Family: Felidae (Cat family)
>   - Genus: Panthera
>     - Species: Panthera leo (Lion)
>     - Species: Panthera tigris (Tiger)
>   - Genus: Felis
>     - Species: Felis catus (Domestic Cat)
>     - Species: Felis silvestris (Wildcat)

- Debes almacenar información sobre cada ejemplar de animal que alberguen los zoos, como: Número de identificación, especie a la que pertenece, género, sexo, año de nacimiento, país de origen y continente.
- Una misma especie no puede clasificarse al mismo tiempo en dos familias o géneros diferentes.
- El número de familias de animales está sujeto a cambios a medida que se realizan nuevos descubrimientos. Según estimaciones recientes, existen entre 1.200 y 1.300 familias de animales reconocidas.
- Una familia puede abarcar muchas especies de animales. Las familias agrupan géneros relacionados, y cada género contiene múltiples especies que comparten características comunes.

Por ejemplo:

- **Felidae (la familia de los felinos)** incluye varios géneros como Panthera (que incluye leones, tigres, leopardos y jaguares) y Felis (que incluye gatos domésticos y gatos monteses). Cada uno de estos géneros contiene múltiples especies.
- **Canidae (la familia de los perros)** incluye el género Canis (que incluye perros, lobos y coyotes) y otros géneros como Vulpes (zorros). Cada género de la familia Canidae contiene varias especies.

Cuando hayas terminado el modelo, asegúrate de [compartir el enlace en público](https://4geeks.com/lesson/learn-in-public).
