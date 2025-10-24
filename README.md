📊 Análisis de Datos de Alumnos

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![Node.js](https://img.shields.io/badge/Node.js--green)
![HTML5](https://img.shields.io/badge/HTML5-orange)

Sistema para análisis y consulta de datos de alumnos utilizando JavaScript, JSON y una interfaz web interactiva.

## Características

- 00 registros** de alumnos con datos realistas
- **4 consultas diferentes** predefinidas
- **Interfaz web** responsive y moderna
- **Estadísticas** en tiempo real
- **Múltiples formatos** de salida (JSON, HTML, Console)

## Estructura del Proyecto
proyecto-alumnos/
├── README.md # Esta documentación
├── alumnos.json # Datos de 200 alumnos
├── consultas.js # Script de consultas en Node.js
├── index.html # Interfaz web interactiva
└── package.json # Configuración del proyecto

## Instalación y Uso

### Prerrequisitos
- Node.js (v14 o superior)
- Navegador web moderno

### Versión Consola (Node.js)
```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/proyecto-alumnos.git

# Navegar al directorio
cd proyecto-alumnos

# Ejecutar consultas
node consultas.js

# Abrir en navegador
open index.html
# o simplemente hacer doble clic en index.html
Consultas Disponibles
Alumnos de IDM - Filtra por carrera "IDM"

ISC de Yucatán - Filtra por carrera "ISC" y estado "Yucatan"

Todas las Alumnas - Filtra por género "Female"

ID y Nombre Completo - Transforma datos para mostrar información específica

Consulta desde JavaScript

// Filtrar alumnos de IDM
const alumnosIDM = alumnos.filter(alumno => alumno.carrera === "IDM");
console.log(`Total de alumnos IDM: ${alumnosIDM.length}`);}

Estructura de Datos
{
  "id": 1,
  "first_name": "Juan",
  "last_name": "Pérez",
  "gender": "Male",
  "estado": "Yucatan",
  "carrera": "ISC"
}

Estadísticas del Dataset
Total de registros: 200 alumnos

Distribución por género: 100 hombres / 100 mujeres

Carreras: ISC, ICO, ITCC, IDM (50 alumnos cada una)

Estados: Yucatán, Campeche, Chiapas, Tabasco (50 alumnos cada uno)

Tecnologías Utilizadas
JavaScript (ES6+)

HTML5 & CSS3

Node.js

JSON

Git & GitHub
