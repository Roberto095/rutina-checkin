# Check-in Rutina

App web para seguir día a día la rutina de entrenamiento en casa (fase 1): marcar series, temporizador de descanso, cuerda con conteo de saltos, agua, creatina, energía, dolor del pie, peso, cintura y colgada en barra.

Funciona en el navegador del celular, la tableta o el computador. No necesita instalación ni servidor.

## Estructura

```
index.html       Estructura de la página
css/styles.css   Apariencia (colores, tipografía, modo claro y oscuro)
js/app.js        Lógica: plan, check-in, gráficas, temporizador y guardado
```

## Cómo usarla

Abre `index.html` en el navegador. Los datos se guardan en el navegador (`localStorage`) y, cuando se abre como artifact de Claude, también en tu cuenta.

## Dónde cambiar cosas

- **Ejercicios y series:** objeto `SESS` en `js/app.js`.
- **Qué sesión toca cada día:** objeto `WEEK` en `js/app.js`.
- **Pesas disponibles:** propiedad `w` de cada ejercicio.
- **Colores:** variables de `:root` al inicio de `css/styles.css`.

Hecho por Roberto Sánchez Vargas.
