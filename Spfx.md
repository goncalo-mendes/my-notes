# Spfx - Sharepoint Framework & Viva

- [Instalar](#Instalar)

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

`yo @microsoft/sharepoint`

## Depois do inicio do projeto

`gulp trust-dev-cert`