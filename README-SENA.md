# Sistema de Reportes Sistematizados - SENA

## Descripción General
Sistema automatizado para la gestión de reportes de juicios evaluativos en la transición de aprendices del SENA desde la etapa lectiva hacia la etapa productiva.

## Características Principales

### 1. Dashboard
- Vista general del estado de los reportes
- Estadísticas en tiempo real
- Progreso de documentación
- Reportes recientes

### 2. Gestión de Reportes
- Filtros avanzados por ficha, instructor y estado
- Búsqueda por nombre de aprendiz
- Exportación a Excel y PDF
- Generación masiva de reportes

### 3. Lista de Chequeo Digital
- Validación de documentación requerida
- Seguimiento de progreso por aprendiz
- Documentos obligatorios y opcionales
- Generación automática de actas

### 4. Configuración
- Integración con OneDrive
- Notificaciones personalizadas
- Configuración de formatos de exportación
- Auditoría de acciones

## Tecnologías Utilizadas
- **Frontend**: Next.js 15, React 19, TypeScript
- **UI Framework**: Tailwind CSS, shadcn/ui
- **Estado**: React Hooks
- **Estilos**: CSS personalizado con colores SENA

## Colores Institucionales SENA
- **Primario**: #0066CC (Azul SENA)
- **Secundario**: #FF6600 (Naranja SENA)
- **Éxito**: #00A651 (Verde)
- **Advertencia**: #FFB81C (Amarillo)
- **Error**: #E60000 (Rojo)

## Instalación y Configuración

### Requisitos Previos
- Node.js 18+ 
- npm o yarn

### Instalación
```bash
npm install
```

### Desarrollo
```bash
npm run dev
```

### Construcción
```bash
npm run build
```

## Estructura del Proyecto
```
src/
├── app/
│   ├── globals.css          # Estilos globales
│   ├── globals-sena.css     # Estilos personalizados SENA
│   ├── layout.tsx          # Layout principal
│   └── page.tsx            # Página principal
├── components/
│   ├── app-sidebar.tsx     # Barra lateral de navegación
│   ├── header.tsx          # Encabezado
│   ├── dashboard.tsx       # Vista dashboard
│   ├── reports.tsx         # Vista de reportes
│   ├── checklist.tsx       # Vista de lista de chequeo
│   └── settings.tsx        # Vista de configuración
└── components/ui/          # Componentes UI de shadcn
```

## Funcionalidades por Sprint

### Sprint 1 - MVP
- ✅ Dashboard con estadísticas
- ✅ Lista de reportes con filtros
- ✅ Lista de chequeo digital
- ✅ Configuración básica

### Sprint 2 - Integración
- 🔄 Integración con OneDrive
- 🔄 Sincronización automática
- 🔄 Exportación de reportes

### Sprint 3 - Automatización
- 🔄 Descarga automática desde Sofía Plus
- 🔄 Generación automática de actas
- 🔄 Notificaciones inteligentes

## Equipo de Desarrollo
- **Product Owner**: Kevin Espinel
- **Scrum Master**: George Lemus
- **Desarrolladores**: Juan Jácome, Cristian Pérez, Emerson Velásquez

## Seguridad y Auditoría
- Registro de todas las acciones
- Auditoría de cambios
- Control de acceso por roles
- Encriptación de datos sensibles

## Soporte
Para soporte técnico o consultas sobre el sistema, contactar al equipo de desarrollo.

## Licencia
Este sistema es propiedad del SENA y está diseñado exclusivamente para uso institucional.
