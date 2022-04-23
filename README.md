# Recipe Representation Learning with Networks
This is the official repo for the paper "[Recipe Representation Learning with Networks](https://dl.acm.org/doi/abs/10.1145/3459637.3482468)", accepted at CIKM 2021.

## Data
Please first [download the data](https://drive.google.com/drive/folders/1KMo4Kg0vs7lx-h0fS9QjRgC_myuGqQVH?usp=sharing), then put them under folder 'data/'.

For the mappings between the nodes in RecipeNet and the recipe text (recipes_weighted_and_USDAmapped.json), please check the following code block:
```
recipeID2nodeID_dict, nodeID2recipeID_dict = torch.load('../data/recipeID2nodeID_and_nodeID2recipeID.pt')
ingreID2nodeID_dict, nodeID2ingreID_dict = torch.load('../data/ingre2nodeID_and_nodeID2ingre.pt')
```

## Code
All codes have been put into a jupyter notebook for easy reading and executing. We further log the results in the notebook for demonstration purposes. 


## Citing rn2vec
If you find rn2vec useful, please cite our paper.
```
@inproceedings{rn2vec,
  author = {Tian, Yijun and Zhang, Chuxu and Metoyer, Ronald and Chawla, Nitesh V.},
  title = {Recipe Representation Learning with Networks},
  booktitle = {CIKM},
  year = {2021}
}
```
