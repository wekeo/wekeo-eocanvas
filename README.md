# wekeo-eocanvas

**wekeo-eocanvas** is a collection of Python-based code 
designed to provide introductory training on the use 
of the [eocanvas]('https://earthkit-data.readthedocs.io/en/latest/examples/wekeo.html') tool . This module is designed to stand-alone but also forms parts of wider 
WEkEO training activities.

WEkEO EOCanvas is a service to bring serverless processing for all Copernicus data to users. The EOCanvas python module or API enables users to process and analyse data without downloading any files to the local directory. In general, all data, which is available though the <a href='https://www.wekeo.eu/docs/harmonised-data-access-api' target='_blank'>Harmonised Data Access (HDA) API</a> can be processed throu the EOCanvas service. The processes are executed on the cloud, so that only the final result is downloaded to the local directory. 

EOCanvas Read The Docs: https://eocanvas.readthedocs.io/en/latest/index.html
EOCanvas Github : https://github.com/wekeo/eocanvas

## License
 
This code is licensed under an MIT license. 
See file LICENSE.txt for details on the usage and distribution terms.

All product names, logos, and brands are property of their respective owners. 
All company, product and service names used in this website are for 
identification purposes only.
 

## Authors
* [**Anna-Lena Erdmann**](mailto://annalena.erdmann@eumetsat.int) - *Initial development* - [EUMETSAT](http://www.eumetsat.int)

 
## Getting Started
  
The course is based on [Jupyter notebooks](https://jupyter.org/), which allow
a high-level of interactive learning, as code, text description and 
visualisation is combined in one place. If you have not worked with 
`Jupyter Notebooks` before, you can look at the module 
[Introduction to Python and Project Jupyter](./welcome_to_wekeo_jupyterlab.ipynb) 
to get a short introduction to the WEkEO Jupyter Lab workspace.

### Prerequisites
 
If you are working on a local machine, you will require Jupyter notebook to run this code. We recommend that you install the
latest Anaconda Python distribution for your operating system (https://www.anaconda.com/). 
Anaconda Python distributions include Jupyter Notebook. We recommend setting up an
environment as recommended below, however you may also adapt your current Python 
environment to include the dependencies listed.
 
### Dependencies

| Package   | Version | License      | Link                                                                 |
|-----------|---------|--------------|----------------------------------------------------------------------|
| python    | 3.10.1  | PSF-2.0      | [python.org](https://www.python.org/downloads/release/python-3100/)  |
| hda       | 2.34    | Apache-2.0   | [anaconda.org/conda-forge/hda](https://anaconda.org/conda-forge/hda) |
| matplotlib       | 3.10.6    | PSF-2.0   | [anaconda.org/conda-forge/matplotlib](https://anaconda.org/conda-forge/matplotlib) |
| ipykernel | 7.0.0a2 | BSD-3-Clause | [anaconda.org/conda-forge/ipykernel](https://anaconda.org/conda-forge/ipykernel) |
| hdf5nc | 1.6.4 | BSD-3-Clause | [anaconda.org/conda-forge/h5netcdf/](https://anaconda.org/conda-forge/h5netcdf/) |
| boto3 | 1.40.41 | Apache-2.0 | [anaconda.org/conda-forge/boto3](https://anaconda.org/conda-forge/boto3) |
| botocore | 1.40.41 | Apache-2.0 | [anaconda.org/conda-forge/botocore](https://anaconda.org/conda-forge/botocore) |
| cartopy | 0.25.0 | BSD-3-Clause | [anaconda.org/conda-forge/cartopy](https://anaconda.org/conda-forge/cartopy) |
| eocanvas | 0.2.7 | Apache-2.0 | [pypi.org/project/eocanvas/](https://pypi.org/project/eocanvas/) |
| xarray | 2025.9.0 | Apache-2.0 | [anaconda.org/conda-forge/xarray](https://anaconda.org/conda-forge/xarray) |
| xcube-core | 1.7.1 | MIT | [anaconda.org/conda-forge/xcube](https://anaconda.org/conda-forge/xcube) |
| zarr | 2.18.3 | MIT | [anaconda.org/conda-forge/zarr](https://anaconda.org/conda-forge/zarr) |