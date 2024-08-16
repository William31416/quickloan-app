<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).


# 🛠️ Sentando Bases con NestJS

---

## **Objetivo:**
**Sentar las bases en NestJS** a través de una serie de temas fundamentales que permitirán al estudiante construir una comprensión sólida de este poderoso framework. Los temas a tocar en el taller incluyen:

- 🛡️ **¿Qué es Nest?**
- 🤔 **¿Por qué usarlo?**
- 🗂️ **Explicación sobre cada archivo en un proyecto nuevo de Nest**
- 🏗️ **Core Nest building blocks**
- 📦 **Módulos**
- 📋 **Controladores (Post, Patch, Get, Delete)**
- 🏷️ **Primeros decoradores**
- 💼 **Servicios**
- 💉 **Inyección de dependencias**
- 🧪 **Pipes**
- 🚨 **Exception Filters**

---

## **Introducción:**
> **¡Bienvenidos!** 🎉 Después de un viaje profundo por el mundo de Node.js, TypeScript, decoradores, pruebas de desempeño y otras cosas que generan una potencial frustración 😅, nos adentramos ahora en el universo de NestJS, un framework que nos permitirá estructurar nuestras aplicaciones de manera modular y escalable, llevando nuestras habilidades a un nuevo nivel. En este taller, crearemos una base sólida en NestJS, preparándonos para enfrentar problemas complejos en el ámbito de la tecnología financiera.

---

## **Instrucciones de Entrega:**
- **Subir tu proyecto a GitHub:** Crea un repositorio en GitHub y sube tu proyecto de NestJS.
- **Compartir el enlace:** Sube tu enlace a la plataforma de Laboratoria para que pueda revisar tu proyecto.
---

## **Problemática:**

**Contexto de la Problemática:**

Imagina que has sido contratado por una fintech emergente que busca revolucionar el mercado de microcréditos. La compañía, **QuickLoan**, quiere ofrecer préstamos rápidos a personas con poca o ninguna historia crediticia, pero se enfrenta a varios desafíos:

1. **Velocidad y Seguridad:** Los usuarios esperan decisiones inmediatas sobre sus solicitudes de préstamo, lo cual requiere un sistema rápido y seguro.
2. **Escalabilidad:** A medida que la fintech crezca, el sistema debe ser capaz de manejar miles de solicitudes simultáneamente.
3. **Modularidad y Mantenimiento:** El sistema debe ser modular para permitir la incorporación de nuevas funcionalidades y mejoras sin comprometer la estabilidad.
4. **Personalización y Manejo de Excepciones:** Se requiere un sistema que pueda personalizar las ofertas de crédito y manejar excepciones de manera eficiente para evitar posibles fraudes.

**Problemática**: QuickLoan necesita un sistema backend robusto que permita manejar solicitudes de préstamos de manera segura, rápida y escalable, asegurando una experiencia fluida para el usuario final. Debes crear la base de este sistema utilizando NestJS.

---

## **Epica:**

**Como** desarrollador backend en **QuickLoan**,
**Quiero** construir un sistema modular y seguro en NestJS,
**Para** gestionar ***solicitudes de préstamos*** de manera eficiente y escalable, mientras garantizo la seguridad de los datos y el manejo adecuado de excepciones.

---

## **Criterios de Aceptación:**

- **Comprensión y Explicación de la Estructura de un Proyecto NestJS**: El estudiante debe identificar y explicar la función de cada archivo en la estructura básica de un proyecto NestJS.
- **Implementación de Controladores Eficientes**: El estudiante debe crear controladores que manejen diferentes métodos HTTP (Post, Patch, Get, Delete) para gestionar solicitudes de préstamo.
- **Uso Efectivo de Decoradores y Servicios**: Implementar decoradores y servicios que permitan personalizar y manejar la lógica de negocio del sistema de préstamos.
- **Configuración Adecuada de Pipes y Exception Filters**: Configurar y aplicar pipes para la validación de datos y filtros de excepción para manejar errores y proteger el sistema.
- **Aplicación de la Inyección de Dependencias para Modularidad**: Usar inyección de dependencias para construir un sistema modular, permitiendo la fácil adición de nuevas funcionalidades.


---

## **Historias de Usuario**

## **Historia de Usuario 1: Configuración Inicial y Estructura del Proyecto**

**Como** desarrollador backend,  
**Quiero** aprender a configurar y entender la estructura básica de un proyecto NestJS,  
**Para** asegurarme de que la arquitectura del proyecto sea modular y fácilmente escalable.

**Tareas:**

### **1. Configuración del Proyecto**

- **Propuesta de Solución**:
   - Crear un nuevo proyecto NestJS llamado `quickloan-app` utilizando el CLI:
   ```bash
   nest new quickloan-app
   ```
   - Revisar y entender la estructura de archivos generada por defecto. Asegúrate de leer la documentación o las notas adicionales proporcionadas. Puedes explorar cada archivo y carpeta para comprender su propósito y cómo contribuye a la arquitectura del proyecto [aquí](../notes/files-explanation.md) o [aquí](../notes/components.md).
   - Identificar el propósito de cada archivo y cómo contribuye a la modularidad del proyecto. Puedes leer la siguiente documentación [Estructura propuesta aplicaciones NestJS](../notes/proposed-architecture.md).

- **Preguntas**:
   1. ¿Qué propósito cumple el archivo `main.ts` en un proyecto NestJS y por qué es crucial en la configuración inicial? Puedes leer más sobre el archivo [aquí](../first-step-project/src/main.ts) en la sección inferior de
   notas.
   **Respuesta:** El archivo main.ts es el punto de entrada de la aplicación NestJS. Aquí se configura el módulo principal, se inicializa el servidor y se establece la configuración global, como los pipes de validación. Es crucial porque arranca la aplicación y define cómo se inicia y configura el servidor HTTP.

   2. ¿Qué diferencia existe entre `app.module.ts` y `app.controller.ts`? ¿Cómo se relacionan estos archivos con la modularidad y la estructura de la aplicación? Puedes leer sobre el archivo [aquí](../notes/files-explanation.md) o [aquí](../notes/components.md).
   **Respuesta:** app.module.ts es el módulo raíz de la aplicación, donde se definen los módulos importados y los servicios disponibles en toda la aplicación. app.controller.ts define los endpoints HTTP (rutas) y cómo se manejan las solicitudes entrantes. app.module.ts y app.controller.ts trabajan juntos para estructurar la aplicación y manejar las solicitudes de manera organizada.

---

### **2. Creación de Módulos Básicos**

- **Propuesta de Solución**:
   - Crear un módulo `LoansModule` para gestionar operaciones de préstamos:
   ```bash
   nest g mo loans
   ```
   - Crear un módulo `UsersModule` para gestionar la información de los usuarios:
   ```bash
   nest g mo users
   ```

- **Cascarita**: Revisa el nombre del módulo generado y asegúrate de que sea correcto y consistente con el estándar de nombres.

- **Preguntas**:
   1. ¿Por qué crees que es importante modularizar la aplicación separando funcionalidades en diferentes módulos?
   **Respuesta:** Modularizar la aplicación ayuda a mantener el código organizado y facilita su mantenimiento y escalabilidad. Cada módulo se encarga de una parte específica de la funcionalidad, lo que permite hacer cambios y añadir nuevas características sin afectar el resto de la aplicación.

   2. ¿Cómo crees que afecta la modularidad al mantenimiento y escalabilidad de la aplicación?
   **Respuesta:** La modularidad hace que la aplicación sea más fácil de mantener porque los cambios se pueden hacer en módulos específicos sin impactar otras partes del sistema. También facilita la escalabilidad, ya que nuevos módulos pueden ser añadidos sin necesidad de reestructurar toda la aplicación.

   3. Despues de crear los archivos de los módulos, ¿qué archivos se generan y cómo se relacionan con los módulos creados?
   **Respuesta:** Al crear un módulo, se generan archivos como el archivo del módulo (.module.ts), el archivo del servicio (.service.ts), y a veces el archivo del controlador (.controller.ts). Estos archivos se relacionan entre sí para proporcionar la funcionalidad completa del módulo, organizando cómo se manejan las solicitudes y cómo se gestionan los datos.
---

### **3. Implementación de Controladores**

- **Propuesta de Solución**:
   - Crear un controlador `LoansController` para manejar solicitudes POST de creación de préstamos:
   ```bash
   nest g co loans
   ```
   - Implementar rutas GET para consultar el estado de un préstamo en el mismo controlador:
   ```typescript
   import { Controller, Get, Post, Body, Param } from '@nestjs/common';

   @Controller('loans')
   export class LoansController {
     @Post()
     createLoan(@Body() createLoanDto: any) {
       return 'Loan created';
     }

     @Get(':id')
     getLoanStatus(@Param('id') id: string) {
       return `Status of loan ${id}`;
     }
   }
   ```

- **Cascarita**: Asegúrate de que las rutas estén correctamente definidas y que los decoradores estén aplicados en los lugares correctos.

- **Preguntas**:
   1. ¿Qué sucede si defines incorrectamente un decorador en un controlador? ¿Cómo afecta esto a la funcionalidad del endpoint?
   **Respuesta:** Si un decorador se define incorrectamente, el endpoint puede no funcionar como se espera. Por ejemplo, si el decorador @Post() se usa en lugar de @Get(), la ruta no responderá a solicitudes GET. Los decoradores son esenciales para que el framework entienda cómo debe manejar cada solicitud.

   2. ¿Por qué es importante manejar rutas dinámicas (por ejemplo, `@Get(':id')`) en aplicaciones que interactúan con bases de datos?
   **Respuesta:** Manejar rutas dinámicas es crucial para acceder y manipular recursos específicos en la base de datos. Permite realizar operaciones como obtener, actualizar o eliminar un recurso particular basado en su identificador único, facilitando la interacción con datos individuales.
---

## **Historia de Usuario 2: Implementación de la Lógica de Negocio y Seguridad**

**Como** desarrollador backend,  
**Quiero** aprender a implementar la lógica de negocio y asegurar la seguridad de las transacciones,  
**Para** garantizar que el sistema maneje las solicitudes de préstamos de manera segura y eficiente.

**Tareas:**

### **1. Desarrollo de Servicios**

- **Propuesta de Solución**:
   - Crear un servicio `LoansService` para manejar la lógica de negocio de los préstamos:
   ```bash
   nest g s loans
   ```
   - Implementar un método para calcular el riesgo del préstamo basado en el perfil del usuario:
   ```typescript
   import { Injectable } from '@nestjs/common';

   @Injectable()
   export class LoansService {
     calculateLoanRisk(userProfile: any): string {
       // Lógica básica para determinar el riesgo
       if (userProfile.creditScore > 700) {
         return 'Low Risk';
       } else {
         return 'High Risk';
       }
     }
   }
   ```

- **Cascarita**: Verifica que el nombre del método y su propósito estén alineados con la lógica de negocio y que el servicio esté correctamente inyectado en el controlador.

- **Preguntas**:
   1. ¿Qué ventajas tiene manejar la lógica de negocio en servicios en lugar de controladores?
   **Respuesta:** Manejar la lógica de negocio en servicios permite mantener los controladores limpios y enfocados solo en la gestión de solicitudes. Los servicios pueden ser reutilizados en diferentes controladores y pruebas, promoviendo la separación de preocupaciones y facilitando el mantenimiento del código.

   2. ¿Cómo se relaciona la inyección de dependencias con la modularidad y la capacidad de prueba de la aplicación?
   **Respuesta:** La inyección de dependencias permite que los servicios y módulos se conecten entre sí sin acoplarse directamente. Esto hace que el sistema sea más modular y permite realizar pruebas unitarias más fáciles, ya que las dependencias pueden ser sustituidas por mocks o stubs durante las pruebas.
---

### **2. Aplicación de Decoradores y Pipes**

- **Propuesta de Solución**:
   - Utilizar decoradores como `@Body`, `@Param`, y `@Query` para manejar datos de las solicitudes en el `LoansController`:
   ```typescript
   @Post()
   createLoan(@Body() createLoanDto: any) {
     return `Loan created for ${createLoanDto.userId}`;
   }
   ```

   - Implementar un `ValidationPipe` para validar los datos de entrada:
   ```typescript
   import { ValidationPipe } from '@nestjs/common';

   // En main.ts
   app.useGlobalPipes(new ValidationPipe());
   ```

- **Cascarita**: Asegúrate de que el `ValidationPipe` esté configurado correctamente y aplicado en la instancia de la aplicación.

- **Preguntas**:
   1. ¿Por qué es crucial validar los datos de entrada en una aplicación que maneja transacciones financieras?
   **Respuesta:** Validar los datos de entrada es crucial para asegurar que la información que entra en el sistema sea correcta y segura. En aplicaciones financieras, esto previene errores, inconsistencias y posibles fraudes, garantizando que solo datos válidos sean procesados.

   2. ¿Qué podría suceder si un decorador está mal colocado o si no se aplican los pipes correctamente?
   **Respuesta:** Si un decorador está mal colocado, el controlador no funcionará como se espera, y las rutas pueden no responder correctamente. Si los pipes no se aplican, los datos de entrada pueden no ser validados, lo que podría llevar a errores o vulnerabilidades en la aplicación.
---

### **3. Configuración de Exception Filters**

- **Propuesta de Solución**:
   - Implementar filtros de excepción para manejar errores comunes:
   ```typescript
   import { ExceptionFilter, Catch, ArgumentsHost, HttpException } from '@nestjs/common';

   @Catch(HttpException)
   export class HttpErrorFilter implements ExceptionFilter {
     catch(exception: HttpException, host: ArgumentsHost) {
       const ctx = host.switchToHttp();
       const response = ctx.getResponse();
       const status = exception.getStatus();

       response.status(status).json({
         statusCode: status,
         message: exception.message,
       });
     }
   }
   ```

   - Asegurarse de que los errores se manejen adecuadamente en las respuestas al usuario.

- **Cascarita**: Verifica que el filtro de excepción esté registrado correctamente en el módulo o aplicado globalmente.

- **Preguntas**:
   1. ¿Cómo impacta el manejo adecuado de excepciones en la experiencia del usuario y en la seguridad de la aplicación?
   **Respuesta:** Un manejo adecuado de excepciones asegura que los errores se gestionen de manera controlada y se proporcionen mensajes de error claros y útiles al usuario. Esto mejora la experiencia del usuario y protege la aplicación contra vulnerabilidades que podrían ser explotadas por errores no manejados.

   2. ¿Por qué es importante tener un manejo centralizado de excepciones en una aplicación NestJS?
   **Respuesta:** El manejo centralizado de excepciones permite gestionar todos los errores de manera uniforme y consistente. Esto facilita el mantenimiento y asegura que todos los errores sean tratados de manera segura y coherente, evitando la exposición de detalles internos que podrían comprometer la seguridad.
---