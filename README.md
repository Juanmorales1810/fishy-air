# Fishy Air

Bienvenido al repositorio de Fishy Air, una plataforma web diseñada para ofrecer productos aromáticos personalizados para mejorar el ambiente de cualquier espacio. Este proyecto está construido con Astro y utiliza Tailwind CSS para el diseño y la estilización.

## Descripción

Fishy Air se enfoca en proporcionar una experiencia única a través de productos aromáticos de alta calidad. Nuestra página web ofrece información detallada sobre los beneficios de nuestros productos, testimonios de clientes, y una sección sobre nosotros para conocer más acerca de nuestra misión y visión.

## Estructura del Proyecto

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── HeroPrincipal.astro
│   │   ├── WhyFhishiAir.astro
│   │   ├── Benefits.astro
│   │   ├── AboutUs.astro
│   │   ├── Aromas.astro
│   │   ├── Hero.astro
│   │   └── Cta.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── globals.css
└── package.json
```

## Instalación

Para instalar y ejecutar el proyecto localmente, sigue estos pasos:

1. Clona el repositorio:
   ```sh
   git clone https://github.com/Juanmorales1810/fishy-air.git
   ```
2. Navega al directorio del proyecto:
   ```sh
   cd fishy-air
   ```
3. Instala las dependencias:
   ```sh
   npm install
   ```

## Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala las dependencias                         |
| `npm run dev`             | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build`           | Compila el sitio de producción en `./dist/`      |
| `npm run preview`         | Previsualiza la compilación localmente antes de desplegar |
| `npm run astro ...`       | Ejecuta comandos CLI de Astro como `astro add`, `astro check` |
| `npm run astro -- --help` | Obtén ayuda sobre el CLI de Astro                |

## Tecnologías Utilizadas

- **Astro**: Un moderno framework de construcción web que permite crear sitios rápidos y optimizados.
- **Tailwind CSS**: Un framework de CSS para crear diseños personalizados de manera rápida y eficiente.
- **TypeScript**: Un superconjunto tipado de JavaScript que mejora el desarrollo y la mantenibilidad del código.

## Componentes

El proyecto incluye una variedad de componentes de interfaz de usuario, diseñados para proporcionar una experiencia atractiva y funcional:

- **HeroPrincipal**: Sección principal de la página, destacando el producto principal.
- **WhyFhishiAir**: Explicación de por qué elegir Fishy Air.
- **Benefits**: Beneficios de los productos aromáticos.
- **AboutUs**: Información sobre la empresa y su misión.
- **Aromas**: Descripción de los diferentes aromas disponibles.
- **Hero**: Componente de hero adicional.
- **Cta**: Llamada a la acción para los visitantes.

## Cómo Contribuir

¡Las contribuciones son bienvenidas! Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Enlace al Proyecto

- Repositorio en GitHub: [Fishy Air](https://github.com/Juanmorales1810/fishy-air)
