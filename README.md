# Domain-Adaptation-Comparisons
 Comparisons of Various of Domain Adaptative Semantic Segmentation Algorithms in the tasks of **GTAs-to-Cityscapes** and **SYNTHIA-to-Cityscapes**. It can be seen that our proposed **Crack-DA** can have better performance than the SOTAs **BA-PA** and **Pro-DA** for both the **large semantic classes** such as the bus and train and the **small semantic classes** such as the pedestrians. The results further demonstrate the effectiveness of depth and edge features in the tasks of domain adaptive semantic segmentation.
 
 ![cardinal](./figures/Domain_Adaptive_Seg.png)
 
# Our Cooresponding Crack-DA Edge and Depth Map
You can also find the cooresponding data augmentation results, edge detection map, depth prediction map by our **Crack-DA**. Our **Crack-DA** is the first approaches which make full use of the auxiliary relative low-level depth and edge features to do UDA. Our approach makes sense for the fact that the edge and depth features are closely related to semantic features as indicated below.

 ![cardinal](./figures/Domain_Adaptive_Seg_CrackDA.png)
