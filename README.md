# ALGORITMO DE ENCRIPTACIÓN

Este proyecto está desarrollado en Java utilizando la interfaz Java Swing. Para ejecutar este proyecto, es necesario contar con Java 1.8 instalado en el entorno de ejecución.

## ALGORITMO AES

Este proyecto implementa el algoritmo de encriptación AES (Advanced Encryption Standard) con un modo de operación ECB (Electronic Codebook) y un esquema de relleno PKCS5Padding.

### Parámetros del Algoritmo

- **SEMILLA:** Valor utilizado para la encriptación. Debe ser definido previamente.
- **VALOR:** Ingrese el valor que desea encriptar. Si desea encriptar múltiples valores, sepárelos con comas.
- **RESULTADO:** Resultado del proceso de encriptación o desencriptación.

### Nota sobre la Seguridad

El modo ECB (Electronic Codebook) es uno de los modos de operación más básicos de AES. Sin embargo, no es el más seguro para muchos usos debido a que no oculta patrones en los datos. Para una mayor seguridad, se recomienda utilizar modos de operación como CBC (Cipher Block Chaining) junto con un vector de inicialización (IV).

