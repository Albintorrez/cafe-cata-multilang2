# Cafe Cata Platform (Multilenguaje)

Plataforma para productores, tostadores y compradores de café.  
Incluye frontend (React/Vite) y backend (FastAPI).

## Deploy

### Backend (Render)
1. Subir este repositorio a GitHub.
2. Crear un **Web Service** en Render.
3. Configurar:
   - Language: Python
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `uvicorn backend.main:app --host 0.0.0.0 --port 10000`
   - Root Directory: `.`

### Frontend (Vercel)
1. Conectar la carpeta `Interfaz/` en Vercel.
2. Framework: Vite.
3. Build Command: `npm run build`
4. Output: `dist`
