# Carga Excel Python

Ejemplo de tratamiento de Excel con python cargando los datos en una tabla SQLITE.

## Obtener SQLite
Descargar **SQLITE Browser**, .[DB Browser for SQLite no installer](https://github.com/sqlitebrowser/sqlitebrowser/releases/download/v3.13.1/DB.Browser.fo.r.SQLite-v3.13.1-win64.zip)

Crear fichero **permisos.db** y una tabla opermisos con los campos codigo, descripcion y formulario.

## Python

Crear entorno virtual y activarlo, (en un directorio de entornos virtuales ):
```console
# Creamos
python -m venv venvfp
# Activamos
.\venvfp\Scripts\activate
```

Ademas instalamos libreria de excel.

```console
pip install openpyxl
```