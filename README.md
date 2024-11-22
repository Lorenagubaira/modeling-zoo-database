---
title: "Modeling a Zoo database"
description: "Based on the requirements presented to you, create a database model that responds to the proposal."
tags: ["postgres", "modeling","sql","4geeks"]
authors: ["arnaldoperez"]

---

<onlyfor saas="true" withBanner="false">

## 🌱 How to start a project?

Log on to [quickdatabasediagrams.com](https://app.quickdatabasediagrams.com) and create a new diagram. Then you can start creating your model and share it later.

</onlyfor>

## 📝Instructions

Build a database model that responds to the requirements stated in the following paragraph.

- You want to design a relational database that stores information about the world's **zoos** and the animal species they house.
- For each zoo we know the name, city and country where it is located, size (in m2) and annual budget.
- For each animal we want to store the **species**, the common name, scientific name, the **genus**, the **family** to which it belongs and whether it is in danger of extinction or not.
- The relationship between species, genus, and family is hierarchical and reflects the evolutionary relationships among organisms. Here’s an overview of each level and their relationships:

>- Family: Felidae (Cat family)
>   - Genus: Panthera
>     - Species: Panthera leo (Lion)
>     - Species: Panthera tigris (Tiger)
>   - Genus: Felis
>     - Species: Felis catus (Domestic Cat)
>     - Species: Felis silvestris (Wildcat)

- You should store information about each animal specimen that the zoos are hosting, such as: Identification number, corresponding species, genus, sex, year of birth, country of origin and continent.
- A single species cannot be classified into two different families or genus at the same time.
- The number of animal families is subject to change as new discoveries are made. As of recent estimates, there are approximately 1,200 to 1,300 recognized animal families.
- One family can encompass many species of animals. Families group together related genera (plural of genus), and each genus contains multiple species that share common characteristics.

For example:

- **Felidae (the cat family)** includes various genera such as Panthera (which includes lions, tigers, leopards, and jaguars) and Felis (which includes domestic cats and wildcats). Each of these genera contains multiple species.
- **Canidae (the dog family)** includes the genus Canis (which includes dogs, wolves, and coyotes) and other genera like Vulpes (foxes). Each genus within the Canidae family contains multiple species.

Once you have finished the model be sure to [share the link in public](https://4geeks.com/lesson/learn-in-public).
