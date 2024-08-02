# Algoritmos

Este proyecto está desarrollado en Java utilizando la interfaz Java Swing. Para ejecutar este proyecto, es necesario contar con el Java Development Kit (JDK) 8 o superior instalado en el entorno de ejecución. El repositorio se actualiza periódicamente con ejemplos y prácticas sobre diversos tipos de encriptaciones existentes.

## Algoritmos en la Lista
- AES
- RSA

---

### Algoritmo AES

Este proyecto implementa el algoritmo de encriptación AES (Advanced Encryption Standard) con un modo de operación ECB (Electronic Codebook) y un esquema de relleno PKCS5Padding.

#### Parámetros del Algoritmo

- **Semilla:** Valor utilizado para la encriptación. Debe ser definido previamente.
- **Valor:** Ingrese el valor que desea encriptar. Si desea encriptar múltiples valores, sepárelos con comas.
- **Resultado:** Resultado del proceso de encriptación o desencriptación.

#### Nota sobre la Seguridad

El modo ECB (Electronic Codebook) es uno de los modos de operación más básicos de AES. Sin embargo, no es el más seguro para muchos usos debido a que no oculta patrones en los datos. Para una mayor seguridad, se recomienda utilizar modos de operación como CBC (Cipher Block Chaining) junto con un vector de inicialización (IV).

---

### Algoritmo RSA

Este proyecto demuestra cómo implementar un encriptador y desencriptador utilizando criptografía de clave pública y privada (RSA) en Java.

#### Funcionalidades

- Generar nuevas claves públicas y privadas.
- Encriptar/desencriptar valores utilizando las claves generadas.

#### Nota sobre el Uso

Para la encriptación se utiliza la clave pública y para la desencriptación se utiliza la clave privada.
