# FNATIC - Red Social Móvil.
Trabajo integrador Programación-03 React Native UdeSA/DigitalHouse.

Aplicación móvil estilo red social desarrollada con React Native y Expo, con backend serverless en Firebase. Permite a los usuarios publicar fotos, interactuar mediante likes y comentarios, y explorar perfiles de otros usuarios.
Funcionalidades:

Registro e inicio de sesión con email/contraseña y autenticación con Google
Publicación de fotos tomadas con la cámara del dispositivo o desde la galería
Feed principal con posts en tiempo real ordenados cronológicamente
Sistema de comentarios y likes por publicación
Perfiles de usuario con historial de posts, biografía y foto de avatar
Búsqueda de usuarios
Eliminación de cuenta con reautenticación
Navegación por tabs con íconos

Tecnologías y herramientas evaluadas:

Mobile: React Native 0.69, Expo SDK 46
Navegación: React Navigation v6 — Stack Navigator y Bottom Tab Navigator
Backend/BaaS: Firebase — Authentication (email/password y Google OAuth), Firestore (base de datos en tiempo real), Storage (almacenamiento de imágenes)
Cámara y multimedia: expo-camera, expo-image-picker
UI: StyleSheet API, FlatList, expo-google-fonts, @expo/vector-icons
