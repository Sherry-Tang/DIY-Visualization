# Visualization Using Matplotlib
Hi! Welcome to my github :wink:, This repository stores the DIY chart I designed using matplotlib.

- This function helps to generate a set of gradient colors 
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
- 1.TimeMachinePie and QueenDiomondPie
```
TimeMachinePie(data,index_data=index_data,language='CHN',fontsize=55,radius=1,title="I am a Time Machine",legend_loc=[0,0.015],saving_path='C://Users/sherr/Sherry/qzj/newpic')
QueenDiomondPie(data,index_data=index_data,language='CHN',fontsize=55,radius=1,legend_loc=[0,0.015],saving_path='C://Users/sherr/Sherry/qzj/newpic')
```

Both of the two charts are based on pie chart, but it can further visualize subcategories with each category.



Welcome to reach out if you have any questions.
 
