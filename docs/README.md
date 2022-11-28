# Bullets Diagramation

Este componente muestra los niveles de inferiores de navegación dentro de una lista de bullets con imágenes, y se renderiza de diferente forma en dispositivos móviles y de escritorio.

- **Desktop**
![image](https://user-images.githubusercontent.com/92064924/204375790-92b51fda-8b39-44c0-8f8d-9b665546f14d.png)

- **Mobile**
![image](https://user-images.githubusercontent.com/92064924/204376159-c4aa26ec-6e52-4947-870c-aa4ca91c6d47.png)

## Configuration 

### Paso 1 - Clonar

Realizar la [clonación](https://github.com/Daniela1421/itgloberspartnercl-bullets-diagramation.git) de este repositorio.

### Paso 2 - Editar el Manifest.json 

Ingresar al archivo manifest.json y realizar modificaciones en: `vendor`, `name`, `version`, `title` y `description`
como se muestra en el siguiente ejemplo: 
```
{
  "vendor": "itgloberspartnercl",
  "name": "bullets-diagramation",
  "version": "0.0.1",
  "title": "Bullets diagramation",
  "description": "Es un contexto de elementos que renderizan los niveles de inferiores de navegacion dentro de una lista de bullets con imágenes",
}
```
Además, verifique que el archivo cuente con los siguientes builders: 
```
  "builders": {
    "react": "3.x",
    "messages": "1.x",
    "docs": "0.x",
    "store": "0.x"
  }
```
### Paso 3 - Instalar node-modules

Para realizar esta instalación de node-modules, debe estar ubicado en la carpeta de `react` de la aplicación y ejecutar el comando `yarn`, y tendrá instaladas todas las dependencias necesarias para usar esta plantilla.

### Paso 4 - Ejecutar el preview

Despues de realizar los pasos anteriores puede verificar si su componente está funcionando ejecutando el comando `vtex link` si todo funciona correctamente deberá ver en consola `Sending locale change event`, si por el contrario ocurre un error verifique los pasos anteriores y realice nuevamente este paso. 

### Paso 5 - Implementar el componente

Por último, para utilizar el componente debe agregarlo a las `dependencies` en el `manifest.json` de su tienda de la siguiente manera: vendor.name : version. Por ejemplo: 
```
  "dependencies": {
     "itgloberspartnercl.bullets-diagramation": "0.x"
  }
```

## Dependencies

1. "vtex.css-handles": "0.x"
2. "vtex.native-types": "0.x"
3. "vtex.list-context": "0.x"
4. "vtex.device-detector": "0.x"

## Contributors ✨

Daniela Ducuara Cañas
