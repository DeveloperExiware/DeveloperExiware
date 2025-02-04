# CRM SMART SALES MOBILE
# REACT NATIVE EEXPO Y SQLITE


![Image](https://i.imgur.com/iO7vaP1.png)



## Descargar y Actualizar Dependencias

instalar dependencias de desarrollo

### `npm install` o `yarn`

Expo SDK version 49.0.0, mantener el SDK y las bibliotecas/dependencias actualizadas, algunas con el paso del tiempo quedan deprecadas.el comando para actualizar el SDK es:

```
yarn add expo@latest
```
A continuación puedes ejecutar para actualizar las dependencias:

```
npx expo install --fix
```

o individualmente entrando a la documentacion de cada paquete leyendo si esta o no deprecada para este proyecto

Expo le mostrará qué dependencias deben actualizarse. Instale las dependencias que Expo le sugiere. Es posible que haya caché y tengas que ejecutar.

```
yarn start --reset-cache
```

luego si puedes inicializar el proyecto 


## Inicializar Proyecto.

### `npx expo start -c`


## Buildear Aplicacion Para IOS/ANDROID

### `npx expo prebuild`

# Publicacion y Distribucion en PlayStore y AppStore

## Crear compilación

Instale la última CLI de EAS 

### `npx eas-cli@latest` o  `npm install -g eas-cli`

logearse con eas 
username: deividexiware@gmail.com 
password: Exiware2019

### `eas login`

revisar que si este logeado

### `eas whoami`

# Buildeo Aplicacion ANDROID archivo abb

### `eas build --platform android`

# Buildeo Aplicacion ANDROID archivo abb

### `eas build --platform ios`

## Distribuicion de la aplicacion en APPSTORE

### `eas submit -p ios --latest`

en la pagina de <a href="https://expo.dev/">expo</a> se puede revisar los log e historial de compilaciones

seguir la documentacion <a href="https://play.google.com/console/u/2/developers/8593982463897147808/app-list?pli=1">PlayConsole</a>
para publicar en las plataformas de Android

seguir la documentacion <a href="https://developer.apple.com/account">PlayConsole</a>
para publicar en las plataformas de Android

