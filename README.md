# Neural Style Transfer: Colorful *The Last of Us: Part II (TLOU2)*

*TLOU2* was popular for its grim storyline which was further emphasized in the game's dim environments and displays of graphic violence. It was still beloved by many because of its strong emotional pull towards its characters. I thought that it'd be interesting to see how the style of colorful and less visually realistic game like *Shovel Knight* would look applied to the darker tones in *TLOU2*.

Doing this to the original images 

![Original images](https://raw.githubusercontent.com/marjcuerdo/NeuralStyleTransfer-TLOUColor/main/output/results1.png)

resulted in:

![Resulting image](https://raw.githubusercontent.com/marjcuerdo/NeuralStyleTransfer-TLOUColor/main/output/results.png)

Here's a couple GIFs of versions of the process:

## Iterations: 300 - 3000
![Resulting image](https://raw.githubusercontent.com/marjcuerdo/NeuralStyleTransfer-TLOUColor/main/output/animated_3000.gif)


## Iterations: 1000 - 10000
![Resulting image](https://raw.githubusercontent.com/marjcuerdo/NeuralStyleTransfer-TLOUColor/main/output/animated.gif)

While there are details that I would like better handled (Ellie's face being more blurred), I appreciated the blending of colors becoming smoother with more iterations. It's awesome that the style of the trees in the *Shovel Knight* image were copied over into the more realistic trees in *TLOU*. The hints of yellow/orange to focus the center of the image also worked the way that I hoped it out.

To try this yourself, check out the [Google Colab notebook](https://colab.research.google.com/github/marjcuerdo/NeuralStyleTransfer-TLOUColor/blob/main/Neural_Style_Transfer_for_Colorful_The_Last_of_Us_Part_II.ipynb) that I adapted from [here](https://colab.research.google.com/drive/11vmlxovVLBitrnrNZvvEiEl21xr_azka#scrollTo=jo5PziEC4hWs). Follow the instructions to execute the code sequentially from the top and it should work.
