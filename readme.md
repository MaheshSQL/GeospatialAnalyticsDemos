---------

Geospatial Analytics Master Class demos

---------
conda create --name geospatial python==3.9 --yes

conda activate geospatial

conda install notebook ipykernel --yes

ipython kernel install --name geospatial --display-name "Python 3.9 (geospatial)" --user

---------
conda install --channel conda-forge geopandas --yes
#conda install geopandas --yes <==THIS GIVES CRS Error!!
pip install planetary-computer

pip install pyarrow
pip install fsspec
pip install adlfs

pip install contextily
pip install stackstac
pip install xarray-spatial

#To access the Azure ML datastore on CI
pip install -U azureml-fsspec mltable

pip install azure-storage-blob azure-identity
pip install azure-storage-file-datalake --pre

python -m pip install "dask[complete]"    # Install everything
pip install dask-geopandas
pip install dask-gateway

---------
