# Temporal-Series

## Description of the project

<style>body {text-align: justify}</style>

The main goal of this project was to study the features about 'Turismos' data set, that can be found in [this page](http://www.minetad.gob.es/es-ES/IndicadoresyEstadisticas/Paginas/Estadisticas.aspx), and make predictions about it. The data set is about the production of tourisms in Spain and the observations are reported monthly.

First of all, we applied Box-Jenkins methodology to obtain a stationary series. Once the temporal series was transformed, some posible models were proposed to fit it. Then, the validation of residuals was done to study how good our models were. 

At that point, and just before analysing some statistics as AIC or BIC, we removed the last year of the series and predicted it. By that, we were able to compute some statistics (MAPE & RMSPE) and check if the predictions resembled the observations.

By last, we linealised (removed the outliers) the series with the model chosen regarding the above metrics. Thus, we had to apply Box-Jenkins again for the linealized temporary series and repeat the same steps, fit some models, and for the one chosen, predict the following year for which we didn't have information. 

- - -

## Authors

Rodrigo Bonferroni (https://github.com/RodrigoBonferroni) & Pol Lizaran Campano (https://github.com/PolLizaran)

Data Science and Engineering, UPC, 2022
