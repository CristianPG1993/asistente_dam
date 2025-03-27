# 🎓 Asistente Virtual por Asignatura – FP DAM

Este proyecto es un asistente virtual personalizado para cada asignatura del ciclo formativo **Desarrollo de Aplicaciones Multiplataforma (DAM)**. A partir del contenido proporcionado por los profesores (PDF/TXT), la IA es capaz de responder preguntas específicas usando procesamiento de lenguaje natural.

---

## 🧠 Objetivo del proyecto

- Crear una herramienta real y útil para estudiantes y profesores del FP DAM.
- Desarrollar el backend y frontend desde cero, paso a paso.
- Integrar Inteligencia Artificial sin coste usando embeddings locales.
- Aplicar una arquitectura limpia y escalable.

---

## 🚀 Tecnologías utilizadas

| Parte         | Tecnología                |
|---------------|---------------------------|
| Backend       | Python + FastAPI          |
| IA (embeddings) | Sentence-Transformers + FAISS |
| Lectura de PDF| pdfplumber                |
| Frontend      | React (en desarrollo)     |
| DB            | SQLite / PostgreSQL (próxima fase) |
| Control de versiones | Git + GitHub       |

---

## 📂 Estructura del proyecto

asistente_dam/ ├── backend/ │ ├── main.py │ ├── docs/ # PDFs/TXT por asignatura │ ├── services/ # Lógica: lectura, embeddings, chunks │ ├── routers/ # Endpoints de API (futuro) │ ├── vector_store/ # Vectores generados │ └── models/ # Esquemas (futuro) ├── frontend/ # Interfaz web (futuro) ├── requirements.txt └── README.md


---

## 🧩 Fases del proyecto

### ✅ Fase 1: Preparación del entorno
- [x] Crear estructura de carpetas
- [x] Crear entorno virtual y archivo `.gitignore`
- [x] Subir repositorio a GitHub

### ✅ Fase 2: Organización por asignatura
- [x] Crear carpetas por asignatura
- [x] Añadir documentos de ejemplo (PDF o TXT)

### 🔄 Fase 3: Lector de documentos
- [ ] Leer cada archivo por asignatura
- [ ] Extraer texto desde PDF
- [ ] Devolver lista con textos organizados

### 🔄 Fase 4: División en chunks
- [ ] Dividir los textos en fragmentos útiles
- [ ] Preparar para generar embeddings

### 🔄 Fase 5: Generación y almacenamiento de embeddings
- [ ] Generar embeddings locales con `sentence-transformers`
- [ ] Almacenar con FAISS

### 🔄 Fase 6: Búsqueda semántica y generación de respuestas
- [ ] Buscar el fragmento más relevante ante una pregunta
- [ ] Generar respuesta con IA contextualizada

### 🔄 Fase 7: Desarrollo del frontend
- [ ] Chat básico con React
- [ ] Selección de asignatura
- [ ] Visualización de respuestas

### 🔒 Fase 8: Seguridad y autenticación (futura)
- [ ] Separación de roles (profesor, alumno)
- [ ] Protección de rutas

### 📊 Fase 9: Funcionalidades extra (futuras mejoras)
- [ ] Feedback del alumno (“Me ayudó / No entendí”)
- [ ] Historial de preguntas por usuario
- [ ] Subida de documentos vía web (panel profe)
- [ ] Exportar modelo entrenado
- [ ] Generador de tests automáticos por IA (bonus)

---

## 🧑‍💻 Autor

**Cristian Paños**  
Estudiante de DAM y apasionado del desarrollo eficiente y de la Inteligencia Artificial aplicada a la educación.

GitHub: [CristianPG1993](https://github.com/CristianPG1993)

---

## 📜 Licencia

Este proyecto está bajo licencia MIT.  
Puedes reutilizarlo, modificarlo y adaptarlo con fines personales, educativos o comerciales.

---

## ⭐ ¿Te gusta la idea?

Dale una ⭐ en GitHub y sigue el progreso.  
Este proyecto está siendo desarrollado paso a paso, con enfoque educativo y con estructura escalable.
