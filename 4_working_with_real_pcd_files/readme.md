
how to run the code in ubuntu ?

$ mkdir build
$ cd build
$ cmake ..
$ make
$ ./environment

The lidar data before voxel filtering (checkout 2. commit)

![Screenshot from 2023-06-04 02-11-03](https://github.com/altayilker/sensor_fusion/assets/31896212/c998e610-f881-4ab3-8864-23e9405e4f94)

The lidar data after voxel filtering (checkout after voxel filtering commit)

![Screenshot from 2023-06-04 02-04-52](https://github.com/altayilker/sensor_fusion/assets/31896212/65b28189-3f40-4c5b-b990-66e8aa1492f4)

Crop the data for region of interest and remove roof lidar points (checkout the related commit )

![Screenshot from 2023-06-04 14-39-37](https://github.com/altayilker/sensor_fusion/assets/31896212/cc7e838f-b020-4c82-beab-dec413fe1962)

Segmented PCD ( segment ground and objects, checkout Segmented PCD commit)

![Screenshot from 2023-06-04 16-06-33](https://github.com/altayilker/sensor_fusion/assets/31896212/0c39bf82-35fc-448d-8a72-e8d96bf899f8)

Clustering PCD ( give different colors to different objects around, checkout Clustering PCD commit)

![Screenshot from 2023-06-04 16-34-47](https://github.com/altayilker/sensor_fusion/assets/31896212/132084f5-66cf-4353-9087-14883cb0def7)
