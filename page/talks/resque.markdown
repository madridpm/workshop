---
title: Resque to the rescue!
data:
    twitter:
        title: Resque to the rescue! (Diego Kuperman)
        description: Conoce el port a Perl de Resque, una cola de trabajos asíncrona basada en Redis desarrollada por Github.

---

# Resque to the rescue!

### Autor
Diego Kuperman

### Resumen
Resque es una cola de tareas, originalmente desarrollada en ruby por github, montada sobre Redis.

He portado Resque de ruby a perl hace cosa de 5 años y desde entonces la hemos estado usando intensamente en soysuper.com para atender millones de tareas al dia entre workers distribuidos en muchísimas maquinas.

En esta charla voy a explicar por qué he decidido portar y usar resque por sobre las opciones existentes en ese momento, cómo funciona internamente y mostraré algunos ejemplos de cómo lo usamos.

