# Detectron for image/video feature extraction
Follow the official [instructions](https://github.com/facebookresearch/Detectron) for Caffe2 and Detectron installation.

## VLP
For [VLP](https://github.com/LuoweiZhou/VLP), download the corresponding [config](https://onedrive.live.com/download?cid=E5364FD183A1F5BB&resid=E5364FD183A1F5BB%212013&authkey=AHIvnE1FcggwiLU) file and the [checkpoint](https://onedrive.live.com/download?cid=E5364FD183A1F5BB&resid=E5364FD183A1F5BB%212014&authkey=AAHgqN3Y-LXcBvU) file and place under this root dir. Refer to `extract_feat_flickr30k.sh` and `tools/extract_features.py` for the usage.

## GVD
For [GVD](https://github.com/facebookresearch/grounded-video-description), download the corresponding [config](http://dl.fbaipublicfiles.com/ActivityNet-Entities/ActivityNet-Entities/e2e_faster_rcnn_X-101-64x4d-FPN_2x.yaml) file (rename to `e2e_faster_rcnn_X-101-64x4d-FPN_2x-gvd.yaml`) and the [checkpoint](http://dl.fbaipublicfiles.com/ActivityNet-Entities/ActivityNet-Entities/e2e_faster_rcnn_X-101-64x4d-FPN_2x.pkl) file (rename to `e2e_faster_rcnn_X-101-64x4d-FPN_2x-gvd.pkl`) and place under this root dir. Refer to `extract_feat_gvd_anet.sh` and `tools/extract_features_gvd_anet.py` for the usage.
