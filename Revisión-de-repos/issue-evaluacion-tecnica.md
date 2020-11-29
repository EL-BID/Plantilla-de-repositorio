### Este issue forma parte del proceso de revisión del Laboratoria Code Squads Noviembre 2020 de la iniciativa Código para el desarrollo del @EL-BID.

## Issue de revisión de evaluación técnica:

Al haber contrastado la información presentadas en el repo oficial con los campos solicitados en la plantilla de README.md hemos encontrado los siguiente puntos a mejorar:

- [ ] Agregar el microservicio de reportes de evaluación estática de código de Sonarcloud, teniendo en cuenta que las condiciones ideales de los reportes son:

      1 Ausencia de fallos estructurales
      2 Menos del 25% de líneas duplicadas
      3 Menos de 10 problemas críticos
      4 Más del 50% de clases, interfaces y métodos documentados
      5 Deuda técnica menor a 30 días
      6 Cobertura de test más del 25%
      
      Esto se valida automáticamente cuando corre el reporte del último commit del repositorio.
      
- [ ] Agregar el badge en markdown de este servicio visible en el readme.md.

- [ ] Agregar un microservicio de integración continua de código, recomendamos Travis CI (opcional).

- [ ] Agregar el badge del microservicio de integración continua de código visible en el readme.md. El build debe estar en estado passing.(opcional).

- [ ] Actualizar versión de todas las dependencias.

## Caso de uso de este template:
https://github.com/datauy/ElijoEstudiar/issues/103
