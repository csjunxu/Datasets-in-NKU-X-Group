# datasets and the corresponding paths

超分辨率数据集

1. DIV2K和Flicker2K
10.40.13.207 
```
/home/xj019174/xty/AS-SR/DIV2K_train_HR 
                        /DIV2K_valid_HR
                        /DF2K
```

10.40.13.220 
```
/home/ubuntu/Datasets/SRdataset/DIV2K
                               /benchmark_SR
                               /DIV2K (crop to 480*480)
```

2. DIV2K和Set5，Set14，BSD100, Urban100, Mango109, Test2K, Test4K
10.40.13.216 /data/xty/DNet/SRData/DIV2K_train_HR
                                  /DIV2K_valid_HR
                                  /benchmark/Set5
                                            /Set14
                                            /B100
                                            /Urban100
                                            /Manga109
                                            /test2k
                                            /test4k
10.40.13.220 /home/ubuntu/Datasets/SRdataset/DIV2K
                                            /benchmark_SR
                                            /DIV2K (crop to 480*480)
                                            /Set5
                                            /Set14
                                            /B100
                                            /Urban100
                                            /Manga109
                                            /test2k
                                            /test4k

人脸超分辨率数据集

1. celebAHQ
10.40.13.234 /home/ps/zyj/sr/liif/load/celebAHQ

曝光矫正数据集

1. MSEC, CVPR 2021, Brown组提供的
10.40.13.212 /home/ubuntu/liangjin/SEC/imagepatch_512
10.40.13.233 /home/ubuntu/lc/mmtrain/  (MEF格式)

逆色调映射数据集
1. HDRTV1K
训练集（crop to 256*256）: 10.40.13.213 /home/csjunxu-3090/syb/downsampleFactor_04/hr/ 
测试集：10.40.13.213 /home/csjunxu-3090/syb/HDRTV_test/ \test_hdr, test_sdr
2. 我们自己收集的ITM-4K测试集
10.40.13.213 /home/csjunxu-3090/xlq/new_test/


医学影像数据

1. 兔子和人体的低剂量和标准剂量CT影像数据 （来自西安交大第一附属医院）
10.40.13.213 /new/CTdata

2. 人眼视线估计数据 (来自德国图宾根大学)
TeyeD（瞳孔检测）: 10.40.13.207 /home/xj019174/dachuang/data   
OpenEDS、LPW（瞳孔检测）: 10.40.13.207 /home/xj019174/pupil detection


分类分割检测数据集

1. ImageNet
ImageNet-1k 10.40.13.227 /data/imagenet   

企业数据集

1. 360篡改检测数据集
10.40.13.212 /home/ubuntu/Disk/zyj/cg/dat