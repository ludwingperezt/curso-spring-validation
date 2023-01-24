# Servicio de verificación #

Este es un servicio auxiliar de la aplicación mobile-app-ws que se usa para
validar los tokens de verificación de correos electrónicos que se envían por
email al momento de registrar un nuevo usuario.

También se usa para el formulario de reset de contraseña.

También tiene una prueba para pedir un token de autenticación al endpoint de
login (para probar CORS).

Esta aplicación simula un frontend para la API.  Para pruebas locales el servicio
de backend debe estar en el puerto 8080 y el servicio de verificación debe
correr en el puerto 8091.  El backend debe tener CORS configurado.