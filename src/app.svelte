<!--Svelte es una herramienta para construir apps web
Permite construir una app declarativamente desde modulos, 
combinando marcado, estilos y comportamientos.
Estos componentes son compilados en pequeños modulos de JS
los cuales eliminan la saturacion que tendria un framework de UI-->

<script>
    // your script goes here
    let name = 'Svelte';
    let src = "/image.png"
    let imgDescr = "GavenJr"
</script>>

<h1>Mi app en { name.toLowerCase() }!</h1>

<img src={src} alt="Una imagen de {imgDescr}"/>
