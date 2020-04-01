# SHP files database

In this repository you will find a collection of some files in SHP format that I have been finding on the Internet. All the maps are of a geographical-political type. These maps were extracted from the following sources: 

- https://tapiquen-sig.jimdofree.com/descargas-gratuitas/

Note that I will try to update this shp repository with new maps over time :) 

The following Python syntax has been used to create the following maps 

```python

import matplotlib.pyplot as plt
import geopandas
import numpy as np

def create_maps(path_shp, title)

    data = geopandas.read_file(path_shp)
    data['Random'] = np.random.randn(datos.shape[0], 1)

    data.plot(column='Random')
    plt.title(title)
    plt.savefig(title + '.png')

```

As far as the different maps are concerned, you will find the following: 

## Spain

### Autonomous Communities 
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/Comunidades%20autonomas%20(Administrativo).png)
### Regions
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/Comarcas%20(Administrativo).png)
### Population centres 
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/Nucleos%20de%20poblacion%20(Administrativo).png)
### Provinces
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/Provincias%20%20(Administrativo).png)
### Urban agglomerations 
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/Aglomeraciones%20urbanas%20(Poblacion).png)
## Canada

### Provinces
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/Canada.png)
## Europe

### Countries
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/Europa.png)
## Mexico

### States
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/Mexico.png)
## South America 

### Countries
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/America%20del%20sur.png)
## United States 

### Counties 
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/USA%20Condados.png)
### Regions 
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/USA%20regiones.png)
### States 
![](https://github.com/Guillermo-C-A/SHP-files-data-base/blob/master/Examples/USA%20estados.png)
