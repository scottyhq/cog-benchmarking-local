# cog-benchmarking-local
cloud optimized geotiff benchmarking w/ AWS credentials

idea is to test performance of rasterio, xarray, dask to access cloud optimized geotiffs on private or requester pays buckets on S3.

to run this notebook, you need to have AWS credentials on your machine

```
jupyter-repo2docker https://github.com/scottyhq/cog-benchmarking-local
```
