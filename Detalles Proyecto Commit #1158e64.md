 Estructura

src/app/
|
├──core/
|    ├──service/
|          └──  lenguage.service.ts
├── shared/
│   ├── navbar/
│   └── footer/
│
└── components/
    ├── hero/
    ├── services/
    ├── about/
    ├── testimonials/
    └── contact/

# Core/service/lenguage.service.ts

Donde deberas poner todos los textos de la pagina para poder remplazarlo dependiendo del lenguaje que seleccione el usuario

De esta manera se tiene que integrar en cada componente en la seccion de cada
`Component-Generic.ts`:

`import {LanguageService} from '../../core/services/lenguage.service';'
`export class Component-Generic {
`constructor(public langService: LanguageService) {}`  
`}`

De la siguiente manera se tiene que implementar en los textos en los archivos HTML:

`<h3>{{ langService.translate('texto-de-ejemplo') }}</h3>`

# Shared

Componentes simple que siempre tiene que estar en la pagina como componentes genericos

# Componentes

Estructuras de objetos completos listos para la insersion sin necesidad de añadir codigo

# App.routers.ts

Para poder visualizar los  componentes que se van desarollando de la siguiente manera:

`import { Navbar } from './shared/navbar/navbar'`
"Para poder importar los componentes"

`{path:'Page-Name', component: ComponenteAAñadir},`
"El path es la ruta que se genera para el componente que se incluye por ejemplo
`(http://localhost:4200/landing)`"

Si se llega a necesitar generar mas componentes se tiene que mover por el terminar a la carpeta donde se quiere generar el componente ya sea shared  o component y ingresar el siguiente comando
`ng generate component component-name`

Para poder visualizar la pagina y correr correr el codigo
`ng erve`

# Importante

Cuando vayas empezar con el codigo ejecuta estos comandos en la terminal

`git checkout -b component-name`