# DL_Yolov5 Custom data 결과
## 1차 시도 :  epoch:100 image size:320 batchsize: 8(train : 8, val:16)


 결과
Epoch   gpu_mem       box       obj       cls    labels  img_size
     99/99        0G   0.07086    0.1003     0.949        18       320: 100%|██████████| 322/322 [33:37<00:00,  6.26s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100%|██████████| 46/46 [03:10<00:00,  4.13s/it]
                 all        736        738    0.00839      0.305    0.00604    0.00104
                 cat        736        251    0.00792     0.0876    0.00357   0.000567
                 dog        736        487    0.00885      0.522    0.00851    0.00152

![image](https://user-images.githubusercontent.com/56629324/231930697-76e23320-7160-4fcf-9969-d10bd6f085d4.png)



## 2차 시도 :  epoch:200 image size:320 batchsize: 16 (train : 16, val:16) 

 결과
     Epoch   gpu_mem       box       obj       cls    labels  img_size
   199/199        0G   0.03224   0.05265   0.05606        27       320: 100%|██████████| 161/161 [18:19<00:00,  6.83s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100%|██████████| 23/23 [01:33<00:00,  4.06s/it]
                 all        736        738      0.971      0.959      0.979      0.676
                 cat        736        251      0.993      0.968      0.984      0.759
                 dog        736        487      0.949       0.95      0.974      0.594
![image](https://user-images.githubusercontent.com/56629324/231930712-de4588f0-3595-4b64-8080-82d27177d4ea.png)



## 3차 시도 :  epoch:200 image size:320 batch size: 32

 결과
     Epoch   gpu_mem       box       obj       cls    labels  img_size
   199/199        0G   0.02884   0.04815   0.03825        27       320: 100%|██████████| 81/81 [17:49<00:00, 13.20s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100%|██████████| 12/12 [01:34<00:00,  7.88s/it]
                 all        736        738      0.969      0.956      0.983      0.715
                 cat        736        251      0.984      0.964      0.985      0.797
                 dog        736        487      0.955      0.948       0.98      0.634





## 4차 시도 :  epoch:300 image size:320 batch size: 16   :세세한것까지 잡음

 결과
     Epoch   gpu_mem       box       obj       cls    labels  img_size
   299/299        0G   0.04705   0.06912    0.1402        40       320: 100%|██████████| 161/161 [1:30:59<00:00, 33.91s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100%|██████████| 23/23 [03:13<00:00,  8.40s/it]
                 all        736        738       0.88      0.863      0.907      0.473
                 cat        736        251      0.899      0.916      0.942      0.561
                 dog        736        487       0.86      0.809      0.872      0.385

![image](https://user-images.githubusercontent.com/56629324/231930780-a0a4b785-d8c6-48bf-a0a8-cd651f760283.png)





## 5차 시도 :  epoch:300 image size:320 batch size: 32 (train : 32, val:32) :세세한것까지 잡음. 학습제일 잘된것같다.

 결과
     Epoch   gpu_mem       box       obj       cls    labels  img_size
   299/299        0G   0.02592   0.04432    0.0248        41       320: 100%|██████████| 81/81 [17:36<00:00, 13.05s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100%|██████████| 12/12 [01:34<00:00,  7.87s/it]
                 all        736        738       0.99      0.966      0.986      0.756
                 cat        736        251          1      0.976      0.986      0.828
                 dog        736        487      0.981      0.957      0.986      0.684


 


## 6차 시도 :  epoch:300 image size:320 batch size: 8 (최종)

 결과
     Epoch   gpu_mem       box       obj       cls    labels  img_size
   299/299        0G    0.0487   0.06933    0.1514        16       320: 100%|██████████| 322/322 [20:55<00:00,  3.90s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100%|██████████| 46/46 [01:41<00:00,  2.20s/it]
                 all        736        738      0.898      0.876      0.917      0.473
                 cat        736        251      0.927      0.916      0.949      0.557
                 dog        736        487      0.869      0.836      0.885      0.389
![image](https://user-images.githubusercontent.com/56629324/231930826-efd7038d-368b-4858-9c09-577dfbd326b6.png)
![image](https://user-images.githubusercontent.com/56629324/231930840-f2b252c3-c199-4b87-ab4d-404a1a99fbad.png)
![image](https://user-images.githubusercontent.com/56629324/231930850-af91897a-fcd9-42be-8b15-19aaa4b3242e.png)
![image](https://user-images.githubusercontent.com/56629324/231930856-a5099cd3-695f-45d1-bd86-4ccfc6e2ebea.png)
![image](https://user-images.githubusercontent.com/56629324/231930870-3101885f-250d-45ce-853a-3e80f6e002cd.png)

Validation
![image](https://user-images.githubusercontent.com/56629324/231930882-b1d74b7a-8c00-41b0-b5d8-4101ee07bc31.png)
![image](https://user-images.githubusercontent.com/56629324/231930893-67964aa5-a1eb-488b-85a5-7c51f5d277e1.png)
![image](https://user-images.githubusercontent.com/56629324/231930906-4e0cb965-f33b-4cf9-8b45-c24114d7d612.png)
![image](https://user-images.githubusercontent.com/56629324/231930912-3e62a00d-c6b0-4717-a4ed-d1c95bf5c557.png)              

Detection
![image](https://user-images.githubusercontent.com/56629324/231930926-af05c6f8-8ed8-46bb-bce4-b8550614c270.png)
![image](https://user-images.githubusercontent.com/56629324/231930938-55d707e6-1521-4069-9d70-800dc1f591bc.png)
![image](https://user-images.githubusercontent.com/56629324/231930947-ea2f758f-2284-4bdb-a7f8-7c93ed4c347e.png)
![image](https://user-images.githubusercontent.com/56629324/231930955-fb56e69e-0942-4c03-937f-d72d45db5b1d.png)


