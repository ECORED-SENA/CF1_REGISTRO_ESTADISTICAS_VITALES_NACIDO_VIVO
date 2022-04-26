<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span.text-white 3
      h1 Certificación de causas de defunción
  
    p.mb-5 En este apartado se verán los procesos de certificación de defunción, de enmienda estadística y proceso tardío.

    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.1. Proceso de certificación de causas de defunción 

    p.mb-5 En el siguiente video se describen los procesos de certificación de causas de defunción necesarios para realizar los certificados correspondientes.
   
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    p.mb-4 Con el siguiente recurso se identifica el complemento del proceso de certificación de las causas de defunción.
  
    p.mb-4.text-center <b>Por tipo de defunción encontramos dos diferencias claras:</b> 

    .row.justify-content-center.mb-3
      .col-lg-10
        figure
          img(src='@/assets/curso/tema3/img03.svg')

    .row.justify-content-center.align-items-center
      .col-lg-6
        p.mb-4 Estas definiciones son de gran ayuda en el proceso de identificación de causalidad a relacionar, ya que en muchas oportunidades son registrados en las defunciones fetales diagnósticos de insuficiencia respiratoria y otras como enfermedad de membrana hialina, lo que indicaría que este producto si vivió, causando para este evento un error de registro y posterior necesidad de enmienda estadística. Las muertes también se caracterizan por el sitio de ocurrencia. En esta diferenciación tendremos las muertes institucionales y las extrainstitucionales.
        p La muertes Institucionales son muertes que ocurren en el interior de una institución prestadora de servicios de salud (hospital, clínica, centro o puesto de salud). Las muertes en domicilio - otro sitio: hace referencia a las muertes ocurridas extrainstitucionalmente. En el caso de las defunciones es relevante consignar en el certificado el lugar donde ocurre el fallecimiento, pues esta información permite realizar una adecuada clasificación de la defunción y análisis estadístico por el DANE y componentes epidemiológicos. 
      .col-lg-6.mb-5
        figure
          img.px-2.mb-5(src='@/assets/curso/tema3/img04.png')

    p.mb-4.text-center <b>De acuerdo con la probable manera de muerte, se establece diferencia como:</b> 

    .row.mb-5.justify-content-center.align-items-center
      .col-lg-4
        .tarjeta-avatar
          img(src='@/assets/curso/tema3/img05.svg' alt='AvatarTop')
          .tarjeta-color.BG06
            .p-4
              p.my-5.px-2.pt-4 <b>Natural:</b> corresponden a aquellas situaciones biológicas o estados morbosos que conducen a la muerte, y no por causas incidentales o accidentales.
      .col-lg-4
        .tarjeta-avatar
          img(src='@/assets/curso/tema3/img06.svg' alt='AvatarTop')
          .tarjeta-color.BG06 
            .p-4
              p.mt-5.mb-0.px-2.pt-4 <b>No natural:</b> son esas circunstancias externas que incidentalmente o accidentalmente producen la muerte; por ejemplo, accidentes de transporte, caídas accidentales, lesiones autoinfligidas, ahogamientos, homicidios entre otras.

    .row.justify-content-center
      .col-lg-8
        .tarjeta-color.BG11 
          .p-4
            p.mt-3.px-2 <b>Estudio:</b> son las circunstancias que requieren investigaciones judiciales para poder determinar si se trata de una muerte natural o no natural. Este tipo de muerte solo es certificada por el Instituto Nacional de Medicina Legal y Ciencias Forenses, o por quien ellos autoricen o deleguen cuando en determinada jurisdicción no cuentan con unidades básicas de atención.

    Separador

    p.mb-4 <b>Certificado de defunción</b> Consta de dos partes: la primera es el certificado antecedente para el registro civil e insumo para la expedición de la licencia de inhumación; la segunda corresponde a información estadística que está dividida en cinco capítulos y 52 variables.

    .row.mb-5
      .col-lg-6.mb-4
        LineaTiempoD.color-secundario
          p.text-small(numero="1" titulo="Información general:") corresponde a las características propias de la defunción: dónde ocurre el hecho vital (departamento, municipio, área, institución de salud, sitio donde ocurrió la defunción, tipo de defunción, sexo del fallecido, nombres y apellidos, tipo y número de documento del fallecido, fecha de nacimiento del fallecido, estado conyugal, edad, nivel educativo, ocupación, pertenencia étnica, lugar y área de residencia, régimen de seguridad social y entidad administradora de plan de beneficios, la probable manera de muerte y quién expide el certificado de defunción). Esta información permite dar un contexto de caracterización de los fallecimientos, para posterior uso en estadísticas y políticas públicas.
          p.text-small(numero="2" titulo="Defunciones fetales o de menores de un año: ") si se seleccionó muerte fetal o el fallecido es menor de un año, se activa lo que corresponde a la relación de la muerte con el parto, tipo de parto, multiplicidad del embarazo, tiempo de gestación, peso al nacer, datos de la madre del feto o menor de un año, tipo y número de documento, edad de la madre, número de hijos nacidos vivos y nacidos muertos que ha tenido la madre, estado conyugal y nivel educativo de la madre.
          p.text-small(numero="3" titulo="Defunciones de mujeres en edad fértil: ") si el fallecido es de sexo femenino y está en el rango de edad de 10 a 54 años, se activa este capítulo que registra antecedentes obstétricos correspondientes a la información de si estaba embarazada al momento del fallecimiento, o si estuvo embarazada en las últimas seis semanas o en los últimos 12 meses.
          p.text-small(numero="4" titulo="Muertes violentas: ") este capítulo se activa cuando se han seleccionado las opciones de muerte violenta o en estudio en la pregunta probable manera de muerte. Este capítulo es exclusivo para el médico legista y consta de las variables probable manera de muerte, cómo ocurrió, lugar o dirección de la ocurrencia del hecho (proceso de migración de datos por consumo web).
          p.text-small(numero="5" titulo="Causas de defunción: ") este capítulo se activa para todas las defunciones. Consta de las variables de cómo determinó la causa de muerte, s se recibió asistencia médica durante el proceso que lo llevó a la muerte, causas de defunción que se dividen en dos partes, una correspondiente a la cadena causal; la segunda a otros estados patológicos que contribuyeron a la muerte, así como el tiempo aproximado entre el comienzo de cada causa y el deceso. Por último, la variable de causa probable de muerte cuando no es certificada por un médico sino por personal autorizado de salud (Decreto 1171 de 1997).
          p.text-small(numero="6" titulo="Datos de quien certifica la defunción: ") datos del profesional de la salud que está realizando la certificación del hecho vital, estos datos ya vienen precargados de acuerdo con los datos de generación del usuario en la IPS. La fecha y lugar de expedición ya viene diligenciada (departamento y municipio de la institución de salud) y la fecha actual cargada del sistema, que corresponde a la fecha en que se está ingresando el hecho vital a la plataforma.
      .col-lg-6
        img(src='@/assets/curso/tema3/img07.png')

    .bg_img11_t3
      .row.justify-content-center.align-items-center.mt-5
        .col-lg-6.mb-4
          p.mt-4 El procedimiento para certificar la defunción se resume en los siguientes pasos:
          ol.lista-img01.px-4
            li 
              p.mb-3 El profesional de salud o personal autorizado, diligencia el formulario registro en la web del certificado antecedente de defunción, se imprime y se entrega al familiar o personal autorizado. 
            li
              p.mb-3 En caso de presentarse eventos de contingencia certificada, puede diligenciarse el formato de registro impreso, sin embargo, se recomienda que el proceso sea siempre preferiblemente virtual. 
            li 
              p.mb-3 El certificado de antecedente impreso es requisito para que la familia o delegados por los servicios funerarios tramiten la licencia de traslado del cadáver, inhumación o cremación. Adicionalmente, este certificado antecedente de defunción, es el documento necesario para trámite ante la notaría o registraduría para el registro de defunción del ciudadano.
            li
              p.mb-3 El diligenciamiento de los registros de certificados de defunción y nacimiento, permite la consolidación de la información estadística sociodemográfica en el Sistema RUAF ND, que el DANE transforma y que nos permite cumplir con los compromisos adquiridos por el País de reportar indicadores en línea, como por ejemplo los indicadores relacionados con el cumplimiento de los Objetivos del Desarrollo Sostenible.
        .col-lg-6
          figure
            img.me-5(src='@/assets/curso/tema3/img08.png' style= "width: 590px")
        .col-lg-6.mb-5
          figure
            img.me-4(src='@/assets/curso/tema3/img09.png' style= "width: 583px")
        .col-lg-6.mb-5
          p.mb-4 La certificación de una defunción es un acto médico, legal y administrativo que:
          ol.lista-img01.px-4
            li 
              p.mb-3 Da constancia de la muerte de una persona.
            li
              p.mb-3 Cancela el documento de identidad del fallecido en el Registro Civil (censos electorales, sistema de salud).
            li 
              p.mb-3 Sirve de sustrato para el reconocimiento de derechos y deberes póstumos que atañen a los familiares del fallecido.
            li
              p.mb-3 Permite efectuar los procesos para la disposición final del cadáver (inhumación, cremación u otra disposición de los restos).El certificado se haya numerado de manera individual, única y secuencial; por tal razón, no se  aceptan certificados diligenciados en fotocopias. Esta numeración individual, garantiza la calidad, brinda confiabilidad y evita la presencia de duplicidades.
            li 
              p.mb-5 En términos estadísticos, provee la información básica para determinar el perfil de las causas de muerte de una comunidad.
        .col-lg-6.mb-4
          p.mt-4 Permite la caracterización de la mortalidad evitable (aspectos demográficos):
          ol.lista-img01.px-4
            li 
              p.mb-3 Disminuir la alta omisión en estas mortalidades (fetales-perinatales-infantiles).
            li
              p.mb-3 Orienta las acciones en salud pública para impactar la mortalidad evitable.
            li 
              p.mb-3 La desagregación Sub-nacional visibiliza los contextos departamentales y municipales donde ocurren estas muertes.
            li
              p.mb-3 Permite la comparación internacional de los indicadores Objetivos de Desarrollo Sostenible (indicadores de desarrollo mortalidad infantil).
            li 
              p.mb-3 Indica las causas principales por las cuales se presenta la mortalidad perinatal (defectos congénitos).
            li
              p.mb-5 Permite efectuar los procesos para la disposición final del cadáver (inhumación, cremación u otra).  
        .col-lg-6
          figure
            img.me-5.mb-5(src='@/assets/curso/tema3/img10.png' style= "width: 560px")

    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.2. Proceso de enmienda estadística

    p.mb-4 La enmienda estadística al mecanismo mediante el cual se realiza la corrección de los certificados de defunción que presentan fallas o inconsistencias en los certificados; y se utiliza únicamente con fines estadísticos
    p.mb-4 La información objeto de realiza la enmienda estadística, en el certificado de defunción respectivamente corresponde a: 

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-8.mb-4
        figure
            img.me-5.mb-5(src='@/assets/curso/tema3/img12.svg')

    p.mb-4 Dentro el proceso de registrar el certificado de defunción pueden ocurrir errores, déficit en la información y diversas inconsistencias que deben ser subsanadas mediante el proceso de enmienda estadística, más conocido como “Mecanismo de enmienda estadística” de la información y se puede realizar a nivel departamental, local y distrital. 
    p.mb-4 Es necesario aclarar que este mecanismo de enmienda es potestad de los comités de estadísticas vitales que son los encargados de todo el proceso estadístico y calidad del dato en los mismos. Además, es importante precisar que los cambios que se lleguen a realizar a los certificados de defunción, no van a repercutir o modificar el registro civil de defunción. 

    p.mb-4.text-center El proceso de enmienda estadística se desarrolla en dos niveles, a saber:

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-5.mb-4
        figure
            img.me-5.mb-5(src='@/assets/curso/tema3/img13.svg')
      .col-lg-5.mb-4
        figure
            img.me-5.mb-5(src='@/assets/curso/tema3/img14.svg')

    p.mb-4 Es importante aclarar el rol de cada uno de los actores que puede participar en el proceso de enmienda estadística: 

    .row.mb-1
      .col-lg-2.BG12.me-1
        p.p-3.pt-4.text-center <b>Médico tratante</b>
      .col-lg-9.BG13 
        p.pt-3 Médico que ha participado en el diagnóstico, tratamiento o rehabilitación y tiene conocimiento del proceso patológico que desencadenó y causó la muerte del paciente.
    .row.mb-1
      .col-lg-2.BG12.me-1
        p.p-3.pt-5.text-center <b>Médico no tratante</b>
      .col-lg-9.BG13 
        p.pt-3 Médico que no participó en el diagnóstico, tratamiento o rehabilitación y no tiene conocimiento directo del proceso patológico que desencadenó y causó la muerte del paciente, pero por responsabilidad institucional o social accede al conocimiento indirecto a través del Expediente Clínico, pruebas de laboratorio o interrogatorio a familiares o testigos o autopsia.
    .row.mb-1
      .col-lg-2.BG12.me-1
        p.p-3.pt-4.text-center <b>Médico Forense</b>
      .col-lg-9.BG13 
        p.pt-3 Médico que atiende la situación en todo caso de muerte violenta o para aclarar las causas de la muerte cuando no hay claridad en la muerte no violenta.
    .row.mb-1
      .col-lg-2.BG12.me-1
        p.p-3.pt-4.text-center <b>Personal de salud autorizado</b>
      .col-lg-9.BG13 
        p.pt-3 Son los profesionales de la salud no médicos, a quienes se les faculta a realizar esta función exclusivamente en caso de muerte no violenta donde no exista profesional médico en el área.

    p.py-5 En el módulo de nacimientos y defunciones (RUAF ND) dispuesto por el Ministerio de Salud y Protección Social, existen varios perfiles asignados a los diversos actores que hacen parte del proceso, de los cuales los siguientes están autorizados para solicitar y/o revisar la enmienda estadística:

    .row.mb-1
      .col-lg-2.BG14.me-1
        h3.pt-5.text-center.text-white <b>Actor</b>
      .col-lg-2.BG13.me-1 
        p.pt-3 Funcionario de estadísticas vitales de la IPS
      .col-lg-3.BG13.me-1 
        p.pt-3 Funcionario designado por las secretarías departamentales de salud
      .col-lg-2.BG13.me-1 
        p.pt-3 Funcionario del DANE
      .col-lg-2.BG13 
        p.pt-3 Funcionarios estadísticas vitales DANE
    .row.mb-1
      .col-lg-2.BG14.me-1
        h3.p-3.pt-4.text-center.text-white <b>Función</b>
      .col-lg-2.BG13.me-1 
        p.pt-3 Solicitar enmiendas
      .col-lg-3.BG13.me-1 
        p.pt-3 Solicitar enmiendas 
      .col-lg-2.BG13.me-1 
        p.pt-3 Solicitar y revisar enmiendas
      .col-lg-2.BG13 
        p.pt-3 Solicitar y revisar enmiendas

    .bg_img15_t3.pt-5
      p.mb-4.position-relative El proceso de enmienda estadística procura fortalecer el sistema de estadísticas vitales mediante el control de la papelería que tiene como objetivo minimizar y controlar los puntos críticos que provocan subregistro o fallas a la cobertura de los hechos vitales.  
    
      .row.justify-content-center.mb-4.position-relative
        .col-lg-8
          .tarjeta-color.BG15 
            .p-3
              h3.mt-3.px-2.text-white Para optimizar y garantizar la calidad del dato en el diligenciamiento de los certificados de nacido vivo y defunción, se establecen tres niveles básicos de control: 
      
      .row.justify-content-center
        .col-lg-6
          .tarjeta-avatar-b.mb-3
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema3/img16.svg' alt='AvatarTop')
            .tarjeta.tarjeta--azul
              .p-4
                h3 Primer Nivel
                p Las instituciones prestadoras de servicios de salud realizan la fase de precrítica del diligenciamiento de los certificados de nacido vivo y de defunción generados dentro de la institución. Este primer control busca garantizar el diligenciamiento completo y correcto de las variables, por medio de la identificación de errores y déficit de la información.
      .row.justify-content-center
        .col-lg-6
          .tarjeta-avatar-b.mb-3
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema3/img17.svg' alt='AvatarTop')
            .tarjeta.tarjeta--azul
              .p-4
                h3 Segundo Nivel
                p La Secretaría Departamental de Salud evalúa la información contenida en los certificados, a su vez selecciona los certificados de defunción y nacido vivo inconscientes, realizando aclaración de lo detectado. En caso que sea necesario, la SSD informa las inconsistencias al Comité de estadísticas vitales para que este ente solicite la enmienda estadística. Es responsabilidad exclusiva de ente territorial de salud, coordinado por la oficina de Vigilancia en Salud Publica.
      .row.justify-content-center
        .col-lg-6
          .tarjeta-avatar-b.mb-5
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema3/img18.svg' alt='AvatarTop')
            .tarjeta.tarjeta--azul
              .p-4
                h3 Tercer Nivel
                p Este nivel está conformado por el comité de estadísticas vitales, al cual se le comentan los casos que ameriten discusión antes de tomar otras medidas. Dentro de sus funciones principales está la de velar por el mejoramiento de la calidad en el diligenciamiento de los certificados de nacimiento y defunción; así mismo evaluar la cobertura de la certificación de los nacimientos y de las defunciones en Colombia.

      p.mb-4 ¿Cómo se da el proceso general de enmienda estadística?
      p.mb-4 Para conocer este proceso, es necesario tener claridad que el cargue de información y enmienda de la misma dependerá si la institución prestadora de salud cuenta o no con automatización de los registros. A continuación, se describen las principales diferencias entre el paso a paso que siguen las IPS con proceso automatizado y aquellas que no cuentan con el mismo. 
      
      .row.justify-content-center.mb-4
        .col-lg-12
          table
            tr.BG11
              td
                h2.text-center.m-0 Instituciones Prestadoras de Salud – IPS
          table
            tr.BG08
              td
                h3.text-center.m-0 Automatizadas
              td
                h3.text-center.m-0 No automatizadas
          table
            tr.BG16
              td.px-5.pt-1 <b>1.</b>	El prestador recopila el certificado de nacimiento vivo y defunción a través de la web después de que ha ocurrido el evento vital y antes de que se entregue el historial a los familiares del nacido vivo o fallecido.
              td.p-4 <b>1.</b>	Tramita el certificado estadístico de nacimiento o defunción, según sea el caso, posterior a la ocurrencia del hecho vital y antes de la entrega del certificado antecedente a los familiares del nacido vivo o del fallecido.
          table
            tr.BG17
              td.px-5.pt-1 <b>2.</b>	Realiza la precrítica antes de confirmar el registro, verificando la consistencia, integridad y vigencia de los datos en base a la información registrada en la historia clínica.
              td.p-4 <b>2.</b>	Realiza la precrítica, verifica la integridad, consistencia y validez antes de que el certificado estadístico organizado sea enviado a la DMS o Localidad del Distrito Capital.
          table
            tr.BG16
              td.px-5.pt-1 <b>3.</b>	Corrobora el registro antes de los 8 días posteriores a la entrada.
              td.p-4 <b>3.</b>	Remitir antes que se cumplan los 8 días de diligenciado el certificado de nacido vivo o defunción a la DMS o localidad del Distrito Capital. 
          table
            tr.BG17
              td.px-5.pt-1 <b>4.</b>	Efectúa los cambios necesarios a solicitud de la DMS (Dirección Territorial de Salud) o localidad del Distrito Capital dentro de los 30 días posteriores al registro.
              td.p-4 <b>4.</b>	Organiza el formato para actualización de datos del certificado de nacido vivo y defunción antes nombrada enmienda estadística. Esta acción solo se realiza por solicitud de la Dirección Municipal o Distrital de Salud.
          table
            tr.BG16
              td.px-5.pt-1 <b>5.</b>	Organiza el formato de actualización de los datos del certificado de nacimiento vivo o defunción, anteriormente denominado enmienda estadística, a solicitud expresa de la DTS o Localidad del Distrito Capital, para registros que tengan más de 30 días de ingreso.
              td.p-4 <b>5.</b> Remite el formulario para actualizar los datos del certificado de nacido vivo o de defunción completado dentro de los 8 días posteriores a la recepción de la solicitud por correo electrónico o fax a la dirección correspondiente.           
          table
            tr.BG17
              td.px-5.pt-1 <b>6.</b>	Remite el formulario de actualización de los datos del certificado de nacimiento o defunción cumplimentado, dentro de los 8 días siguientes a la recepción de la solicitud, a la dirección correspondiente por correo electrónico o fax.
              td.p-4 <b>6.</b>	Para los casos en que el antecedente para el registro de nacidos vivos o defunciones presente inconsistencias o datos incompletos, así como para los casos de pérdida de los mismos por miembros de la familia, las acciones que se deben realizar son aquellas contenidas en el Manual de Principios y Procedimientos.
          table
            tr.BG16
              td.px-5.pt-3 <b>7.</b>	Elabora un listado de los registros de nacidos vivos y defunciones utilizadas, canceladas y disponibles, en papelería y formatos de control de llenado, en soporte magnético, en forma semanal, posterior a esto remite de manera mensual el estado del consolidado a la DMS o localidad del Distrito Capital según los esquemas establecidos a tal efecto.
              td.p-4 <b>7.</b>	Organiza el listado de los certificados de nacido vivo y de defunciones utilizadas, canceladas y disponibles, en los formatos de control de papelería y llenadas en soporte magnético. Esta relación se realiza de manera semanal. Es enviado a la DMS o localidad del Distrito Capital en un consolidado mensual. 
          table
            tr.BG17
              td.px-5.pt-1 <b>8.</b>	Remite semanalmente los certificados de nacimiento o defunción cancelados al DMS o Distrital o localidad del Distrito Capital para verificar la cobertura.
              td.p-4 <b>8.</b>	Remite los certificados estadísticos completados que están cancelados semanalmente a la DMS o localidad del Distrito Capital.
          table
            tr.BG16
              td.px-5.pt-1 <b>9.</b>	Utiliza el esquema de procesos requeridos por la IPS. 
              td.p-4 <b>9.</b>	Utiliza el esquema de procesos requeridos por la IPS.

    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.3. Registro tardío

    .banfondo1_t3.pt-5.mb-5
      .row.justify-content-center.align-items-center(data-aos="zoom-in-up")
        .col-md-5.col-lg-5
          figure
            img.position02(src="@/assets/curso/tema3/img20.png")        
        .col-md-6.col-lg-6
          p.mb-4.ms-4 Se entiende como registro tardío, toda aquella información que se cargue con inoportunidad en el sistema dispuesto para la entrega de datos (RUAF ND); así todo hecho vital que sea reportado al DANE posterior a la fecha de cierre y divulgación de las cifras definitivas del respectivo año, se considera registro tardío.
          p.mb-4.ms-4 Algunas posibles causas del registro se deben a barreras administrativas, logísticas o geográficas, además algunas instituciones prestadoras de servicios de salud pueden tener dificultades de desplazamiento y conectividad en las zonas rurales. 

    p.mb-5.text-center <b>Proceso de organización para el registro tardío de nacidos vivos</b>

    .row.justify-content-center.mb-5
      .col-lg-8
        figure.mb-4
          img(src="@/assets/curso/tema3/img21.svg") 
        .tarjeta-color.BG18.me-5 
          .p-1
            p.mt-1.ms-3.mb-0 Fuente: anexo 2: “Proceso de registro tardío”

    p.mb-5.pb-5 Para la investigación y construcción de las series históricas en lo que corresponde a los nacimientos, se organiza la información teniendo presente los datos relacionados con lugar de ocurrencia y residencia. 

    .banfondo2_t3.pt-5.mb-5.mt-5
      .row.justify-content-center.align-items-center(data-aos="zoom-in-up")
        .col-md-6.col-lg-6.mb-4
          p.mb-4 <b>Ejemplo de estructura para presentar la información</b>
          ol.lista-ol.lh-2
            li 
              span.text-bold 1. 
              | Nacimientos por sexo, según departamento de ocurrencia y grupos de edad de la madre.
            li 
              span.text-bold 2. 
              | Nacimientos por sexo, según departamento de residencia y grupos de edad de la madre. 
        .col-md-5.col-lg-5
          figure
            img.position03(src="@/assets/curso/tema3/img23.png")        

    .row.justify-content-center.mb-5.pt-5
      .col-lg-10
        figure.mb-4
          img(src="@/assets/curso/tema3/img24.svg") 
    
    .banfondo3_t3.pt-5.mb-5
      .row.justify-content-center.align-items-center
        .col-md-5.col-lg-5
          figure
            img.ms-5.position04(src="@/assets/curso/tema3/img25.png")        
        .col-md-5.col-lg-5
          p.mb-4 <b>Ejemplo de estructura para presentar la información:</b>
          ol.lista-ol.lh-1.mb-4
            li 
              span.text-bold 1. 
              | Defunciones por grupos de edad y sexo, según departamento, municipio y residencia.
            li
              span.text-bold 2. 
              p.mb-4 Grupos por causas de defunción (lista de causas agrupadas 6/67 CIE – 10 de OPS) para cada año.

    .row.justify-content-center.mt-5.mb-5
      .col-lg-10
        .tarjeta-color.BG19 
          .p-4
            h4.mt-3.px-2.text-white <b>Nota:</b> según la fuente de información DANE, los datos de los registros de tardíos tanto para nacidos vivos como defunciones no son incorporados en los microdatos anonimizados de la serie histórica, ni en el sistema de consulta de REDATAM 

      



</template>

<script>
export default {
  name: 'Tema3',
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
