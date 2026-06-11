# ChatApp

Aplicación de chat desarrollada en **C#/.NET** con arquitectura **MVVM** y comunicación cliente-servidor.

El proyecto está orientado a practicar el desarrollo de aplicaciones de escritorio en Windows, separación de responsabilidades con MVVM y comunicación entre componentes de red.

## Tecnologías utilizadas

- C#
- .NET 8
- WPF / Windows Desktop
- MVVM
- Cliente-servidor
- Networking

## Funcionalidades principales

- Interfaz de escritorio para chat.
- Organización del código usando patrón MVVM.
- Separación entre vistas, modelos y lógica de presentación.
- Comunicación cliente-servidor.
- Estructura base para mensajería en red.

## Estructura del proyecto

```txt
ChatApp/
├── MVVM/              # Estructura basada en Model-View-ViewModel
├── Net/               # Comunicación de red / cliente-servidor
├── App.xaml
├── App.xaml.cs
├── ChatApp.sln
├── ChatClient.csproj
└── README.md
```

## Instalación y ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/Hhurtadoabcx/ChatApp.git
cd ChatApp
```

### 2. Restaurar dependencias

```bash
dotnet restore
```

### 3. Ejecutar el proyecto

```bash
dotnet run
```

> Si el proyecto requiere iniciar servidor y cliente por separado, documenta aquí el orden exacto de ejecución.

## Estado del proyecto

Proyecto académico orientado a practicar aplicaciones de escritorio con C#/.NET, arquitectura MVVM y comunicación cliente-servidor.

## Aprendizajes

- Aplicación de arquitectura MVVM.
- Organización de una app de escritorio.
- Comunicación cliente-servidor.
- Manejo de estructura de proyectos en .NET.
- Separación entre interfaz, estado y lógica.
