**Date created:** 3/11/26    
**Last Updated:** 4/14/26    
**Author:** Chloe Lucido (block of code adapted from Kai Saito)   
**Project:** mouse low dose ARIA (Akhil's project)  
**Purpose:** Analysis of low dose ARIA Xenium Spatial Transcriptomics data  
**Conda env:** scverse_env  
**Python kernel:** Python (scverse_env)   
**- 01.** create SpatialData object from Xenium output folders and format tables (anndata) with Seurat metadata  
**- 02.**     
**- 03.**      

**Packages used**    

 
anndata             0.12.0       
geopandas           1.1.2       
matplotlib          3.10.8     
numpy               2.3.5    
openpyxl            3.1.5   
pandas              3.0.1    
scanpy              1.11.5   
seaborn             0.13.2    
session_info        1.0.0   
shapely             2.1.2   
sklearn             1.8.0    
spatialdata         0.7.2   
spatialdata_io      0.6.0    
spatialdata_plot    0.2.14   
squidpy             1.8.1   
tifffile            2026.2.24   


Modules imported as dependencies    
CoreFoundation              NA   
Foundation                  NA  
PIL                         12.1.1   
PyObjCTools                 NA   
annotated_types             0.7.0   
annsel                      0.1.2   
anyio                       NA   
appnope                     0.1.4   
arrow                       1.4.0   
asttokens                   NA   
attr                        25.4.0   
attrs                       25.4.0   
babel                       2.18.0  
backports                   NA  
brotli                      1.2.0   
certifi                     2026.04.22  
charset_normalizer          3.4.4  
cloudpickle                 3.1.2  
comm                        0.2.3  
cycler                      0.12.1  
cython_runtime              NA  
cytoolz                     1.1.0  
dask                        2026.1.1  
dask_image                  NA  
datashader                  0.18.2  
dateutil                    2.9.0.post0  
debugpy                     1.8.20  
decorator                   5.2.1  
defusedxml                  0.7.1  
docrep                      0.3.2  
donfig                      0.8.1.post1  
executing                   2.2.1  
fast_array_utils            NA  
fastjsonschema              NA  
flexcache                   0.3  
flexparser                  0.4  
flowio                      1.4.0  
fqdn                        NA  
fsspec                      2026.2.0  
google_crc32c               NA  
h5py                        3.15.1  
idna                        3.11  
imagecodecs                 2025.11.11  
imageio                     2.37.0  
importlib_metadata          NA   
ipykernel                   7.2.0  
ipywidgets                  8.1.8  
isoduration                 NA   
jedi                        0.19.2  
jinja2                      3.1.6   
joblib                      1.5.3   
json5                       0.13.0  
jsonpointer                 3.0.0  
jsonschema                  4.26.0  
jsonschema_specifications   NA  
jupyter_events              0.12.0  
jupyter_server              2.17.0  
jupyterlab_server           2.28.0  
kiwisolver                  1.4.9  
lark                        1.3.1  
lazy_loader                 0.4  
legacy_api_wrap             NA  
llvmlite                    0.46.0  
lxml                        6.0.2  
lz4                         4.4.5  
markupsafe                  3.0.3  
matplotlib_scalebar         0.9.0  
more_itertools              10.8.0  
mpl_toolkits                NA  
msgpack                     1.1.2  
multipledispatch            0.6.0  
multiscale_spatial_image    2.0.3  
narwhals                    2.17.0  
natsort                     8.4.0  
nbformat                    5.10.4  
networkx                    3.6.1  
numba                       0.63.1  
numcodecs                   0.16.5  
objc                        12.1  
ome_types                   0.6.3  
ome_zarr                    0.13.0  
overrides                   NA  
packaging                   26.0  
parso                       0.8.6  
pathlib_abc                 NA  
patsy                       1.0.2  
pims                        0.7  
pint                        0.25.2  
platformdirs                4.9.2  
pooch                       v1.9.0  
prometheus_client           NA  
prompt_toolkit              3.0.52  
psutil                      7.2.2  
pure_eval                   0.2.3  
pyarrow                     23.0.1  
pyct                        0.6.0  
pydantic                    2.12.5  
pydantic_core               2.41.5  
pydantic_extra_types        2.11.0   
pydev_ipython               NA  
pydevconsole                NA  
pydevd                      3.2.3  
pydevd_file_utils           NA  
pydevd_plugins              NA  
pydevd_tracing              NA  
pygments                    2.19.2  
pyparsing                   3.3.2  
pyproj                      3.7.2  
pythonjsonlogger            NA  
pytz                        2025.2  
readfcs                     2.1.0  
referencing                 NA  
requests                    2.32.5  
rfc3339_validator           0.1.4  
rfc3986_validator           0.1.1  
rfc3987_syntax              NA  
rich                        NA  
rpds                        NA  
scipy                       1.17.1  
send2trash                  NA  
six                         1.17.0  
skimage                     0.26.0  
slicerator                  1.1.0  
sniffio                     1.3.1  
socks                       1.7.1   
spatial_image               1.2.3  
stack_data                  0.6.3  
statsmodels                 0.14.6  
tblib                       3.2.2    
testing                     NA  
threadpoolctl               3.6.0   
tlz                         1.1.0  
toolz                       1.1.0  
tornado                     6.5.4  
tqdm                        4.67.3  
traitlets                   5.14.3  
typing_extensions           NA  
typing_inspection           NA  
upath                       0.3.10  
uri_template                NA  
urllib3                     2.6.3  
validators                  0.35.0  
wcwidth                     0.6.0  
webcolors                   NA  
websocket                   1.9.0  
xarray                      2026.2.0  
xarray_dataclass            3.0.0  
xmltodict                   NA  
xrspatial                   0.5.3  
xsdata                      26.2  
xsdata_pydantic_basemodel   0.1.0  
yaml                        6.0.3  
zarr                        3.1.5  
zipp                        NA  
zmq                         27.1.0  
zoneinfo                    NA  

     
IPython             9.10.0  
jupyter_client      8.8.0  
jupyter_core        5.9.1  
jupyterlab          4.5.5  
notebook            7.5.4  
    
Python 3.11.14 | packaged by conda-forge | (main, Jan 27 2026, 00:01:01) [Clang 19.1.7 ]   
macOS-26.3.1-arm64-i386-64bit   


Session information updated at 2026-05-01 13:22   
