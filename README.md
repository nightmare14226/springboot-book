# Ecommerce platform (fullstack project) Spring boot 3, Angular 18, Tailwind CSS, PostgreSQL, Kinde 
Monorepo of the Ecommerce platform app. 

### Key Features:
- 🛠️ Admin panel for products and categories 
- 🔍✨ Filter engine
- 🌐⚡ Angular SSR 
- 💳 Stripe integration
- 🏢 Hexagonal architecture (Backend)

## Screenshots
<img width="1254" height="760" alt="Image" src="https://github.com/user-attachments/assets/e1dd5c3d-0fa8-40d5-a5c2-d005e99f2886" />

<img width="1254" height="760" alt="Image" src="https://github.com/user-attachments/assets/144aab6f-791a-4c83-864c-c52edfa353df" /> 

<img width="1254" height="760" alt="Image" src="https://github.com/user-attachments/assets/cbb9d9d6-d2ba-4948-9238-66a04eeca333" />



## Work flow
<img width="7455" height="6029" alt="Image" src="https://github.com/user-attachments/assets/dfacc7ec-26a6-4799-a48f-8e6c40648a15" />

 



## Usage
### Prerequisites
- [NodeJS 20.17 LTS](https://nodejs.org/dist/v20.17.0/node-v20.17.0.pkg)
- [Angular CLI v18](https://www.npmjs.com/package/@angular/cli)
- IDE ([VSCode](https://code.visualstudio.com/download), [IntelliJ](https://www.jetbrains.com/idea/download/))
- [JDK 21](https://adoptium.net/temurin/releases/)
- Docker ([Docker Desktop](https://docs.docker.com/engine/install/))

### Fetch dependencies
``npm install``

Create an .env file at the root of the ecom-backend folder with the following values :

````
KINDE_CLIENT_ID=<client-id>
KINDE_CLIENT_SECRET=<client-secret>
STRIPE_API_KEY=<stripe-api-key>
STRIPE_WEBHOOK_SECRET=<stripe-webhook-secret>
````

## Manage the frontend

To run the dev server for your app, use:

```sh
npx nx serve ecom-frontend
```

To create a production bundle:

```sh
npx nx build ecom-frontend
```

To see all available targets to run for a project, run:

```sh
npx nx show project ecom-frontend
```

## Manage the Backend

To run the dev server for your app, use:

```sh
npx nx serve ecom-backend
```

To create a production bundle:

```sh
npx nx build ecom-backend
```

To see all available targets to run for a project, run:

```sh
npx nx show project ecom-backend
```
 

