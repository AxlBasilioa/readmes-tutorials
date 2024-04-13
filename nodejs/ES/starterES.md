# Tutorial de Node.js

Bienvenido a este tutorial sobre Node.js, donde aprenderás qué es Node.js, cómo utilizarlo y cómo crear tu primer proyecto "Hola Mundo".

## ¿Qué es Node.js?

Node.js es un entorno de ejecución para JavaScript construido sobre el motor de JavaScript V8 de Chrome. Permite ejecutar código JavaScript en el servidor, fuera de un navegador web. Esto lo hace ideal para desarrollar aplicaciones de servidor debido a su modelo de operaciones de entrada/salida sin bloqueo y orientado a eventos.

## Instalación de Node.js

Para comenzar a usar Node.js, primero necesitas instalarlo en tu sistema. Puedes descargar la última versión de Node.js desde su sitio web oficial [Node.js](https://nodejs.org/).

### Windows y Mac:

1. Descarga el instalador desde [Node.js](https://nodejs.org/).
2. Ejecuta el instalador y sigue las instrucciones.
3. Una vez instalado, puedes verificar la instalación abriendo una terminal y escribiendo:
   ```bash
   node -v
   ```
   Deberias de recibir como respuesta el numero de version que instalaste
   al igual que con npm(Node Package Manager)
   ```bash
   npm -v
   ```
## Linux:
Puedes instalar Node.js desde el terminal con los siguientes comandos, dependiendo de tu distribución:

### Debian y Ubuntu:
```bash
sudo apt update
sudo apt install nodejs npm
```
### Fedora y RedHat:
```bash
sudo dnf install nodejs npm
```

### Crear tu primer proyecto en Node.js

Para crear tu primer proyecto "Hola Mundo" en Node.js, sigue estos pasos:

- Crea un nuevo directorio para tu proyecto y navega a él:
```bash
mkdir miProyectoNode
cd miProyectoNode
```

- Inicializa un nuevo proyecto de Node.js:
```bash
npm init -y
```
- Crea un archivo llamado index.js:
```bash
echo console.log('Hola Mundo!') > index.js
```
- Ejecuta tu aplicación:
```bash
node index.js
```
Deberías ver en la terminal el mensaje "Hola Mundo!".

### Conclusión
¡Felicidades! Ahora has creado tu primer proyecto en Node.js y has ejecutado tu primer script "Hola Mundo". Este es solo el principio de lo que puedes hacer con Node.js. ¡Continúa explorando y aprendiendo más sobre este poderoso entorno de ejecución!