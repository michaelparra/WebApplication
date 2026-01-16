# Barismo & Café Especialidad - Web Application

Sitio web completo sobre barismo y café de especialidad, orientado a emprendedores que desean iniciar un food truck de café en Chile.

## Descripción

Este sitio web está construido con **ASP.NET Core** (Razor Pages) y proporciona información completa sobre:

- **Café de Especialidad**: Guías sobre granos, tueste, preparación y máquinas
- **Recetas y Prácticas**: Recetas profesionales y buenas prácticas de barismo
- **Manejo de Alimentos**: Normas y prácticas para manipulación segura de alimentos
- **Emprendimiento en Chile**: Permisos sanitarios, impuestos, licencias y consideraciones para food truck

## Tecnologías Utilizadas

- **ASP.NET Core 8.0** (Razor Pages)
- **Bootstrap 5** (UI Framework)
- **jQuery** (JavaScript)
- **C#** (.NET 8.0)

## Estructura del Proyecto

```
WebApplication/
├── Pages/
│   ├── Index.cshtml                    # Página principal
│   ├── Recetas.cshtml                  # Recetas de café
│   ├── BuenasPracticas.cshtml          # Buenas prácticas de barismo
│   ├── ManejoAlimentos.cshtml          # Manejo seguro de alimentos
│   ├── CafeEspecialidad.cshtml         # Café de especialidad
│   ├── Granos.cshtml                   # Granos de café
│   ├── Tueste.cshtml                   # Tueste de café
│   ├── Preparacion.cshtml              # Preparación de café
│   ├── MaquinasCafe.cshtml             # Máquinas de café
│   ├── FoodTruck.cshtml                # Food truck móvil
│   ├── PermisosSanitarios.cshtml       # Permisos sanitarios (Chile)
│   ├── Permisos.cshtml                 # Permisos y licencias (Chile)
│   ├── Impuestos.cshtml                # Impuestos y obligaciones (Chile)
│   └── Shared/
│       └── _Layout.cshtml              # Layout principal
├── wwwroot/
│   ├── css/
│   │   └── site.css                     # Estilos personalizados
│   └── lib/                              # Librerías (Bootstrap, jQuery)
├── Program.cs                            # Configuración de la aplicación
└── WebApplication3.csproj                # Archivo de proyecto
```

## Páginas del Sitio

### Café & Técnicas
- **Café de Especialidad**: Información sobre café de especialidad y mercado en Chile
- **Granos**: Guía sobre especies, variedades y selección de granos
- **Tueste**: Proceso de tueste y niveles de tueste
- **Preparación**: Métodos y técnicas de preparación profesional
- **Máquinas de Café**: Equipamiento y consideraciones para food truck

### Recetas & Prácticas
- **Recetas**: Recetas profesionales (Espresso, Cappuccino, V60, Cold Brew, etc.)
- **Buenas Prácticas**: Principios fundamentales del barismo
- **Manejo de Alimentos**: Normas sanitarias y prácticas seguras

### Emprendimiento
- **Food Truck Móvil**: Guía completa para establecer un food truck
- **Permisos Sanitarios**: Requisitos y proceso de obtención en Chile
- **Permisos y Licencias**: Todos los permisos necesarios
- **Impuestos**: Obligaciones tributarias en Chile

## Requisitos

- **.NET 8.0 SDK** o superior
- **Visual Studio 2022** o **Visual Studio Code** (opcional)
- **Navegador web moderno**

## Instalación y Ejecución

1. **Clonar o descargar el proyecto**

2. **Restaurar dependencias** (si es necesario):
   ```bash
   dotnet restore
   ```

3. **Ejecutar la aplicación**:
   ```bash
   dotnet run
   ```

4. **Abrir en el navegador**:
   - La aplicación se ejecutará en `https://localhost:5001` o `http://localhost:5000`
   - Consulta la consola para la URL exacta

## Características

- ✅ Diseño responsive (móvil, tablet, desktop)
- ✅ Navegación intuitiva con menús desplegables
- ✅ Contenido completo sobre barismo y café
- ✅ Información específica para Chile (permisos, impuestos)
- ✅ Guías prácticas para food truck
- ✅ Estilos personalizados con tema de café

## Notas Importantes

- **Información Legal**: La información sobre permisos, impuestos y regulaciones es una guía general. Siempre consulta con profesionales y autoridades competentes para tu situación específica.
- **Imágenes**: El sitio utiliza placeholders para imágenes. Se recomienda agregar imágenes reales relacionadas con café/barismo sin derechos de autor.
- **Precios**: Los precios mencionados son estimados y pueden variar según la región y condiciones del mercado.

## Licencia

Este proyecto es de código abierto y está disponible para uso educativo y comercial.

## Autor

Desarrollado como guía completa para emprendedores del café en Chile.

## Recursos Adicionales

- [ASP.NET Core Documentation](https://learn.microsoft.com/aspnet/core)
- [Ministry of Health Chile](https://www.minsal.cl)
- [SII Chile](https://www.sii.cl)
- [Specialty Coffee Association](https://sca.coffee)

---

**Nota**: Este sitio web está diseñado como una guía informativa. Para asesoría legal, tributaria o sanitaria específica, siempre consulta con profesionales calificados.
