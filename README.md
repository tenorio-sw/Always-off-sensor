
## Objetivo
Ele simplesmente chama a função service call sensor_privacy, chamando a versão do android via "getprop ro.build.version.release" para fazer a ativação.

Ele não funciona em dispositivo anteriores ao android 10, por motivo da função ser inexistente.