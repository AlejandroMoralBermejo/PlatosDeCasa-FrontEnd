# Platos de Casa - Frontend

## ¿De qué va el proyecto?

Platos de Casa es una aplicación web diseñada para almacenar todas tus recetas en un solo lugar. Los usuarios pueden guardar sus propias recetas incluyendo el nombre, los ingredientes y el proceso de preparación. También permite un módulo familiar donde varios usuarios pueden compartir recetas, así como un foro global para publicar recetas, recibir puntuaciones y comentarios. El proyecto está pensado para uso personal y familiar, sin fines comerciales.

## Herramientas y Tecnologías Utilizadas

* **Frontend:** React + Next.js (SSR/SSG para SEO y rendimiento)
* **Autenticación:** NextAuth + JWT
* **Chat en tiempo real:** Socket.IO
* **Despliegue:** Vercel
* **Control de versiones:** GitHub (repositorios separados para frontend y backend)

## Cómo Iniciar

1. Clona el repositorio del frontend:

   ```bash
   git clone https://github.com/AlejandroMoralBermejo/PlatosDeCasa-FrontEnd
   ```
2. Accede a la carpeta del proyecto:

   ```bash
   cd PlatosDeCasa-FrontEnd
   ```
3. Instala las dependencias:

   ```bash
   npm install
   ```
4. Crea un archivo `.env.local` basado en `.env.example` y añade tus variables de entorno.
5. Inicia el servidor de desarrollo:

   ```bash
   npm run dev
   ```
6. Abre tu navegador en [http://localhost:3000](http://localhost:3000)

## Cosas a Tener en Cuenta

* **No** subir archivos `.env` a GitHub para mantener tus datos sensibles privados.
* Asegúrate de que el servidor backend esté en funcionamiento y accesible para las solicitudes API.
* Sigue las convenciones de nombres de ramas:

  * Desarrollo personal: `dev_<tu-nombre>`
  * Integración de funcionalidades: `features`
  * Producción: `main`

## Quién lo Desarrolló

El frontend fue desarrollado por \[Alejandro Moral Bermejo].

## Contacto

Para preguntas o soporte, puedes comunicarte a través de:

* Linkedin: www.linkedin.com/in/alejandro-moral-bermejo
* GitHub: [https://github.com/AlejandroMoralBermejo](https://github.com/AlejandroMoralBermejo)
