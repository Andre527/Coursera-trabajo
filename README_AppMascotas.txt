AppMascotas 🐶🐱

Aplicación Android desarrollada como parte del proyecto final del curso Desarrollo de Aplicaciones con Android.
Esta app permite mostrar y guardar de forma local las últimas 5 mascotas calificadas por el usuario, utilizando Room Database.

----------------------------------------

🧩 Funcionalidades

- Muestra una lista de las 5 mascotas más recientes calificadas.
- Cada mascota incluye:
  - Identificador único (id)
  - Nombre
  - Foto (vía URL)
  - Valoración (rating)
- Persistencia de datos usando Room (solo se guardan las últimas 5).
- Visualización en lista con RecyclerView.
- Carga de imágenes desde internet usando Picasso.

----------------------------------------

🛠️ Tecnologías utilizadas

- Java
- Android SDK
- Room (Jetpack)
- RecyclerView
- Picasso

----------------------------------------

📁 Estructura del proyecto

AppMascotas/
├── java/
│   └── com.example.appmascotas/
│       ├── MainActivity.java
│       ├── MascotaAdapter.java
│       ├── model/
│       │   └── Mascota.java
│       └── database/
│           ├── AppDatabase.java
│           └── MascotaDao.java
├── res/
│   └── layout/
│       ├── activity_main.xml
│       └── item_mascota.xml

----------------------------------------

🧪 Requisitos

- Android Studio instalado
- SDK mínimo: API 21 (Lollipop)
- Conexión a internet (para cargar las imágenes desde URL)

----------------------------------------

▶️ Instrucciones para ejecutar

1. Clonar el repositorio:
   git clone https://github.com/tu-usuario/AppMascotas.git

2. Abrir el proyecto con Android Studio.
3. Ejecutar en un emulador o dispositivo físico.
4. La app insertará automáticamente una mascota de prueba al iniciar.

----------------------------------------

👤 Autor

Desarrollado por Andrea Paola Calderon
Proyecto académico - Curso Desarrollo de Aplicaciones con Android

----------------------------------------

📌 Estado del proyecto

✅ Finalizado
📦 Listo para entrega
