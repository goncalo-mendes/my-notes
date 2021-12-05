# Spfx - Sharepoint Framework & Viva

- [Instalar](#instalar)
- [Inicio do projetos](#inicio-do-projetos)
- [Rest](#rest)

## Instalar
Nodejs:

`choco install nodejs.install --version=14.17.6 -y`

Nvm:

`choco install nvm -y`

`nvm install <version>`
`nvm use <version>`
`nvm list`

Gulp e Yeoman:
`npm install gulp-cli yo @microsoft/generator-sharepoint --global`

Yeoman SharePoint generator:
`npm install @microsoft/generator-sharepoint --global`


## Inicio do projetos

### Tipos de projeto
- [WebPart](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/guidance/simplify-adding-web-parts-with-preconfigured-entries)
- [Extensões](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/extensions/overview-extensions)
- [Libraria](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/library-component-overview)
- [Adaptive Card](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/viva/get-started/build-first-sharepoint-adaptive-card-extension)
`yo @microsoft/sharepoint`

### Depois do inicio do projeto

`gulp trust-dev-cert

## Rest
Lista: `https://{site_url}/_api/web/lists/GetByTitle('List Title')`

Field: `https://{site_url}/_api/web/lists/GetByTitle('List Title')/items?$select=Title`

Top10: `https://{site_url}/_api/web/lists/GetByTitle('List Title')/items?$top=10`

[Link](https://docs.microsoft.com/en-us/sharepoint/dev/apis/syntex/syntex-model-rest-api)