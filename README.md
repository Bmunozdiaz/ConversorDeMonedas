# 💱 Conversor de Monedas

Aplicación de consola en Java que permite convertir entre diferentes monedas utilizando la API de ExchangeRate.

##  Características

- Conversión entre 6 pares de monedas diferentes
- Consumo de API REST en tiempo real
- Manejo de errores y validaciones
- Interfaz de consola amigable

##  Tecnologías

- Java 17+
- Gson para parsing de JSON
- HttpClient de Java
- ExchangeRate API

##  Configuración

1. Clona el repositorio
2. Crea un archivo `config.properties` en la raíz del proyecto
3. Agrega tu API key de ExchangeRate:
```properties
   api.key=TU_API_KEY_AQUI
```
4. Obtén tu API key gratuita en: https://www.exchangerate-api.com/

##  Uso

1. Ejecuta la clase `Principal.java`
2. Selecciona una opción del menú (1-7)
3. Ingresa el monto a convertir


##  Conversiones disponibles

1. Peso Chileno (CLP) ↔ Dólar (USD)
2. Peso Chileno (CLP) ↔ Real Brasileño (BRL)
3. Peso Chileno (CLP) ↔ Peso Argentino (ARS)

## Autor
[Bmunozdiaz](https://github.com/Bmunozdiaz)
