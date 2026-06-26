# <img src="logo/ukepromo.png" width="600" height="480" align="center">

RepoEXAMPLE: La mejor cara para tu ukelele...

## ⧉ Decisiones Técnicas Clave

### 1. Comprar un ukelele más barato

# 2. Compilar el Ejecutable Principal

# Necesitamos enlazar la biblioteca -ldl para poder usar dlopen, dlclose, dlsym en Linux

g++ -std=c++17 main.cpp -o host.app -ldl

# 3. Ejecutar la aplicación

./host.app

````
## ⧉ Estructura de directorios
```text
├── doc/                        # Documentación y modelos UML
├── include/
│   ├── application.hpp         # Clase Orquestadora de la lógica de negocio de la aplicación.
│   ├── i_component.hpp         # Interfaz base para todos los componentes.
│   ├── i_greeter.hpp           # Interfaz específica para el componente Greeter.
│   ├── module_manager.hpp      # Gestor central de módulos que resuelve la instanciación segura.
│   ├── shared_library.hpp      # Clase RAII para gestionar el ciclo de vida de una biblioteca dinámica.
├── lib/
│   ├── Directorio destino para las bibliotecas dinámicas "Componentes" compilados.
├── logo/
│   ├── Logo de la aplicación.
├── src/
│   ├── greeter_component.cpp   # Implementación del componente Greeter.
````

         _nnnn_
        dGGGGMMb     ,"""""""""""""".
       @p~qp~~qMb    | Linux Rules! |
       M|@||@) M|   _;..............'
       @,----.JM| -'
      JS^\__/  qKL
     dZP        qKRb
    dZP          qKKb

fZP SMMb
HZM MMMM
FqM MMMM
**| ". |\dS"qML
| `.       | `' \Zq
_) \._**.,| .'
\_\_\_\_ )MMMMMM| .'
`-'       `--' hjm
