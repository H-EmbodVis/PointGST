## Get Started

### Installation

We recommend using Anaconda to start this project. You may also refer to [Pointcept](https://github.com/pointcept/pointcept#installation) for environment configuration.

## S3DIS

```bash
# Linear Probing
$ sh scripts/train.sh -m 1 -g 2 -d PGST-on-PTv3 -c semseg-ptv3-s3dis-lin -n semseg-ptv3-s3dis-lin -w /path/to/pretrain_weight

# Lin + Pointgst
$ sh scripts/train.sh -m 1 -g 2 -d PGST-on-PTv3 -c semseg-ptv3-s3dis-pgst-lin -n semseg-ptv3-s3dis-pgst-lin -w /path/to/pretrain_weight

# Decoder Probing
$ sh scripts/train.sh -m 1 -g 2 -d PGST-on-PTv3 -c semseg-ptv3-s3dis-dec -n semseg-ptv3-s3dis-dec -w /path/to/pretrain_weight

# Dec with Pointgst
$ sh scripts/train.sh -m 1 -g 2 -d PGST-on-PTv3 -c semseg-ptv3-s3dis-pgst-dec -n semseg-ptv3-s3dis-pgst-dec -w /path/to/pretrain_weight

# FFT
$ sh scripts/train.sh -m 1 -g 2 -d PGST-on-PTv3 -c semseg-ptv3-s3dis-ft -n semseg-ptv3-s3dis-ft -w /path/to/pretrain_weight
```