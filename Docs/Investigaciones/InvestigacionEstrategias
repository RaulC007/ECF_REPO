# Investigación de Estrategias de Trabajo Colaborativo en Git

## 1.1 Feature Branch (Ramas por Funcionalidad)

¿Qué es?
Una Feature Branch es una rama independiente en un sistema de control de versiones (por ejemplo, Git) que se crea para desarrollar una función o característica específica. El código dentro de esta rama está separado de la base principal del código (main o master), lo que permite a los desarrolladores llevar a cabo cambios y probar nuevas funcionalidades sin afectar la estabilidad del código principal.

Características y Beneficios:
• Al crear una rama separada para cada funcionalidad, los desarrolladores pueden trabajar en nuevas características sin afectar la estabilidad del código principal. Esto permite un desarrollo y pruebas más eficientes.
• Permiten mantener un historial claro de las distintas versiones del código. Si es necesario, los desarrolladores pueden revertir a una versión anterior con facilidad.
• Sirven para validar nuevas funciones antes de lanzarlas a producción. Esto permite detectar y corregir errores a tiempo, antes de afectar a los usuarios finales.

## 1.2 Flujo de Trabajo Centralizado

¿Qué es?
En sistemas centralizados, habitualmente solo hay un modelo de colaboración: el flujo de trabajo centralizado. Consiste en un repositorio o punto central que acepta código, y todos los integrantes sincronizan su trabajo directamente con él. Unos cuantos desarrolladores actúan como nodos de trabajo —consumidores de dicho repositorio— y sincronizan de forma continua con ese punto.

Integración:
Esto significa que si dos desarrolladores clonan desde el punto central y ambos hacen cambios, solo el primer desarrollador en subir sus cambios lo podrá hacer sin problemas. El segundo desarrollador debe fusionar obligatoriamente el trabajo del primero antes de subir sus propios cambios, garantizando así que no se sobrescriba la información previa.

## 1.3 Fork (Bifurcaciones)

¿Qué es?
En el modelo basado en bifurcaciones, existe un repositorio de proyecto bajo una organización ascendente (upstream) administrado por el maestro de código. Cada desarrollador obtiene una copia completa y personal (fork) de dicho repositorio en su propia cuenta.

Funcionamiento:
• El repositorio del proyecto administrado bajo la organización ascendente puede tener múltiples restricciones, tales como reglas de protección de ramas, donde la rama principal (master/main) solo se actualiza mediante solicitudes de extracción (Pull Requests).
• Es posible que un desarrollador no tenga permisos de escritura directa para crear ramas en el repositorio upstream, pero tiene acceso ilimitado a su versión fork del mismo.
• Si el repositorio es privado, únicamente los colaboradores explícitamente invitados podrán acceder a él.


## 2. Tabla Comparativa de Estrategias

| Estrategia | ¿Qué es? | ¿Cómo funciona y ventajas? | Consideraciones y Restricciones |
| --- | --- | --- | --- |
| **Feature Branch** | Rama independiente separada de la base principal (main/master) creada para desarrollar una función o característica específica. | • Desarrolla y prueba nuevas funciones sin afectar la estabilidad del código principal.<br>• Mantiene un historial claro que facilita revertir a versiones anteriores.<br>• Permite validar cambios y corregir errores antes de lanzar a producción. | Requiere el uso de Pull Requests para revisar e integrar el código de vuelta a la rama principal. |
| **Flujo Centralizado** | Modelo de colaboración basado en un único repositorio central con el que todos los desarrolladores sincronizan su trabajo. | • Todos los desarrolladores actúan como nodos de trabajo enviando y consumiendo código de un único punto.<br>• Modelo tradicional, directo y de aprendizaje inmediato. | • Si dos desarrolladores modifican a la vez, solo el primero sube directamente.<br>• El segundo debe fusionar obligatoriamente los cambios del primero antes de subir para no sobrescribirlos. |
| **Fork (Bifurcaciones)** | Modelo donde cada desarrollador obtiene una copia completa (bifurcación) del repositorio en su propia cuenta personal. | • Otorga control e independencia total al desarrollador dentro de su propio fork.<br>• Protege totalmente el repositorio principal de modificaciones directas no autorizadas. | • La rama principal del repositorio upstream no permite envíos directos y solo se actualiza mediante Pull Requests.<br>• Si el repositorio es privado, requiere invitación explícita. |

