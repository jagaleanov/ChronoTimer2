# Chronotimer2
## Jorge Galeano && Juan Sebastian Moreno
## Diagrama de casos de uso
![Diagrama de casos de uso](01casosUso.png)

## Diagramas de actividades
### Cronómetro
#### Iniciar
![Diagrama de actividades - Iniciar cronómetro](02actividadIniciarChrono.png)
#### Pausar 
![Diagrama de actividades - Pausar cronómetro](03actividadPausarChrono.png)
#### Guardar memoria 
![Diagrama de actividades - Guardar memoria cronómetro](04actividadGuardarMemoriaChrono.png)
#### Detener 
![Diagrama de actividades - Detener cronómetro](05actividadDetenerChrono.png)
#### Reiniciar 
![Diagrama de actividades - Reiniciar cronómetro](06actividadReiniciarChrono.png)

### Temporizador
#### Establecer tiempo inicial
![Diagrama de actividades - Establecer temporizador](07actividadEstablecerTempo.png)
#### Inciar 
![Diagrama de actividades - Inciar temporizador](08actividadIniciarTempo.png)
#### Pausar 
![Diagrama de actividades - Pausar temporizador](09actividadPausarTempo.png)
#### Reiniciar 
![Diagrama de actividades - Reiniciar temporizador](10actividadReiniciarTempo.png)


## Especificación de requerimientos
| Requerimiento:                          | Iniciar cronómetro                                                |
| --------------------------------------- | ----------------------------------------------------------------- |
| Actores:                                | Usuario                                                           |
| Precondiciones:                         | El cronómetro esta pausado                                        |
| Escenarios:                             |                                                                   |
| 1                                       | El cronómetro cambia estado a avanzar                             |
|                                         | El cronómetro inicia avanzar cronómetro
| 2                                       | Si el cronómetro no esta en estado de pausa, iniciar no es válido |
| Poscondiciones:                         | El cronómetro esta en estado avanzar                              |








## Diagramas de secuencia
### Cronómetro
#### Iniciar
![Diagrama de secuencia - Iniciar cronómetro](11secuenciaIniciarChrono.png)
#### Pausar 
![Diagrama de secuencia - Pausar cronómetro](12secuenciaPausarChrono.png)
#### Pausar 
![Diagrama de secuencia - Pausar cronómetro](13secuenciaGuardarMemoriaChrono.png)
#### Detener 
![Diagrama de secuencia - Detener cronómetro](14secuenciaDetenerChrono.png)
#### Reiniciar 
![Diagrama de secuencia - Reiniciar cronómetro](15secuenciaReiniciarChrono.png)

### Temporizador
#### Establecer tiempo inicial 
![Diagrama de secuencia - Establecer temporizador](16secuenciaEstablecerTempo.png)
#### Iniciar 
![Diagrama de secuencia - Iniciar temporizador](17secuenciaIniciarTempo.png)
#### Pausar 
![Diagrama de secuencia - Iniciar temporizador](18secuenciaPausarTempo.png)
#### Reiniciar 
![Diagrama de secuencia - Reiniciar temporizador](19secuenciaReiniciarTempo.png)

## Diagramas de flujo de datos
### Avanzar cronómetro
![Diagrama de flujo - Avanzar cronómetro](AvanzarChrono.png)
### Retroceder temporizador
![Diagrama de flujo - Retroceder temporizador](RetrocederTemporizador.png)

## Diagrama de clases
![Diagrama de clases](clases.png)
