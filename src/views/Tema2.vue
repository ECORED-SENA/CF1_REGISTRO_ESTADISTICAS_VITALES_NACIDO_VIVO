<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span.text-white 2
      h1 Estructura de los formatos de certificado recién nacido vivo y de defunción.
    
    p.mb-5 Se invita a explorar el siguiente recurso, en donde se aprenderá la estructura de los formatos de certificado recién nacido vivo.

    .row.justify-content-center.mb-5
      .col-md-5
        SlyderF(columnas="col-12")
          .tarjeta.BG02.p-4
            .row.justify-content-center.mb-3
              .col-4
                img.pt-2(src='@/assets/curso/tema2/img01.svg' alt='AvatarTop')
            h4.ps-3.pe-4.pt-2 Estructura de los formatos de certificado recién nacido vivo y de defunción
            p.ps-3.pe-4.pt-2 El registro civil es un protocolo que, de manera detallada y auténtica, deja constancia de todos los hechos relativos a la identidad, filiación y estado civil de las personas, desde que nacen hasta que mueren. 
          .tarjeta.BG02.px-5.py-4
            .row.justify-content-center.mb-3
              .col-4
                img.pt-2(src='@/assets/curso/tema2/img02.svg' alt='AvatarTop')
            h4.pt-4 En este registro civil 
            p.pt-3 Se sientan los nacimientos, reconocimientos de hijos, adopciones, matrimonios, separaciones, divorcios, defunciones y declaraciones de presunción de muerte, como los principales acontecimientos que importan en la vida civil de las personas.
          .tarjeta.BG02.px-5.py-4
            .row.justify-content-center.mb-3
              .col-4
                img.pt-2(src='@/assets/curso/tema2/img03.svg' alt='AvatarTop')
            h4.pt-4 La certificación de este registro civil
            p.pt-3 Es esencial para el reconocimiento de los derechos y la exigencia de sus deberes a todo(a) colombiano(a) en relación con el Estado, la sociedad y con su familia.
          .tarjeta.BG02.px-5.py-4
            .row.justify-content-center.mb-3
              .col-4
                img.pt-2(src='@/assets/curso/tema2/img04.svg' alt='AvatarTop')
            h4.pt-4.ps-3 En colombia
            p.pt-3.ps-3 Existen tres tipos de registro civil: nacimiento, por el que el ciudadano(a) nace a la vida jurídica; matrimonio, con el que se legaliza el matrimonio frente al Estado, y defunción, con el que se confirma el fallecimiento de una persona.
          .tarjeta.BG02.px-4.pt-2
            .row.justify-content-center
              .col-4
                img.px-2(src='@/assets/curso/tema2/img05.svg' alt='AvatarTop')
            h4.ps-3.pt-2 El reconocimiento de una persona
            p.ps-3.pe-2 En el registro civil de nacimiento y especialmente de todos los niños, permite definir su existencia legal e individualizarla con la designación de un nombre y un Número Único de Identificación Personal (NUIP). Con esta inscripción es posible el reconocimiento de los derechos y deberes como colombiano, así como también le permite acceder a los bienes y servicios del Estado colombiano.
          .tarjeta.BG02.px-4.py-4
            .row.justify-content-center.mb-3
              .col-4
                img.pt-2(src='@/assets/curso/tema2/img06.svg' alt='AvatarTop')
            h4.pt-4.ps-3 El registro civil 
            p.ps-3 Deja constancia de quiénes son los padres del recién nacido, pero también puede registrarse a las personas, niños y niñas de quienes se desconocen sus padres.
          .tarjeta.BG02.px-4.py-4
            .row.justify-content-center.mb-3
              .col-4
                img(src='@/assets/curso/tema2/img07.svg' alt='AvatarTop')
            h4.pt-2.ms-2.me-1 Adicional a la expedición de estos registros
            p.ms-2.me-1 También es posible realizar trámites para enmendarlos, corregirlos, suscribirlos, anularlos, cancelarlos o reconstruirlos, de acuerdo con determinados contextos, algunos con mediación de procesos legales. Por esto, la importancia de familiarizarnos con la estructura de los formatos de recién nacido vivo y de defunción en Colombia.
      .col-md-5
        figure 
          img(src='@/assets/curso/tema2/img08.png')

    ol.lista-img03.ps-4
      li 
        h3.ps-2 Estructura del formato de certificado recién nacido vivo y antecedente para el registro civil

    .row.BGIMG03.align-items-center.mb-4
      .col-lg-4.col-md-5.col-12
        p El objetivo principal del certificado de nacido es recolectar la información verídica sobre la natalidad. Establece, además, el documento antecedente para la inscripción del nacimiento de los niños y niñas en Colombia, ante las respectivas oficinas autorizadas para el diligenciamiento del Registro Civil.
      .col-lg-4.col-md-2.col-8
        img(src='@/assets/curso/tema2/img10.png')
      .col-lg-4.col-md-5.col-12
        p El formato de registro de certificado de recién nacido vivo, consta de dos componentes principales, cuyos objetivos son diferentes. 
        ol.lista-img01.px-4
          li 
            | El certificado de nacido vivo como antecedente y requisito para la inscripción al registro civil.
          li
            | El certificado de nacido vivo como registro de información sobre la natalidad.

    p.mb-5 Por medio de la siguiente infografía, se indican algunas estructuras de los formatos de certificado tanto del recién nacido vivo como de los certificados de defunción.

    .row.justify-content-center.mb-5
      .col-lg-8.mb-4
        h4 Recomendaciones e instrucciones generales: para el diligenciamiento del certificado de recién nacido vivo, es importante tener en cuenta las siguientes recomendaciones: 
      .col-lg-8.col-md-10.col-12
        ImagenInfograficaB.color-acento-botones.mb-4
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema2/img12.png')
          div(x="14.5%" y="48.4%" tooltip="tooltip de max 35 caracteres" numero="1")
            .row.align-items-center
              .col-lg-1.BG04.p-2.mb-4
                h1.text-white.text-center.mb-1 1
              .col-lg-12
                ol.lista-img02.px-4
                  li 
                    | Todos los datos que solicita el DANE en este formulario son estrictamente confidenciales, y estos datos están protegidos bajo reserva estadística por la Ley 79 de 1993, artículo 5°.
                  li 
                    | Se recomienda diligenciar el certificado con letra de imprenta, clara y legible, sin borrones ni enmiendas.
                  li 
                    | Solo se debe marcar con una equis (x) la opción seleccionada para cada pregunta.
                  li 
                    | Antes de realizar el registro se deben revisar las fuentes de información y realizar las indagaciones necesarias para adquirir la información completa y veraz, pues la calidad del dato es importantes para el Sistema Nacional de Registro Civil.
          div(x="26.7%" y="44.9%" tooltip="tooltip de max 35 caracteres" numero="2")
            .row.align-items-center
              .col-lg-1.BG04.p-2.mb-4
                h1.text-white.text-center.mb-1 2
              .col-lg-12
                ol.lista-img02.px-4
                  li 
                    | Se debe verificar antes de escribir todos los datos personales solicitados, tales como nombres completos, edad y  número de identificación de la madre del recién nacido, y que estos datos corresponden fielmente a los documento de identificación. Igualmente los valores de peso y talla de la historia clínica deben ser convalidados; esto con el fin de evitar errores en el trámite, y contratiempos en la notaría o registraduría.
          div(x="41.9%" y="31.3%" tooltip="tooltip de max 35 caracteres" numero="3")
            .row.align-items-center
              .col-lg-1.BG04.p-2.mb-4
                h1.text-white.text-center.mb-1 3
              .col-lg-12
                ol.lista-img02.px-4
                  li 
                    | El registro de la información en el certificado de recién nacido vivo debe ser completo, esto evita posibles fraudes y reduce el subregistro de información.
                  li 
                    | Cuando un formato de certificado se invalide por borrones, enmendaduras o mal diligenciamiento, este debe ser anulado y no destruido. Este formulario anulado, debe ser remitido posteriormente a la dirección seccional o local de salud.
          div(x="61.3%" y="35%" tooltip="tooltip de max 35 caracteres" numero="4")
            .row.align-items-center
              .col-lg-1.BG04.p-2.mb-4
                h1.text-white.text-center.mb-1 4
              .col-lg-12
                ol.lista-img02.px-4
                  li 
                    | Al diligenciar el certificado debe tenerse en cuenta, que se hará en su totalidad, no se deben dejar espacios en blanco, de lo contrario la Oficina de Registro Civil no lo acepta como válido.
                  li 
                    | El certificado se haya numerado de manera individual, única y secuencial; por tal razón, no se  aceptan certificados diligenciados en fotocopias. Esta numeración individual, garantiza la calidad, brinda confiabilidad y evita la presencia de duplicidades.
          div(x="71.5%" y="43.5%" tooltip="tooltip de max 35 caracteres" numero="5")
            .row.align-items-center
              .col-lg-1.BG04.p-2.mb-4
                h1.text-white.text-center.mb-1 5
              .col-lg-12
                ol.lista-img02.px-4
                  li 
                    | No se deben utilizar abreviaturas o siglas en ninguno de los espacios del certificado.
                  li 
                    | El certificado de nacido vivo debe ser diligenciado por el médico o la enfermera que asistió el parto; en las áreas del país en donde no exista este recurso humano, las auxiliares de enfermería y las promotoras de salud están autorizadas para diligenciarlo. En el evento en que el parto haya sido asistido por partera, ella deberá informar a la promotora de salud del área, o auxiliar de enfermería para que ésta avale la información y diligencie el respectivo certificado. 
          div(x="64.8%" y="51.9%" tooltip="tooltip de max 35 caracteres" numero="6")
            .row.align-items-center
              .col-lg-1.BG04.p-2.mb-4
                h1.text-white.text-center.mb-1 6
              .col-lg-12
                ol.lista-img02.px-4
                  li 
                    | La firma del profesional que diligencia el certificado garantiza la validez del documento.

    p.mb-5 Se explica cada ítem uno a continuación: el certificado de nacido vivo como antecedente para registro civil se estructura de la siguiente manera: 
    ol.lista-img03.px-4.mb-5
      li 
        h3 Información general
                        
    .row.mb-5
      .col-lg-6.mb-4
        h5.mb-3 En este recurso se indican las pautas al momento de diligenciar los formatos.
        LineaTiempoD.color-secundario
          p.text-small(numero="1" titulo="Lugar de nacimiento") Se debe diligenciar el departamento y municipio. Para el caso de distritos capitales, equivale un solo nombre en los dos ítems, ejemplo Distrito Capital de Bogotá.
          p.text-small(numero="2" titulo="Área del nacimiento") Seleccionar con una X: cabecera municipal, o  centro poblado: inspección, corregimiento o caserío o rural disperso.
          p.text-small(numero="3" titulo="Fecha del nacimiento") Registrar en números arábigos año, mes y día.
          p.text-small(numero="4" titulo="Hora del nacimiento") Anotar hora y minutos en formato de hora militar. En caso de no tener seguridad de la hora exacta de nacimiento, debe diligenciarse una X en el cuadro correspondiente a sin establecer.
          p.text-small(numero="5" titulo="Sexo del nacido vivo") De acuerdo con el examen clínico integral registrar con una X: masculino, femenino o  indeterminado.
      .col-lg-6
        img(src='@/assets/curso/tema2/img15.png')
      .col-lg-6
        img(src='@/assets/curso/tema2/img16.png')
      .col-lg-6
        LineaTiempoD.color-secundario
          p.text-small(numero="6" titulo="Hemoclasificación del nacido vivo") Registrar en letra de imprenta, clara y legible, sin borrones ni enmiendas el grupo sanguíneo y factor Rh.
          p.text-small(numero="7" titulo="Del nombre") Diligenciar primer apellido, segundo apellido, primer nombre, y segundo nombre de la madre (verificar la información en el documento de identidad), en caso de no tener segundo apellido o segundo nombre, dejar el espacio sin diligenciar.
          p.text-small(numero="8" titulo="Tipo de documento de identificación de la madre") Seleccionar con una X solo uno de los siguientes: Registro Civil, o Tarjeta de Identidad, o Cédula de Ciudadanía, o sin información, o Cédula de Extranjería, Pasaporte u otro: definiendo por escrito específicamente ¿cuál? y el número de identificación de la madre (tal como figura en el documento de identidad).
          p.text-small(numero="9" titulo="TDe acuerdo con la cultura") Pueblo o rasgos físicos, el nacido vivo es reconocido por sus padres como: seleccionar solo uno de los nominados con una X. Solo en caso de que sea seleccionado el numeral. 
          p.text-small(numero="10" titulo="Indígena") Se debe describir en la línea a cuál pueblo indígena pertenece. 

    p.mb-4 Por medio de este recurso se podrán descubrir los diferentes puntos que se deben llenar en el formato de recién nacido vivo.

    .row.BG03.mb-5.p-4
      .col-lg-3.col-md-6.col-6
        img(src='@/assets/curso/tema2/img17.png')
        .row.justify-content-center
          .col-5.p-2          
            a.boton.BG06.texto-blanco(href="https://drive.google.com/file/d/1xHw--OzxCM80Fla-EmrCtzVnh-YhKYw5/view?usp=sharing" target="_blank")
              span Descargar
              i.fas.fa-file-download
      .col-lg-9.col-md-6.col-6
        img(src='@/assets/curso/tema2/img18.png')
        img(src='@/assets/curso/tema2/img19.png')

    ol.lista-img03.px-4.mb-5
      li 
        h3 Datos del nacimiento
    p.mb-5 Siguiendo con la temática relacionada con los certificados y la estructura de los registros, se invita a conocer cómo diligenciar los datos del nacimiento.

    .row.justify-content-center
      .col-lg-10
        SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img20.svg') 
                h4.text-center.mt-4 Área del nacimiento
                p.text-center.px-4 Marcar con una equis (X) en la casilla correspondiente, el área donde ocurrió el nacimiento.
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img21.svg')
                h4.text-center.pt-4 Sitio del parto 
                p.text-center.px-4 Marque con una equis (X), el sitio donde ocurrió el nacimiento, especificando el lugar de ocurrencia (automóvil, avión, etc.).
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img22.svg')
                h4.text-center.pt-4 Nombre de la institución de salud 
                p.text-center.px-4 Si en la pregunta 4 (sitio del parto) se seleccionó institución de salud, registre el nombre del organismo de salud o IPS  y el código correspondiente.
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img23.svg')
                h4.text-center.pt-4 Sexo del nacido vivo
                p.text-center.px-4 De acuerdo al examen clínico integral registrar con una X: masculino, femenino o  indeterminado.
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img24.svg')
                h4.text-center.pt-4 Peso del nacido vivo, al nacer
                p.text-center.px-4 De acuerdo al examen clínico integral y registro en el historial clínico, anotar en las respectivas casillas el peso en gramos, mediante dígitos arábigos. 
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img25.svg')
                h4.text-center.pt-4 Talla del nacido vivo, al nacer 
                p.text-center.px-4 De acuerdo al examen clínico integral y registro en el historial clínico, anotar en las respectivas casillas la talla en centímetros, mediante dígitos arábigos. 
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img26.svg')
                h4.text-center.pt-4 Fecha del nacimiento 
                p.text-center.px-4 Anote, en números arábigos, el año, mes y día en que ocurrió el nacimiento.
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img27.svg')
                h4.text-center.pt-4 Hora del nacimiento
                p.text-center.px-4 Registre la hora y minutos del nacimiento en formato de hora militar. La casilla «Sin establecer» se diligencia únicamente en aquellos casos en los que el parto no sea atendido por personal de salud.
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img28.svg')
                h4.text-center.pt-4 El parto fue atendido por 
                p.mb-0.text-center.px-4 Seleccione el tipo de personal de salud que atendió el parto.
                p.text-center.px-4 Si se trata de otra persona diferente a personal de salud, especifique quién atendió el parto. (policía, azafata, familiar, etc.).
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img29.svg')
                h4.text-center.pt-4.px-1 Tiempo de gestación del nacido vivo 
                p.text-center.px-2 Escriba en números arábigos el número de semanas completas de gestación verificadas. La casilla «Ignorado» solo debe ser diligenciada cuando se desconozca o no sea posible determinar el tiempo de gestación.
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img30.svg')
                h4.text-center.pt-4 Número de consultas prenatales que tuvo la madre del recién nacido vivo 
                p.text-center.px-2 Escriba en números arábigos el número de consultas que tuvo la madre del recién nacido. Esta información puede transcribirse del historial clínico o carnet CLAP diligenciado.
          .tarjeta.BG05
            .row.justify-content-center.mb-2
              .col-12
                img(src='@/assets/curso/tema2/img31.svg')
                h4.text-center.pt-3.px-2 Tipo de parto de este nacimiento  
                p.mb-0.ps-2.pe-2 Seleccione y registre con una X en el cuadro correspondiente el tipo de parto del actual nacimiento: 
                ol.lista-ol.px-3
                  li.mb-0
                    span.text-bold 1. 
                    | Espontáneo.
                  li.mb-0 
                    span.text-bold 2. 
                    | Cesárea.
                  li.mb-0 
                    span.text-bold 3. 
                    | Instrumentado.
                  li.mb-0 
                    span.text-bold 4. 
                    | Ignorado.
          .tarjeta.BG05
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema2/img32.svg')
                h4.text-center.pt-4 Multiplicidad del embarazo  
                p.text-center.px-4.pt-2 Se diligenciará solo si el recién nacido es producto de un embarazo simple, doble, triple, cuádruple o más.
        
    p.mb-5 APGAR del nacido vivo al nacer: la puntuación de escala Apgar, es una herramienta para validar el estado del neonato y su respuesta a la adaptación, se realiza al minuto y a los cinco minutos del nacimiento, clasificando al neonato según los siguientes parámetros: 

    .row.align-items-center.mb-5
      .col-lg-8.col-md-6.col-10
        img(src='@/assets/curso/tema2/img33.png')
      .col-lg-4.col-md-6.col-10.p-0
        .BG06.p-5
          p.mb-0 Hemoclasificación del recién nacido vivo: anotar el grupo sanguíneo y el factor Rh del neonato.
          p De acuerdo con la cultura, pueblo o rasgos físicos, el nacido vivo es reconocido por sus padres.Se debe preguntar y anotar cómo consideran los padres al recién nacido, de acuerdo a la pertenencia cultural, no a los rasgos físicos o al color de la piel. Seleccionar solo un enunciado, en caso seleccionar la opción uno, complementar la respuesta con el registro de a cuál pueblo indígena pertenece.
    
    .row.BG01.align-items-center.justify-content-center.p-4.ms-2
      .col-lg-2.col-md-2.col-1
        img.w-75(src='@/assets/curso/tema1/img11.png')
      .col-lg-8.col-md-8.col-8
        h5.text-white Luego de ver los diferentes formatos, se invita a explorar el siguiente enlace para reforzar lo aprendido.
        p.text-white Enlace para diligenciamiento de nacido vivo:
      .col-sm-auto.mt-4
        a.boton.color-acento-botones.texto-blanco(href="https://nd.ruaf.gov.co/WebSiteNDE/BirthsPages/CertificadoNacimiento.aspx" target="_blank")
          span Descargar
          i.fas.fa-file-download

    .row.justify-content-center
      .col-lg-10
        p.my-5 Teniendo en cuenta que se ha venido trabajando sobre la estructura de los formatos, se sugiere explorar la siguiente información en donde se podrá aprender el diligenciamiento del certificado de defunción. 
        .row.justify-content-start.align-items-center     
          .col-9.mb-4
            .bloque-texto.color.BG06.p-4
              h5.ps-4 Estructura de los formatos de certificado de defunción.
              p.ps-4.pe-5 El Registro de Defunción es el documento que certifica legalmente el fallecimiento de una persona.  Este  registro inscribe las defunciones que ocurran en territorio nacional, las defunciones de colombianos por nacimiento o adopción, y las de extranjeros residentes en el país, así como las  ocurridas fuera de este, y adicional las sentencias judiciales ejecutoriadas que declaren la presunta muerte por desaparecimiento.
          .col-3.mb-4
            figure
              img.mx-4.img-fluid(src='@/assets/curso/tema2/img34.svg')
        .row.justify-content-end.align-items-center     
          .col-4.mb-4
            figure
              img(src='@/assets/curso/tema2/img35.svg' style= 'height: 184px')
          .col-8.mb-4
            .bloque-texto.color.BG06.p-2.pb-2
              p.pt-4.ps-2 Para el proceso de inscripción de una muerte natural, se realiza en la Oficina de Registro del Estado Civil de la ciudad o lugar donde ocurrió la muerte o se encontró el cadáver, legalmente dentro de los dos días siguientes al momento en que se tuvo noticia del hecho.
        .row.justify-content-start.align-items-center     
          .col-9.mb-4
            .bloque-texto.color.BG06.p-4
              p.px-4 Para la inscripción y registro de una muerte natural que no ha sido denunciada dentro del término establecido por ley de dos días, se realiza mediante orden escrita del Inspector de Policía del lugar de ocurrencia, quien debe investigar las causas del retardo en la inscripción y sancionar a los responsables de esta omisión si hubiere lugar a ello.
          .col-3.mb-4
            figure
              img.img-fluid(src='@/assets/curso/tema2/img36.svg' style= 'height: 164px')
        
    .bg_img48_t2.mb-5
      .row.justify-content-center.align-items-center.mt-4
        .col-lg-6.mb-4.mt-5
          p Para el proceso de registro de defunción, la persona que solicita el registro debe presentar su documento de identificación, además de mínimo una prueba del hecho. En caso de que el fallecimiento se produzca por muerte natural, se puede acreditar con certificado expedido por el médico tratante o quien atendió a la persona fallecida en su última enfermedad o por un médico forense.
          p Si no existe ninguno de estos dos conceptos, se puede certificar la muerte por parte de un médico de sanidad o en último caso cualquier médico que desempeñe un cargo oficial relacionado con su profesión en el lugar o sitio de ocurrencia o un profesional médico. Solo en caso de no existir médicos en la localidad, se podrá definir el fallecimiento mediante declaración de dos testigos, que se debe presentar dentro de los dos días hábiles siguientes al fallecimiento.
        .col-lg-5.mb-5.mt-5
          figure
            img.ms-5(src='@/assets/curso/tema2/img38.png' style= "width: 445px")
        .col-lg-6
          figure
            img.ms-5(src='@/assets/curso/tema2/img39.png' style= "width: 545px")
        .col-lg-6
          ol.lista-img03.px-4.mb-4
            li 
              h4 Legalmente, la inscripción de una muerte para el registro civil, la puede solicitar: 
          ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta
                  span a
              | La o el cónyuge sobreviviente, o los parientes más próximos del occiso.
            li 
              .lista-ol--cuadro__vineta
                  span b 
              | Las personas que habiten en la casa en que ocurrió́ el fallecimiento.
            li 
              .lista-ol--cuadro__vineta
                  span c
              | El profesional tratante médico que haya asistido al fallecido en su última enfermedad.
            li 
              .lista-ol--cuadro__vineta
                  span d
              | El servicio funerario que atiende la sepultura del fallecido. 
            li 
              .lista-ol--cuadro__vineta
                  span e 
              | En caso de presentarse la defunción en estado de acuartelamiento, o en un convento, hospital, clínica, asilo, cárcel o establecimiento carcelario público o privado, el deber de denunciar también compromete al director o administrador del establecimiento. 
            li 
              .lista-ol--cuadro__vineta
                  span f 
              | En el evento de encontrarse un cadáver de persona desconocida o que no sea reclamado, es deber de la autoridad policial el realizar el denuncio correspondiente. 
            li 
              .lista-ol--cuadro__vineta
                  span g
              | Las personas que tengan interés en denunciar el fallecimiento de cualquier persona, lo puede hacer, siempre y cuando presenten los documentos que soportan de manera pertinentes el caso.

    .BG06
      SlyderA
        .row.justify-content-center.align-items-center.mb-5  
          .col-lg-2
            img(src='@/assets/curso/tema2/img40.svg')
          .col-lg-8
            p Las Instituciones Prestadoras de Servicios de Salud IPS que conocieron del fallecimiento, en caso de pérdida del certificado de defunción para el Registro Civil, si son requeridos, deben expedir una constancia del mismo con base en la historia clínica del paciente fallecido; en esta certificación o constancia, se debe escribir textualmente el nombre e identificación del fallecido como aparece en el documento de identificación, así como el número del certificado de defunción expedido.
        .row.justify-content-center.align-items-center.mb-5 
          .col-lg-8
            p Como requerimiento legal el certificado de defunción instituye documento antecedente para la inscripción en el registro civil de defunción, únicamente cuando es firmado por médico con tarjeta profesional reconocida y expedida en Colombia. Los certificados de defunción diligenciados y firmados por un o una profesional en enfermería con licencia o una enfermera auxiliar o cualquier otro personal de salud, no pueden ser aceptados como documento antecedente para inscribir la defunción en el Registro Civil.
          .col-lg-2
            img(src='@/assets/curso/tema2/img41.svg')
        .row.justify-content-center.align-items-center.mb-5  
          .col-lg-2
            img(src='@/assets/curso/tema2/img42.svg')
          .col-lg-8
            p.mb-0 La inscripción en el registro de defunción de una muerte violenta, solo puede ser realizada por orden o autorización judicial, por lo cual no tiene término legal para su inscripción.
            p En este evento, una persona diferente a la autoridad que está investigando una muerte violenta, puede solicitar la inscripción en el registro de defunción de esta muerte violenta, solo si presenta la copia auténtica del acta de levantamiento del cadáver.
        .row.justify-content-center.align-items-center.mb-5 
          .col-lg-8
            p Así mismo, las sentencias ejecutoriadas que declaren la muerte presunta por desaparecimiento, deben tramitarse en el registro de defunción consignando en este los datos que la sentencia legal defina. Las defunciones de colombianos por nacimiento o por adopción, y las de extranjeros residentes en el país, ocurridas fuera de este, cuando así́ lo solicite el interesado que acredite el hecho, se deben registrar en el competente consulado colombiano o en una de las notarías o registradurías de la ciudad de Bogotá D. C.
          .col-lg-2
            img(src='@/assets/curso/tema2/img43.svg')
        .row.justify-content-center.align-items-center.mb-5  
          .col-lg-2
            img.pt-4(src='@/assets/curso/tema2/img44.svg')
          .col-lg-8
            p El formato de registro de certificado de defunción consta de dos componentes principales, cuyos objetivos son diferentes: 
            ol.lista-img04.px-4
              li 
                | El certificado de defunción como antecedente y requisito para la inscripción al registro civil.
              li 
                | Certificado de defunción como registro de información sobre la mortalidad en estadísticas vitales.
  
    .bg_img49_t2
      .row.justify-content-center.align-items-center.mt-5
        .col-lg-6.mb-4
          ol.lista-img03.px-4
            li 
              h4 Recomendaciones e instrucciones generales
          p.mt-4 Para el diligenciamiento del certificado de defunción, es importante tener en cuenta las siguientes recomendaciones:
          ol.lista-img01.px-4
            li 
              p.mb-3 Legalmente el certificado de defunción y antecedente para el registro civil, es requisito para la inscripción en el registro civil y para el trámite de la expedición de la licencia de inhumación.
            li
              p.mb-3 Los datos que se registran en el formulario, solicitados por el DANE, son estrictamente confidenciales, y están protegidos bajo reserva estadística por la Ley 79 de 1993, Artículo 5°.
            li 
              p.mb-3 La firma del profesional que diligencia  el certificado garantiza la validez del documento.
            li
              p.mb-3 Se recomienda diligenciar el certificado con letra de imprenta, clara y legible, sin borrones ni enmendaduras.
            li 
              p.mb-3 Solo se debe marcar con una equis (x) la opción seleccionada para cada pregunta.
            li
              p.mb-3 Antes de realizar el registro, se deben revisar las fuentes de información y realizar las indagaciones necesarias para adquirir la información completa y veraz, pues la calidad del dato es importantes para el Sistema Nacional de Registro Civil.
        .col-lg-6
          figure
            img.me-5(src='@/assets/curso/tema2/img46.png' style= "width: 623px")
        .col-lg-6.mb-5
          figure
            img.ms-4(src='@/assets/curso/tema2/img47.png' style= "width: 595px")
        .col-lg-6.mb-5
          ol.lista-img01.px-4
            li 
              p.mb-3 Se debe verificar antes de escribir todos los datos personales solicitados, tales como nombres completos, lugar donde ocurrió la defunción,  edad y  número de identificación del fallecido, y que estos datos correspondan fielmente a los documento de identificación. Estos datos deben ser convalidados; esto con el fin de evitar errores en el trámite, y contratiempos en la notaría o registraduría.
            li
              p.mb-3 El certificado debe ser llenado en su totalidad, no se deben dejar espacios en blanco, de lo contrario la Oficina de Registro Civil no lo acepta como válido, igualmente esto evita posibles fraudes y disminuye el subregistro de información.
            li 
              p.mb-3 Cuando un formato de certificado se invalide por borrones, enmendaduras o mal diligenciamiento, este debe ser anulado y no destruido. Este formulario anulado, debe ser remitido posteriormente a la Dirección seccional o local de salud.
            li
              p.mb-3 El certificado se haya numerado de manera individual, única y secuencial; por tal razón, no se  aceptan certificados diligenciados en fotocopias. Esta numeración individual, garantiza la calidad, brinda confiabilidad y evita la presencia de duplicidades.
            li 
              p.mb-5 No se deben utilizar abreviaturas o siglas en ninguno de los espacios del certificado.  

    p.mb-4 El formato de registro de certificado de defunción, consta de dos componentes principales, cuyos objetivos son diferentes. El certificado de defunción como antecedente y requisito para la inscripción en el registro civil y el certificado de defunción como registro de información sobre la mortalidad en estadísticas vitales.       
    p.mb-4 Ahora, se explicará cada uno: el certificado de defunción como antecedente y requisito para la inscripción al registro civil, se estructura de la siguiente manera: 
    ol.lista-img03.px-4.mb-4
          li 
            h4 Certificado de defunción como registro de información sobre la mortalidad en estadísticas vitales.
    p.mb-4 El contenido del formato del certificado de defunción está dividido en seis partes, por lo tanto le invitamos a explorar el siguiente recurso, donde encontrará cómo se diligencia y que partes lo construyen:

    .tarjeta-color.BGIMG02.p-4.mb-5
      SlyderA(indicadores="derecha")
        .row.justifiy-content-center.align-items-center 
          .col-md-5.mb-4.mb-md-0
            figure.flex-center
             img(src='@/assets/curso/tema2/img50.png', alt='Texto que describa la imagen')
             a.boton.color-acento-botones.mt-5(href="https://drive.google.com/file/d/10wDNGKNxDEkP0OP5N5PBdwcZSVmTIOS2/view?usp=sharing" target="_blank")
              span Descargar
              i.fas.fa-file-download       
          .col-md-7
            figure
              img.mb-5(src='@/assets/curso/tema2/img51.png', alt='Texto que describa la imagen')

        .row.justifiy-content-center.align-items-center 
          .col-md-5.mb-4.mb-md-0
            figure.flex-center
             img(src='@/assets/curso/tema2/img52.png', alt='Texto que describa la imagen')
             a.boton.color-acento-botones.mt-5(href="https://drive.google.com/file/d/10wDNGKNxDEkP0OP5N5PBdwcZSVmTIOS2/view?usp=sharing" target="_blank")
              span Descargar
              i.fas.fa-file-download       
          .col-md-7
            figure
              img.mb-5(src='@/assets/curso/tema2/img53.png', alt='Texto que describa la imagen')
        
        .row.justifiy-content-center.align-items-center 
          .col-md-5.mb-4.mb-md-0
            figure.flex-center
             img(src='@/assets/curso/tema2/img54.png', alt='Texto que describa la imagen')
             a.boton.color-acento-botones.mt-5(href="https://drive.google.com/file/d/10wDNGKNxDEkP0OP5N5PBdwcZSVmTIOS2/view?usp=sharing" target="_blank")
              span Descargar
              i.fas.fa-file-download       
          .col-md-7
            figure
              img.mb-5(src='@/assets/curso/tema2/img55.png', alt='Texto que describa la imagen') 
        .row.justifiy-content-center.align-items-center 
          .col-md-5.mb-4.mb-md-0
            figure.flex-center
             img(src='@/assets/curso/tema2/img54.png', alt='Texto que describa la imagen')
             a.boton.color-acento-botones.mt-5(href="https://drive.google.com/file/d/10wDNGKNxDEkP0OP5N5PBdwcZSVmTIOS2/view?usp=sharing" target="_blank")
              span Descargar
              i.fas.fa-file-download       
          .col-md-7
            figure
              img.mb-5(src='@/assets/curso/tema2/img56.png', alt='Texto que describa la imagen') 
        .row.justifiy-content-center.align-items-center 
          .col-md-5.mb-4.mb-md-0
            figure.flex-center
             img(src='@/assets/curso/tema2/img54.png', alt='Texto que describa la imagen')
             a.boton.color-acento-botones.mt-5(href="https://drive.google.com/file/d/10wDNGKNxDEkP0OP5N5PBdwcZSVmTIOS2/view?usp=sharing" target="_blank")
              span Descargar
              i.fas.fa-file-download       
          .col-md-7
            figure
              img.mb-5(src='@/assets/curso/tema2/img57.png', alt='Texto que describa la imagen')        
        .row.justifiy-content-center.align-items-center 
          .col-md-5.mb-4.mb-md-0
            figure.flex-center
             img(src='@/assets/curso/tema2/img58.png', alt='Texto que describa la imagen')
             a.boton.color-acento-botones.mt-5(href="https://drive.google.com/file/d/10wDNGKNxDEkP0OP5N5PBdwcZSVmTIOS2/view?usp=sharing" target="_blank")
              span Descargar
              i.fas.fa-file-download       
          .col-md-7
            figure
              img.mb-5(src='@/assets/curso/tema2/img59.png', alt='Texto que describa la imagen')
        .row.justifiy-content-center.align-items-center 
          .col-md-5.mb-4.mb-md-0
            figure.flex-center
             img(src='@/assets/curso/tema2/img58.png', alt='Texto que describa la imagen')
             a.boton.color-acento-botones.mt-5(href="https://drive.google.com/file/d/10wDNGKNxDEkP0OP5N5PBdwcZSVmTIOS2/view?usp=sharing" target="_blank")
              span Descargar
              i.fas.fa-file-download       
          .col-md-7
            figure
              img.mb-5(src='@/assets/curso/tema2/img60.png', alt='Texto que describa la imagen')

    p.mb-4 Por medio del siguiente recurso se podrá visualizar y ver la funcionabilidad del certificado de defunción como un registro de información sobre la mortalidad en estadísticas vitales. Luego de terminar de explorar este recurso se invita a seguir conociendo más del proceso para certificar una defunción. 

    .tarjeta.BGIMG05.p-5.mb-5
      PasosB.color-acento-contenido
        .row.justify-content-around.align-items-center
          .col-md-7.mb-4.mb-md-0
            ol.lista-img01.px-4.ms-3
              li 
                p.mb-3 <b>Número de certificado de defunción:</b> el certificado se enumera de manera individual, única y secuencial; para efecto de garantizar la calidad, brindar confiabilidad y evitar duplicidades, por tal razón, no se  aceptan certificados diligenciados en fotocopias.
              li
                p.mb-3 <b>Lugar donde ocurrió la defunción:</b> se debe diligenciar el departamento y municipio. Para el caso de distritos capitales, equivale un solo nombre en los dos ítems, ejemplo Distrito Capital de Bogotá.
              li 
                p.mb-3 <b>Área donde ocurrió la defunción:</b> seleccionar cabecera municipal, o  centro poblado. En caso de ser centro poblado, definir inspección, corregimiento o caserío o rural disperso.
              li
                p.mb-3 <b>Sitio donde ocurrió la Defunción:</b> Definir el sitio exacto de la defunción.
              li 
                p.mb-3 <b>Nombre de la Institución de Salud donde ocurrió la Defunción y Código de la IPS:</b> Recordar este espacio debe ser llenado en letra de imprenta, clara y legible, sin borrones ni enmiendas y la codificación para la IPS en números arábigos.
          .col-md-5
            figure
              img.pe-5.mb-5.pb-3(src='@/assets/curso/tema2/img61.png')
        .row.justify-content-around.align-items-center
          .col-md-5
            figure
              img.ps-5.mb-5(src='@/assets/curso/tema2/img62.png')
          .col-md-6.mb-4.mb-md-0
            ol.lista-img01.px-4.ms-3
              li 
                p.mb-3 <b>Fecha en que ocurrió la defunción:</b> Diligencie en números arábigos dentro de las respectivas casillas.
              li
                p.mb-3 <b>Hora en que ocurrió la defunción:</b> Registre hora y minutos del nacimiento en formato de hora militar. El numeral ¨Sin establecer¨ únicamente es aceptada en casos de muertes violentas o muertes fetales, en las cuales no se puede determinar la hora de fallecimiento.
              li 
                p.mb-3 <b>Sexo del fallecido:</b> Diligencia la casilla correspondiente al examen e inspección. La casilla «Indeterminado» debe ser utilizada unicamente para los casos en que, por el estado del cadáver, no es posible determinarlo.
              li
                p.mb-3 <b>Apellido(s) y Nombre(s) del fallecido(a),</b> diligenciar Primer Apellido, Segundo Apellido, Primer Nombre, Segundo Nombre. En caso de no tener segundo apellido o segundo nombre, dejar el espacio sin diligenciar. Validar el documento de Identidad. 
        .row.justify-content-around.align-items-center
          .col-md-7.mb-4.mb-md-0
            ol.lista-img01.px-4.ms-3
              li 
                p.mb-3 <b>Número de identificación del fallecido</b> (tal como figura en el documento de identidad), diligenciar en números arábigos.
              li
                p.mb-3 <b>Fecha de nacimiento del fallecido:</b>  Diligenciar en números arábigos, de acuerdo al registro en los documentos.
              li 
                p.mb-3 <b>Estado conyugal del fallecido:</b> Seleccione con una X, sólo  uno de los estados enunciados.
              li
                p.mb-3 <b>Edad del fallecido:</b> Seleccione con una X, uno de los siguientes rangos de edad, y frente a la edad registre con exactitud la edad en números arábigos, de acuerdo a los criterios establecidos por rango de edad:
                ol.lista-img63.lh-2.ms-5
                  li 
                    | Menor de una hora (en minutos) (00-59).
                  li 
                    | Menor de un día (en horas) (01-23).
                  li 
                    | Menor de un mes (en días) (01-29).
                  li 
                    | Menor de un año (en meses) (01-11).
                  li 
                    | De un año o más (en años cumplidos).
                  li 
                    | Edad: _____
          .col-md-5
            figure
              img.pe-5.mb-5.pb-3(src='@/assets/curso/tema2/img61.png')
        .row.justify-content-around.align-items-center
          .col-md-5
            figure
              img.ps-5.mb-4.px-4(src='@/assets/curso/tema2/img62.png')
          .col-md-7.mb-4.mb-md-0
            ol.lista-img01.px-4.ms-3
              li 
                p.mb-3 <b>Último año de estudios aprobado por el fallecido:</b> seleccione con una X, el enunciado que corresponda a el mayor de los estudios aprobados por el fallecido, y describa en números arábigos, el Último año o grado aprobado en las casillas correspondientes.
              li
                p.mb-3 <b>La ocupación pudo ser causa o estar asociada con la defunción:</b> seleccione con una X uno de los enunciados. Debe tener en cuenta las definiciones establecidas para accidente de trabajo y enfermedad profesional. Registre de manera adicional el último trabajo habitual del fallecido.
              li 
                p.mb-3 <b>Seleccionar uno de los enunciados a la pregunta:</b> de acuerdo con la cultura, pueblo o rasgos físicos, el fallecido como se reconocía. En caso de seleccionar el enunciado numerado 1. Indígena, definir a cuál pueblo indígena pertenece.
              li
                p.mb-3 <b>Lugar de residencia habitual del fallecido:</b> describir país, departamento, y municipio. Recordar que  para muerte fetal o de menor de un año, se debe escribir el lugar de residencia habitual de la madre. Los espacios deben ser diligenciados en letra de imprenta, clara y legible, sin borrones ni enmiendas.
              li
                p.mb-3 <b>Área de residencia habitual del fallecido:</b> para muerte fetal o de menor de un año, se debe escribir el área de residencia habitual de la madre. 
        .row.justify-content-around.align-items-center
          .col-md-7.mb-4.mb-md-0
            ol.lista-img01.px-4.ms-3
              li 
                p.mb-3 <b>Régimen de seguridad social en salud del fallecido:</b> para la muerte fetal o de menor de un año, se debe seleccionar el régimen de seguridad social de la madre. Seleccione y marque con una equis (X) en la casilla correspondiente.
              li
                p.mb-3 <b>Entidad administradora en salud a la que perteneció el fallecido:</b> seleccione el tipo de administradora y escriba el nombre de esta, según el régimen de seguridad social en salud. Para muerte fetal o de menor de un año, seleccione la entidad administradora a la que pertenece la madre. 
              li 
                p.mb-3 <b>Probable manera de muerte:</b> de acuerdo con el análisis de información, especificar si la defunción fue natural o violenta. La casilla “en estudio”, solo se usa cuando en el momento de diligenciar el certificado, no se ha podido establecer la manera de muerte; esta casilla es para uso exclusivo de trámite en Medicina Legal.
              li
                p.mb-3 <b>Certificado de defunción expedido por:</b> seleccione el profesional de salud o personal de salud autorizado, o funcionario del registro civil, quien expide el certificado.
          .col-md-5
            figure
              img.pe-5.mb-5.mt-4(src='@/assets/curso/tema2/img61.png')
      
</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
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
