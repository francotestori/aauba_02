# DETALLE DE LOS ARCHIVOS CSV

Estos son los archivos con los features de los wav sobre los que basamos nuestro analisis

## AUDIO ORIGINAL

### audio_digits.csv

Features de los WAV del dataset original sin alterar.

## RUIDO BLANCO ADITIVO

### audio_digits_AWN20.csv



* Features de los WAV del dataset original agregandole ruido blanco gaussiano (AWN) de potencia 1/20 con respecto a la señal original del audio limpio.
* Mucho ruido.


### audio_digits_AWN40.csv

* Features de los WAV del dataset original agregandole ruido blanco gaussiano (AWN) de potencia 1/40 con respecto a la señal original del audio limpio.
* Medio ruido.


### audio_digits_AWN100.csv

* Features de los WAV del dataset original agregandole ruido blanco gaussiano (AWN) de potencia 1/100 con respecto a la señal original del audio limpio.
* Poco ruido.

## RUIDO AMBIENTE ADITIVO EXTRAIDO DE QUT-NOISE_DB

### audio_digits_CAFE-CAFE-1_lvl_10.csv

* Features de los WAV del dataset original agregandole ruido de cafeteria de potencia 1/10 con respecto al archivo original de ruido.
* El archivo con la fuente de ruido es CAFE-CAFE-1.wav.


### audio_digits_CAFE-FOODCOURTB-1_lvl_10.csv

* Features de los WAV del dataset original agregandole ruido de patio de comidas de potencia 1/10 con respecto al archivo original de ruido.
* El archivo con la fuente de ruido es CAFE-FOODCOURTB-1.wav.


### audio_digits_HOME-KITCHEN-1_lvl_10.csv

* Features de los WAV del dataset original agregandole ruido de cocina de potencia 1/10 con respecto al archivo original de ruido.
* El archivo con la fuente de ruido es HOME-KITCHEN-1.wav.


### audio_digits_STREET-CITY-1_lvl_10.csv

* Features de los WAV del dataset original agregandole ruido de calle de potencia 1/10 con respecto al archivo original de ruido.
* El archivo con la fuente de ruido es STREET-CITY-1.wav.


## GRABACIONES PROPIAS

### self_recorded_digits.csv

* Features de los WAV del dataset de audios propios de pronunciaciones de digitos en ingles bajo distintas condiciones ambientales.
