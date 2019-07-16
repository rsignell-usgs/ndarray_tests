# ndarray_tests

Test reading 4680 11Mb chunks from stores on uswest2

| Format  | workers/CPUs |  Time (s) | Region |
| ------------- | ------------- | -------------|----|
| S3  | 4/8  |  506  | uswest2 |
| S3  | 8/16  | 253 | uswest2 |
| S3  | 16/32  | 130 | uswest2 |
| ------------- | ------------- | -------------|----|
| Zarr  | 4/8  | 190 | uswest2 | 
| Zarr  | 8/16 | 108 | uswest2 |
| Zarr  | 16/32  | 64 | uswest2 | 
| ------------- | ------------- | -------------|----|
| hsds | 4/8 | 264 | uswest2 |
| hsds | 8/16 | 210 | uswest2 |
| hsds | 16/32 | 192 | uswest2 |
