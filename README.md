# Visualization Using Matplotlib
Hi! Welcome to my github :wink:, This repository stores the DIY chart I designed using matplotlib.
```
def SchemeColors(colormap,n,colorrange=[0.3,0.8]):
    randomlist=np.linspace(colorrange[0],colorrange[1],n)
    colors=[]
    for i in randomlist:
        cmap=plt.get_cmap(colormap)
        color=cmap(i)
        colors.append(color)
    return colors
    
```
This function helps to generate a set of gradient colors 


Welcome to reach out if you have any questions.
 
