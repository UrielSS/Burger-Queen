# 🍔 Burger Queen

## Descripción
**Burger Queen** es una aplicación móvil desarrollada con **Ionic 7**, diseñada para gestionar pedidos en un restaurante de comida rápida. La aplicación ofrece una interfaz intuitiva que permite a los usuarios realizar pedidos, procesar pagos a través de **Stripe** y gestionar la información del restaurante de manera eficiente.

## ✨ Características Principales

- **Gestión de Pedidos**: Interfaz intuitiva para la creación y seguimiento de pedidos
- **Procesamiento de Pagos**: Integración con Stripe para pagos seguros
- **Autenticación de Usuarios**: Sistema de inicio de sesión seguro 
- **Base de Datos**: Almacenamiento y gestión eficiente de datos
- **Multiplataforma**: Desarrollada con Ionic para funcionar en iOS y Android
- **Funcionalidades Nativas**: Implementación de herramientas de Capacitor para acceso a funciones del dispositivo

## 🛠️ Tecnologías Utilizadas

- **Ionic 7**: Framework para el desarrollo de aplicaciones móviles híbridas
- **Angular**: Framework front-end para crear interfaces de usuario
- **Capacitor**: Acceso a APIs nativas del dispositivo
- **Stripe**: Plataforma de procesamiento de pagos
- **TypeScript**: Lenguaje de programación tipado

## 📱 Capturas de Pantalla


## 🚀 Instalación y Configuración

### Prerrequisitos
- Node.js (v14 o superior)
- npm (v6 o superior)
- Ionic CLI (`npm install -g @ionic/cli`)
- Cuenta de Stripe para la integración de pagos

### Pasos de Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/UrielSS/Burger-Queen.git
cd Burger-Queen
```

2. Instalar dependencias:
```bash
npm install
```

3. Configurar variables de entorno:
   - Crear un archivo `.env` en la raíz del proyecto
   - Añadir las siguientes variables desde tu cuenta de Stripe:
   ```bash
  publishKey: 'tu_clave_publica',
  secretKey: 'tu_clave_secreta',
  ```
  ```
4. Iniciar la aplicación en modo desarrollo:
``` bash
ionic serve -o
```

### Compilación para Plataformas Móviles

#### Android
```bash
ionic build
ionic cap add android
ionic cap copy android
ionic cap sync android
ionic cap open android
```

#### iOS
```bash
ionic build
ionic cap add ios
ionic cap copy ios
ionic cap sync ios
ionic cap open ios
```

## 📋 Uso de la Aplicación

1. **Inicio de Sesión**: Accede con tus credenciales de usuario
2. **Panel Principal**: Visualiza los pedidos activos y su estado
3. **Crear Pedido**: Añade productos al carrito y completa la información del cliente
4. **Procesar Pago**: Utiliza la integración con Stripe para cobrar al cliente

