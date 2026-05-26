# Instalacion rapida - Backend Google Apps Script v4

1. Abre el Google Sheet que usas como backend.
2. Ve a Extensiones > Apps Script.
3. Reemplaza todo el contenido por `backend-apps-script.gs`.
4. Configura las propiedades del script:

```text
ADMIN_EMAIL=tu_correo@empresa.com
DRIVE_FOLDER_ID=id_de_carpeta_para_evidencias
```

5. Despliega como WebApp:

```text
Deploy > New deployment > Web app
Execute as: Me
Who has access: Anyone
```

6. Copia la URL `/exec` y pegala en `js/config.js` en `SCRIPT_URL`.
7. Entra a `mapeo-ti.html` y presiona Inicializar hojas.

## Orden recomendado de carga

1. Usuarios.
2. Cuentas y accesos.
3. Equipos.
4. Dispositivos moviles.
5. Perifericos.
6. Asignaciones y riesgos.
