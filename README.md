# Prueba Ingreso Front (Selenium + Rest Assured)

Este proyecto nos permite ejectuar 5 casos de pruebas automatizadas utilizando la página web de:

https://www.falabella.com/falabella-cl

Puedes instalar el proyecto clonando el repositorio:

- $ git clone 'url'


Luego de haber clonando el proyecto, puedes utilizar los siguientes comandos para lanzar los test:

1. Para lanzar el test suite completo (incluye los 5 caso de pruebas):
  mvn -P AllTestSuite test
  
2. Para lanzar un test case individualmente, puedes utilizar los siguientes comandos:
  mvn -Dtest=test.TestCase00<X>
  
  *Importante reemplazar el <X> por un numero entre 1 al 5, dependiendo cual test case deseas lanzar.*
