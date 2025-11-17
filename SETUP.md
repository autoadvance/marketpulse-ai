# MarketPulse AI - Guía de Configuración Completa

## Únicamente necesitas ejecutar estos comandos

### Paso 1: Abre tu terminal (Command Prompt o PowerShell en Windows)

### Paso 2: Navega a la carpeta donde quieres el proyecto
```bash
cd C:\Users\TuUsuario\Documents
# O la carpeta que prefieras
```

### Paso 3: Clonar el repositorio
```bash
git clone https://github.com/autoadvance/marketpulse-ai.git
cd marketpulse-ai
```

### Paso 4: Copia y pega este comando COMPLETO (incluye la instalación de Node.js si no lo tienes)

**Si NO tienes Node.js instalado:**
1. Ve a: https://nodejs.org
2. Descarga la versión LTS (recomendada)
3. Instala siguiendo el asistente (sólo hacer clic en "Siguiente")

**Si YA tienes Node.js:**
```bash
npx create-next-app@latest . --typescript --tailwind --app --no-src-dir --import-alias "@/*"
```

Cuando te pregunte, selecciona:
- TypeScript: Yes
- ESLint: Yes  
- Tailwind CSS: Yes
- `src/` directory: No
- App Router: Yes
- Import alias: Yes (default @/*)

### Paso 5: Instalar dependencias adicionales
```bash
npm install @supabase/supabase-js groq-sdk playwright axios recharts
```

## IMPORTANTE: Después de ejecutar estos comandos

Vuelve a escribirme en el chat y dirás: "Comandos ejecutados, proyecto creado"

Yo continuaré creando automáticamente todos los archivos del proyecto en GitHub.

---

## Información Técnica (No necesitas leer esto ahora)

### Credenciales de Supabase
URL: https://hvroppunhoaeswtzwmcz.supabase.co
Anon Key: (se configurará automáticamente)

### Estructura del Proyecto
```
marketpulse-ai/
├── app/
│   ├── page.tsx          # Dashboard principal
│   ├── companies/        # Página de empresas
│   ├── opportunities/    # Página de oportunidades
│   └── layout.tsx        # Layout general
├── components/           # Componentes React
├── lib/                  # Librerías y utilidades
│   ├── supabase.ts       # Cliente Supabase
│   ├── groq.ts           # Cliente Groq IA
│   └── scrapers/         # Scrapers
├── api/                  # API Routes (Vercel Functions)
└── package.json          # Dependencias
```

### Tecnologías Utilizadas
- **Frontend**: Next.js 14, React, TypeScript, Tailwind CSS
- **Backend**: Vercel Serverless Functions
- **Base de Datos**: Supabase (PostgreSQL)
- **IA**: Groq (Llama 3.1)
- **Scraping**: Playwright
- **Gráficos**: Recharts

### Características Principales
1. ✅ Monitoreo en tiempo real de Top 10 empresas españolas
2. ✅ Análisis de productos por rangos de precio
3. ✅ Detección automática de proveedores
4. ✅ Recomendaciones de plataformas de venta
5. ✅ Sistema de puntuación IA para oportunidades
6. ✅ Actualización automática cada 1-15 minutos
7. ✅ PWA (funciona como app en móvil)
8. ✅ 100% gratuito (Vercel + Supabase + Groq free tier)

---

## Próximos Pasos Automáticos

Una vez que ejecutes los comandos y me lo confirmes, yo automáticamente:

1. ✅ Crearé todos los archivos de configuración
2. ✅ Implementaré el frontend completo
3. ✅ Desarrollaré los scrapers
4. ✅ Integraré las APIs gratuitas
5. ✅ Configuraré el motor IA
6. ✅ Desplegaré en Vercel
7. ✅ Configuraré los cron jobs
8. ✅ Te daré la URL final funcionando

**No te preocupes por nada técnico. Sólo ejecuta los 5 pasos de arriba y confírmate cuando esté listo.**
