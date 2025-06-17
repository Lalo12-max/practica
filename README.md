# Práctica - Landing Page con GitHub Pages

Proyecto de práctica que implementa una landing page con React y deployment automático usando GitHub Actions.

## Descripción del proyecto

Este proyecto demuestra la implementación de un flujo de trabajo completo de desarrollo web moderno, desde la creación de la aplicación hasta su deployment automático en GitHub Pages.

## Proceso de desarrollo

### 1. Desarrollo de la aplicación
- Aplicación React con componentes modernos
- Diseño responsivo y optimizado
- Estructura de proyecto escalable
- Configuración de build para producción

### 2. Control de versiones
- Repositorio en GitHub con historial completo
- Configuración de ramas 
- Gestión de commits y versionado

### 3. CI/CD con GitHub Actions
- Workflow automatizado para deployment
- Pipeline que incluye:
  - Checkout del código
  - Instalación de dependencias
  - Build de la aplicación
  - Deploy a GitHub Pages
- Configuración de permisos y tokens

### 4. Resultado
- Deployment automático en cada push
- Sitio web disponible 24/7
- Tiempo de deployment: ~2 minutos
- URL estable y accesible públicamente

## Enlaces

- **Repositorio**: https://github.com/Lalo12-max/practica
- **Sitio web**: https://lalo12-max.github.io/practica/
- **Actions**: Ver historial de deployments en la pestaña Actions

## Flujo de trabajo

1. Desarrollo local con `npm start`
2. Commit y push de cambios
3. GitHub Actions ejecuta el workflow automáticamente
4. Aplicación actualizada disponible en producción

## Stack tecnológico

- **Frontend**: React, HTML5, CSS3, JavaScript ES6+
- **Build**: Node.js, npm
- **CI/CD**: GitHub Actions
- **Hosting**: GitHub Pages
- **Control de versiones**: Git, GitHub

## Instalación local

```bash
git clone https://github.com/Lalo12-max/practica.git
cd practica
npm install
npm start```