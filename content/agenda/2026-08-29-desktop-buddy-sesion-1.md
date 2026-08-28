---
title: "Desktop Buddy – Sesión 1"
date: '2026-08-29T14:00:00-05:00'
draft: false
location: "Gógoblu"
city: "El Carmen de Viboral"
eventType: "taller"
speakers: []
tags:
  - "Desarrollo"
  - "Hardware & Making"
description: "Primera sesión del ciclo Desktop Buddy: el grupo decide cómo es la criatura y cada equipo sale con trabajo propio empezado."
---

El cuerpo ya está vivo. Antes de esta primera sesión el firmware base ya dibuja caras con ocho expresiones, responde a las caricias, lee calcomanías NFC y demostró en protoboard el ciclo completo de voz: mantener un botón, hablar, soltar y oírse. Todo eso está medido y funcionando.

Eso cambia a qué venimos. No a pelear con un compilador para ver el primer píxel, sino a **decidir cómo es esta criatura** y a repartir el trabajo. La primera hora son decisiones de verdad, tomadas en grupo, cada una con su contexto ya escrito: si la pantalla sigue siendo redonda, cómo se llama el conjunto de estados del buddy, qué puede traer escrito una calcomanía NFC y si la interfaz web lleva contraseña. Salen decididas esa tarde.

Después el trabajo se reparte en seis frentes que corren en paralelo durante todo el ciclo: firmware, voz, web, electrónica, diseño 3D y personalidad. **Cuatro de los seis no necesitan que programes.**

## Agenda

Duración aproximada: 4 horas

- **Primera hora — las decisiones abiertas, en grupo.** ¿Seguimos redondos? ¿Cómo se llama el conjunto de estados? ¿Qué puede decir una calcomanía? ¿Lleva contraseña la interfaz web? La de la forma va primero: sin ella el equipo de diseño 3D no puede empezar.
- **Firmware** — adelantar la configuración por WiFi. Hoy la clave va compilada dentro del binario, así que nadie puede llevarse una placa y usarla en su casa; ese es el bloqueo a romper. Y acompañar a los otros equipos para que terminen la tarde con su primer aporte hecho.
- **Voz** — medir cuánto le cuesta al chip abrir una conexión segura. Es el número que decide el diseño del reconocimiento de voz de la sesión 2.
- **Web** — inventario del editor de reflejos: qué hace hoy y qué le falta.
- **Electrónica** — cerrar la lista de componentes y probar el lector NFC en la placa clásica.
- **Diseño 3D** — medir componentes y bocetar la carcasa, apenas se decida la forma.
- **Personalidad** — el equipo es dueño de tres de las decisiones de la primera hora; después, arrancar el contenido del pack.
- **Cierre** — demo por equipo y responsables confirmados. El frente de voz necesita 1–2 personas comprometidas hasta la sesión 4.

## Requisitos

- Trae tu portátil con cargador.
- Instala antes el toolchain de ESP-IDF; hay guía en el repositorio. Está verificado en macOS, así que si usas Linux o Windows llega 15 minutos antes y lo montamos juntos.
- No necesitas experiencia en electrónica ni en C++. Hay trabajo real desde el primer día para quien no programa.
