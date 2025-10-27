# TestBotCypress - Automatización con Behave y Selenium

Proyecto de automatización de pruebas usando Behave (BDD) y Selenium WebDriver.

## 📋 Descripción

Este proyecto automatiza el proceso de registro de usuarios usando la metodología BDD (Behavior-Driven Development) con Behave y Selenium.

## 🚀 Características

- ✅ Framework BDD con Behave
- ✅ Selenium WebDriver para automatización de navegador
- ✅ Page Object Model para mejor mantenibilidad
- ✅ Manejo robusto de errores
- ✅ Screenshots automáticos en cada escenario
- ✅ Validación de variables de entorno
- ✅ Documentación completa en código

## 📦 Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/danigonzalez21201/Cypress.git
cd TestBotCypress
```

2. Instalar dependencias:
```bash
pip install -r requirements.txt
```

3. Crear archivo `.env` con las siguientes variables:
```env
URL=https://tu-url.com
EMPRESA=Nombre de Empresa
CORREO=correo@email.com
CLAVE=TuPassword
NOMBRE=Nombre
APELLIDO=Apellido
```

## 🎯 Ejecución

Ejecutar las pruebas con:
```bash
behave
```

## 📁 Estructura del Proyecto

```
TestBotCypress/
├── features/
│   ├── environment.py      # Configuración de entorno de Behave
│   ├── registro.feature    # Definición de escenarios BDD
│   ├── pages/
│   │   ├── Metodos.py      # Métodos de interacción con la página
│   │   └── Objetos.py      # Selectores de elementos
│   └── steps/
│       └── registro_page.py # Definición de steps
├── requirements.txt        # Dependencias del proyecto
└── .gitignore             # Archivos ignorados por git
```

## 📝 Dependencias

- `behave==1.2.6` - Framework BDD
- `selenium==4.15.0` - Automatización web
- `webdriver-manager==4.0.1` - Gestión de drivers
- `python-dotenv==1.0.0` - Variables de entorno

## ✨ Mejoras Implementadas

- ✅ Limpieza de imports duplicados
- ✅ Manejo robusto de errores
- ✅ Validación de variables de entorno
- ✅ Documentación mejorada
- ✅ Click con fallback a JavaScript
- ✅ Organización de código mejorada
- ✅ Screenshots con paths seguros

## 🔧 Autor

danigonzalez21201

