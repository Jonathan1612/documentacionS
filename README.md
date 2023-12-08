# Documentacion general de aplicaciones y sistemas

## 1. Introducción y Objetivos:

**Descripción General:**

- Propósito de la aplicación.
- Contexto y necesidades empresariales.

**Objetivos de Documentación:**

- Explicar la estructura y el funcionamiento de la documentación.
- Definir audiencia (desarrolladores, administradores, etc.).

## 2. Arquitectura de la Aplicación:

**Diagramas:**

- Diagrama de arquitectura.
- Diagrama de componentes.
- Diagrama de despliegue.

**Tecnologías Utilizadas:**

- Lenguajes de programación.
- Bases de datos.
- Frameworks y bibliotecas.
- Servidores y servicios externos.

## 3. Configuración del Entorno:

**Requisitos del Sistema:**

- Hardware y software necesario.
- Dependencias externas.

**Instalación y Configuración:**

- Pasos detallados para instalar la aplicación.
- Configuración inicial.

## 4. Estructura del Código Fuente:

**Organización de Carpetas:**

- Estructura del proyecto.
- Propósito de cada carpeta.

**Módulos y Componentes:**

- Descripción de los módulos principales.
- Relaciones entre componentes.

## 5. Flujo de Datos y Procesos:

**Diagramas de Flujo:**

- Procesos principales.
- Interacción de módulos.

**Casos de Uso:**

- Escenarios típicos de interacción del usuario.

## 6. Base de Datos:

**Esquema de la Base de Datos:**

- Estructura de tablas y relaciones.
- Descripción de campos.

**Scripts de Migración y Semillas:**

- Procedimientos para la creación de la base de datos.

## 7. API y Servicios Web:

**Documentación de API:**

- Endpoints disponibles.
- Métodos HTTP permitidos.
- Ejemplos de solicitudes y respuestas.

## 8. Seguridad:

**Gestión de Usuarios y Roles:**

- Políticas de acceso.
- Roles y permisos.

**Protección contra Amenazas Comunes:**

- Manejo de sesiones.
- Validación de entrada.

## 9. Gestión de Errores y Logging:

**Manejo de Excepciones:**

- Tipos de errores.
- Respuestas esperadas.

**Registro (Logging):**

- Qué información se registra.
- Configuración del sistema de registro.

## 10. Pruebas:

**Suite de Pruebas:**

- Tipos de pruebas (unitarias, integración, etc.).
- Herramientas utilizadas.

**Instrucciones para Ejecutar Pruebas:**

- Configuración necesaria.
- Comandos o pasos para ejecutar pruebas.

## 11. Despliegue:

**Proceso de Despliegue:**

- Pasos detallados para implementar la aplicación.
- Configuración del servidor.

**Monitoreo:**

- Herramientas utilizadas para el monitoreo.

## 12. Mantenimiento y Actualizaciones:

**Procedimientos de Mantenimiento:**

- Resolución de problemas comunes.
- Actualización de dependencias.

**Registro de Cambios:**

- Historial de versiones.
- Cambios significativos.

## 13. Recursos Adicionales:

**Enlaces Útiles:**

- Referencias a documentación externa.
- Recursos de soporte.

## 14. Equipo de Desarrollo y Contacto:

**Información del Equipo:**

- Lista de desarrolladores.
- Información de contacto.



# Documentacion de commits Git

**Tipo de commit:**

Comienza tu mensaje de commit con un tipo que indique la naturaleza del cambio. Algunos ejemplos comunes son:

***feat***: para nuevas características.

```
git commit -m "feat(usuario): Agrega la funcionalidad de cambiar la foto de perfil

Implementa una nueva característica que permite a los usuarios cambiar su foto de perfil desde la configuración del perfil."
```

***fix***: para corrección de errores.

```
git commit -m "fix(validación): Corrige la validación de contraseñas débiles

Se corrigió un error que permitía contraseñas débiles no cumplir con los requisitos mínimos de seguridad."
```

***docs***: para cambios en la documentación.

```
git commit -m "docs(readme): Actualiza el README con ejemplos de uso

Se mejoró la documentación del proyecto incluyendo ejemplos de uso y configuración."
```

***style***: para cambios en el formato del código (sin cambios en la lógica).

```
git commit -m "style(css): Alinea las reglas CSS en el archivo de estilos principal

Se aplicaron cambios en el formato del código para mejorar la legibilidad del archivo CSS principal."
```

***refactor***: para refactorización de código.

```
git commit -m "refactor(api): Reorganiza la lógica de autenticación en el servicio Auth

Se refactorizó el servicio de autenticación para mejorar la modularidad y facilitar el mantenimiento."
```

***test***: para la adición de pruebas.

```
git commit -m "test(auth): Agrega pruebas unitarias para la función de autenticación

Se introdujeron nuevas pruebas unitarias para garantizar la robustez y fiabilidad de la función de autenticación."
```

***chore***: para tareas de construcción y otras tareas no relacionadas con el código.

```
git commit -m "chore(build): Actualiza las dependencias del sistema de construcción

Este commit actualiza las versiones de las herramientas de construcción y sus dependencias para garantizar la compatibilidad con las últimas versiones."
```


# Documentacion de aplicaciones Front (Codigo)

# CountriesHub

Este es un componente Vue.js personalizado llamado "CountriesHub". Componente que muestra un resumen de países, incluyendo un encabezado, gráficos y tablas..

## Propiedades
| Propiedad | Tipo   | Descripción                          |
| --------- | ------ | ------------------------------------ |
| `` |    |  |

## Datos
| Nombre | Tipo   | Descripción                          |
| ------ | ------ | ------------------------------------ |
| `varLocal` |  Boolean  | Variable local que controla si se deben utilizar datos locales o solicitarlos al servidor.  |
| `varMedia` |  Boolean  | Variable que controla si se deben utilizar datos|
| `loading` |  Boolean  | Valor booleano que indica si se está cargando la información. |
| `period` |  Date  | Períodos seleccionado. |
| `incidentsH` |  Object  | Un objeto que almacena los detalles de los incidentes relevantes.  |
| `impactsH` |  Object  | NA |
| `incidentsWH` |  Object  | NA |
| `impactsWH` |  Object  | NA |
| `tablesHub` |  Array  | NA |
| `tablesWithoutHub` |  Array  | NA |

## Métodos
| Componete    | Descripción                         |
| --------- |------------------------------------ |
| `NA`  | NA |

## Servicios
| Ruta    | Descripcion                         |
| --------- |------------------------------------ |
| `/gateway/incidentdashboard/v2/agata/segundaPantallaAnalisisIncidentesPaisesHUB`  | Este servicion  |
| `/gateway/incidentdashboard/v2/agata/segundaPantallaAnalisisImpactosPaisesHUB`  | Este servicion  |
| `/gateway/incidentdashboard/v2/agata/segundaPantallaAnalisisIncidentesPaisesNoHUB`  | Este servicion  |
| `/gateway/incidentdashboard/v2/agata/segundaPantallaAnalisisImpactosPaisesNoHUB`  | Este servicion  |
| `/gateway/incidentdashboard/v2/agata/segundaPantallaAnalisisPorPaisesTablaPaisesNoHUB`  | Este servicion  |
| `/gateway/incidentdashboard/v2/agata/segundaPantallaAnalisisPorPaisesTablaPaisesHUB`  | Este servicion  |
| `/gateway/incidentdashboard/v2/agata/graficaDonaProblemas`  | Este servicion  |

## Ejemplo de Uso

~~~
Vue

    Servicio: segundaPantallaAnalisisIncidentesPaisesHUB

    api.chartIncidentsForCountryHub({ previous: previous, current: current }).then(response => {
        this.incidentsH = response
        const currentPercentageIcRH = parseFloat((parseInt(this.incidentsH.current.quantity) * 100) / (parseInt(this.incidentsH.previous.quantity) + parseInt(this.incidentsH.current.quantity))).toFixed(2)
        const previousPercentageIcRH = parseFloat((parseInt(this.incidentsH.previous.quantity) * 100) / (parseInt(this.incidentsH.previous.quantity) + parseInt(this.incidentsH.current.quantity))).toFixed(2)
        this.labelsIncH = [this.incidentsH.previous.year + ': ' + previousPercentageIcRH, this.incidentsH.current.year + ': ' + currentPercentageIcRH]
        this.seriesIncH = [parseInt(this.incidentsH.previous.quantity), parseInt(this.incidentsH.current.quantity)]
      }).catch(error => {
        console.log(error)
      })

      Servicio: segundaPantallaAnalisisImpactosPaisesHUB

      api.chartImpactsForCountryHub({ previous: previous, current: current }).then(response => {
        this.impactsH = response
        const currentPercentageImRH = parseFloat((parseInt(this.impactsH.current.quantity) * 100) / (parseInt(this.impactsH.previous.quantity) + parseInt(this.impactsH.current.quantity))).toFixed(2)
        const previousPercentageImRH = parseFloat((parseInt(this.impactsH.previous.quantity) * 100) / (parseInt(this.impactsH.previous.quantity) + parseInt(this.impactsH.current.quantity))).toFixed(2)
        this.labelImpH = [this.impactsH.previous.year + ': ' + previousPercentageImRH, this.impactsH.current.year + ': ' + currentPercentageImRH]
        this.seriesImpH = [parseInt(this.impactsH.previous.quantity), parseInt(this.impactsH.current.quantity)]
      }).catch(error => {
        console.log(error)
      })

      Servicio: segundaPantallaAnalisisIncidentesPaisesNoHUB

      api.chartIncidentsForCountryWithoutHub({ previous: previous, current: current }).then(response => {
        this.incidentsWH = response
        const currentPercentageIcRWH = parseFloat((parseInt(this.incidentsWH.current.quantity) * 100) / (parseInt(this.incidentsWH.previous.quantity) + parseInt(this.incidentsWH.current.quantity))).toFixed(2)
        const previousPercentageIcRWH = parseFloat((parseInt(this.incidentsWH.previous.quantity) * 100) / (parseInt(this.incidentsWH.previous.quantity) + parseInt(this.incidentsWH.current.quantity))).toFixed(2)
        this.labelsIncWH = [this.incidentsWH.previous.year + ': ' + previousPercentageIcRWH, this.incidentsWH.current.year + ': ' + currentPercentageIcRWH]
        this.seriesIncWH = [parseInt(this.incidentsWH.previous.quantity), parseInt(this.incidentsWH.current.quantity)]
      }).catch(error => {
        console.log(error)
      })

      Servicio: segundaPantallaAnalisisImpactosPaisesNoHUB

      api.chartImpactsForCountryWithoutHub({ previous: previous, current: current }).then(response => {
        this.impactsWH = response
        const currentPercentageImRWH = parseFloat((parseInt(this.impactsWH.current.quantity) * 100) / (parseInt(this.impactsWH.previous.quantity) + parseInt(this.impactsWH.current.quantity))).toFixed(2)
        const previousPercentageImRWH = parseFloat((parseInt(this.impactsWH.previous.quantity) * 100) / (parseInt(this.impactsWH.previous.quantity) + parseInt(this.impactsWH.current.quantity))).toFixed(2)
        this.labelImpWH = [this.impactsWH.previous.year + ': ' + previousPercentageImRWH, this.impactsWH.current.year + ': ' + currentPercentageImRWH]
        this.seriesImpWH = [parseInt(this.impactsWH.previous.quantity), parseInt(this.impactsWH.current.quantity)]
      }).catch(error => {
        console.log(error)
      })

      Servicio: segundaPantallaAnalisisPorPaisesTablaPaisesNoHUB

      api.tablesForCountryWithoutHub({ previous: previous, current: current }).then(response => {
        this.tablesWithoutHub = response
        this.tablesWithoutHub.sort(function (a, b) {
          if (a.country < b.country) {
            return -1
          }
          if (a.country > b.country) {
            return 1
          }
          return 0
        })
        for (let c = 0; this.tablesWithoutHub.length > c; c++) {
          for (let i = 0; countriesData.length > i; i++) {
            if (countriesData[i].name === this.tablesWithoutHub[c].country) {
              this.tablesWithoutHub[c].flag = countriesData[i].flag
            }
          }
        }
      }).catch(error => {
        console.log(error)
      })

      Servicio: segundaPantallaAnalisisPorPaisesTablaPaisesHUB

      api.tablesForCountryHub({ previous: previous, current: current }).then(response => {
        this.tablesHub = response
        this.tablesHub.sort(function (a, b) {
          if (a.country < b.country) {
            return -1
          }
          if (a.country > b.country) {
            return 1
          }
          return 0
        })
        for (let c = 0; this.tablesHub.length > c; c++) {
          for (let i = 0; countriesData.length > i; i++) {
            if (countriesData[i].name === this.tablesHub[c].country) {
              this.tablesHub[c].flag = countriesData[i].flag
            }
          }
        }
        this.loading = false
      }).catch(error => {
        console.log(error)
        this.loading = false
      })

Axios

    Servicio: segundaPantallaAnalisisIncidentesPaisesHUB

    function chartIncidentsForCountryHub (params) {
        return Axios.get(`${path}/segundaPantallaAnalisisIncidentesPaisesHUB?aniocurrent=${params.current}&anioprevious=${params.previous}`).then((response) => { return response.data })
    }

    Servicio: segundaPantallaAnalisisImpactosPaisesHUB

    function chartImpactsForCountryHub (params) {
        return Axios.get(`${path}/segundaPantallaAnalisisImpactosPaisesHUB?aniocurrent=${params.current}&anioprevious=${params.previous}`).then((response) => { return response.data })
    }

    Servicio: segundaPantallaAnalisisIncidentesPaisesNoHUB

    function chartIncidentsForCountryWithoutHub (params) {
        return Axios.get(`${path}/segundaPantallaAnalisisIncidentesPaisesNoHUB?aniocurrent=${params.current}&anioprevious=${params.previous}`).then((response) => { return response.data })
    }

    Servicio: segundaPantallaAnalisisImpactosPaisesNoHUB

    function chartImpactsForCountryWithoutHub (params) {
        return Axios.get(`${path}/segundaPantallaAnalisisImpactosPaisesNoHUB?aniocurrent=${params.current}&anioprevious=${params.previous}`).then((response) => { return response.data })
    }

    Servicio: segundaPantallaAnalisisPorPaisesTablaPaisesNoHUB

    function tablesForCountryWithoutHub (params) {
        return Axios.get(`${path}/segundaPantallaAnalisisPorPaisesTablaPaisesNoHUB?aniocurrent=${params.current}&anioprevious=${params.previous}`).then((response) => { return response.data })
    }

    Servicio: segundaPantallaAnalisisPorPaisesTablaPaisesHUB

    function tablesForCountryHub (params) {
        return Axios.get(`${path}/segundaPantallaAnalisisPorPaisesTablaPaisesHUB?aniocurrent=${params.current}&anioprevious=${params.previous}`).then((response) => { return response.data })
    }

~~~

## Parámetros de entrada
| Servicio    | Parametro                        |
| --------- |----------------------------------- |
| `chartIncidentsForCountryHub`  | **aniocurrent** , **anioprevious** |
| `chartImpactsForCountryHub`  | **aniocurrent** , **anioprevious** |
| `chartIncidentsForCountryWithoutHub`  | **aniocurrent** , **anioprevious** |
| `chartImpactsForCountryWithoutHub`  | **aniocurrent** , **anioprevious** |
| `tablesForCountryWithoutHub`  | **aniocurrent** , **anioprevious** |
| `tablesForCountryHub`  | **aniocurrent** , **anioprevious** |

## Parámetro de salida
| Servicio  | Tipo      | Descripción                         |
| --------- | --------- |------------------------------------ |
| `chartIncidentsForCountryHub`  | Consultar | Consultar |
| `chartImpactsForCountryHub`  | Consultar | Consultar |
| `chartIncidentsForCountryWithoutHub`  | Consultar | Consultar |
| `chartImpactsForCountryWithoutHub`  | Consultar | Consultar |
| `tablesForCountryWithoutHub`  | Consultar | Consultar |
| `tablesForCountryHub`  | Consultar | Consultar |

## Servicios
| Ruta    | Descripcion                         |
| --------- |------------------------------------ |
| `NA`  | NA  |

## Ejemplo de Uso

~~~
Vue

    Servicio: calendario

Axios

    Servicio: calendario

~~~

## Parámetros de entrada
| Servicio    | Parametro                        |
| --------- |----------------------------------- |
| `NA`  | NA |

## Parámetro de salida
| Servicio  | Tipo      | Descripción                         |
| --------- | --------- |------------------------------------ |
| `NA`  | NA | NA |

* ### Respuestas http
    ~~~

    Servicio: calendario

    

    ~~~


## Fecha de liberación de desarrollo
01/06/2023

## Nombre y correo del desarrollador
Nombre: Jonathan Alejandro Colin Medina

Correo: jonathanalejandro.colin.contractor@bbva.com

## Componentes hijos
| Componete    | Descripción                         |
| --------- |------------------------------------ |
| `HeaderHub`  | Componente que muestra el encabezado. |
| `Graph`  | Componente que muestra un gráfico. |
| `GraphHorizontal`  | Componente de gráfico personalizado. |
| `TableCountry`  | Componente que muestra una tabla de países. |
| `TableCountryInf`  | Componente que muestra informacion de una tabla de países. |
| `HeaderNotHub`  |  Componente que muestra el encabezado. |
| `Loading`  | Componente utilizado para mostrar un indicador de carga cuando se están cargando los datos. |

## Ejemplo de Uso

    <CountriesHub />