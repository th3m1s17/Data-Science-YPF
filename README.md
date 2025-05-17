Trabajo-Final: Ingenia-2025
Detección de fraudes en transacciones bancarias


INTEGRANTES GRUPO 7 
Integrantes
Vanessa Carpio
Nancy Lopez 

Introducción
Este proyecto es parte del trabajo final para el curso de Data Science dictado por Fundación YPF - 2025
El pago en línea es el método de transacción más popular en el mundo hoy en día. Sin embargo, el aumento de los pagos en línea también conlleva un aumento del fraude. El objetivo de este análisis identificar pagos fraudulentos y no fraudulentos . El conjunto de datos proviene de Kaggle, que contiene información histórica sobre transacciones fraudulentas que puede utilizarse para detectar fraudes en pagos en línea.


OBJETIVOS
Desarrollar un modelode analisis para  detectar  los prosibles fraudes , que se deaslloran en las distintos tipos de transacciones , (:CASH-IN, CASH-OUT, DEBIT, PAYMENT y TRANSFER.)
basandose en los compartamiento de los montos como asi tambien los dias que se realizan esas transacciones y poder ver que cuentas estan siendo afectadas , como tambien el destino donde va ese dinero o esas transferencia


el data set consiste en  10 tipos de variables:


step: mapea una unidad de tiempo en el mundo real. En este caso 1 step es 1 hora de tiempo. Pasos totales 744 (31 días de simulación).


type:  tipo de transaccion en linea :CASH-IN, CASH-OUT, DEBIT, PAYMENT y TRANSFER.


amount: cantidad de la transacción en moneda local.


nameOrig: cliente que inició la transacción


oldbalanceOrg: saldo inicial antes de la transacción


newbalanceOrig: nuevo saldo después de la transacción.

nameDest: cliente que es el destinatario de la transacción


oldbalanceDest: receptor inicial de saldo antes de la transacción. Tenga en cuenta que no hay información para los clientes que comiencen con M (Merchants).
newbalanceDest: nuevo receptor de saldo después de la transacción. Tenga en cuenta que no hay información para los clientes que comiencen con M (Merchants).


isFraud: Estas son las transacciones realizadas por los agentes fraudulentos dentro de la simulación. En este conjunto de datos específico el comportamiento fraudulento de los agentes pretende beneficiarse tomando el control o las cuentas de los clientes y tratar de vaciar los fondos transfiriendo a otra cuenta y luego sacar el dinero del sistema.


isFlaggedFraud: El modelo de negocio tiene como objetivo controlar las transferencias masivas de una cuenta a otra y marca intentos ilegales. Un intento ilegal en este conjunto de datos es un intento de transferir más de 200.000 en una sola transacción.







 Dataset utilizado

El conjunto de datos utilizado aquí se obtuvo de Kaggle.com, un sitio web popular para buscar y publicar conjuntos de datos. Se trata de un conjunto de datos enorme que, como se mencionó, presenta miles de transacciones monetarias, independientemente de si fueron consideradas fraudulentas por la autoridad competente. Este conjunto se utilizará como material para desarrollar y entrenar los modelos de clasificación. Sin embargo, dado que el conjunto de datos es considerablemente grande (su archivo CSV supera los 400 MB), por lo tanto lo subiremos desde gitlab para que puedan guardarse los datos y poder utilizarlos 

Website del database
https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset


Estructura del Repositorio
README.md
Dataset (setFraudes.cvs)
dataSetFraude1.ipynb

Limpieza de Datos
Pasos que aplicamos en la limpieza del dataset
Carga de base de datos 
Visualización de base de datos
Analizamos las variables y vemos de que tipo son las mismas
Cantidad de Filas y Columnas 
Estadistica descriptiva basica 
Nulos y eliminación de los mismos 
Función Discrep 
Cantidad de registros 
Botsplot 
Matriz de correlación
Histograma



 Estructura del repositorio
Limpieza de Datos
Pasos que aplicamos en la limpieza del dataset
+Carga de base de datos
+Visualización de base de datos +
Analizamos las variables y vemos de que tipo son las mismas +
Cantidad de Filas y Columnas +
Estadistica descriptiva basica +
Nulos y eliminación de los mismos +
Función Discrep 
Cantidad de registros 
Botsplot 
Histograma



Metodología
Análisis de base de datos mediante codigos de Python
Librerias  Panda  Numpy,matplotlib,sklearn,seaborn

 Herramientas utilizadas
Google colab
excel
Github
Gitlab
Jupiter 





