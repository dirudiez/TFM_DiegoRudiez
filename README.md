# TFM_DiegoRudiez
Repositorio donde se encuentran todas las pruebas realizadas en cuadernos de Jupyter. 

Se han realizado pruebas sin procesar los datos y empleando técnicas de balanceo. Se han separado por la función de pérdida usada, CEL (cross entropy loss) y FL (focal loss). El preprocesado de los datos y su análisis se incluye también. Los modelos se han organizado se la siguiente forma:

```.
└── Repostorio
    ├── autoencoder
    └── /binario
        └── /CEL
            ├── sinProcesar
            ├── balanceoSklearn
            └── balanceoImblearn
        └── /FL
            ├── sinProcesar
            ├── balanceoSklearn
            └── balanceoImblearn
    └── /multi-label
        └── CEL
        └── FL
    └── /autoencoders
    └── /autoencoders
    └── /autoencoders
```
