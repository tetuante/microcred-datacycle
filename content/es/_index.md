---
title: DataCycle
---

{{< blocks/cover  title="Gestión del Ciclo de Vida del Dato" image_anchor="top" height="full" filter="true" >}}

<p class="mt-2 mb-4 lead font-weight-bold" style="text-shadow: 2px 2px 4px rgba(0,0,0,0.5); font-size: 1.6rem;">
    De la ingesta a la IA: formación avanzada en arquitecturas modernas.
</p>


<div class="d-flex flex-column flex-md-row align-items-center justify-content-center mt-4 mb-5" style="gap: 25px;">
    <div class="d-flex align-items-center px-3 py-2 rounded" 
         style="background: rgba(255, 255, 255, 0.15); border: 1px solid rgba(255, 255, 255, 0.2); backdrop-filter: blur(10px); min-width: 180px;">
        <i class="fa-solid fa-graduation-cap fa-2x text-primary mr-3"></i>
        <div class="text-left">
            <div class="text-white font-weight-bold" style="line-height: 1; font-size: 1.1rem;">6 ECTS</div>
            <small class="text-white-50 text-uppercase font-weight-bold" style="font-size: 0.7rem; letter-spacing: 0.5px;">Microcredencial</small>
        </div>
    </div>
    <a class="btn btn-primary btn-lg shadow-lg d-flex align-items-center" 
       href="https://informatica.ucm.es/estudios/2025-26/microcredenciales-ciclovidadato2601"
       style="padding: 12px 30px; height: 58px;">
       <span>Inscripción</span>
       <i class="fa-solid fa-circle-right ms-3"></i> </a>
</div>

{{< blocks/link-down color="info" >}}

{{< /blocks/cover >}}

{{< blocks/section color="white" >}}
<div class="container">
    <div class="text-center mb-5">
        <h2 class="display-4 font-weight-bold">Módulos del Curso</h2>
    </div>
</div>

<div class="container">
    <div class="row" id="accordionModulos">
        {{< modulo id="1" titulo="Módulo 1" subtitulo="Fundamentos Data & IA" modalidad="Presencial" horas="12" >}}
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Arquetipos de Arquitecturas de Data & IA.
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Cloud y Multicloud.
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Modelos de implementación y servicios AWS/Azure/GCP.
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Principales drivers de decisión en el diseño de arquitecturas Data & IA.

        {{< /modulo >}}

        {{< modulo id="2" titulo="Módulo 2" subtitulo="Tratamiento del dato" modalidad="Presencial" horas="16" >}}
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Introducción a bases de datos relacionales (Snowflake) y no relacionales (MongoDB)
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Modelos de datos: operacionales vs. analíticos SQL/MQL
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Principales herramientas ETL/ELT. Python y Pyspark.
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Introducción a la IA: ML, IAGen, prompting engineering.
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Insights. Reporting y cuadros de mando. PowerBI.

        {{< /modulo >}}

        {{< modulo id="3" titulo="Módulo 3" subtitulo="Gestión del dato y proyectos data & IA" modalidad="Online" horas="10" >}}
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Metodologías de gestión de proyectos Data & IA.
* <i class="fa-solid fa-circle-check text-primary me-2"></i>  Gobierno del dato.
        {{< /modulo >}}

                {{< modulo id="4" titulo="Módulo 4" subtitulo="Caso práctico y preparación certiciación AWS" modalidad="Online" horas="12" >}}
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Desarrollo de caso práctico integral.
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Revisión de conceptos clave AWS.
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Ejercicios tipo examen de certificación.
* <i class="fa-solid fa-circle-check text-primary me-2"></i> Consejos y estrategias para el examen.

        {{< /modulo >}}
    </div>
</div>
{{< /blocks/section >}}

{{< blocks/section color="light" >}}
<div class="container text-center">
    <div class="row align-items-stretch">
        {{< info-card titulo="Fechas y horarios" icono="fa-solid fa-calendar-day" >}}
Comienzo del curso:    

*13 de Febrero, 2026*

Sesiones presenciales: 

*viernes de 16:00 a 20:00*
{{< /info-card >}}

{{< info-card titulo="Ubicación" icono="fa-solid fa-location-dot" >}}
[Facultad Informática UCM](https://informatica.ucm.es/)

*Campus de Moncloa*
{{< /info-card >}}
        {{< info-card 
            titulo="Precio y Becas" 
            icono="fa-solid fa-graduation-cap" 
            destacado="true"
            precio_general="240€"
            beca_titulo="Becas UCM"
            precio_beca="120€" 
        >}}
10 becas del 50% para estudiantes UCM
        {{< /info-card >}}
    </div>
</div>
{{< /blocks/section >}}

{{< blocks/section color="white" >}}
<div class="container text-center py-2  ">
    <div class="row justify-content-center align-items-center g-0">
        {{< partners src="images/logo-ucm.jpg" alt="Logo Universidad Complutense de Madrid" url="https://www.ucm.es/" altura="100px" ancho="4" >}}
        {{< partners src="images/logo-nfq.svg" alt="Logo Nfq" url="https://nfq.es/" altura="60px" ancho="4" >}}
    </div>
</div>
{{< /blocks/section >}}

<style>

    /* Forzamos que el contenido (título, texto, botones) esté por encima de la capa */
  .td-cover-block .container {
    position: relative !important;
    z-index: 10 !important;
    padding-top: 0 !important;
    margin-top: -110px !important; /* Ajusta este valor para subirlo más o menos */
  }
  /* 2. Hace que el título ocupe menos espacio y suba */
  .td-cover-block h1.display-1 {
    margin-top: 0 !important;
    padding-top: 0 !important;
    line-height: 1.1 !important;
    font-size: 4.2rem !important; /* Un poco más pequeño para ganar espacio */
  }

  /* 3. Ajusta el contenedor del Cover para que no sea tan rígido con el centrado */
  .td-cover-block {
    display: flex !important;
    align-items: flex-start !important; /* Cambia de center a start */
    padding-top: 250px !important; /* Espacio para que no choque con la Navbar */
  }
/* Creamos una capa que se sitúa justo encima de la imagen pero debajo del texto */
  .td-cover-block::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    /* Capa de oscurecimiento (puedes ajustar el 0.6) */
    background-color: rgba(0, 0, 0, 0.5) !important;
    /* Efecto de desenfoque sobre lo que hay detrás */
    backdrop-filter: blur(5px) !important;
    z-index: 0;
  }

.td-offset-anchor + .section-index {
     padding-top: 1rem !important;
     padding-bottom: 1rem !important;
  }
  
  /* Reducción específica para la última sección de la página */
  section:last-of-type {
    padding-top: 1.5rem !important;
    padding-bottom: 1.5rem !important;
  }


</style>