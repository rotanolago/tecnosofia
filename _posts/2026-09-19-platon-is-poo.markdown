---
layout: post
title:  "Platon es POO"
date:   2026-09-19 22:31:57 +0200
categories: platon programacion tecnologia filosofia
---

La forma más fácil de entender a Platón es la Programación Orientada a Objetos (POO).

Como programador web estudiando el grado de Filosofía, me resulta natural mapear conceptos filosóficos a arquitecturas de software. Y en la Historia del Pensamiento hay correlaciones tan directas que cuesta ignorarlas.

La primera y más obvia: la Teoría de las Ideas de Platón.

Si traducimos el "Timeo" platónico a código, la equivalencia es casi literal:

- Clase === Idea (la Forma pura, inmaterial y perfecta)
- Instancia === Objeto en memoria (la versión material e imperfecta)
- Demiurgo === El ejecutor / Constructor (que moldea la materia según el modelo)
- Materia / RAM === La cárcel del objeto (lo degradable, sujeto al tiempo y al estado)

Para Platón, existe un mundo sensible (lleno de sombras e imperfecciones) y un mundo inteligible (donde residen los modelos perfectos que solo alcanzamos con la razón).

Llevado a la ingeniería de software, esta ontología tiene consecuencias prácticas claras:

1. Acepta la imperfección de la ejecución: Una instancia en ejecución lidia con latencia, estado y memoria; la clase/interfaz representa la intención pura. Tu implementación jamás será tan prístina como el diseño inicial.

2. Aísla el estado sensible: Haz que los objetos vivan en el scope más restringido posible, limita los efectos secundarios y deja que se destruyan cuando cumplan su ciclo (un Garbage Collector muy sococrático).

3. Eleva el nivel de abstracción: Céntrate en lo inmaterial. Las interfaces, tipos y contratos de arquitectura son siempre más mantenibles e inteligibles que la lógica imperativa llena de condicionales.

¿Qué otras analogías encuentras entre la teoría del conocimiento y el diseño de sistemas?

(Próxima parada: La inmutabilidad de Parménides y por qué odiaría el estado mutable).
