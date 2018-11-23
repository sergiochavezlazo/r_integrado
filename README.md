
<center>
<img src="https://github.com/Reproducibilidad/herramientasDataScience/raw/master/Logo_LabPUCP.png" style="width: 300px;"/>
</center>


<center> <h1>Herramientas de la Ciencia de Datos <br></br>para la Investigación Social Reproducible</h1> </center>

<br></br>

* Profesor:  <a href="http://www.pucp.edu.pe/profesor/jose-manuel-magallanes/" target="_blank">Dr. José Manuel Magallanes, PhD</a> ([jmagallanes@pucp.edu.pe](mailto:jmagallanes@pucp.edu.pe))<br>Profesor del **Departamento de Ciencias Sociales, Pontificia Universidad Católica del Peru**.<br>
Senior Data Scientist del **eScience Institute** and Visiting Professor at **Evans School of Public Policy and Governance, University of Washington**.<br>
Fellow Catalyst, **Berkeley Initiative for Transparency in Social Sciences, UC Berkeley**.


## Integración Total

En esta sesión veremos cómo producir un paper usando las herramientas mencionadas la vez pasada.

Si estás leyendo esto, es por que estás en un repositorio de Github; pero ahora quieres que este repositorio esté al "alcance" de R. Los pasos serán muy simples:

1) Primero _forkea_ este repositorio, esto producirá una copia de este trabajo. Hazlo, y luego sigue leyendo.

2) Luego ve a tu maquina y crea una carpeta llamada "DataScience".

3) Ahora, ve a RStudio y crea un NUEVO **PROYECTO**. El proyecto debe ser de tipo **VERSION CONTROL**. De estos, elige **GIT**. De ahi copia y pega la dirección de este repositorio donde se te pida. De ahi pones el nombre del _repo_ (si es que no aparece). Indicale a RStudio que este _repo_ que está en la web será una carpeta (folder) dentro de "DataScience". Finalmente, selecciona: "open in new session". Luego de eso, debes ver que llegan los archivos de este _repo_.

4) Ve al tab **consola**. Ahí escribe una a una estas lineas, dando _Enter_ luego de cada una:

* git config --global user.email "tuemail_@_entrecomillas"
* git config --global user.name "nombredeusuario_entrecomillas"

5) Luego ve a _Tools_ / _Global Options_ y ahi busca la opcion **GIT/SVN**. Ahí, crea una RSA key: no necesitas password, solo creala y copiala.

6) la RSA Key que has creado debes añadirla a Github: ve a **settings** en tu **profile** y creala dentro de **SSH and GPG keys**.

7) Luego regresa a la consola y tipea:
git config remote.origin.url "VEATU_REPO_Y_BUSCA_CLONAR_CON_SSH"


8) Cuando hayas hecho eso, todo lo que quieras que esté en tu _repo_ debes hacer dos pasos:
* **Commit** (lo que hayas "staged"). Cada commit lleva un comentario.
* **Push** (lo que haya pasado por _Commit_). Es la flecha hacia arriba.

9) Si deseas traer contenido, usa la flecha pull (hacia abajo).

Ya tienes el repo de la sesión. Disfruta!




_____

**AUSPICIO**: 

El desarrollo de estos contenidos ha sido posible gracias al grant del Berkeley Initiative for Transparency in the Social Sciences (BITSS) at the Center for Effective Global Action (CEGA) at the University of California, Berkeley


<center>
<img src="https://github.com/MAGALLANESJoseManuel/BITSS_ToolsWorkshop/raw/master/LogoBitss.jpg" style="width: 300px;"/>
</center>

**RECONOCIMIENTO**

EL Dr. Magallanes agradece a la Pontificia Universidad Católica del Perú, por su apoyo en la elaboración de este trabajo.

<center>
<img src="https://github.com/MAGALLANESJoseManuel/BITSS_ToolsWorkshop/raw/master/LogoPUCP.jpg" style="width: 200px;"/>
</center>


El autor reconoce el apoyo que el eScience Institute de la Universidad de Washington le ha brindado desde el 2015 para desarrollar su investigación en Ciencia de Datos.

<center>
<img src="https://github.com/MAGALLANESJoseManuel/BITSS_ToolsWorkshop/raw/master/LogoES.png" style="width: 300px;"/>
</center>

<br>
<br>
