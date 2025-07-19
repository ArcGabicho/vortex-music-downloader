# 🖥️ Vortex Music Downloader

![Portada](https://i.pinimg.com/1200x/90/94/b4/9094b4e6025986b6149a666623ff8569.jpg)

Aplicación de escritorio para descargar y reproduccion de Musica en formato MP3 construida con **C# y WinForms** que utiliza **SQL Server Express LocalDB** como base de datos embebida. Ideal para sistemas de gestión local con independencia total del servidor SQL tradicional.

---

## 🚀 Características

- Interfaz simple y moderna con WinForms (.NET 9)
- Base de datos local `.mdf` con SQL Server LocalDB
- Totalmente funcional sin necesidad de instalar SQL Server completo
- Consultas SQL puras con `SqlConnection` y `SqlCommand`
- Instalador `.msi` con base de datos embebida

---

## 🧩 Tecnologías usadas

- C# (.NET 9)
- Windows Forms
- SQL Server Express LocalDB
- Visual Studio Community 2022
- Instalador MSI con Setup Project

---

## 🛠️ Requisitos

- Windows 10/11
- [.NET Desktop Runtime 6 o 7](https://dotnet.microsoft.com/en-us/download)
- [SQL Server Express LocalDB](https://learn.microsoft.com/es-es/sql/database-engine/configure-windows/sql-server-express-localdb)

---

## 🏗️ Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/MiAppEscritorioLocalDB.git
   ```
2. Abre el archivo .sln en Visual Studio

3. Asegúrate de tener instalado SQL Server Express LocalDB

4. Ejecuta el proyecto (F5)

---

# 📦 Instalador MSI

- Se incluye un proyecto de instalación (Setup Project)

- Copia el archivo .mdf al directorio de instalación (|DataDirectory|)

- Al ejecutar la app, crea su propia instancia de base de datos local

---

# 📂 Estructura del proyecto

```
MiAppEscritorioLocalDB/
│
├── MiAppEscritorioLocalDB/          # Proyecto principal WinForms
│   ├── Form1.cs                     # Lógica principal
│   ├── App.config                   # Cadena de conexión
│   ├── MiBD.mdf                     # Base de datos local
│   └── Program.cs
│
├── SetupProyecto/                  # Proyecto instalador MSI
└── README.md

```
---

## ✒️ Autor

**Gabriel Polack**  
Consultor TI & Software Architect  
[LinkedIn](https://www.linkedin.com/in/gabriel-polack-castillo/) | [GitHub](https://github.com/ArcGabicho)  
✉️ ceo.@blackmountcorporation.com
