# Descenso

App personal de seguimiento: comidas, peso, medidas, actividad, reportes semanales y el plan de alimentación (1660 kcal).

Sitio: https://rosariogebala-cyber.github.io/descenso/

## Dónde están los datos

- **En cada navegador** (almacenamiento interno del sitio). Es la copia de trabajo.
- **En el repositorio privado `descenso-datos`** (`descenso.json`). Es la copia compartida entre dispositivos.

Este repositorio es público y contiene solo el sitio (`index.html`). No guarda datos personales.

## Conectar un dispositivo (Mac, celular)

1. Creá un token de acceso de GitHub (fine-grained) con acceso solo a **descenso-datos** y permiso **Contents → Read and write**.
2. En el sitio: **⚙ Configuración → Sincronización entre dispositivos**, pegá el token y tocá **Conectar este dispositivo**.

El token queda guardado en ese navegador. El sitio sincroniza solo al abrirse, al volver a la pestaña y cada vez que guardás. Junta los registros de todos los dispositivos: los borrados se respetan y, si se edita lo mismo en dos lugares, gana la versión más reciente.

## Respaldo

En **⚙ Configuración** podés descargar un respaldo JSON en cualquier momento.
