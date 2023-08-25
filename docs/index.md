---
hide:
  - footer
  - navigation
  - toc
---


#
</br>
</br>
</br>
<p style="font-size: 33px; color: white;font-family: 'Roboto Condensed', sans-serif;font-weight: bold;">Explorando un Futuro Sostenible: Descubriendo las Energías Renovables</p>

<p style="font-size: 22px; color: white;font-family: Roboto Condensed;">
En este blog, nos sumergiremos en el mundo de las energías renovables a través de la perspectiva única de un ingeniero e instalador especializado. Exploraremos la normativa y las últimas innovaciones en tecnologías de generación solares y eólicas, entenderemos cómo se diseñan, construyen, legalizan, tramitan subvenciones... para los sistemas de energía renovable.


</br>
</br>
</br>
</br>
</br>
</br>
<div class="collage">
    <img src="figs/Distancia mínima entre filas de módulos_page_2.png" alt="Imagen 2">
    <img src="figs/Distancia mínima entre filas de módulos_page_4.png" alt="Imagen 1">
    <img src="figs/Contrato_page_3.png" alt="Imagen 1">
    <img src="figs/Declaración de autoconsumo del proyecto ejecutado Anexo_page_4.png" alt="Imagen 2">
</div>


<style> 
body { 
  background-image: url('https://github.com/asolear/assets/blob/master/imgs/fondo3.jpg?raw=true'); 
  background-repeat: no-repeat; 
  background-attachment: fixed; /* background-size: cover; */ 
  background-size: 100% 100%;
   } 

.collage {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 10px;
}
.collage img {
    max-width: 100%;
    height: auto;
    transform: rotate(0deg);
    /* Rotar la imagen 15 grados */
    transition: transform 0.3s ease;
    /* Agregar una transición suave */
}
.collage img:hover {
    transform: scale(1.1) rotate(10deg);
    /* Escalar la imagen al 110% y volver a la rotación original en el hover */
}

</style> 

<script>
    const images = document.querySelectorAll('.collage img');
    images.forEach(img => {
        img.style.transform = `rotate(${getRandomRotation()}deg) scale(${getRandomScale()})`;
    });
    function getRandomRotation() {
        return Math.floor(Math.random() * 31) - 15; // Valores de rotación aleatorios entre -15 y 15 grados
    }
    function getRandomScale() {
       return 0.8 + Math.random() * 0.4; // Valores de escala aleatorios entre 0.8 y 1.2
    }
</script>