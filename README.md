# Sesion 4

Contenido:

<a href='Sesion-04/Sesion-04.ipynb'>Sesión 4: Tipo de operaciones en Pnadas</>
  
indice = ['gerente', 'supervisor', 'vendedor', 'cajero']
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
