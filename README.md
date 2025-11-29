# Sistema de Gestión de Tareas

Una aplicación web completa desarrollada con **ASP.NET Core MVC** para la gestión personal de tareas con autenticación de usuarios y funcionalidades CRUD completas.

## 🚀 Características Principales

- **🔐 Autenticación Segura**: Sistema de registro e inicio de sesión con hash de contraseñas
- **📝 Gestión Personal de Tareas**: Cada usuario tiene su propia lista privada de tareas
- **✅ Operaciones CRUD Completas**: 
  - Crear nuevas tareas
  - Ver lista de tareas
  - Actualizar tareas existentes
  - Eliminar tareas
- **🎯 Sistema de Prioridades**: Clasificación en Alta, Media y Baja prioridad
- **🔍 Filtrado Avanzado**:
  - Por estado: Pendientes, Completadas
  - Por prioridad: Alta, Media, Baja
- **📊 Ordenamiento Múltiple**: Por prioridad, fecha de vencimiento, fecha creación o título
- **📅 Fechas de Vencimiento**: Establecer fechas límite para las tareas
- **🎨 Interfaz Responsive**: Diseño moderno con Bootstrap 5 que se adapta a todos los dispositivos

## 🛠️ Tecnologías Utilizadas

- **Backend**: ASP.NET Core 6.0, Entity Framework Core
- **Frontend**: Bootstrap 5, Font Awesome, HTML5, CSS3
- **Base de Datos**: SQLite
- **Autenticación**: Sesiones con hash SHA256
- **Patrón**: Modelo-Vista-Controlador (MVC)

## 📦 Instalación y Ejecución


1. **Restaurar dependencias**
   ```bash
   dotnet restore
   ```

2. **Ejecutar la aplicación**
   ```bash
   dotnet run
   ```

3. **Abrir en el navegador**
   ```
   https://localhost:7000
   ```

## 🗂️ Estructura del Proyecto

```
TodoApp/
├── Controllers/          # Controladores MVC (Auth, Todo)
├── Models/               # Modelos (User, TodoItem)
├── Views/                # Vistas Razor
├── Services/             # Lógica de negocio (AuthService, TodoService)
├── Data/                 # Contexto de BD (ApplicationDbContext)
└── wwwroot/              # Archivos estáticos
```

## 👤 Funcionalidades de Usuario

### Autenticación
- Registro de nuevos usuarios con validación
- Inicio de sesión seguro
- Gestión de sesiones automática
- Cierre de sesión

### Gestión de Tareas
- Crear tareas con título, descripción, prioridad y fecha opcional
- Marcar/desmarcar como completadas
- Editar todos los campos de las tareas
- Eliminar con confirmación
- Visualización con colores por prioridad
- Indicadores visuales de estado

## 🎮 Uso de la Aplicación

1. **Registro/Login**: Crear cuenta o iniciar sesión
2. **Dashboard**: Ver todas las tareas en tarjetas organizadas
3. **Filtros**: Usar dropdowns para filtrar por estado o prioridad
4. **Ordenar**: Cambiar el orden de visualización
5. **Acciones**: Usar botones para completar, editar o eliminar
6. **Nueva Tarea**: Botón "+ Nueva Tarea" para agregar

## 🔒 Seguridad

- Contraseñas hasheadas con SHA256
- Sesiones por usuario
- Aislamiento de datos entre usuarios
- Validación de entrada en servidor y cliente

## 📱 Compatibilidad

- ✅ Desktop (Windows, Mac, Linux)
- ✅ Tablets
- ✅ Smartphones
- ✅ Navegadores modernos (Chrome, Firefox, Safari, Edge)

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crear una rama feature (`git checkout -b feature/AmazingFeature`)
3. Commit cambios (`git commit -m 'Add AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abrir un Pull Request



