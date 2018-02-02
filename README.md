# Acerca de la BitLana

La BitLana es una criptomoneda enfocada en proveer un mecanismo descentralizado de intercambio y anonimidad por medio de transacciones  no rastreables y no vinculables.

¡La BitLana es de todos! El código es completamente abierto y gratuito para usar sin restricción alguna, excepto las especificadas en la licencia.

Si quieres hacer algún cambio al código, por favor haz un pull request en la rama `master`. 

Puedes conocer más de esta criptomoneda en [https://www.bitlana.com](https://www.bitlana.com)

## Suministro y emisión de monedas

* Suministro total: 18,446,744 monedas. Alrededor del 20% fue preminado para asegurar el desarrollo futuro de la criptomoneda.
* Símbolo: BLANA
* Unidades:
  * 1 bitlanita  = 0.000000000001 BLANA (12)
  * 1 bitlana = 1 BLANA (0)
* Algorítmo de proof-of-work: CryptoNight

## Compilando la BitLana

### En * nix / OS X

Dependencias: GCC 4.7.3 o superior, CMake 2.8.6 o superior, y Boost 1.59 o superior

Puedes descargar las dependencias de:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/

Para compilar, cambia al directorio donde se encuentra este archivo y ejecuta `make`. Los ejecutables los podrás encontrar en `build/release/src`.

#### Opciones avanzadas de compilación:

* Compilación en paralelo: Ejecuta `make -j<número de hilos>` en lugar de `make`.
* Compilación en modo de depuración: Ejecuta `make build-debug`.
* Banco de pruebas: Ejecuta `make test-release` para correr el banco de pruebas y compilar. Si ejecutas `make test-debug` hará lo mismo pero con el modo de depuración.

### En Windows

Dependencias: MSVC 2015 o superior, CMake 2.8.6 o superior, y Boost 1.59 o superior.

Puedes descargar las dependencias de:

* http://www.microsoft.com/
* http://www.cmake.org/
* http://www.boost.org/

Para compilar, cambia al directorio donde se encuentra este archivo, y ejecuta los siguientes comandos:

```
mkdir build
cd build
cmake -G "Visual Studio 14 Win64" ..
```

Y ahora compílala desde MSVC. 

En algunos casos, puede ser necesario que tengas que agregar de manera explícita la ruta a Boost:

```
cmake.exe -DBOOST_ROOT=C:\boost_1_59_0 -DBOOST_LIBRARYDIR=C:\boost_1_59_0\libs -G "Visual Studio 14 Win64" ..
```

## Comunidad y soporte

Nos puedes encontrar en:

* [Comunidad oficial de Telegram](https://t.me/inbestcoin)

## Licencia

BitLana está licenciado bajo la GNU Lesser General Public License v3.0.

## Créditos

Con tecnología de [CryptoNote Fundation](https://cryptonotefoundation.org/).
