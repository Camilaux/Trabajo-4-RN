# 📚 Trabajo 04: Construcción de un Generador de Contenido Educativo basado en LLM

## 📖 Descripción General  
Este proyecto desarrolla un agente basado en modelos de lenguaje (LLMs) que asiste en la generación de contenido educativo a partir de programas de curso universitario. El agente es capaz de analizar documentos en múltiples formatos y generar materiales didácticos estructurados para facilitar la enseñanza y el aprendizaje.  

## 🫂 Integrantes
- Maria Camila Zapata
- Anna Ospina Bedoya
- Jose Daniel Londoño


## 🚀 Funcionalidades  
- Procesamiento de documentos en formatos PDF, TXT y DOCX  
- Generación automática de materiales educativos:  
  - 📖 Notas de clase  
  - ❓ Problemas de práctica con soluciones  
  - 🗣️ Preguntas para discusión  
  - 🎯 Objetivos de aprendizaje  
  - 📚 Recomendaciones de lectura y recursos  
- Evaluación del contenido generado mediante métricas de calidad  
- Implementación de estrategias de ingeniería de prompts  

## 🏗️ Tecnologías Utilizadas  
- **Lenguaje**: Python  
- **Procesamiento de documentos**: LangChain, PyPDFLoader
- **Vectorización**: HuggingFace Embeddings, ChromaDB  
- **Entorno de ejecución**: PyTorch  
- **Manejo de entorno**: dotenv  

## 📋 Instalación y Configuración  

### 1️⃣ Clonar el Repositorio  
```bash
git clone https://github.com/Camilaux/Trabajo-4-RN/
cd Trabajo-4-RN
```

### 2️⃣ Crear un Entorno Virtual (Opcional)  
```bash
python -m .venv venv
source .venv/bin/activate  # En macOS/Linux
.venv\Scripts\activate  # En Windows
```

### 3️⃣ Instalar Dependencias  
```bash
pip install -r requirements.txt
```

### 4️⃣ Configurar Variables de Entorno  
Crea un archivo `.env` en la raíz del proyecto y añade las claves del GOOGLE_API_KEY de gemini

### 5️⃣ Ejecutar el Proyecto  
```bash
python main.py
```

## 📊 Evaluación del Sistema  
1. **Evaluación automática**:  
   - Relevancia del contenido  
   - Consistencia de información  
   - Legibilidad y comprensión  
   - Uso correcto de terminología específica  

## 📅 Roadmap  
- ✅ Procesamiento de documentos  
- ✅ Generación de contenido educativo  
- 🔄 Evaluación de calidad  
- 🔜 Optimización del pipeline  
- 🔜 Integración con nuevas fuentes de datos

Para detalles adicionales, consulta la documentación en el siguiente enlace: [Notion del Proyecto](https://www.notion.so/Trabajo-02-Modelos-de-riesgo-de-cr-dito-con-RNA-180ff1977f418058bc45c9316e160abf)
