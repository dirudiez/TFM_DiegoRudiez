# TFM_DiegoRudiez
Repositorio donde se encuentran todas las pruebas realizadas en cuadernos de Jupyter. 

Se han realizado pruebas sin procesar los datos y empleando técnicas de balanceo. Se han separado por la función de pérdida usada, CEL (cross entropy loss) y FL (focal loss). Además, se ha hecho una subsivisión más para separarlos según la técnica de balanceo aplicada. El preprocesado de los datos y su análisis se incluye en también. Los modelos se han organizado se la siguiente forma:

```.
└── Repostorio TFM
    ├── /autoencoder
    └── /binario
        └── /CEL
            ├── /sinProcesar
            ├── /balanceoSklearn
            └── /balanceoImblearn
        └── /FL
            ├── /sinProcesar
            ├── /balanceoSklearn
            └── /balanceoImblearn
    └── /multi-label
        └── /CEL
        └── /FL
    └── /autoencoders
    └── 0. AnálisisDataset
    └── 1. ReducirDataset
    └── 2. ProcesarImagenes
```
