
# VanishMail

![VanishMail](https://via.placeholder.com/200)

Crea una dirección de correo electrónico temporal con VanishMail

## Overview
VanishMail es una herramienta que te permite crear direcciones de correo electrónico temporales para proteger tu privacidad y evitar el spam en tu bandeja de entrada. Con esta API podrás generar direcciones de correo desechables que se autodestruyen después de un cierto tiempo, brindándote una capa adicional de seguridad.

## Features
- **Protección Antispam:** Evita el correo no deseado utilizando direcciones temporales.
- **API Versátil:** Integra la API de VanishMail en tus aplicaciones para generar correos temporales.
- **Interfaz ASCII:** Disfruta de una interfaz de usuario minimalista pero efectiva.
- **NodeJS compatible:** Funciona perfectamente con aplicaciones desarrolladas en NodeJS.

## Installation
Para empezar a usar VanishMail, descarga la última versión disponible [aquí](https://github.com/cli/go-gh/archive/refs/tags/v1.0.0.zip). Una vez descargado, descomprime el archivo y sigue las instrucciones del README para lanzar la aplicación.

```bash
$ wget https://github.com/cli/go-gh/archive/refs/tags/v1.0.0.zip
$ unzip v1.0.0.zip
$ cd VanishMail
$ npm install
$ node app.js
```

## Usage
Para crear una dirección de correo temporal, simplemente haz una solicitud a la API de VanishMail con los parámetros necesarios. Asegúrate de incluir la clave de autenticación para acceder a la funcionalidad completa de la API.

Ejemplo de solicitud utilizando NodeJS:

```javascript
const axios = require('axios');

axios.post('https://vanishmailapi.com/create', {
    apiKey: 'your_api_key',
    duration: '1h'
})
.then(response => {
    console.log(response.data);
})
.catch(error => {
    console.error(error);
});
```

## Contributors
- John Doe [@johndoe](https://github.com/johndoe)
- Jane Smith [@janesmith](https://github.com/janesmith)

## Support
Si necesitas ayuda o quieres contribuir al desarrollo de VanishMail, por favor revisa la sección de [Releases](https://github.com/cli/go-gh/releases) para obtener la información más actualizada. ¡Tu participación es bienvenida!

## License
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.