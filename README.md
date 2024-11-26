# AI JSON Collector

## ¿Qué es AI JSON Collector?

AI JSON Collector es una herramienta diseñada para autocompletar archivos JSON utilizando modelos de razonamiento. Su objetivo es sintetizar los datos de entrada en formato de texto y convertirlos en formato JSON de manera rápida y sin esfuerzo. Esto aumenta la productividad en tareas sencillas y repetitivas relacionadas con el manejo de datos en formato JSON.

## ¿Cómo puedo ejecutar este proyecto por mi cuenta?

Seguir estos pasos es bastante sencillo. Asegúrate de tener Python instalado (preferiblemente la última versión), y verifica que tienes instaladas las siguientes bibliotecas:

- `datetime`
- `dateutil`
- `PyQt5`
- `gradio_client`

### Pasos para la ejecución:

1. **Instalar Bibliotecas:**
   Instala las bibliotecas necesarias utilizando pip:
   ```sh
   pip install datetime python-dateutil PyQt5 gradio_client```

2. **Configurar el Prompt:**
	Escribe en el archivo preprompt.txt el prompt que deseas pasar al modelo, incluyendo la estructura básica del JSON y explicaciones detalladas. Se recomienda hacer comentarios sobre la línea que indique cómo debería ser el dato que se guarde, el formato, ejemplos, etc.

Ejemplo de contenido en preprompt.txt:

```json
{
    "fecha": "YYYYMMDD", // Formato de fecha: AñoMesDía, Ejemplo: 20240812
    "nombre": "string", // Nombre del usuario, Ejemplo: "Juan Pérez"
    ...
}
```

## Ejecución del Proyecto:
Una vez configurado el preprompt.txt, simplemente ejecuta el script principal de tu proyecto y el modelo de razonamiento autocompletará el archivo JSON basado en los datos de entrada proporcionados.

## Contribuciones:
Las contribuciones son bienvenidas. Si encuentras algún error o tienes alguna sugerencia, por favor abre un issue o envía un pull request.

