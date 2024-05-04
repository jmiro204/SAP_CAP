# Getting Started

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch`
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.

## Learn More SAP CAP

## GITHUB 
•	Inicializar -> git init
•	Configurar
o	    git config --global user.email juliomiro204@gmail.com
o	    git config --global user.name "jmiro204"
•	Agregar remote/origin -> git remote add origin https://github.com/jmiro204/SAP_CAP.git
•	Agregar archivos -> git add .
•	Commit -> git commit -m "First Commit CAP"
•	Push -> git push origin master
o	    En caso de error (error: src refspec master does not match any) ejecutar comando -> git checkout -b master
o	    Luego el push otra vez

## SQLITE
•	Instalar SQLITE npm i @cap-js/sqlite
•	Verificar SQLITE cds env requires.db
•	Deploy (Crear tablas y registros de CSV si existen) cds deploy --to sqlite
•	Crear conexión
o	    En SQLTools se agrega la conexión
	        Ruta fichero db-sqlite del proyecto


## Proyecto CAP
	Ejecutar nuestro proyecto CAP: cds wath o npm run

Se puede modularizar el codigo por contexto o agrupación de entidades
 
Entity sap.logali.groupA{ 
    Entity A{}
    Entity B{}
}

