﻿# naic2022semi-final
Training:
```
 python tools/train_net.py --config-file ./configs/NAIC2021Reid/sbs_mlp2x.yml MODEL.DEVICE "cuda:0"
 # Outputs at logs/NAIC2021Reid/sbs_mlp2x
```
Inference
```
python tools/train_net.py --config-file ./configs/NAIC2021Reid/sbs_mlp2x_inference.yml --infer-only MODEL.DEVICE "cuda:0"
# Submit file at logs/NAIC2021Reid/sbs_mlp2x_inference/Inference_On_NAIC2021ReidTestA/
```
