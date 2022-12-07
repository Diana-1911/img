---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS (experimental)
css: unocss
---

# SISTEMA DE CONTROL ENTRADA Y SALIDA HIKVISION®

Arroyo Rodríguez Diana - López García Emmanuel - Zaragoza Flores Vania Yemili

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>


---

# INTRODUCCIÓN 

Desde hace tiempo las organizaciones con un numero chico, mediano o grande de empleados han tenido la necesidad de controlar el flujo de entrada y salida del personal.
La evolucion de la tecnologia genera metodos mas versatiles de verificacion de asistencia como:

- **Biometricos** 
- **Huella Dactilar** 
- **Reconocimiento Facial**

Dentro del Instituto Tecnológico Gustavo A Madero se implemento un sistema de reconocimiento facial Hinkvision®, modelo DS-K1T7MF.
<br>
<br>

Para mas información [Hinkvision](https://www.hikvision.com/es-la/products/Access-Control-Products/Face-Recognition-Terminals/Pro-Series/ds-k1t671mf/)


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# DESCRIPCIÓN DEL PROBLEMA
<BR>
<p style="text-align:justify">El Instituto Tecnológico Gustavo A. Madero implemento un registro de entrada y salida mediante el dispositivo de reconocimiento facial Hikvision4® modelo DS-K1T671MF.</p>

<p style="text-align:justify">El área de Recursos Humanos presenta problemas entorno al tiempo y accesibilidad de su información, ya que la información generada por el dispositivo no cumple con los datos necesarios para tener un control exacto de su personal.</p>

<img src = "">

<p style="text-align:justify">Actualmente el área de Recursos Humanos sigue utilizando practicas manuales para el contraste de la información dada por el software IVMS-4200 con la información que tiene el área sobre su personal, esta práctica le quita tiempo valioso a dicha área.</p>


---

# OBJETIVO GENERAL
Apoyar al área de Recursos Humanos con el control de personal a la hora de entrada y salida, sistematizando la información dada por el programa. 
## OBJETIVOS ESPECIFICOS
- Conocer el funcionamiento del dispositivo Hikvision modelo DS-K1T671MF 
- Conectar con el software IVMS-4200 y manipular la información   
- Conocer los resultados que da el sistema a Recursos Humanos 
- Modificar el Excel con especificaciones tales como: nombre completo, hora de llegada, saber si llego temprano o tarde, saber si registro su entrada 
- Indicar en el Excel a que especialidad académica pertenece 
- Graficar los resultados estadísticos del registro entrada y salida del personal 
---

# TERMINALES DE RECONOCIMIENTO FACIAL
El reconocimiento facial es una manera de identificar o confirmar la identidad de una persona mediante su rostro.El reconocimiento facial es una categoría de seguridad biométrica.
El uso del reconocimiento facial en el control de acceso y la asistencia de tiempo ha sido una tendencia inevitable, que crea una experiencia ventajosa "sin contacto". 

---
# PRO FACE ACCESS TERMINAL DS-K1T671MF
Este dispositivo de la marca Hikvision reconoce rostros de manera inteligente, ya que al reconocer una cara usando cubre boca, lanza una alerta de voz, recordando que no tiene el cubre boca puesto y al mismo tiempo no se autentica la entrada. Del mismo modo cuando la cara tiene un cubre boca también se lanza una alerta de voz pero esta vez la autenticación es válida. 

La distancia para que un rostro pueda ser reconocido por el dispositivo es de 0.3 m a 3m sin usar mascarilla. 

El dispositivo permite el control de acceso para el uso que se le quiera dar. Tiene un máximo de reconocimiento de rostros que es de 6000, 6000 tarjetas y 5000 huellas dactilares. Usa protocolos TCP/IP. Otra gran función es que se puede configurar via cliente web. 


---

# Animations

---

# LaTeX

---

# Diagrams
---

# Learn More
