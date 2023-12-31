## Criterios de Correccion Requisitos Lenguaje Natural
### Aspectos generales:
Hay que desarrollar una especificación de requisitos en lenguaje natural. Qué se espera de ella:

#### Muy críticos (pueden invalidar la resolución)
* Que incluya al menos un índice
* Que tenga una estructura que siga los lineamientos propuestos por [Weigers] (no necesariamente debe ser igual) Se debe ir de lo general a lo particular y los requisitos deben agruparse de acuerdo a algún tipo de criterio.
* Que sea clara, consistente, auto explicativa.
* Que identifique y clasifique correctamente cada uno de los requisitos (al menos se deben diferenciar los funcionales de los no funcionales)

#### Críticos
* Que incluya carátula e índice (Preguntar que es la caratula)
* Opcionalmente, que se sigan los lineamientos EARS al describir los requisitos.

#### Menores
* Faltas de ortografía
* Que se hable en presente como si ya estuviera hecho el sistema (Sacado de una correccion)
* No se describe como se calculan subtotales, descuentos y totales (Sacado de una correccion)

### Temas importantes en este ejercicio:
#### Muy críticos
##### La cantidad de requisitos puede variar. Lo importante es que se refleje la siguiente funcionalidad:
- Actualización de aranceles de matrículas y cuotas
- Emisión y envío de facturas
- Cobro mediante tarjetas de crédito/débito, con autorización contra el Gateway de Pagos
- Recepción y registro del comprobante de pago por transferencia
- Envío diario de las transacciones de pago al Gateway de Pagos.

###### No se debe describir ningún aspecto de implementación. Se deben describir los requisitos funcionales, es decir, la esencia del sistema (lo que el sistema debe hacer independientemente de cómo se implemente) Los requisitos no funcionales pueden deducirse a partir de la descripción que se hace de ciertos aspectos particulares, pero deben ser bien específicos..

#### Críticos
* Se debe incluir una visión general del sistema.
* Se debe aclarar cómo se hacen los cálculos. También se debe describir la interacción con el gateway de pagos.
* Se debe describir claramente la composición de la información intercambiada con los actores externos. Es deseable incluir un glosario con la descripción de la información que debe manejar internamente el sistema.

#### Menores
* Faltas de ortografía y/o falta de claridad en la redacción.
