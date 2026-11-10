# Descenso

Descargá `index.html` y abrilo con Chrome. La app funciona localmente y guarda una copia en el navegador. GitHub conserva el respaldo en `datos/descenso.json` dentro de este repositorio privado.

1. Si ya usabas Descenso, exportá un respaldo JSON desde la versión anterior e importalo en **Configuración** de esta app. El código de este repositorio empieza con un historial vacío.
2. Creá un [token de acceso de GitHub](https://github.com/settings/personal-access-tokens/new). En **Repository access** elegí **Only select repositories** y marcá **descenso**. En **Contents** elegí **Read and write**.
3. Pegá el token en **Configuración → Base de datos en GitHub** y elegí **Guardar en GitHub**. La primera vez se completa el archivo JSON, que empieza vacío. Para recuperar tus registros en otra copia, conectá GitHub y elegí **Traer desde GitHub**.

El token solo se usa durante la sesión de la pestaña. El guardado en GitHub es manual, y admite hasta 900 KiB por respaldo incluidas las fotos. Si el archivo supera ese tamaño, descargá un respaldo JSON local desde **Configuración** para guardar todos los datos. Si otro dispositivo actualizó el JSON, la app bloquea el guardado hasta que traigas esa versión.

Mantené este repositorio privado. GitHub conserva las versiones anteriores de los datos en el historial.
