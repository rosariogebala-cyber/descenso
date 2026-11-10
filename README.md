# Descenso

Descargá `index.html` y abrilo con Chrome. La app guarda una copia en el navegador, puede escribir automáticamente un JSON en la carpeta que elijas y puede sincronizarse con este repositorio privado.

## Copia en tu Mac

1. Si tenés un historial en otra versión, descargá su respaldo JSON e importalo desde **Configuración** en esta versión.
2. Guardá en tu carpeta de Descenso el JSON inicial incluido en `datos/descenso.json`, con el nombre `descenso-datos.json`. Si la carpeta ya tiene un archivo con ese nombre, conservalo e incorporá las comidas con **Importar respaldo JSON**, usando el JSON inicial.
3. En **Configuración → Copia en tu Mac → Elegir carpeta local**, seleccioná la carpeta de Descenso y permití la escritura. El archivo local se actualiza cada vez que guardás un cambio. Chrome puede pedirte que elijas nuevamente la carpeta al reabrir la app.

El JSON inicial incorpora 14 comidas del respaldo de Supabase del 31 de octubre. Al leerlo, la app agrega las comidas que faltan por fecha y tipo y conserva las mediciones, fotos y otros registros que tengas abiertos.

## Copia en GitHub

1. Creá un [token de acceso de GitHub](https://github.com/settings/personal-access-tokens/new) limitado a **descenso**, con **Contents → Read and write**.
2. Conectalo en **Configuración → Base de datos en GitHub**. Usá **Traer desde GitHub** para incorporar el respaldo. Después, **Guardar en GitHub** sincroniza tus registros.

El token se usa durante la sesión de la pestaña. Guardar en GitHub es manual y admite hasta 900 KiB por respaldo, incluidas las fotos. El archivo local no tiene ese límite. Si otro dispositivo actualiza el JSON remoto, la app bloquea el guardado hasta que traigas esa versión. Mantené el repositorio privado. GitHub conserva versiones anteriores de los datos.
