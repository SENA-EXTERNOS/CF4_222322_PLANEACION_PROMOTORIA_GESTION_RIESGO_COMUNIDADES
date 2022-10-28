<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Diagnóstico y planificación participativa

    .fondo-1.py-5.mb-5
      .row.justify-content-center.align-items-center  
        .col-md-3.mb-4.mb-md-0
          img.img-a(src='@/assets/curso/temas/tema_1/img_3.png', alt='Texto que describa la imagen')
        .col-lg-7
          p.text-small El conocimiento de las situaciones que afectan a las comunidades y su entorno, es parte del proceso de avanzar en la toma de conciencia, sobre los problemas y elementos que son obstáculo para el desarrollo individual y grupal de las mismas. Se trata de crear un aprendizaje colectivo, basado en el intercambio de experiencias y de la memoria histórica de la comunidad. Este proceso tiene un nivel educativo que pretende el enriquecimiento de la experiencia y el conocimiento de las comunidades. 

    .row.justify-content-center.mb-5
      .col-lg-10
        p Partiendo de lo anterior, es a través del diagnóstico participativo, como las comunidades pueden analizar, sacar conclusiones, ejercer su poder de decisión, estar al tanto de lo que hacen los demás y ofrecer su esfuerzo y experiencia para llevar adelante una labor en común. A continuación, se exponen los recursos necesarios, para desarrollar un correcto diagnóstico:

    .row.mb-5.justify-content-stretch.align-items-stretch.d-flex.h-100
      .col-md-6.col-lg.mb-5.mb-lg-0(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_4.svg' alt='AvatarTop')
          .tarjeta.mog
            .p-4 
              h5.text-center  Recursos con los que cuenta la comunidad.
      .col-md-6.col-lg.mb-5.mb-lg-0(data-aos="fade-down")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_5.svg' alt='AvatarTop')
          .tarjeta.mog
            .p-4 
              h5.text-center  Personas que pueden trabajar.
      .col-md-6.col-lg.mb-5.mb-lg-0(data-aos="fade-left")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_6.svg' alt='AvatarTop')
          .tarjeta.mog
            .p-4
              h5.text-center  Dinero que se puede reunir para solucionar el problema, o determinar qué organismo nacional o internacional apoyaría la iniciativa.

    p.mb-5 Es así como la participación comunitaria se puede entender como la toma de conciencia, de manera colectiva, de un grupo de personas, sobre factores que afecten sus necesidades y recursos existentes, llevando a que se formulen proyectos o actividades con intereses comunes. Es fundamental que este proceso tenga en cuenta los siguientes factores:

    .fondo-2.p-5
      .row
        .col-lg-3.mb-4.mb-md-0(data-aos="fade-left")
          img.img-a(src='@/assets/curso/temas/tema_1/img_7.png', alt='Texto que describa la imagen')
        .col-lg-9(data-aos="fade-right").bg_sp
          AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg_1")
            div(titulo="Factor 1")
              p La participación se concibe y se mide, de acuerdo con el grado de decisión y de poder para actuar dentro de una comunidad, la cual representa la perspectiva democrática sobre cómo funciona una sociedad y el papel que desempeña al efectuar acciones dentro de sí misma. 

            div(titulo="Factor 2")
              p Inicia como un proceso individual, en el cual, las personas logran reconocer los valores y potencialidades que tienen para participar activamente en un grupo, ya que todo proceso participativo está caracterizado por buscar transformar una realidad, partiendo de las decisiones para asumir nuevos cambios. 

              p La planificación participativa se entiende como un proceso que permite que se aumenten las capacidades colectivas de identificar y analizar problemáticas puntuales, con el fin de formular y planificar diversas visiones y soluciones hacia el desarrollo sostenible de las comunidades, en las cuales se movilicen los recursos y se implementen acciones en las diferentes áreas de esparcimiento humano, en el intento de las personas por ganar control sobre los procesos que condicionan sus vidas.
            div(titulo="Factor 3")
              p Las etapas de desarrollo de la participación, han logrado llegar a conformar los denominados procesos sociales, los cuales se adelantan con acciones colectivas en espacios públicos, en los cuales se permite el acceso fácilmente, para lograr objetivos que estén acordes con las necesidades de la población. La participación debe ser política, comunitaria, ciudadana y social, para que sea integrada y congruente con las metas pactadas.
              
    separador
    #t_1_1.titulo-segundo.color-acento-contenido.mt-5
      h2 1.1 Identificación de las instituciones y organizaciones comunitarias

    .row.align-items-center.mb-5 
      .col-md-7.mb-4.mb-md-0(data-aos="fade-right")
        p La participación comunitaria dentro de una comunidad se encuentra dividida en los siguientes dos grupos:

        p En un primer momento, se conocerá al grupo que se caracteriza por estar determinado según los procesos sociales de la participación.
      .col-lg-4(data-aos="fade-left")
        img.img-a(src='@/assets/curso/temas/tema_1/img_9.png', alt='Texto que describa la imagen')

    TabsC.color-primario.mb-5
      .py-3.py-md-4(titulo="Participación política")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0
            img.img-a(src='@/assets/curso/temas/tema_1/img_10.png', alt='Texto que describa la imagen')
        
          .col-md-6
            h4 Participación política
            p Se genera únicamente con grupos de manera legal, legítima y conscientemente organizados, ya sea, en partidos o movimientos políticos, en los cuales los ciudadanos participan de las decisiones y gestiones que estén asociadas a la implementación de acciones públicas. 
      .py-3.py-md-4(titulo="Participación social")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0
            img.img-a(src='@/assets/curso/temas/tema_1/img_11.png', alt='Texto que describa la imagen')
        
          .col-md-6
            h4 Participación social
            p Conformada por los ciudadanos agrupados y organizados en forma colectiva, que hacen parte de instituciones que no pertenecen al Estado en ninguna de las ramas del poder público.
        
      .py-3.py-md-4(titulo="Participación comunitaria")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0
            img.img-a(src='@/assets/curso/temas/tema_1/img_12.png', alt='Texto que describa la imagen')
        
          .col-md-6
            h4 Participación comunitaria
            p Involucra a los ciudadanos en acciones ejecutadas colectivamente, para la búsqueda de soluciones a las necesidades de su vida cotidiana.

    .fondo-2.p-5
      p A continuación se analiza el segundo grupo, en el cual las variables de actuación son las que lo determinan.

      .bg_2.mb-5
        TabsC.color-acento-contenido
          .py-3.py-md-4(titulo="Participación pasiva")
            .row.justify-content-center.align-items-center
              .col-md-4.mb-4.mb-md-0(data-aos="fade-right")
                img.img-a(src='@/assets/curso/temas/tema_1/img_13.png', alt='Texto que describa la imagen')
            
              .col-md-6(data-aos="fade-left")
                h4 Participación pasiva
                p Es el impulso inicial que se obtiene ante una información que se recibe con bajo interés, al punto que tiende a desaparecer rápidamente.  
          .py-3.py-md-4(titulo="Participación mediante la consulta")
            .row.justify-content-center.align-items-center
              .col-md-4.mb-4.mb-md-0(data-aos="fade-right")
                img.img-a(src='@/assets/curso/temas/tema_1/img_14.png', alt='Texto que describa la imagen')
              .col-md-6(data-aos="fade-left")
                h4 Participación mediante la consulta
                p Es el medio para lograr la construcción de opiniones frente al tema que se esté tratando, buscando el avance en la toma de decisiones. 
          .py-3.py-md-4(titulo="Participación por incentivos")
            .row.justify-content-center.align-items-center
              .col-md-4.mb-4.mb-md-0(data-aos="fade-right")
                img.img-a(src='@/assets/curso/temas/tema_1/img_15.png', alt='Texto que describa la imagen')
              .col-md-6(data-aos="fade-left")
                h4 Participación por incentivos
                p Consiste en proveer recursos materiales por trabajo (alimentos, dinero, entre otros).
          .py-3.py-md-4(titulo="Participación funcional")
            .row.justify-content-center.align-items-center
              .col-md-4.mb-4.mb-md-0(data-aos="fade-right")
                img.img-a(src='@/assets/curso/temas/tema_1/img_16.png', alt='Texto que describa la imagen')
              .col-md-6(data-aos="fade-left")
                h4 Participación funcional
                p En este momento los grupos desarrollan acciones y análisis en conjunto, logrando la formulación de planes estratégicos y el fortalecimiento de las comunidades locales.
          .py-3.py-md-4(titulo="Participación interactiva")
            .row.justify-content-center.align-items-center
              .col-md-4.mb-4.mb-md-0(data-aos="fade-right")
                img.img-a(src='@/assets/curso/temas/tema_1/img_17.png', alt='Texto que describa la imagen')
              .col-md-6(data-aos="fade-left")
                h4 Participación interactiva
                p Son las interrelaciones en el interior de la estructura formal de los grupos, y las gestiones desarrolladas mediante contactos con organizaciones externas en el logro de objetivos comunitarios. 
          .py-3.py-md-4(titulo="Participación desarrollada")
            .row.justify-content-center.align-items-center
              .col-md-4.mb-4.mb-md-0(data-aos="fade-right")
                img.img-a(src='@/assets/curso/temas/tema_1/img_18.png', alt='Texto que describa la imagen')
              .col-md-6(data-aos="fade-left")
                h4 Participación desarrollada
                p Es la máxima madurez lograda por una organización, representada en la toma de iniciativas independientes y con capacidad de responder, por las metas de una colectividad.

      h3.mb-0 Mecanismos constitucionales

    .row.mb-5.align-items-center
      .col-lg-7.mb-4.mb-md-0
        .cajon.color-primario.p-4.mb-4
          p.text-small.mb-0 El Estado colombiano contribuye a la organización, promoción y capacitación de todas aquellas asociaciones profesionales, cívicas, sindicales, comunitarias, juveniles, benéficas, o que sean de utilidad común no gubernamental, para que constituyan mecanismos democráticos de representación en todas las instancias de participación, concertación, control y vigilancia de la gestión pública que se establezca. 
      .col-lg-4  
        img.img-a(src='@/assets/curso/temas/tema_1/img_19.png', alt='Texto que describa la imagen')

    p Los mecanismos constitucionales que tiene la ciudadanía en Colombia para participar en la toma de decisiones son:

    TabsC.color-secundario.fondo-3.mb-5
      .py-3.py-md-4(titulo="Plebiscito")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
            img.img-a(src='@/assets/curso/temas/tema_1/img_20.png', alt='Texto que describa la imagen')
        
          .col-md-5(data-aos="fade-left").text-small
            h4 Plebiscito
            p Es el pronunciamiento del pueblo, una vez es convocado por el presidente de la República, mediante el cual la comunidad apoyará o rechazará una determinada decisión del ejecutivo. 

            p De acuerdo con el Artículo 77 de la Ley 134 de 1994, el presidente de la República de Colombia, con la firma de todos los ministros, podrá convocar al pueblo para que se pronuncie sobre las políticas del Ejecutivo, que no requieran aprobación del Congreso, excepto, las relacionadas con los estados de excepción y el ejercicio de los poderes correspondientes.

      .py-3.py-md-4(titulo="Iniciativa popular legislativa")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
            img.img-a(src='@/assets/curso/temas/tema_1/img_21.png', alt='Texto que describa la imagen')
        
          .col-md-5(data-aos="fade-left").text-small
            h4 Iniciativa popular legislativa
            p Partiendo del Artículo 2 de la Ley 134 de 1994, la iniciativa popular, es el derecho político de un grupo de ciudadanos de presentar un proyecto de acto legislativo y de ley ante el Congreso de la República, de ordenanza ante las Asambleas departamentales, de acuerdo ante los Concejos municipales o Distritales,  de resolución ante las Juntas administradoras locales, y demás resoluciones de las corporaciones o entidades territoriales, de acuerdo con las leyes que las reglamentan según el caso, para que sean debatidos y posteriormente aprobados, modificados o negados por la corporación pública correspondiente.

            p Para realizar esta iniciativa, en primera instancia, se debe inscribir un comité de promotores, el cual debe estar respaldado por apoyos representados en firmas que equivalgan al cinco por mil del censo electoral. 

      .py-3.py-md-4(titulo="Referendo")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
            img.img-a(src='@/assets/curso/temas/tema_1/img_22.png', alt='Texto que describa la imagen')
        
          .col-md-5(data-aos="fade-left").text-small
            h4 Referendo
            p Es la convocatoria que se le hace a la comunidad, para que sea aprobado o rechazado un proyecto de norma jurídica ya vigente. 

            p.mb-0 #[strong Existen dos tipos de referendos:] 
            | Aprobatorio: es aquel proyecto de acto legislativo que es sometido a consideración de la comunidad, para que decida si lo aprueba o lo rechaza, de manera total o parcialmente. <br>
            | Derogatorio: es el sometimiento de una norma, que ya ha sido aprobada por el Congreso, el Concejo municipal o la Asamblea departamental, a consideración de la comunidad, para que tome la decisión de derogar la respectiva ley o acuerdo. 

      .py-3.py-md-4(titulo="Revocatoria del mandato")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
            img.img-a(src='@/assets/curso/temas/tema_1/img_23.png', alt='Texto que describa la imagen')
        
          .col-md-5(data-aos="fade-left").text-small
            h4 Revocatoria del mandato
            p Este mecanismo de participación ciudadana consiste en el derecho político que tienen todos los colombianos, para dar por terminado el mandato que le han conferido a un gobernador o alcalde.

            p Si como resultado de la votación, no se revoca el mandato, no podrá volver a intentarse este mecanismo por lo que resta de su período. De lo contrario, desde la Ley 134 de 1994, es la Registraduría Nacional del Estado Civil, el ente encargado de hacer la notificación oficial al presidente de la República del resultado de la revocatoria.

      .py-3.py-md-4(titulo="Cabildo abierto")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
            img.img-a(src='@/assets/curso/temas/tema_1/img_24.png', alt='Texto que describa la imagen')
        
          .col-md-5(data-aos="fade-left").text-small
            h4 Cabildo abierto
            p El cabildo abierto es la reunión pública de todos los consejos distritales, municipales o de las juntas de administraciones locales, en las cuales, la comunidad puede participar directamente, con la finalidad de discutir diversos asuntos que sean de interés para los habitantes. 

            p Cualquier tema que sea de impacto para la comunidad, podrá ser material del cabildo abierto, con excepción de proyectos de ordenanza, acuerdos o algún otro acto administrativo. A los cabildos pueden asistir todas las personas que tengan interés en el asunto.

    h3.mb-5 Actores sociales

    .row.justify-content-center.mb-5
      .col-lg-11
        .bloque-texto-g.color-secundario.p-5.p-sm-5.p-md-5
          .bloque-texto-g__img.m-left(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema_1/img_25.png')})`}"
          )
          .bloque-texto-g__texto.py-5.px-3.txt-g.bloque-g-txt
            h5.mb-0 Representan sujetos activos que inciden en procesos económicos, culturales o políticos de la comunidad en la cual intervienen. #[.txt_1 Sus acciones están direccionadas a aportar valores al beneficio de la comunidad. ]

    .row.mb-5.align-items-center
      .col-lg-5.mb-4.mb-md-0(data-aos="fade-right")
        img.img-a(src='@/assets/curso/temas/tema_1/img_26.png', alt='Texto que describa la imagen')
      .col-lg-7(data-aos="fade-left")
        span.bg_txt_1 La estructuración de los actores sociales está basada en la toma de conciencia propia, en la cual el sujeto sea portador de valores y recursos los cuales le permitan actuar dentro de una sociedad para defender los intereses de los diferentes miembros que la componen para dar respuesta a las necesidades que se identifican prioritariamente. También puede ser entendido como un grupo de intervención, tal que percibe a sus miembros como productores de su historia, para la transformación de su situación. O sea que el actor social actúa sobre el exterior, pero también sobre sí mismo.
        p Estos actores se pueden identificar y caracterizar como aquellas personas influyentes, no por su capital económico, sino por el poder en la toma de decisiones. Usualmente, se encuentran al interior de los grupos o instituciones que tienen alguna relación con el ciclo social de interés para su comunidad.

    p Las características de los actores sociales son:

    .fondo-4.p-4.mb-5
      .row.justify-content-center
        .col-lg-8(data-aos="flip-left")
          img.img-a(src='@/assets/curso/temas/tema_1/img_27.svg', alt='Texto que describa la imagen')

    .row.justify-content-center.mb-5
      .col-lg-10
        .cajon.color-primario.p-4
          p.mb-0 Los actores que se encuentran en la comunidad, se deben analizar según su nivel de influencia. De esta manera, se comprende la colaboración y el conflicto que contemplan las relaciones dentro del grupo, la legitimidad en el reconocimiento de los derechos y responsabilidades de cada persona. 

    .row.mb-5
      .col-lg-3.mb-4.mb-md-0(data-aos="fade-left")
        img.img-a(src='@/assets/curso/temas/tema_1/img_29.png', alt='Texto que describa la imagen')
      .col-lg-9(data-aos="fade-right").bg_sp
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg_1")
          .row.justify-content-center(titulo="Delegaciones gubernamentales")
            .col-lg-10
              ul
                li.lista-ul__vineta
                  span Organismos del gobierno central
                li.lista-ul__vineta
                  span Gobierno regional
                li.lista-ul__vineta
                  span Gobierno local
          .row.justify-content-center(titulo="Comunidades y organizaciones sociales")
            .col-lg-10
              ul
                li.lista-ul__vineta
                  span Comunidades campesinas
                li.lista-ul__vineta
                  span Juntas de regentes
                li.lista-ul__vineta
                  span Asociaciones de propietarios
                li.lista-ul__vineta
                  span Sindicatos
                li.lista-ul__vineta
                  span Asociaciones de vecinos
          .row.justify-content-center(titulo="Organizaciones no gubernamentales")
            .col-lg-10
              ul
                li.lista-ul__vineta
                  span Fundaciones
                li.lista-ul__vineta
                  span Asociaciones
                li.lista-ul__vineta
                  span Cooperativas
                li.lista-ul__vineta
                  span Club de desarrollo
                li.lista-ul__vineta
                  span Consejos o Comités de desarrollo
                li.lista-ul__vineta
                  span Consorcios
          .row.justify-content-center(titulo="Centros educativos")
            .col-lg-10
              ul
                li.lista-ul__vineta
                  span Centros universitarios
                li.lista-ul__vineta
                  span Institutos superiores tecnológicos
                li.lista-ul__vineta
                  span Colegios
          .row.justify-content-center(titulo="Programas y proyectos")
            .col-lg-10
              ul
                li.lista-ul__vineta
                  span Programas y proyectos de cooperación internacional
                li.lista-ul__vineta
                  span Programas y proyectos nacionales
                li.lista-ul__vineta
                  span Programas y proyectos sectoriales
          .row.justify-content-center(titulo="Banca y finanzas")
            .col-lg-10
              ul
                li.lista-ul__vineta
                  span Bancos
                li.lista-ul__vineta
                  span Financieras y microfinancieras
                li.lista-ul__vineta
                  span Casas de cambio
                li.lista-ul__vineta
                  span Aseguradoras
                li.lista-ul__vineta
                  span Administradoras de fondos de pensiones
          .row.justify-content-center(titulo="Centros religiosos")
            .col-lg-10
              ul
                li.lista-ul__vineta
                  span Iglesias
                li.lista-ul__vineta
                  span Congregaciones
          .row.justify-content-center(titulo="Empresa privada")
            .col-lg-10
              ul
                li.lista-ul__vineta
                  span Proveedores
                li.lista-ul__vineta
                  span Contratistas

    h3.mb-3 Grupos focales

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-2.mb-4.mb-md-0(data-aos="fade-rigth")
        img.img-a(src='@/assets/curso/temas/tema_1/img_30.png', alt='Texto que describa la imagen')
      .col-lg-9(data-aos="fade-left")
        p Son un espacio de discusión que facilita el diálogo alrededor de experiencias comunes, estimulando el debate entre los participantes. La finalidad es generar un proceso dinámico, en el cual los diferentes participantes, intercambian ideas de manera que puedan ser contestadas por otros, para así construir colectivamente ideas. 

    .fondo-5.py-5.mb-5
      .row.justify-content-center.align-items-center  
        .col-lg-7.mb-4.mb-md-0(data-aos="fade-rigth")
          p.text-small La principal finalidad de un grupo focal, es poder analizar los diferentes puntos de vista de los actores de la comunidad para entender las necesidades. Esta técnica es de gran utilidad para explorar los conocimientos y experiencias de las personas que están en un ambiente de interacción, lo cual permite que se examine lo que cada una de ellas piensa y las razones que esboza frente a sus pensamientos. Este trabajo grupal facilita la discusión y activa a los participantes a comentar y opinar aún en aquellos temas que se consideran como tabú, lo que permite generar una gran riqueza de testimonios.
        .col-md-4(data-aos="fade-left")
          img.img-a(src='@/assets/curso/temas/tema_1/img_32.png', alt='Texto que describa la imagen')

    .row.justify-content-center.mb-5
      .col-lg-4.mb-4.mb-md-0(data-aos="fade-rigth")
        img.img-a(src='@/assets/curso/temas/tema_1/img_33.png', alt='Texto que describa la imagen')
      .col-lg-8
        p El grupo usualmente está compuesto por un número reducido de personas que han sido seleccionadas cuidadosamente, en función de un conjunto de criterios previamente determinados, los cuales pueden ser: la edad, la ubicación, el nivel socioeconómico, la raza, entre otros.

        .cajon.color-primario.p-4
          p Si los grupos focales son ejecutados efectivamente, la calidad de los resultados estará enfocado en mejorar la capacidad de solucionar problemas a etapa temprana. Cuando los participantes están genuinamente comprometidos con el estudio, el resultado será la claridad en los temas discutidos. 

          p.mb-0 Los pasos que se deben seguir para realizar un grupo focal son:

    .bg_3.p-4.mb-5(data-aos="flip-right")
      SlyderF.mb-5(columnas="col-lg-4 col-xl-4").align-items-stretch.d-flex.h-100
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_34.svg' alt='AvatarTop')
          .tarjeta.bg_4
            .p-4
              p.text-center #[strong Definir el tema que se quiera analizar a profundidad. Es necesario tener en cuenta que, si se selecciona más de un tópico, no se podrá cubrir a fondo el planteado inicialmente. Es por esto que, en ocasiones, se realizan múltiples rondas de grupos focales sobre distintos asuntos.]

        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_35.svg' alt='AvatarTop')
          .tarjeta.bg_4
            .p-4
              p.text-center #[strong Generar un listado de preguntas y sugerencias de discusión, ayudará a recopilar datos que se necesiten. Se deben hacer preguntas abiertas para propiciar respuestas profundas.] 

        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_36.svg' alt='AvatarTop')
          .tarjeta.bg_4
            .p-4
              p.text-center #[strong Seleccionar un moderador para que lidere la discusión y fomente nuevas ideas en los participantes. Al mismo tiempo otra persona se encarga de tomar anotaciones sobre lo expresado.]

        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_37.svg' alt='AvatarTop')
          .tarjeta.bg_4
            .p-4
              p.text-center #[strong Una de las partes más desafiantes de los grupos focales, es lograr que las personas asistan. Por esto, se debe invitar con tiempo prudente, a las personas que se requieren para el encuentro, ya sea, a través de comunicaciones personalizadas o medios de difusión.] 

        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_38.svg' alt='AvatarTop')
          .tarjeta.bg_4
            .p-4
              p.text-center #[strong Antes de iniciar, los participantes deben firmar un formulario de consentimiento, en el cual, se reitera el objetivo de la investigación y las pautas a seguir.]

        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_39.svg' alt='AvatarTop')
          .tarjeta.bg_4
            .p-4
              p.text-center #[strong Se debe iniciar fomentando la participación de las personas involucradas, haciendo que se presenten entre ellos y den una descripción de su historial. Luego se hacen las preguntas.]

    .row.justify-content-center.mb-5(data-aos="flip-right")
      .col-lg-10
        .cajon.color-secundario.bg_5.p-4
          o.mb-0 La principal diferencia que existe entre los grupos focales y las entrevistas grupales, es que, en las entrevistas todo el grupo interactúa al mismo tiempo, haciendo énfasis en las preguntas y respuestas entre el investigador y los participantes. En cambio, el grupo focal está centrado en la interacción que se presenta dentro del grupo, la cual se mueve en torno al tema inicialmente propuesto.

    h3.mb-5 Grupos poblacionales

    .row.justify-content-center.mb-5(data-aos="flip-right")
      .col-lg-11
        .bloque-texto-g.color-secundario.p-5.p-sm-5.p-md-5
          .bloque-texto-g__img.m-left(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema_1/img_40.png')})`}"
          )
          .bloque-texto-g__texto.py-5.px-3.txt-g.bloque-g-txt
            p.mb-0 En las décadas recientes se ha venido avanzando en reconocer la diversidad de los grupos poblacionales que habitan en los territorios. 
            p Estos grupos son comunidades que viven en áreas específicas o tienen entre sí características similares. Centrando la atención en Colombia, existen diferentes segmentos poblacionales, en los cuales hay comunidades que comparten la misma raza y/o, pertenecen a la misma comunidad lingüística y cultural. 

    .row.mb-5.align-items-center
      .col-lg-5.mb-4.mb-md-0(data-aos="fade-right")
        img.img-a(src='@/assets/curso/temas/tema_1/img_41.png', alt='Texto que describa la imagen')
      .col-lg-7(data-aos="fade-left")
        span.bg_txt_1 Para la toma de decisiones en favor de la prevención del riesgo, es necesario que participen todos los grupos poblacionales que presenten niveles de vulnerabilidad elevados, ya que son los principales afectados si se genera una situación de desastre. La inclusión social es fundamental para evaluar los riesgos presentes en las comunidades, no puede existir exclusión de ningún tipo, ya que todos y cada uno de los participantes de una sociedad son igual de importantes, sin distinción de niveles económicos, sociales o diferencias entre sus creencias.
        p Las acciones que se dispongan para reunir a los diferentes grupos poblacionales, deben estar previamente establecidas, para evitar que alguien quede por fuera de la toma de decisiones. La participación adecuada de cada uno de los actores, permite que los conocimientos adquiridos puedan ser re direccionados hacia sus comunidades.

    p Haciendo énfasis en lo anterior, se puede definir la participación comunitaria, como la toma de conciencia de manera colectiva de un grupo de personas, sobre factores que afecten sus necesidades y recursos existentes, llevando a que se formulen proyectos o actividades con intereses comunes.
    p.mb-5 Sus componentes son:


    .row.mb-5
      .col-lg-3.mb-4.mb-md-0(data-aos="fade-left")
        img.img-a(src='@/assets/curso/temas/tema_1/img_42.png', alt='Texto que describa la imagen')
      .col-lg-9(data-aos="fade-right").bg_sp
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg_1")
          .row.justify-content-center(titulo="Identidad")
            .col-lg-10
              p Los miembros de la comunidad comparten gustos, intereses y objetivos, otorgándoles rasgos y características que permiten distinguirlos.
          .row.justify-content-center(titulo="Objetivos en común")
            .col-lg-10
              p El trabajo de la comunidad es en pro de cumplir las metas que se proponen y todos aportan a su cumplimiento.
          .row.justify-content-center(titulo="Compromiso")
            .col-lg-10
              p Se adquieren valores que crean lazos y permiten vivir en armonía.
          .row.justify-content-center(titulo="Cultura")
            .col-lg-10
              p Se comparten costumbres que determinan lo que es y no es permitido; se transmite su tradición de generación en generación.
          .row.justify-content-center(titulo="Interacción")
            .col-lg-10
              p Las personas de la comunidad interactúan dentro de una sociedad más grande, en la cual comparten con otros grupos sociales.
          .row.justify-content-center(titulo="Dinamica")
            .col-lg-10
              p Las comunidades están en constante cambio.

    .fondo-6.p-4.mb-5
      p.mb-5 En el Marco de Acción de Hyogo 2005 - 2015 llamado construyendo la Resiliencia de las Naciones y Comunidades frente a Desastres (MAH) muestra los elementos fundamentales para la GRD priorizados en cinco acciones para el logro de las metas estratégicas de la Conferencia Mundial sobre Reducción de Desastres.      

      SlyderF.mb-5(columnas="col-lg-4 col-xl-4").align-items-stretch.d-flex.h-100
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_43.svg' alt='AvatarTop')
          .tarjeta.bg_5
            .p-4.text-center
              h4 Comunidad científica
              p Es el cuerpo de científicos en su totalidad, en el cual se presentan vínculos e interacciones, a partir del intercambio de ideas, investigaciones y publicaciones. 
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_44.svg' alt='AvatarTop')
          .tarjeta.bg_5
            .p-4.text-center
              h4 Comunidad religiosa
              p Son todos aquellos grupos de personas que profesan una determinada religión. 
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_45.svg' alt='AvatarTop')
          .tarjeta.bg_5
            .p-4.text-center
              h4 Comunidad educativa
              p Conformada por todos los sujetos del ambiente educativo, bien sea de universidades, colegios o jardines infantiles. También se pueden incluir a los profesores, estudiantes y exalumnos. 
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_46.svg' alt='AvatarTop')
          .tarjeta.bg_5
            .p-4.text-center
              h4 Comunidad rural
              p Se compone por individuos que habitan y realizan sus actividades en el campo, tales como la agricultura y la ganadería. 
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_47.svg' alt='AvatarTop')
          .tarjeta.bg_5
            .p-4.text-center
              h4 Comunidad virtual
              p En este grupo se reúnen personas que tienen un interés común, este concepto nace mediante el desarrollo de la web y las redes sociales.
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema_1/img_48.svg' alt='AvatarTop')
          .tarjeta.bg_5
            .p-4.text-center
              h4 Comunidad biológica
              p Está compuesta por los organismos naturales tales como plantas, animales, hongos y humanos los cuales conviven dentro de un mismo ecosistema. 

    h3.mb-5 Promotoría ambiental

    .row.justify-content-center.mb-5
      .col-lg-10
        .cajon.color-primario.p-4
          p.mb-0 Es la capacidad que tienen diversos actores de la comunidad para promover acciones, encaminadas en el cuidado del medio ambiente y la construcción de un futuro basado en modelos de desarrollo sostenible.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-3.mb-4.mb-md-0(data-aos="fade-rigth")
        img.img-a(src='@/assets/curso/temas/tema_1/img_49.png', alt='Texto que describa la imagen')
      .col-lg-7(data-aos="fade-left")
        p.text-small Los promotores ambientales son los principales actores y pilares de la educación ambiental, ya que, además de actuar como líderes comunitarios desarrollando proyectos y programas en pro del medio ambiente y la relación con comunidades, también contribuyen con los procesos de sensibilización y educación. Las responsabilidades sociales que se tiene frente a sus localidades y su región, le permite ser un sujeto respetado y reconocido por la localidad en la que habita. Se destaca por su vocación de servicio, por su saber y conocimiento espontáneo, que le permiten dar respuestas y proponer fórmulas de encuentro para conciliar los intereses de distintos actores sociales.

    p.mb-5 Partiendo de lo anterior, las funciones de un promotor son:

    .row.justify-content-center.mb-5(data-aos="fade-up")
      .col-lg-8
        img.img-a(src='@/assets/curso/temas/tema_1/img_50.svg', alt='Texto que describa la imagen')

    h3.mb-5 Objetivos y estrategias de la promoción ambiental

    .row.justify-content-center.mb-5
      .col-lg-11
        .bloque-texto-g.color-primario.p-5.p-sm-5.p-md-5
          .bloque-texto-g__img.m-left(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema_1/img_51.png')})`}"
          )
          .bloque-texto-g__texto.py-5.px-3.txt-g.bloque-g-txt
            p.mb-0 El Ministerio de ambiente y desarrollo sostenible de Colombia (2020), viene implementado el programa Promotores ambientales comunitarios, como una herramienta para el cumplimiento de la estrategia contenida en la Política nacional de educación ambiental, denominada Formación de educadores y dinamizadores ambientales, cuyo objetivo principal es promover y cualificar la participación ciudadana en los procesos de planificación, gestión y seguimiento de las políticas, planes, programas y proyectos, que orientan el desarrollo sostenible y la educación ambiental, tanto en lo local como en lo regional, buscando dinamizar las entidades territoriales, con la garante de construir una sociedad comprometida y enfocada en mejorar sus interacciones con el medio ambiente.


    separador
    #t_1_2.titulo-segundo.color-acento-contenido.mt-5
      h2 1.2	Programas de capacitación y sensibilización

    h5.mb-5 Programas de capacitación y sensibilización ambiental.

    figure.mb-5(data-aos="zoom-in-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video

    p.mb-5 Estos son los principales sucesos históricos en los cuales se comenzó a hablar de la educación ambiental:

    .fondo-7
      LineaTiempoB.color-primario.mb-5(:datos="datosLineaTiempoB")

    separador
    #t_1_3.titulo-segundo.color-acento-contenido.mt-5
      h2 1.3 Instrumentos de capacitación y sensibilización

    .fondo-8.py-5.p-4.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-4.mb-4.mb-md-0(data-aos="fade-rigth")
          img(src='@/assets/curso/temas/tema_1/img_61.png', alt='Texto que describa la imagen')
        .col-lg-7.text-small
          p La capacitación hace referencia a un conjunto de actividades didácticas que están orientadas a ampliar diferentes conocimientos y habilidades sobre un tema específico. Es una de las herramientas más útiles para transmitir de manera efectiva, ciertos temas que son necesarios para el desarrollo de actividades, tanto individuales como colectivas. 
          p La tarea de educar y sensibilizar a las poblaciones es el principal soporte para impulsar el desarrollo sostenible de una manera constante y permanente, por ende, es necesario que se orienten los esfuerzos en torno al diseño, implementación y masificación de campañas de sensibilización, a través de todos los medios de comunicación, de manera directa a nivel nacional, regional, local y comunitario.

    .row.justify-content-center.mb-5
      .col-lg-7(data-aos="slide-right")
        .bloque-texto-b.color-secundario.p-4
          .bloque-texto-b__texto
            h6.mb-0 Es necesario incrementar el nivel de conciencia ciudadana sobre la importancia de los riesgos y su relación con la calidad de vida de la población, sobre sus responsabilidades frente a estos y reforzar su compromiso y su participación en la gestión de riesgos de desastres. Se debe adelantar acciones, para que las sociedades entiendan que la responsabilidad es de todos en la construcción de soluciones.
      .col-lg-3(data-aos="slide-left")
        img(src='@/assets/curso/temas/tema_1/img_62.png', alt='Texto que describa la imagen')

    p.mb-5 Se puede capacitar a una comunidad de las siguientes maneras:

    .fondo-2.p-5
      .row
        .col-lg-5.mb-4.mb-md-0(data-aos="fade-left")
          img.img-a(src='@/assets/curso/temas/tema_1/img_63.png', alt='Texto que describa la imagen')
        .col-lg-7(data-aos="fade-right")
          AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
            div(titulo="Aprendizaje pasivo")
              p El participante es el receptor pasivo de los conocimientos que está impartiendo el instructor, ya sea de manera directa o indirecta.
            div(titulo="Aprendizaje activo")
              p Le exige al participante actuar y pensar para que logre descubrir el conocimiento. El instructor y los medios didácticos, juegan un papel que consiste en facilitar, guiar y estimular al aprendiz.
            div(titulo="Capacitación grupal")
              p Esta capacitación es brindada a un grupo de participantes y se genera una enseñanza colectiva.
            div(titulo="Capacitación individual")
              p La empresa se entiende como un todo mediante el planteamiento de un programa formativo, el cual se adelante a través de talleres o seminarios, con el fin de que cada uno de los miembros de la organización adquieran los mismos conocimientos útiles.
            div(titulo="Capacitación organizacional")
              p La empresa se entiende como un todo mediante el planteamiento de un programa formativo, el cual se adelante a través de talleres o seminarios, con el fin de que todos los miembros de la organización adquieran los mismos conocimientos útiles. 
            div(titulo="Capacitación asertiva")
              p Esta es aplicada cuando existen dificultades de comunicación entre los líderes y sus colaboradores, cuando las tareas no son debidamente elaboradas por la falta de comprensión de las reglas.

    .row.justify-content-center.mb-5(data-aos="flip-right")
      .col-lg-10
        .cajon.color-primario.p-4
          p.mb-0 La educación, al igual que todos los campos de actividad del hombre, requiere también de una buena dosis de técnica por parte del maestro, la cual debe estar encaminada al manejo de la clase, la organización de la asignatura y al proceso de interrelación maestro –alumno, para la elaboración de los conocimientos, sin descuidar, además, la comprobación de los resultados que hacen de la evaluación un proceso en el que debe notarse la preparación profesional del educador.

    p.mb-5 Haciendo énfasis en lo anterior, se revisan las técnicas educativas más utilizadas:

    TabsC.color-primario.fondo-3.mb-5
      .py-3.py-md-4(titulo="Técnicas para el aprendizaje asistido")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
            img.img-a(src='@/assets/curso/temas/tema_1/img_64.png', alt='Texto que describa la imagen')
        
          .col-md-5(data-aos="fade-left")
            h4 Técnicas para el aprendizaje asistido
            ul.lista-ul
              li 
                span.fas.fa-angle-right
                | Entrevista
              li 
                span.fas.fa-angle-right
                | Estudio dirigido exegético
              li 
                span.fas.fa-angle-right
                | Exposición didáctica expositiva
              li 
                span.fas.fa-angle-right
                | Redescubrimiento
              li 
                span.fas.fa-angle-right
                | Resolución de problemas
              li 
                span.fas.fa-angle-right
                | Seminario
      .py-3.py-md-4(titulo="Técnicas para el aprendizaje colaborativo")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
            img.img-a(src='@/assets/curso/temas/tema_1/img_65.png', alt='Texto que describa la imagen')
        
          .col-md-6(data-aos="fade-left")
            h4 Técnicas para el aprendizaje colaborativo
            .row
              .col-lg-6.mb-4.mb-md-0
                ul.lista-ul
                  li 
                    span.fas.fa-angle-right
                    | Argumentación (interrogatorio) tipo asamblea
                  li 
                    span.fas.fa-angle-right
                    | Debate 
                  li 
                    span.fas.fa-angle-right
                    | Entrevista
                  li 
                    span.fas.fa-angle-right
                    | Foro abierto 
                  li 
                    span.fas.fa-angle-right
                    | Discusión dirigida 
                  li 
                    span.fas.fa-angle-right
                    | Lluvia de ideas
              .col-lg-6
                ul.lista-ul
                  li 
                    span.fas.fa-angle-right
                    | Mesa redonda 
                  li 
                    span.fas.fa-angle-right
                    | Panel Phillips 6-6
                  li 
                    span.fas.fa-angle-right
                    | Simposio
                  li 
                    span.fas.fa-angle-right
                    | Socio drama
                  li 
                    span.fas.fa-angle-right
                    | Taller

      .py-3.py-md-4(titulo="Técnicas para el aprendizaje asistido")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
            img.img-a(src='@/assets/curso/temas/tema_1/img_66.png', alt='Texto que describa la imagen')
        
          .col-md-5(data-aos="fade-left")
            h4 Técnicas para el aprendizaje asistido
            ul.lista-ul
              li 
                span.fas.fa-angle-right
                | Cuestionario 
              li 
                span.fas.fa-angle-right
                | Encuesta 
              li 
                span.fas.fa-angle-right
                | Estudio de caso 
              li 
                span.fas.fa-angle-right
                | Experiencia directa
              li 
                span.fas.fa-angle-right
                | Experimental 
              li 
                span.fas.fa-angle-right
                | Lista de cotejo 
              li 
                span.fas.fa-angle-right
                | Observación 
              li 
                span.fas.fa-angle-right
                | Redescubrimiento 
              li 
                span.fas.fa-angle-right
                | Registro anecdótico

      .py-3.py-md-4(titulo="Técnicas para el aprendizaje autónomo")
        .row.justify-content-center.align-items-center
          .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
            img.img-a(src='@/assets/curso/temas/tema_1/img_67.png', alt='Texto que describa la imagen')
        
          .col-md-6(data-aos="fade-left")
            h4 Técnicas para el aprendizaje autónomo
            .row
              .col-lg-6.mb-4.mb-md-0
                ul.lista-ul
                  li 
                    span.fas.fa-angle-right
                    | Analogía
                  li 
                    span.fas.fa-angle-right
                    | Biográfica
                  li 
                    span.fas.fa-angle-right
                    | Bosquejo
                  li 
                    span.fas.fa-angle-right
                    | Esquemático 
                  li 
                    span.fas.fa-angle-right
                    | Cadena de secuencias
                  li 
                    span.fas.fa-angle-right
                    | Cuadro sinóptico
                  li 
                    span.fas.fa-angle-right
                    | Diagrama jerárquico
                  li 
                    span.fas.fa-angle-right
                    | Estudio dirigido 
                  li 
                    span.fas.fa-angle-right
                    | Investigación bibliográfica 
              .col-lg-6
                ul.lista-ul
                  li 
                    span.fas.fa-angle-right
                    | Mapa conceptual
                  li 
                    span.fas.fa-angle-right
                    | Mapa de un cuento
                  li 
                    span.fas.fa-angle-right
                    | Mapa del carácter 
                  li 
                    span.fas.fa-angle-right
                    | Mapa mental
                  li 
                    span.fas.fa-angle-right
                    | Mentefacto
                  li 
                    span.fas.fa-angle-right
                    | Mesa de la idea principal 
                  li 
                    span.fas.fa-angle-right
                    | Resumen 
                  li 
                    span.fas.fa-angle-right
                    | Rueda de atributos.


    .row.justify-content-center.mb-5(data-aos="flip-left")
      .col-lg-10
        .cajon.color-primario.p-4
          p.mb-0 Hemos llegado al final de este componente formativo.  Recuerde explorar los demás recursos que se encuentran disponibles, para ello diríjase al menú principal en donde encontrará la síntesis, una actividad didáctica, material complementario, entre otros. 





</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
    datosLineaTiempoB: [
      {
        titulo: '1972',
        texto:
          'Conferencia de Estocolmo (Suecia) (Naciones Unidas, 1972).<br>Por primera vez se habla de educación ambiental.',
        icono: require('@/assets/curso/temas/tema_1/img_53.svg'),
      },
      {
        titulo: '1975',
        texto:
          'Seminario de Belgrado (Yugoslavia) (UNESCO, 1977).<br>Se publica la Carta de Belgrado, en la cual se establecieron los objetivos de la educación ambiental.',
        icono: require('@/assets/curso/temas/tema_1/img_54.svg'),
      },
      {
        titulo: '1977',
        texto:
          'Congreso Internacional de Educación Ambiental de Tbilisi (URSS) (Ministerio del medio ambiente de Chile, 2022). <br>La educación ambiental se integra al currículum escolar.',
        icono: require('@/assets/curso/temas/tema_1/img_55.svg'),
      },
      {
        titulo: '1992',
        texto:
          'Cumbre de la Tierra, Río de Janeiro (Brasil) (Ministerio del medio ambiente de Chile, 2022).<br>Aparece la Agenda 21 con un capítulo dedicado al fomento de la educación ambiental, como herramienta prioritaria para alcanzar el desarrollo sustentable.',
        icono: require('@/assets/curso/temas/tema_1/img_56.svg'),
      },
      {
        titulo: '1994',
        texto:
          'Ley 19.300 de Bases Generales del Medio Ambiente (Chile) (Ministerio del medioambiente de Chile, 2022).<br>Consigna la educación ambiental como un instrumento de gestión ambiental.',
        icono: require('@/assets/curso/temas/tema_1/img_57.svg'),
      },
      {
        titulo: '2002',
        texto:
          'Cumbre de Johannesburgo sobre el Desarrollo Sostenible (Sudáfrica) (Ministerio del medio ambiente de Chile, 2022).<br>La ONU decretó, entre 2005 y 2015, como el decenio de la Educación para el desarrollo sostenible.',
        icono: require('@/assets/curso/temas/tema_1/img_58.svg'),
      },
      {
        titulo: '2009',
        texto:
          'Política nacional de educación para el desarrollo sustentable (Chile) (Ministerio del medio ambiente de Chile, 2022).<br>Establece una serie de principios, objetivos y líneas estratégicas, orientadas a lograr una educación que promueva el desarrollo sustentable en el país.',
        icono: require('@/assets/curso/temas/tema_1/img_57.svg'),
      },
      {
        titulo: '2015',
        texto:
          'Cumbre de desarrollo sostenible Nueva York (EEUU) (Ministerio del medio ambiente de Chile, 2022).<br>La asamblea general adopta la Agenda 2030 para el desarrollo sostenible, estableciendo 17 grandes objetivos.',
        icono: require('@/assets/curso/temas/tema_1/img_59.svg'),
      },
    ],
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
