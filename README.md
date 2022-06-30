# Sesion 4

Contenido:

<a href='Sesion-04/Sesion-04.ipynb'>Sesión 4: Tipo de operaciones en Pnadas</>
 
 indice = ['gerente', 'supervisor', 'vendedor', 'cajero']
datos = pd.DataFrame({'nombres':('Carlos Ayala',
                                 'Martha Sánchez'
                                 , 'Jimena Ríos',
                                 'Raul Quiroz'),
            'fechas':(dt.datetime(1995,12,21), 
                      dt.datetime(1989,1,13), 
                      dt.datetime(1992,9,14), 
                      dt.datetime(1993,7,8)),
            'saldo': (3600, 
                      7452, 
                      np.NaN, 
                      12143.5),
            'al corriente':(True, 
                            True, 
                            False, 
                            True)},
            index=indice)

### El método ```iloc[ ]```.

El método ```iloc[ ]``` permite identificar a uno o más elemento dentro de un renglón de un dataframe utilizando números enteros para referenciar tanto al índice como a las columnas.
