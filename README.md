# 🎧 AudioStore

**AudioStore** es una plataforma web para la compra informada de productos de audio y música como parlantes, auriculares, vinilos y más. El objetivo principal es ofrecer a los usuarios una experiencia de compra clara, eficiente y basada en datos, con métricas técnicas relevantes que los ayuden a tomar la mejor decisión.

---

## 📦 Descripción

Este proyecto fue desarrollado por Matias Diaz y Lucas Rada como un trabajo conjunto fullstack. Incluye frontend en React y backend en Django, integrados mediante Docker y conectados a una base de datos MySQL.

AudioStore permite:

- Explorar un catálogo de productos de audio y música.
- Ver especificaciones técnicas claras como respuesta de frecuencia, impedancia, potencia, etc.
- Acceder a reseñas o recomendaciones para orientar la decisión de compra.
- Filtrar productos por tipo, marca o características específicas.
- Navegación fluida, responsive y moderna.

---

## 🛠️ Tech Stack

- **Frontend:** React + Vite + TailwindCSS  
- **Backend:** Django REST Framework  
- **Base de Datos:** MySQL  
- **Contenedores:** Docker + Docker Compose  
- **Servidor de Frontend:** Nginx  
- **ORM:** Django ORM  
- **Gestión de estado:** React hooks + Context API (o Redux si aplica)

---

## 🚀 Instalación y ejecución local

### Requisitos

- Docker & Docker Compose instalados  
- Git

### Clonar el repositorio

```bash
git clone https://github.com/tuusuario/audiostore.git
cd audiostore
```

### Levantar los contenedores

```bash
docker-compose up --build
```

Esto iniciará:

- El backend en `http://localhost:8000`
- El frontend en `http://localhost:3000`
- La base de datos MySQL en el contenedor interno

### Migraciones iniciales (si necesario)

```bash
docker exec -it django_backend python manage.py migrate
```

---

## ✨ Cómo contribuir

¡Contribuciones bienvenidas! Para colaborar:

1. Forkeá el proyecto
2. Creá una nueva rama (`git checkout -b feature/tu-feature`)
3. Hacé tus cambios y commiteá (`git commit -m 'feat: añadí una nueva funcionalidad'`)
4. Hacé push a tu rama (`git push origin feature/tu-feature`)
5. Abrí un Pull Request explicando tu aporte

Asegurate de seguir la estructura del código y dejar comentarios claros.

---

## 📊 Métricas técnicas

Cada producto incluye datos como:

- **Respuesta de frecuencia (Hz)**: ayuda a entender el rango de sonidos que puede reproducir el dispositivo.
- **Sensibilidad (dB SPL)**: mide qué tan fuerte puede sonar.
- **Impedancia (Ω)**: afecta la compatibilidad con amplificadores o teléfonos.
- **Tamaño de driver (mm)**, **peso**, **conectividad**, etc.

Estas métricas permiten a los usuarios hacer comparaciones técnicas rápidas y objetivas.

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Consultá el archivo [LICENSE](./LICENSE) para más detalles.

---
