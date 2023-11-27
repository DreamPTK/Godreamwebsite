# Xarray

`Xarray` is a python library which simplifies working with labelled multi-dimension arrays. Xarray introduces labels in the forms of dimensions, coordinates and attributes on top of raw numpy arrays, allowing for more intitutive and concise development.

## Xarray dataset

Xarray Dataset can be seen as a dictionary structure packing up the data, dimensions and attributes. Variables in a Dataset object are called DataArrays and they share dimensions with the higher level Dataset. 

### Import packages


```python
from Godream.convertool import xarray_ds
```

### Input


```python
file_name = "data/Landsat8_allB4326.tif"
```

### Create Xarray dataset

You have to know the band ordering of your raster image or you can reordering by using [stacking tool](https://dreamptk.github.io/Godreamwebsite/bands_stack/).


```python
ds = xarray_ds(tiff_path=file_name)
```


```python
print(ds)
```

    <xarray.Dataset>
    Dimensions:  (y: 1469, x: 1469)
    Coordinates:
      * x        (x) float64 100.5 100.5 100.5 100.5 ... 100.9 100.9 100.9 100.9
      * y        (y) float64 13.89 13.89 13.89 13.89 ... 14.29 14.29 14.29 14.29
    Data variables:
        band_1   (y, x) float64 -9.999e+03 -9.999e+03 ... -9.999e+03 -9.999e+03
        band_2   (y, x) float64 -9.999e+03 -9.999e+03 ... -9.999e+03 -9.999e+03
        band_3   (y, x) float64 -9.999e+03 -9.999e+03 ... -9.999e+03 -9.999e+03
        band_4   (y, x) float64 -9.999e+03 -9.999e+03 ... -9.999e+03 -9.999e+03
        band_5   (y, x) float64 -9.999e+03 -9.999e+03 ... -9.999e+03 -9.999e+03
        band_6   (y, x) float64 -9.999e+03 -9.999e+03 ... -9.999e+03 -9.999e+03
        band_7   (y, x) float64 -9.999e+03 -9.999e+03 ... -9.999e+03 -9.999e+03
    Attributes:
        crs:        EPSG:4326
        transform:  | 0.00, 0.00, 100.47|\n| 0.00,-0.00, 14.29|\n| 0.00, 0.00, 1.00|
    


```python
print(ds.band_5)
```

    <xarray.DataArray 'band_5' (y: 1469, x: 1469)>
    array([[-9999., -9999., -9999., ..., -9999., -9999., -9999.],
           [-9999., -9999., -9999., ..., -9999., -9999., -9999.],
           [-9999., -9999., -9999., ..., -9999., -9999., -9999.],
           ...,
           [-9999., -9999., -9999., ..., -9999., -9999., -9999.],
           [-9999., -9999., -9999., ..., -9999., -9999., -9999.],
           [-9999., -9999., -9999., ..., -9999., -9999., -9999.]])
    Coordinates:
      * x        (x) float64 100.5 100.5 100.5 100.5 ... 100.9 100.9 100.9 100.9
      * y        (y) float64 13.89 13.89 13.89 13.89 ... 14.29 14.29 14.29 14.29
    


```python
print(ds.crs)
```

    EPSG:4326
    


```python

```
