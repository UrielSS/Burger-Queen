# 🍔 Burger Queen

## 📖 Descripción

**Burger Queen** es una aplicación móvil desarrollada con **Ionic 7**, diseñada para gestionar pedidos en un restaurante de comida rápida. Ofrece una interfaz intuitiva que permite a los usuarios realizar pedidos, procesar pagos a través de **Stripe** y administrar eficientemente la información del restaurante.

---

## ✨ Características Principales

- **Gestión de Pedidos**: Interfaz amigable para la creación y seguimiento de pedidos.
- **Procesamiento de Pagos**: Integración con **Stripe** para pagos seguros y rápidos.
- **Autenticación de Usuarios**: Sistema de inicio de sesión confiable.
- **Base de Datos**: Almacenamiento eficiente de información relevante.
- **Multiplataforma**: Compatible con dispositivos **iOS** y **Android**.
- **Funcionalidades Nativas**: Uso de **Capacitor** para acceso a funciones del dispositivo.

---

## 🛠️ Tecnologías Utilizadas

- **Ionic 7**: Framework para desarrollo de aplicaciones móviles híbridas.
- **Angular**: Framework frontend para construir interfaces modernas.
- **Capacitor**: Herramienta para acceder a funcionalidades nativas.
- **Stripe**: Plataforma de procesamiento de pagos.
- **TypeScript**: Lenguaje tipado que mejora la calidad del código.

---

## 📱 Capturas de Pantalla


---

## 🚀 Instalación y Configuración

### 🔧 Prerrequisitos

- Node.js (v14 o superior)  
- npm (v6 o superior)  
- Ionic CLI  
  ```bash
  npm install -g @ionic/cli
  ```
- Cuenta activa en [Stripe](https://stripe.com) para procesar pagos

### 📦 Pasos de Instalación

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/UrielSS/Burger-Queen.git
   cd Burger-Queen
   ```

2. **Instala las dependencias:**
   ```bash
   npm install
   ```

3. **Configura las variables de entorno:**
   Crea un archivo `.env` en la raíz del proyecto con el siguiente contenido:

   ```env
   publishKey=tu_clave_publica
   secretKey=tu_clave_secreta
   ```

4. **Inicia la aplicación en modo desarrollo:**
   ```bash
   ionic serve -o
   ```

---

## 📲 Compilación para Plataformas Móviles

### 📱 Android

```bash
ionic build
ionic cap add android
ionic cap copy android
ionic cap sync android
ionic cap open android
```

### 🍏 iOS

```bash
ionic build
ionic cap add ios
ionic cap copy ios
ionic cap sync ios
ionic cap open ios
```

> ⚠️ *Para compilar en iOS necesitas macOS y Xcode instalado.*

---

## 📋 Uso de la Aplicación

1. **Inicio de Sesión**: Accede con tus credenciales.
2. **Panel Principal**: Consulta pedidos activos y su estado.
3. **Crear Pedido**: Selecciona productos y registra la información del cliente.
4. **Procesar Pago**: Finaliza el pedido usando Stripe para el cobro.
