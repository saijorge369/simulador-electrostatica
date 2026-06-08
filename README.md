# Simulador de campo electrico, potencial y energia

Pagina HTML autonoma para practicar electrostatica con simulaciones interactivas y un autotest de 10 preguntas.

Autor: Prof. Wong OM SAI RAM  
Copyright 2026. Todos los derechos reservados.

## Licencia de uso

Uso educativo permitido para estudiantes y docentes mediante el enlace publicado por el autor.

No se permite redistribuir, vender, copiar, modificar, republicar, descargar para crear versiones derivadas, ni subir este material a otros sitios o repositorios sin permiso escrito del autor.

Este proyecto se publica para consulta y practica educativa, pero no es software libre ni de codigo abierto.

## Uso local

Abre `index.html` en un navegador o sirve la carpeta con:

```bash
python3 -m http.server 8765
```

Luego entra a:

```text
http://localhost:8765/index.html
```

## Publicar en GitHub Pages

1. Sube `index.html`, `README.md` y `LICENSE` a un repositorio publico.
2. En GitHub, entra a `Settings > Pages`.
3. En `Build and deployment`, selecciona la rama principal y la carpeta raiz.
4. Guarda los cambios y abre el enlace que GitHub Pages genera.

Importante: al publicarlo en GitHub Pages, cualquier navegador puede ver el codigo HTML que se descarga para ejecutar la simulacion. La licencia restrictiva protege el uso autorizado, pero tecnicamente no impide que alguien copie el archivo.

## Temas cubiertos

- Carga positiva y carga negativa.
- Dipolo electrico.
- Dos cargas iguales.
- Cargas desiguales.
- Placas paralelas.
- Esfera conductora solida y conductor hueco.
- Esfera dielectrica hueca.
- Conductor hueco y esfera dielectrica hueca con carga central positiva o negativa.
- Cuatro cargas en las esquinas de un cuadrado.
- Espira/arco circular cargado configurable de 0 a 360 grados.
- Puntos donde el potencial electrico se anula.
- Potencial de un dipolo segun el angulo.
- Grafica V(x) para deducir el campo electrico por pendiente.
- Graficas `E(r)` y `V(r)` para cargas solas/esferas, y `E(d)`/`V(d)` para placas paralelas, con marcador de la posicion de `P`.
- Cuadricula en centimetros para leer posiciones y distancias.
- Coordenadas editables de cada carga: `q`, `x`, `y`.
- Borrado de cargas con boton o tecla Delete.
- Formacion rapida de dipolo, cuadrado y triangulo con separacion configurable.
- Poligonos regulares de 3 a 12 cargas con signos positivos, negativos o alternados.
- Campo electrico, potencial, energia potencial y trabajo.
- Lineas y superficies equipotenciales.
- Autotest con temporizador de 20 minutos, soluciones on/off, impresion y calificacion final.
- Modos visuales: oscuro, GeoGebra, PhET, MIT, minimalista, fondo blanco tipo Pixar, colores intensos, pizarra verde, pizarra plomo y Da Vinci.
