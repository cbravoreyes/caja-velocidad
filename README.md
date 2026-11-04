# Simulador de caja de velocidades manual

Recurso educativo interactivo para comprender el funcionamiento básico de una transmisión manual de cinco velocidades.

## Contenido
- `index.html`: simulación completa (HTML, CSS y JavaScript integrados).
- `README.md`: instrucciones de uso y publicación.

## Uso local
Descarga o clona el repositorio y abre `index.html` en un navegador moderno. No requiere instalación, servidor, dependencias ni conexión a Internet.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html` y `README.md` a la raíz del repositorio.
3. Entra en **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. GitHub Pages publicará el recurso y mostrará la dirección del sitio en esa misma sección.

## Controles
- **N, 1.ª–5.ª:** seleccionan punto muerto o una marcha.
- **Embrague:** alterna entre acoplado y desacoplado.
- **RPM:** modifica las revoluciones del motor.
- **Par motor:** modifica el par de entrada.
- **Comparar primera y quinta:** alterna ambas marchas a las mismas RPM.

## Modelo didáctico y supuestos
Se emplean relaciones de transmisión simplificadas: 1.ª 3,60:1; 2.ª 2,10:1; 3.ª 1,40:1; 4.ª 1,00:1; 5.ª 0,80:1. La relación final del diferencial es 4,10:1, la circunferencia del neumático es 1,90 m y la eficiencia global se aproxima al 90 %.

La velocidad y el par calculados son valores teóricos. El modelo no representa pérdidas variables, deslizamiento del embrague, curvas reales del motor, resistencia aerodinámica, pendientes, inercia ni dinámica completa del vehículo. Al desconectar el embrague, la simulación muestra que deja de transmitirse potencia; no modela la continuidad del movimiento real por inercia.

## Licencia
Puedes añadir una licencia abierta (por ejemplo, MIT) al repositorio si deseas permitir reutilización y modificación bajo sus condiciones.
