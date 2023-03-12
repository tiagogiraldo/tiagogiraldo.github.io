---
title: "Engineconomics"
date: 2023-03-12T10:54:59-05:00
draft: false
---

 ![alt text](/images/engineconomics/img_1.png)

 
 [**EngineEconomics**](https://github.com/tiagogiraldo/engineconomics) is a library developed in Python. It was designed to solve the main problems 
 that arise in the area of Engineering Economics. It focuses on financial mathematics that occur over discrete time periods. The cash flows that are analyzed with this library are restricted to uniform times or fractions, without taking into account cash flows associated to dates, if you have something like that you must convert the periods to integers or fractions of time to be evaluated with the functions developed here.

With this tool it is possible to plot cash flows commonly encountered in Engineering Economics, Finance, Banking, Project Assessment, and Economics related to the Time Value of Money.

The functions developed here can be treated within dataframes of the Pandas library, and thus take advantage of the functionalities that this library offers.

The library consists of 5 classes:

-    factor: designed to calculate the factors to which discrete cash flows relate.

-    time_value: This class is used to estimate the values of money over time according to the type of cash flow to be found.

-    time_value_plot: This class allows to plot in a simple way the cash flows according to the factor used.

-    time_value_table: This class is used to generate dataframes in pandas.

-    compound_interest: This class allows interest rate conversions between different time periods.
