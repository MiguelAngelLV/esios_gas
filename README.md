
# Componente PVPC para Home Assistant con soporte para Comepnsación del Gas


## Importante, cambio en los entities

Debido a unos typos, la última actualización puede obligarte a cambiar algunas configuraciones porque han cambiado algunos nombres.

Realmente no hace falta actualizar ahora mismo, pero si actualizas, lo más fácil es una vez cargue la integración renombrar los ID's al que tuviese antes para no tener problemas.


## Descripción

Esta es una modificación del componente publicado [aquí](https://github.com/azogue/aiopvpc/issues/9#issuecomment-968049577) que incluye soporte tanto para el precio de los excedentes.

Esta modificación añade además el precio de compensación del gas y un sensor adicional que suma ambos.

Tanto el componente original como este requiren un token de acceso a la API de ESIOS. Dicho token podéis solicitarlo enviando un correo a consultasios@ree.es.

## Instalación

Podéis instarlo tanto descargando este proyecto y copiándolo en la carpeta custom_component como usando HACS.

## Uso

Después de instalarlo, tendrás que añadirlo desde el apartado de integraciones buscando ESIOS

## Otros PVPC

Si tienes otros sensores PVPC, se recomenda desinstalarlos antes.


## Balance Neto

Si tienes instalación fotovoltaica es posible que te interese mi otro componente [Balance Neto Horario](https://github.com/MiguelAngelLV/balance_neto) para calcular de forma más precia los euros.
