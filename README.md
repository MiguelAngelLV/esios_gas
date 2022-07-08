
# Componente PVPC para Home Assistant con soporte para Comepnsación del Gas



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
