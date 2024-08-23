### Sección en Español

#### Dependencias y Librerías Utilizadas

En este proyecto se utilizó **Redux** y **Redux Toolkit** para manejar el estado global de la aplicación, utilizando un store que envuelve la aplicación y un slice que realiza los cambios de estado. Además, se utilizó **@react-native-async-storage/async-storage** para hacer persistentes los datos, lo que permite evitar realizar llamadas a la API cada vez que se necesite ver esa información.

#### Instrucciones

1. Clona el repositorio: `git clone https://github.com/FernadoLuna/pagatodo_rnc.git`
2. Abre la carpeta: `cd pagatodo_rnc`
3. Instala las dependencias: `yarn install`
4. Ejecuta el proyecto: `yarn android`

#### Descripción de la Arquitectura Utilizada

Se utilizó en su mayoría una arquitectura MVVC, donde se tiene un screen que corresponde a la vista-modelo, un slice que actúa como el controlador, y un model que se refiere a los métodos con los que se obtiene la data. Cada archivo está ubicado en un lugar separado.

#### Pruebas

Para ejecutar las pruebas solo hace falta ejecutar:

1. yarn test

si hay errores, ejecuta yarn install para reinstalar algunas librerias

### Sección en Inglés

#### Dependencies and Libraries Used

This project used **Redux** and **Redux Toolkit** to manage the global state of the application, utilizing a store that wraps the app and a slice that handles state changes. Additionally, **@react-native-async-storage/async-storage** was used to persist data, which helps avoid making API calls every time that information is needed.

#### Instructions

1. Clone the repository: `git clone https://github.com/FernadoLuna/pagatodo_rnc.git`
2. Open the folder: `cd pagatodo_rnc`
3. Install dependencies: `yarn install`
4. Run the project: `yarn android`

#### Description of the Architecture Used

The project primarily uses an MVVC architecture, where a screen corresponds to the view-model, a slice acts as the controller, and a model refers to the methods for retrieving data. Each file is located in a separate place.

#### Tests

for execute the testing, run this comand

1. yarn test

if you have error, run **yarn install**
