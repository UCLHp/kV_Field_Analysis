# kV_Field_Analysis
Quantifying kV field size at isocentre.  
Three methods of field edge detection are demonstrated in separate workbooks on a single kV image:  
### Global binary mask 
A binary mask is applied using an empirically derived threshold value. Field sizes are derived from the mask edges.  
  
### Otsu's binary mask
A binary mask is applied using Otsu's method, where a threshold is automatically derived from image histogram variance. Field sizes are derived from the mask edges.  
  
### Gradient threshold
Pixel intensity gradients are generated and used to define the kV field edges.  
  
## Running the notebooks in colab  
To run the notebooks in google colab, follow the links:  
https://colab.research.google.com/github/UCLHp/kV_Field_Analysis/blob/demo/kV_Field_Size_Threshold_Method.ipynb  
https://colab.research.google.com/github/UCLHp/kV_Field_Analysis/blob/demo/kV_Field_Size_Gradient_Method.ipynb  
https://colab.research.google.com/github/UCLHp/kV_Field_Analysis/blob/demo/kV_Field_Size_Otsu_Method.ipynb  
  
