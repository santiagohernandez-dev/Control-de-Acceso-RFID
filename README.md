# Sistema de control de acceso RFID

**Universidad Nacional de Colombia – Sede Manizales**  
Asignatura: Diseño Electrónico  
2026-II

## Descripción del proyecto

Sistema electrónico de control de acceso mediante tecnología RFID, basado en ESP32-C3, con identificación de credenciales, autorización de usuarios, registro de eventos y supervisión mediante una interfaz web local.

## Características del sistema

- Microcontrolador ESP32-C3-WROOM-02-N4.
- Lector RFID RC522.
- Reloj de tiempo real DS3231.
- Interfaz de almacenamiento MicroSD.
- Accionamiento de cerradura eléctrica de 12 V.
- Comunicación WiFi local.
- Exportación de registros en formato CSV.
- Diseño esquemático y PCB en Altium Designer.

## Documentación técnica

| Documento | Archivo |
|---|---|
| Documento de requerimientos | [Consultar PDF](Control_Acceso_RFID_Entrega_Final.pdf) |
| Nota de aplicación | [Consultar PDF](Nota_de_Aplicacion_Control_Acceso_RFID.pdf) |
| Presentación final | [Consultar PDF](Presentacion_RFID_Entrega_Final.pdf) |

## Especificaciones técnicas

| Parámetro | Valor |
|---|---|
| Alimentación | 12 V DC / 2 A |
| Potencia disponible | 24 W |
| Potencia máxima estimada | 15,12 W |
| Tensiones de regulación | 3,3 V y 5 V |
| Dimensiones de la PCB | 74,16 × 61,57 mm |
| Protocolos | SPI, I2C, WiFi y HTTP |

## Prueba de concepto

La prueba de concepto permitió demostrar la identificación de credenciales RFID, la autorización de usuarios, el registro de eventos y su visualización mediante una interfaz web local.

## Herramientas de desarrollo

- Altium Designer.
- Arduino IDE.
- Visual Studio Code.
- PlatformIO.

## Aplicaciones

- Laboratorios universitarios.
- Espacios de acceso restringido.
- Oficinas.
- Sistemas de registro y supervisión de accesos.
