# FITZONE-HN Frontend Demo

Copia independiente del frontend. No incluye backend ni base de datos.

## Ejecución local

Usar Node.js 24 LTS y npm.

```sh
npm install
npm run dev
```

## Compilación

```sh
npm run build
npm run preview
```

## Despliegue posterior en Vercel

- Framework: Vite.
- Root Directory: raíz de este repositorio (.).
- Install Command: npm install.
- Build Command: npm run build.
- Output Directory: dist.
- Node.js: 24.x.

No es necesario configurar secretos para mostrar el frontend. No se ha conectado ningún repositorio ni publicado este proyecto.

## Formularios e imágenes

Se conserva el comportamiento original de los formularios. Registro e inicio de sesión requieren una API real: en desarrollo se usa http://localhost:3000/api y en producción /api, salvo que se configure VITE_API_URL. Esta copia no incorpora esa API ni simula operaciones exitosas. La confirmación de inscripción sigue pendiente según el código original.

VITE_API_URL sería una dirección pública incluida en el navegador; no debe contener credenciales. No se incluyen archivos .env.

La imagen de portada conserva su URL externa de Pexels y necesita conexión a Internet.

SOURCE-MANIFEST.json contiene rutas relativas y hashes SHA-256 de los archivos copiados para verificar su integridad. node_modules y dist se generan localmente para validar y quedan excluidos mediante .gitignore; no deben publicarse como archivos del repositorio.
