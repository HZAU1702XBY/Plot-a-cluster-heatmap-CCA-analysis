# Plot-a-cluster-heatmap/CCA analysis
heatmap_plot.R：使用complexheatmap包绘制较为复杂的聚类热图
CCA_analysis.R:CCA分析


CCA_analysis.R env.tsv  Ingredients.tsv prefix
heatmap_plot.R env.tsv  Ingredients.tsv prefix




数据格式：



环境因素文件env.tsv（环境和分组的丰度信息）
|TAXID|分组一|分组二|分组三|......|
|-----|-----|-----|-----|-----|
|环境因素1|.....|.....|.....|.....|
|环境因素2|.....|......|.....|.....|
|环境因素3|......|......|......|....|
|........|......|.....|......|......|
 
成分分析文件 Ingredients.tsv(分泌物或其他物质与分组的丰度信息)
|TAXID|分组一|分组二|分组三|......|
|-----|-----|-----|-----|-----|
|成份因素1|.....|.....|.....|.....|
|成份因素2|.....|......|.....|.....|
|成份因素3|......|......|......|....|



![D9ECFB9B-7F7C-43CC-863F-651A2B62DDA2](https://user-images.githubusercontent.com/61085371/175490640-8fc6248c-4238-4aa2-9eb2-9c00664f31f6.png)
![DE236396-19D3-4271-B241-DDE4565224E9](https://user-images.githubusercontent.com/61085371/175500972-ef82065b-3aae-4d15-9575-70f23f9fdb71.png)
