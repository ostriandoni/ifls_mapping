# ifls_mapping

Visualize geographical data using Jupyter Notebook and gmaps plugin.

## Installation
Use the latest versions of Jupyter Notebook::

    $ pip install -U jupyter

Make sure that you have enabled widgets extensions to Jupyter::

    $ jupyter nbextension enable --py --sys-prefix widgetsnbextension

You can then install gmaps with::

    $ pip install gmaps

Then tell Jupyter to load the extension with::

    $ jupyter nbextension enable --py --sys-prefix gmaps

## Data
* [hidesys/IFLS_GIS](https://github.com/hidesys/IFLS_GIS/blob/master/Indonesian_Family_Life_Survey_4_Longitude_and_Latitude.csv)
* About IFLS, see here: http://www.rand.org/labor/FLS/IFLS.html

## Result
.. image:: map.png
