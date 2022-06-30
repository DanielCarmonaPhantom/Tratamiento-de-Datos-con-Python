# Sesion 4

* ```object``` el cual representa a una cadena de caracteres.
* ```int64``` es el tipo para números enteros. 
* ```float64``` es el tipo para números de punto flotante.
* ```bool``` es el tipo para valores booleanos.
* ```datetime64``` es el tipo usado para gestionar fechas y horas.
* ```timedelta``` es el tipo de diferencias de tiempo. 
* ```category``` es un tipo de dato que contiene una colección finita de posibles valores

datos = pd.DataFrame({'nombres':('Carlos Ayala',
                                 'Martha Sánchez'
                                 , 'Jimena Ríos',
                                 'Raul Quiroz'),
            'fechas':(pd.datetime(1995,12,21), 
                      pd.datetime(1989,1,13), 
                      pd.datetime(1992,9,14), 
                      pd.datetime(1993,7,8)),
            'saldo': (3600, 
                      7452, 
                      np.NaN, 
                      12143.5),
            'al corriente':(True, 
                            True, 
                            False, 
                            True)})
