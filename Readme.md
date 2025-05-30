# COD10K: Camouflaged Object Detection Dataset with 10,000 images

COD10K is a NEW and LARGEST Camouflaged Object Detection dataset included 10,000 elaborately annotated items. (5066 CAMs + 4936 NonCAMs)

Please visit the [project page](http://dpfan.net/Camouflage/) for more detailed information.
Our online demo: http://mc.nankai.edu.cn/cod

# Train/Test data split

|              | Train | Test  | Total Number |
| ------------ | ----- | ----- | ------------ |
| CAM          | 3,040 | 2,026 | 5,066        |
| NonCAM       | 2,960 | 1,974 | 4,934        |
| Total Number | 6,000 | 4,000 | 10000        |

# Files
Root directory contains following folders:
- Train/Test
- - Image
- - GT_Instance
- - GT_Object
- - GT_Edge
- - GT_Detection

## Description


% Simply Naming Rules:

Camouflaged:
COD10K-CAM-SuperNumber-SuperClass-SubNumber-SubClass-ImageNumber

Non-Camouflaged:
COD10K-NonCAM-SuperNumber-SuperClass-SubNumber-SubClass-ImageNumber

% Searching Items
Super_Class_Dictionary = {'1':'Aquatic', '2':'Terrestrial', '3':'Flying', '4':'Amphibian', '5':'Other'}
Sub_Class_Dictionary = {'1':'batFish','2':'clownFish','3':'crab','4':'crocodile','5':'crocodileFish','6':'fish','7':'flounder',
             '8':'frogFish','9':'ghostPipefish','10':'leafySeaDragon','11':'octopus','12':'pagurian','13':'pipefish',
              '14':'scorpionFish','15':'seaHorse','16':'shrimp','17':'slug','18':'starFish','19':'stingaree',
              '20':'turtle','21':'ant','22':'bug','23':'cat','24':'caterpillar','25':'centipede','26':'chameleon',
              '27':'cheetah','28':'deer','29':'dog','30':'duck','31':'gecko','32':'giraffe','33':'grouse','34':'human',
              '35':'kangaroo','36':'leopard','37':'lion','38':'lizard','39':'monkey','40':'rabbit','41':'reccoon',
              '42':'sciuridae','43':'sheep','44':'snake','45':'spider','46':'stickInsect','47':'tiger','48':'wolf',
              '49':'worm','50':'bat','51':'bee','52':'beetle','53':'bird','54':'bittern','55':'butterfly','56':'cicada',
              '57':'dragonfly','58':'frogmouth','59':'grasshopper','60':'heron','61':'katydid','62':'mantis',
              '63':'mockingbird','64':'moth','65':'owl','66':'owlfly','67':'frog','68':'toad','69':'other'}

% License
Our dataset is free for non-commercial usage. Please contact us (dengpfan@gmail.com) if you want to use it for comercial usage.


%Reference
If you use this dataset in your work, you should reference:
@InProceedings{Fan_2020_CVPR,
author = {Fan, Deng-Ping and Ji, Ge-Peng and Sun, Guolei and Cheng, Ming-Ming and Shen, Jianbing and Shao, Ling},
title = {Camouflaged Object Detection},
booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2020}
}