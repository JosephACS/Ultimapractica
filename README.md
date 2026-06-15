<div align="center">

# 📱 ActionBar, ToolBar, FloatingActionButton y Navigation Drawer

### Aplicación Android desarrollada en Kotlin utilizando Material Design

<br>

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)
![Material Design](https://img.shields.io/badge/Material%20Design-757575?style=for-the-badge&logo=materialdesign&logoColor=white)
![Navigation Drawer](https://img.shields.io/badge/Navigation%20Drawer-4285F4?style=for-the-badge)
![Fragments](https://img.shields.io/badge/Fragments-FF9800?style=for-the-badge)

</div>

---

# 📖 Descripción

Este proyecto fue desarrollado para la asignatura de **Aplicaciones Móviles**.

La aplicación implementa componentes fundamentales de Android utilizando **Material Design**, permitiendo al usuario interactuar mediante una barra de navegación superior, menú lateral, botones flotantes y navegación dinámica mediante Fragments.

---

# 🚀 Funcionalidades

✅ ActionBar personalizada

✅ ToolBar con menú de opciones

✅ Floating Action Button (FAB)

✅ Navigation Drawer

✅ NavigationView

✅ Cabecera personalizada

✅ Fragments dinámicos

✅ Toast Messages

✅ Material Design Components

---

# 🛠 Tecnologías Utilizadas

| Tecnología | Uso |
|------------|-----|
| 🤖 Android | Plataforma móvil |
| 🟣 Kotlin | Lenguaje principal |
| 🟢 Android Studio | Entorno de desarrollo |
| 🎨 Material Design | Diseño de interfaz |
| 📑 NavigationView | Menú lateral |
| 🧩 Fragments | Navegación dinámica |
| ➕ Floating Action Button | Acciones rápidas |
| 📂 DrawerLayout | Menú desplegable |

---

# 📦 Dependencias

```gradle
dependencies {

    implementation 'androidx.appcompat:appcompat:1.1.0'

    implementation 'com.google.android.material:material:1.0.0'

    implementation 'de.hdodenhof:circleimageview:3.0.1'

}
```

---

# 🏗 Estructura del Proyecto

```text
app
│
├── java
│   ├── MainActivity.kt
│   ├── FragmentClientes.kt
│   ├── FragmentUsuarios.kt
│   └── FragmentPedidos.kt
│
├── res
│   ├── layout
│   │   ├── activity_main.xml
│   │   ├── cabecera.xml
│   │   ├── fragment_clientes.xml
│   │   ├── fragment_usuarios.xml
│   │   └── fragment_pedidos.xml
│   │
│   ├── menu
│   │   ├── menu1.xml
│   │   └── menu2.xml
│   │
│   ├── drawable
│   │   ├── iconmenu
│   │   ├── iconnuevo
│   │   ├── iconbuscar
│   │   ├── iconsettings
│   │   └── user
│   │
│   └── values
│       └── styles.xml
│
└── AndroidManifest.xml
```

---

# 📋 Componentes Implementados

## 🔹 ActionBar y ToolBar

Se implementó una ToolBar personalizada reemplazando la ActionBar tradicional.

Características:

- Título personalizado.
- Ícono de navegación.
- Menú superior.
- Compatibilidad con Material Design.

---

## 🔹 Menú de Opciones

Opciones implementadas:

- Nuevo
- Buscar
- Configuración

Cada opción muestra una notificación mediante Toast.

---

## 🔹 Floating Action Button (FAB)

Se agregó un botón flotante ubicado en la esquina inferior derecha.

Acción:

```kotlin
fun onClickFAB(view: View) {
    Toast.makeText(
        this,
        "Floating Action Button Clicked",
        Toast.LENGTH_SHORT
    ).show()
}
```

---

## 🔹 Navigation Drawer

Implementado mediante:

- DrawerLayout
- NavigationView
- Toolbar

Permite mostrar un menú lateral deslizable.

---

## 🔹 Cabecera Personalizada

La cabecera contiene:

- Imagen de fondo.
- Imagen de perfil circular.
- Nombre del usuario.

Implementada utilizando:

```gradle
implementation 'de.hdodenhof:circleimageview:3.0.1'
```

---

## 🔹 Fragments

La navegación entre secciones se realiza mediante Fragments.

Funciones:

- Carga dinámica de pantallas.
- Actualización automática del título.
- Cierre automático del menú lateral.

---

# 📸 Capturas de Pantalla

## 🏠 Pantalla Principal

![Pantalla Principal](images/principal.png)

---

## 📑 Menú Superior

![Menu Superior](images/menu_superior.png)

---

## ➕ Floating Action Button

![FAB](images/fab.png)

---

## 📂 Navigation Drawer

![Navigation Drawer](images/navigation_drawer.png)

---

## 🧩 Fragment Sección 1

![Fragment 1](images/fragment1.png)

---

## 🧩 Fragment Sección 2

![Fragment 2](images/fragment2.png)

---

## 🧩 Fragment Sección 3

![Fragment 3](images/fragment3.png)

---

# 🎥 Demostración

Agregar un GIF mostrando el funcionamiento de la aplicación:

```markdown
![Demo](images/demo.gif)
```

---

# ▶️ Instalación

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/usuario/repositorio.git
```

### 2️⃣ Abrir en Android Studio

Abrir la carpeta del proyecto.

### 3️⃣ Sincronizar Gradle

Esperar que Android Studio descargue las dependencias.

### 4️⃣ Ejecutar

Conectar un dispositivo físico o iniciar un emulador.

---

# 🎯 Resultados Obtenidos

- Implementación correcta de Material Design.
- Navegación mediante Navigation Drawer.
- Uso de Floating Action Button.
- Gestión de Fragments.
- Personalización de ToolBar y ActionBar.
- Integración de componentes modernos de Android.

---

# 👨‍💻 Autor

### Joan Calderón

**Ingeniería de Software**

Universidad Técnica Estatal de Quevedo (UTEQ)

Asignatura: Aplicaciones Móviles

Docente: Cristian Zambrano Vega, PhD

---

<div align="center">

⭐ Proyecto académico desarrollado en Android Studio y Kotlin ⭐

</div>
