# MSG-Transformer on MindSpore

##  Installation  

1. Create the `python=3.8` environment with Conda 
```bash
conda create -n msg-transformer-ms python=3.8  
```
2. Activate the new environment  
```bash
conda activate msg-transformer-ms    
```

3. Install mindspore via `pip`  
``` bash
pip install https://ms-release.obs.cn-north-4.myhuaweicloud.com/1.8.1/MindSpore/gpu/x86_64/cuda-11.1/mindspore_gpu-1.8.1-cp38-cp38-linux_x86_64.whl --trusted-host ms-release.obs.cn-north-4.myhuaweicloud.com -i https://pypi.tuna.tsinghua.edu.cn/simple
```

4. Install dependencies   
```bash
pip install mindvision pycocotools opencv-python numpy yacs scipy  
```

##  Test

```bash
python test.py --cfg ./configs/msg_tiny_p4_win7_224.yaml    
```
