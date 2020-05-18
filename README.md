## Analysing air quality trends in Madrid during the COVID-19 crisis.

The aim of this project is to analyse how the social distancing measures taken be the governent and the stop of the economy during the Covid-19 crisis have impacted air quality in Madrid. 

The first case of COVID-19 in Spain was confirmed on 31st January 2020. However, public bodies did not take any serious measure to contrain the pandemic until 9th March, when educational institutions where temporaly closed in Madrid. Since then, more dramatic measures, including the approval of the state of alarm, have been adopted in Madrid as well as the rest of the country. 

This scenario has led to significant decreases in air pollution in Madrid, which can be attributed to a slowdown in economic and urban activity in response to the COVID-19 pandemic.

The conducted analysis has been published (in Spanish) in [Agenda Pública](http://agendapublica.elpais.com/la-calidad-del-aire-en-madrid-en-tiempos-del-coronavirus/).

### Datasets Description

The datesets contain quality-assured daily readings from air quality monitoring stations across Madrid in the period 2010-2020.

The data can be found in the [City of Madrid's Open Data Portal](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=aecb88a7e2b73410VgnVCM2000000c205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default).

A description of the data and monitoring methodology can be found in [here](https://datos.madrid.es/FWProjects/egob/Catalogo/MedioAmbiente/Aire/Ficheros/Interprete_ficheros_%20calidad_%20del_%20aire_global.pdf).

The database with information about the monitoring stations is also included.

### Air quality data description

* PROVINCIA = Numeric code of the province (28).
* MUNICIPIO = Numeric code of the municipality(079).
* ESTACION = Monitoring station number.
* MAGNITUD = Measured value. See Annexe II ["Magnitudes, unidades y técnicas de medida"](https://datos.madrid.es/FWProjects/egob/Catalogo/MedioAmbiente/Aire/Ficheros/Interprete_ficheros_%20calidad_%20del_%20aire_global.pdf).
* PUNTO_MUESTREO = Measurement point. It has the folling format: XXYYYZZZ_M_TT.
    * * XX = Province code
    * * YYY = Municipality code
    * * ZZZ = Monitoring station number
    * * M = Monitored particle.
    * * TT = Técnica de medida
* ANO = Year of the measurement.
* MES = Month of the measurement.
* D01 - D31 = Day of the measurement.
* V01 - V31 = Whether the measurement if valid or not. Valid measurements are marked with a "V"
 
