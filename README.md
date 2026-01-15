# Event-Stream-Compression-for-Neuromorphic-Vision-Grid-DBSCAN-and-Voxelization

```**Spatial_Clustering.ipynb**```
 
Core notebook for the three compression operators. Builds grid top-k, DBSCAN in (x,y,\tilde t) space, and voxelisation. Includes quick visual checks on a few samples, side-by-side before/after plots, and saves small HDF5 snippets plus illustrative PNGs for the paper.

```**compression_two_datasets.ipynb**```
 
Batch compression for CIFAR10-DVS and N-Caltech101 using grid and DBSCAN. Produces dataset-level retention, compression ratio, and size summaries, along with the dashboard figures used in the results section. Exports tables to results/*.csv and plots to figures/*.png. Writes compressed streams as HDF5 per method.

```**compression_ncaltech.ipynb**```
 
Focused runs for N-Caltech101 with finer breakdowns. Reports class-wise retention, per-sample distributions, and optional parameter sweeps at the chosen operating points. Outputs updated CSV summaries and high-resolution PNGs that mirror the dissertation tables.

 

