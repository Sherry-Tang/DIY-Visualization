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
1.TimeMachinePie and QueenDiomondPie
```
TimeMachinePie(data,index_data=index_data,language='CHN',fontsize=55,radius=1,title="I am a Time Machine",legend_loc=[0,0.015],saving_path='C://Users/sherr/Sherry/qzj/newpic')
QueenDiomondPie(data,index_data=index_data,language='CHN',fontsize=55,radius=1,legend_loc=[0,0.015],saving_path='C://Users/sherr/Sherry/qzj/newpic')
```

Both of the two charts are based on pie chart, but it can further visualize subcategories with each category.If you didn't pass the color, the function will randomly generate two color for you.

2. CuteTwoAxisPlotting
```
CuteTwoAxisPlotting(data,'Name','Math','Total score',xlim=[-100,100],title='I am Cute TwoAxis Bar Chart',unit1='分',unit2='分',text_distance=2,bar_width=0.5,sort=True,pad=150)
```
This Chart is based on matplotlib bar chart, it can visualize two side barchart with different lims. If you didn't pass the color, the function will randomly generate two color for you.

3. NightingaleRose
```
NightingaleRose(data,value_col,index_col,cmaps=None,language='ENG',is_label_show=True,labeldis=0.7,label_color='white',fontsize=50,radius=0.9,darkness=0.45,unit="",legend_loc=[0,0],saving_path=None)
```
This chart is based on matplotlib pie chart and adjust the diameter by each category's percentage.  

Keep updating...
Welcome to reach out if you have any questions.
 
