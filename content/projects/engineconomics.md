---
title: "Engineconomics"
date: 2023-03-12T10:54:59-05:00
draft: false
---


 ![alt text](/images/engineconomics/img_1.png)

Desarrollador de la libreria para Python [**EngineEconomics**](https://github.com/tiagogiraldo/engineconomics). Diseñada para resolver los principales problemas que se plantean en el área de la Ingeniería Económica. Se centra en las matemáticas financieras que ocurren en periodos de tiempo discretos. 

Los flujos de caja que se analizan con esta librería están restringidos a tiempos uniformes o fracciones, sin tener en cuenta flujos de caja asociados a fechas, si se tiene algo así se deben convertir los periodos a enteros o fracciones de tiempo para ser evaluados con las funciones aquí desarrolladas.

Con esta herramienta es posible graficar flujos de caja comúnmente encontrados en Economía de la Ingeniería, Finanzas, Banca, Evaluación de Proyectos y Economía relacionada con el Valor del Dinero en el Tiempo.

Las funciones desarrolladas pueden ser tratadas dentro de dataframes de la librería Pandas, y así aprovechar las funcionalidades que esta librería ofrece.

La librería consta de 5 clases

- factor: diseñada para calcular los factores con los que se relacionan los flujos de caja discretos.

- tiempo_valor: Esta clase se utiliza para estimar los valores del dinero en el tiempo según el tipo de flujo de caja que se quiera encontrar.

- time_value_plot: Esta clase permite graficar de forma sencilla los flujos de caja según el factor utilizado.

- time_value_table: Esta clase se utiliza para generar dataframes en pandas.

- compound_interest: Esta clase permite realizar conversiones de tipos de interés entre diferentes periodos de tiempo.
