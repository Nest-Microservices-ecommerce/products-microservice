# Product Microservice

## Dev

1. Clonar el repositorio
2. Instalar las dependencias
   ```bash
   npm install
   ```
3. Renombrar el archivo `.env.template` a `.env`
4. Configurar las variables de entorno
5. Ejecutar migraciones de prisma
   ```bash
   npx prisma migrate dev
   ```
6. Ejecutar el proyecto
   ```bash
    npm run start:dev
   ```

# Comandos

- Crear un recurso
  `nest g res products --no-spec`

# Instalaciones

- Instalar NestJS
  `npm i -g @nestjs/cli`

- validador de dto
  `npm i class-validator class-transformer`

- variables de entorno y joi
  `npm i dotenv joi`

# Instalación de prisma

1. `npm i prisma --save-dev`
2. `npx prisma init`
3. `npx prisma migrate dev --name init`
4. `npm i @prisma/client`

# Configuración de microservicios

- Instalar microservicios
  `npm i @nestjs/microservices`


# Configuración de nats
[Documentación oficial de NestJS](https://docs.nestjs.com/microservices/nats).

