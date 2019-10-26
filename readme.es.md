<img src="Awesome Code Review.png" alt="Awesome Code Review" />

#   Increible Revisión de código [![Increible](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Una lista de herramientas, artículos, libros y cualquier otro recurso relacionado con [revisión de código](https://en.wikipedia.org/wiki/Code_review)

Revisión de código es examinar sistemáticamente (a veces denominado revisión por pares) el código fuente de la computadora.

Leer esto en otros lenguajes: [English](https://github.com/joho/awesome-code-review/blob/master/readme.md), [Español](https://github.com/joho/awesome-code-review/blob/master/readme.es.md).

## Contenido

- [Artículos Académicos](#academic-papers)
- [Artículos](#articles)
- [Libros](#books)
- [Charlas and Podcasts](#talks-and-podcasts)
- [Herramientas](#tools)

## Artículos Académicos

- [Un experimento para evaluar los costos y beneficios de las inspecciones de código en el desarrollo de software a gran escala (Porter, Siy, Toman & Votta, 1997)](http://laser.cs.umass.edu/courses/cs521-621.Fall10/documents/PorterSiyetal.pdf) Documento inicial que probó una variedad de técnicas de revisión actuales, incluida la revisión en varias etapas y la revisión de código a través de una reunión que descubrió que puede obtener la mayor parte del beneficio en un solo paso sin conexión, con dos revisores.
- [Inspecciones de código en cualquier lugar y en cualquier momento: Usando de la Web para eliminar cuellos de botella de inspección en el desarrollo de software a gran escala (Perpich, Perry, Porter, Votta & Wade, 1997)](https://dl.acm.org/citation.cfm?id=253234) Un día en el futuro lejano, la mejor manera de revisar el código será en la internet.
- [Características revisiones de códigos útiles: Un estudio empírico en Microsoft (Bosu, Greiler, Bird, 2015)](https://www.michaelagreiler.com/wp-content/uploads/2019/02/Characteristics-Of-Useful-Comments.pdf) Este documento informa los resultados de un estudio cualitativo y cuantitativo a gran escala que se centra en comprender cuáles comentarios en la revisión de código son considerados útiles por los desarrolladores.
- [Revisión de código en las trincheras: comprender los desafíos, las mejores prácticas y las necesidades de herramientas (MacLeod, Greiler, Storey, Bird, Czerwonka, 2018)](https://www.michaelagreiler.com/wp-content/uploads/2019/03/Code-Reviewing-in-the-Trenches-Understanding-Challenges-Best-Practices-and-Tool-Needs.pdf) Un estudio a gran escala de más de 900 desarrolladores de Microsoft para comprender sus procesos de revisión de código, sus motivaciones para hacer revisiones de código y qué dificultades y mejores prácticas encuentran.
- [Diseño e inspecciones de código para reducir errores en el desarrollo de programas (Fagan, 2002)](https://link.springer.com/chapter/10.1007/978-3-642-59412-0_35) Usar un proceso más formal, particularmente con roles definidos para cada participante e impulsar un gran aumento en la detección de errores durante la revisión.
- [Ayudando a los desarrolladores a ayudarse a sí mismos: Descomposición Automática de Cambios de Revisión de Código (Barnett et al. 2015)](http://research.microsoft.com/pubs/238937/barnett2015hdh.pdf) ([resumen](https://blog.acolyer.org/2015/06/26/helping-developers-help-themselves-automatic-decomposition-of-code-review-changes/)) Investigue sobre la división automática de grandes diferencias en diferencias más pequeñas que conduzcan a mejores revisiones.
- [Revisión de Código Moderno: Un Caso de Estudio en Google](https://sback.it/publications/icse2018seip.pdf) Un estudio que muestra cómo funcionan las revisiones de código en Google
- [Prácticas de Trabajo y Desafíos en el Desarrollo basado en Pull (Gousios et al. 2015)](https://sback.it/publications/icse2016b.pdf) ([resumen](https://blog.acolyer.org/2015/06/23/work-practices-and-challenges-in-pull-based-development/)) Estudio de campo de cómo se utilizan los Pull Request de GitHub.

## Artículos

- [8 Consejos Para Una Gran Revisión de Código](https://kellysutton.com/2018/10/08/8-tips-for-great-code-reviews.html) Algunas reglas básicas para un mejor proceso de revisión de código.
- [Un Zen manifiesto para revisiones efectivas de códigos](https://medium.freecodecamp.org/a-zen-manifesto-for-effective-code-reviews-e30b5c95204a) Consejos prácticos para quién envía y quién revisa para realizar revisiones de código efectivas.
- [Característica de ramificación(branch) - Brian Guthrie](https://twitter.com/bguthrie/status/937750796334174209) Tema en Twitter sobre los pros y los contras del primer modelo de código abierto de GitHub con respecto a la práctica de revisión de código "en la empresa".
- [Construyendo una Cultura de Revisión de Código inclusiva](https://blog.plaid.com/building-an-inclusive-code-review-culture/) Pautas para ayudar a garantizar una cultura colaborativa y de aprendizaje.
- [Etiqueta de Revisión de Código](https://css-tricks.com/code-review-etiquette/) Algunos consejos que ayudan con un compromiso positivo en la revisión del código.
- [Revisión de Código: Just Do It](https://blog.codinghorror.com/code-reviews-just-do-it/) Publicación seminal abogando por la revisión por pares del software en 2006.
- [Las Revisiones de Código en Google son Ligeras y Rápidas](https://www.michaelagreiler.com/code-reviews-at-google/) Detalles sobre cómo funcionan las mejores prácticas y procesos de revisión de código en Google.
- [La Revisión de Código es el Trabajo del Gerente](https://hecate.co/blog/code-review-review-is-the-managers-job) Por qué la administración debería garantizar que la revisión del código se haga y se haga bien.
- [Comentarios Durante las Revisiones de Código](https://medium.com/@otarutunde/comments-during-code-reviews-2cb7791e1ac7) Escribir buenos comentarios durante las revisiones de código.
- [Diseñando impresionantes Revisiones de Código](https://medium.com/unpacking-trunk-club/designing-awesome-code-reviews-5a0d9cd867e3) Principios para diseñar activamente un proceso de revisión de código.
- [Revisiones Efectivas de Códigos sin Dolor](https://www.developer.com/tech/article.php/3579756/Effective-Code-Reviews-Without-the-Pain.htm) Otro clásico de 2006 sobre cómo realizar efectivamente una revisión de código.
- [Cómo Funcionan las Revisiones de Código en Microsoft](https://www.michaelagreiler.com/code-reviews-at-microsoft-how-to-code-review-at-a-large-software-company/) Un análisis en profundidad sobre cómo se ve el proceso de revisión de código en Microsoft.
- [Cómo Reviso el Código](https://engineering.tumblr.com/post/170040992289/how-i-review-code) Más consejos personales sobre cómo revisar mejor un Pull Request desde un ingeniero en Tumblr.
- [Cómo Hacer una Revisión de Código](https://google.github.io/eng-practices/review/reviewer/) Una descripción detallada de cómo los ingenieros de Google hacen revisiones de código.
- [Cómo Hacer Revisiones de Código Como un Humano](https://mtlynch.io/human-code-reviews-1/) Técnicas que tratan la revisión del código no solo como un proceso técnico sino también social.
- [En Revisión de Código](https://medium.com/@schrockn/on-code-reviews-b1c7c94d868c) Artículo sobre herramientas y elementos personales de revisión de código, de un ex ingeniero de Facebook.

- [Pull Requests: Como obtener y dar feedback](https://kickstarter.engineering/pull-requests-how-to-get-and-give-good-feedback-f573469f0c44) Consejos ambos lados del proceso de revisión del código, el revisor y el revisor.
- [Enviar pequeñas diferencias](https://blog.skyliner.io/ship-small-diffs-741308bec0d1) Por qué es mejor revisar los cambios pequeños en lugar de los grandes.
- [Apilados Pull Requests: Manteniendo GitHub Diffs Pequeño](https://graysonkoonce.com/stacked-pull-requests-keeping-github-diffs-small/) Un paso a paso del proceso para dividir grandes Pull Request y aumentar el compromiso de revisión.
- [El Arte de Humanizar Pull Requests](https://blog.usejournal.com/the-art-of-humanizing-pull-requests-prs-b520588eb345) Una rica guía de Emoji sobre el lado humano de la revisión de código a través de Pull Request.
- [Hacia discusiones técnicas productivas](https://cate.blog/2018/07/03/towards-productive-technical-discussions/) Preguntas y acciones tácticas para impulsar las discusiones de revisión de código en un territorio más productivo.
- [Unlearning Toxic Behaviors in a Code Review Culture](https://medium.com/@sandya.sankarram/unlearning-toxic-behaviors-in-a-code-review-culture-b7c295452a3c) Desaprender comportamientos tóxicos en una cultura de revisión de código.
- [Por qué cambié mi forma de pensar sobre la calidad del código](https://medium.freecodecamp.org/why-i-changed-the-way-i-think-about-code-quality-88c5d8d57e68) Por qué la calidad del código es más que solo codificar.

## Libros

- [Los secretos mejor guardados de la revisión del código de pares](https://www.goodreads.com/book/show/1563457.Best_Kept_Secrets_of_Peer_Code_Review) Compilación anterior de 10 ensayos sobre la práctica de revisiones de código. Algunas repeticiones debido a diferentes autores que cubren el mismo territorio.
- [Manual de tutoriales, inspecciones y revisiones técnicas](https://www.amazon.com/Handbook-Walkthroughs-Inspections-Technical-Reviews/dp/0932633196) Un libro más antiguo que cubre recorridos más formales, pero cubre también la política y la dinámica de grupo en revisión.
- [Revisiones por pares en software: una guía práctica](https://www.amazon.com/Peer-Reviews-Software-Practical-Guide/dp/0201734850) Una guía práctica para las inspecciones formales de códigos como práctica de revisión de códigos.
- [Inspección de software: una mejor práctica de la industria](https://www.amazon.com/Software-Inspection-Industry-Best-Practice/dp/0818673400) Compendio de documentos sobre la práctica de revisión de código.
- [Guía definitiva para revisiones de código](https://www.codacy.com/ebooks/guide-to-code-reviews) Codacy patrocinó un libro electrónico de prácticas de revisión de código basado en una encuesta a desarrolladores.
- [Qué buscar en una revisión de código](https://leanpub.com/whattolookforinacodereview) JetBrains patrocinó el libro electrónico sobre cómo detectar los antipatrones de codificación durante la revisión.

## Charlas y Podcasts

- [Revisión de Código: Honestidad, amabilidad, inspiración: elige tres - Jacob Stoebel RubyConf 2017](http://confreaks.tv/videos/rubyconf2017-code-reviews-honesty-kindness-inspiration-pick-three) Cómo hacer una revisión efectiva del código sin dejar de ser amable con el autor original.
- [Ricitos de oro y las tres revisiones de código - Vaidehi Joshi RedDot Ruby Conf 2017](https://confreaks.tv/videos/reddotrubyconf2017-goldilocks-and-the-three-code-reviews) Encontrar la cantidad justa de revisión de código centrándose en lo que está afectando.
- [Implementando una fuerte cultura de revisión de código - Derek Prior Railsconf 2015](https://www.youtube.com/watch?v=PJjmw9TRB7s) Cómo inculcar una cultura de revisión de código saludable en un equipo.

## Herramientas

- [Crucible](https://www.atlassian.com/software/crucible) Herramienta de revisión de código de Atlassian.
- [Gerrit](https://www.gerritcodereview.com/) Herramienta de revisión de código git de código abierto originada en Google.
- [GitHub](https://github.com) Git hosting y pionero de la "Pull Request".
- [GitRise](https://www.gitrise.com/) Recordatorios de Slack para Pull Request.
- [LGTM](https://lgtm.com) Revisión automatizada de código Git para Pull Request de GitHub y Bitbucket para encontrar vulnerabilidades de seguridad y problemas de calidad del código.
- [Phabricator](https://www.phacility.com/phabricator/) Herramienta de revisión de código git / mercurial / svn de código abierto que se origina en Facebook.
- [PullRequest](https://www.pullrequest.com/) Revisión de código como servicio para solicitudes de extracción de GitHub.
- [Pull Reminders](https://pullreminders.com) Recordatorios automatizados de Slack y métricas para Pull Request de GitHub.
- [Reviewable](https://reviewable.io/) Herramienta de revisión de código construida sobre Pull Request de GitHub.
- [Review Board](https://www.reviewboard.org/) Herramienta de revisión de código abierto que es SCM / plataforma neutral.
- [Rubberduck](https://www.rubberduck.io) Extensión del navegador para agregar navegación con reconocimiento de código a los Pull Request de GitHub.
- [Sider](https://sider.review/) Servicio de revisión de código automatizado para GitHub.
- [Softagram](https://softagram.com/) Visualización automatizada de cambio de código (y análisis de dependencia) para Pull Request, Merge Request (GitLab) y conjuntos de parches (Gerrit).
- [Upsource](https://www.jetbrains.com/upsource/) La herramienta de revisión de código git / mercurial / perforce / svn en las instalaciones de JetBrain.

## Contribuir

Las contribuciones son bienvenidas! Lea la [guia de contribución](contributing.md) Primero.

## Licencia

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

En la medida de lo posible según la ley, [John Barton](https://johnbarton.co) ha renunciado a todos los derechos de autor y derechos afines o relacionados a este trabajo.
