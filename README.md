# Stackbit Starter Theme // Tema de inicio de Stackbit

Quim Alborch // v0.3.28.

EN:

# Running Your Site Locally

1. Install [Node.js and npm](https://nodejs.org/en/)

1. Install npm dependencies:

        npm install

1. Get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. Run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. Run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5f7ebdd95c28e5001cb97497

1. Start a local development server:

        npm run develop

1. Browse to [http://localhost:8000/](http://localhost:8000/)

ES:

# Running Your Site Locally

1. Instale [Node.js y npm] (https://nodejs.org/en/)

1. Instale las dependencias npm:

        npm install

1. Obtenga "stackbit-api-key" del menú del proyecto en [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. Ejecute el siguiente comando para asignar esta clave a la variable de entorno `STACKBIT_API_KEY` variable ambiental:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. Ejecute el siguiente comando para obtener contenido adicional del sitio de Stackbit si es necesario:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5f7ebdd95c28e5001cb97497

1. Inicie un servidor de desarrollo local:

        npm run develop

1. Buscar [http://localhost:8000/](http://localhost:8000/)
