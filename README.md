# Detectives del pentagrama

Una pequeña aplicación web para que niñas y niños aprendan a reconocer notas musicales en el pentagrama mientras juegan.

## Motivación

Leer música se aprende poco a poco, a base de observar muchas veces la relación entre una nota escrita y su nombre. **Detectives del pentagrama** convierte esa práctica en un juego breve y amable: se muestra una nota en el pentagrama, el jugador elige su nombre y recibe una corrección inmediata.

El objetivo es favorecer la práctica frecuente, sin presión y con pequeños premios por mantener rachas de aciertos.

## Qué permite hacer

- Practicar las notas naturales: DO, RE, MI, FA, SOL, LA y SI.
- Elegir entre clave de sol, clave de do y clave de fa.
- Trabajar notas en líneas, espacios y hasta dos líneas adicionales por encima o por debajo del pentagrama.
- Escuchar un sonido de piano al acertar.
- Mostrar la nota correcta tras un fallo y mantener la misma pregunta hasta responderla bien.
- Registrar rachas de aciertos e insignias instrumentales:
  - Trompeta: racha de 10.
  - Piano: racha de 50.
  - Tambor: racha de 100.
  - Guitarra: racha de 200.
  - Violín: racha de 500.
- Mantener cuatro perfiles independientes (Luna, Leo, Mia y Nico), cada uno con progreso distinto para cada clave.
- Recordar el último personaje y la última clave seleccionada al volver a abrir el juego.

## Uso

1. Abre `index.html` en un navegador o visita la página publicada con GitHub Pages.
2. Pulsa el botón que muestra el personaje y la clave para abrir el panel lateral.
3. Selecciona el personaje y la clave con los que quieres practicar.
4. Lee la nota del pentagrama y pulsa su nombre.

El progreso se guarda localmente en el navegador del dispositivo. Por ello, cada navegador o iPad conserva su propio progreso.

## Publicación con GitHub Pages

Este proyecto es estático: no necesita servidor ni instalación. Para publicarlo:

1. Sube `index.html`, la carpeta `audio/` y este archivo al repositorio.
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment**, elige desplegar desde una rama y selecciona `main` y la carpeta raíz (`/`).
4. Guarda los cambios y espera a que GitHub genere la dirección pública.

En un iPad, abre esa dirección en Safari y usa **Compartir → Añadir a pantalla de inicio** para tener un acceso directo como si fuera una aplicación.

## Créditos

Las muestras de piano proceden de **Salamander Grand Piano V3**, de Alexander Holm, y se usan bajo licencia [Creative Commons Attribution 3.0](https://creativecommons.org/licenses/by/3.0/).

---

Hecho con cariño para aprender música jugando. 🎵
