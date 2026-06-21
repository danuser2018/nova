# Nova Website

Este repositorio contiene la web oficial del proyecto Nova.

Es una landing page estática construida con HTML5 + Bootstrap 5, pensada para presentar el proyecto de forma clara y ligera.

La web no incluye la documentación técnica ni el código de Nova.
Su función es actuar como punto de entrada al proyecto.

---

## Contenido

* Landing page principal (`index.html`)
* Estilos personalizados (`css/`)
* Recursos estáticos (`images/`)

---

## Tecnologías

* HTML5
* Bootstrap 5 (CDN)
* CSS personalizado ligero

No se utilizan frameworks de frontend ni build tools.

---

## Ejecutar en local

Puedes abrir directamente el archivo:

```bash id="kq3v9m"
open index.html
```

O usar un servidor local sencillo:

```bash id="w9x2pl"
python -m http.server 8000
```

Luego abre:

```
http://localhost:8000
```

---

## Despliegue en GitHub Pages

Este repositorio está preparado para GitHub Pages.

### Activación

1. Ir a **Settings → Pages**
2. Seleccionar:

   * Source: `Deploy from a branch`
   * Branch: `main`
   * Folder: `/ (root)`
3. Guardar

La web se publicará en:

```
https://danuser2018.github.io/nova/
```

---

## Estructura del proyecto

```text id="p1v8ak"
nova-website/
│
├── index.html
├── css/
│   └── style.css
├── images/
├── README.md
```

---

## Propósito

Este repositorio existe únicamente para:

* Presentar Nova de forma pública
* Ofrecer una landing page ligera
* Centralizar enlaces al proyecto principal
* Facilitar acceso a GitHub y documentación técnica

---

## Relación con Nova

La lógica, arquitectura y documentación técnica de Nova se encuentran en el repositorio principal del proyecto.

Esta web no implementa ninguna funcionalidad de Nova.

---

## Contribuir

Si quieres proponer mejoras en la web:

1. Abre un issue
2. Propón el cambio
3. O envía un pull request

---

## Licencia

The MIT license

