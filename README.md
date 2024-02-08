# SimDiff
## Datasets
Please refer to the [MCLEA](https://github.com/lzxlin/MCLEA) to download the datasets.

## Training 
For cross-Kg datasets

```bash
bash SimDiff_mmkb.sh 0,1,2,3 39 FB15K_YAGO15K 0.2 0.001 cuda:0 2
```
Here 0.2 is the seed entity ratio, 0.001 is the scale of the noise

```bash
 bash SimDiff_dbp15k.sh 0,1,2,3 42 fr_en 0.001 cuda:0 2
 bash SimDiff_dbp15k.sh 0,1,2,3 42 zh_en 0.001 cuda:0 2
```

## Acknowledgement

The code is based on [EVA](https://github.com/cambridgeltl/eva) and [MCLEA](https://github.com/lzxlin/MCLEA), and thank them for making the code public.
