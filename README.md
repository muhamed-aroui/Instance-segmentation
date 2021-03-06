# Instance-segmentation
The MaskRCNN instance segmentation model was developed using Facebook AI reseach's (FAIR) [Detectron 2](https://github.com/facebookresearch/detectron2)  framework trained on the [PanNuke Dataset] (https://jgamper.github.io/PanNukeDataset)

# Training
The folder Pannuke_cocoFormat  contains the Pannuke dataset converted to COCO format since it is the expected format of detectron 2, it can be used to train adn do inferance of  the MaskRCNN model using the 'PIMA.ipynb' notebook
# Output
An example of instance segmentation on panuke validation set:

![alt text](https://github.com/muhamed-aroui/Instance-segmentation/blob/main/output/panukeTest6.png?raw=true)
![alt text](https://github.com/muhamed-aroui/Instance-segmentation/blob/main/output/panukeTest3.png?raw=true)
# References
@misc{wu2019detectron2,
  author =       {Yuxin Wu and Alexander Kirillov and Francisco Massa and
                  Wan-Yen Lo and Ross Girshick},
  title =        {Detectron2},
  howpublished = {\url{https://github.com/facebookresearch/detectron2}},
  year =         {2019}
}

@inproceedings{liu2018path,
  author = {Shu Liu and
            Lu Qi and
            Haifang Qin and
            Jianping Shi and
            Jiaya Jia},
  title = {Path Aggregation Network for Instance Segmentation},
  booktitle = {Proceedings of IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year = {2018}
}

@inproceedings{gamper2019pannuke, 
  title={PanNuke: an open pan-cancer histology dataset for nuclei instance segmentation and classification}, 
  author={Gamper, Jevgenij and Koohbanani, Navid Alemi and Benet, Ksenija and Khuram, Ali and Rajpoot, Nasir}, 
  booktitle={European Congress on Digital Pathology}, 
  pages={11--19}, 
  year={2019}, 
  organization={Springer} }
