# full-cycle-ddd-patterns

# Instalar o typescript e criar arquivos e pasta package: 
    npm  i typescript --save-dev

# Iniciar projeto
    npx tsc --init

# Configurações em tsconfig.json:
    Descomentar:
    "incremental": true, (compila somente o que mudoiu
    "outDir": "./dist", (Copilar nessa pasta dist)
    Compila o que esta na pasta src:
    "include": [
        "src/**/*.ts"
    ],

# Instalar o tslint
    npm i tslint --save-dev
    npx tslint --init