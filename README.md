# 📰 Revista con CSS Grid

## Descripción del Proyecto  
Este proyecto educativo enseña CSS Grid mediante la creación de un diseño de revista profesional. Aprenderás a implementar layouts complejos, controlar espacios entre elementos y crear diseños responsivos utilizando el sistema de grillas de CSS.

## 🎯 Objetivos de Aprendizaje  
- ✅ Dominar la creación de layouts con grid-template-areas  
- ✅ Implementar diseños de revista complejos  
- ✅ Controlar el flujo de contenido con grid-auto-flow  
- ✅ Crear diseños responsivos con media queries  
- ✅ Aplicar espacios consistentes con gap  

## 🛠 Tecnologías Utilizadas  
| Tecnología | Uso |  
|------------|-----|  
| HTML5 | Estructura semántica |  
| CSS Grid | Layout principal |  
| Media Queries | Responsividad |  

## ✨ Características Principales  
- Layout de revista profesional  
- Diseño basado en grid-template-areas  
- Adaptación perfecta a diferentes pantallas  
- Espacios consistentes con gap  
- Código bien organizado y comentado  

## 💡 Ejemplo de Código  
```css  
.magazine-layout {
  display: grid;
  grid-template-areas:
    "header header header"
    "main main sidebar"
    "footer footer footer";
  gap: 20px;
}

@media (max-width: 768px) {
  .magazine-layout {
    grid-template-areas:
      "header"
      "main"
      "sidebar"
      "footer";
  }
}

```
## 📚 Recursos de Aprendizaje
Profundiza en Flexbox con el curso [Diseño Web Responsivo de FreeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/)

## 🖼️ Demo del Proyecto
[Ver Revista con CSS Grid](https://informaticaempresarial-tic-docente.github.io/Revista-con-CSS/)

## 👨‍💻 Contacto del Desarrollador
**Victoriano Domínguez Henríquez**  
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://web.facebook.com/profile.php?id=61573209977446&locale=es_LA) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victoriano-dominguez-henr%C3%ADquez-614785144) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/InformaticaEmpresarial-Tic-Docente/InformaticaEmpresarial-Tic-Docente)


---

📄 **Nota:** Este proyecto es parte de un programa educativo de desarrollo web.
