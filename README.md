# rn2vec
Code &amp; data for the CIKM 2021 paper "Recipe Representation Learning with Networks".

## Data
Please first [download the data](https://drive.google.com/drive/folders/1KMo4Kg0vs7lx-h0fS9QjRgC_myuGqQVH?usp=sharing), then put them under folder 'data/'.

For the mappings between the nodes in RecipeNet and the recipe text (recipes_weighted_and_USDAmapped.json), please check the following code block:
```
recipeID2nodeID_dict, nodeID2recipeID_dict = torch.load('../data/recipeID2nodeID_and_nodeID2recipeID.pt')
ingreID2nodeID_dict, nodeID2ingreID_dict = torch.load('../data/ingre2nodeID_and_nodeID2ingre.pt')
```

## Code
All codes have been put into a jupyter notebook for easy reading and executing. We further log the results in the notebook for demonstration purposes. 
