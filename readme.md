# Installation
HaplotypeNetworkView presents a Java-based graphical user interface program compatible with Windows, Linux/Unix, and macOS. It comes bundled with JavaScript libraries, requiring no additional dependencies. Users can conveniently download the software from _[https://github.com/ChenHuaLab/HapNetworkView](https://github.com/HapNetworkView/HapNetworkView)_, where executable programs have been tailored for different operating systems, eliminating the need for manual user selection. After downloading and extracting the software, navigate to the software directory and double-click on "HaplotypeNetworkView_1.0" to start using it.  
# Usage  
**step1**: Click button Open(.gml .phylip .vcf) to input gml, phylip or phased vcf, HapNetworkView will display an uncolored haplotype network upon loading. Example files are also provided.  <br />**step2**: Click button Group file/Map file(phylip) to input sample category information, the file supports different delimiters such as tab, space, comma, and semicolon，The sample file format, separated by semicolons, is as follows: The first column represents the sample number, and the second column represents the sample category. click button Clear, users can re-enter sample category information. Example files are also provided.  <br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/38378023/1691758884501-dc0f8130-cadc-4029-81e2-273b9652cd82.png#averageHue=%23f2ede9&clientId=u7446bd05-af3f-4&from=paste&height=186&id=ua513d852&originHeight=279&originWidth=100&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=5204&status=done&style=none&taskId=u13dcc4f5-4de0-4ef3-9761-402612dda5c&title=&width=66.66666666666667)  <br />After completing these two steps, the complete haplotype network will be presented, showcasing an optimized layout.  <br />**step3**: Click button Save，and input output file name，users can save plot to svg，pdf and png format.  

# Function  
## 1 Adjusting the appenance of network  
We provide multiple parameters to change the apperance of network：  <br />Hover：Whether to display information upon mouse hovering.  <br />AutoLayout：Whether to apply automatic layout optimization. When this parameter is enabled, dragging a node will also modify the overall layout. Disabling this parameter allows individual node dragging only.  <br />Node：Whether to display node ID.  <br />Edge：Whether to display the number of mutation of link.  <br />Node Size：Input the range of node size and click Run.  <br />Edge size：Input the range of edge size and click Run.   <br />Edge force & Node gravity：Adjust these two parameters and click Run to change the layout.  <br />Line width：Input the line width and click Run.  <br />Node(true) & Node(intermediate)：Tick Outline to outline node，users can also change the color of these nodes.   <br />Change the color of sample category: We provide users with a default color scheme, but they can also choose their wanted colors.  
## 2 Check the distribution of  SNP combinations within the haplotype  
In step 1, after inputing files in phylip and phased vcf formats, users can select the desired SNP combinations in the bottom-right panel. These SNP combinations will be automatically assigned colors and displayed in the haplotype network. Please note that the number of SNP combinations should not exceed 10.  <br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/38378023/1691818457690-c05bd935-cd64-47b5-bab8-93fa6b08f71c.png#averageHue=%23faf9f9&clientId=u7446bd05-af3f-4&from=paste&height=313&id=udccaf776&originHeight=1125&originWidth=1789&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=296041&status=done&style=none&taskId=u9c8ff786-141d-4ddf-b5cf-a0e5f8e5296&title=&width=497.3333435058594)  
## 3 Check the distribution of  individual sample or category within the haplotype  
When users click on a sample or category, the corresponding haplotype will be displayed in shadow form.  <br />click on category:  <br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/38378023/1691818514217-55f37183-91b4-4b27-987d-b2ddb0cdc2d2.png#averageHue=%23f9f8f7&clientId=u7446bd05-af3f-4&from=paste&height=245&id=ud7641975&originHeight=848&originWidth=1730&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=250278&status=done&style=none&taskId=uc0320fc8-62d3-4d0f-af6b-546c44aced4&title=&width=500.3333740234375)  <br />click no sample:  <br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/38378023/1691818564768-76b7f806-dd71-4bea-aab2-0f13063eca0f.png#averageHue=%23faf9f9&clientId=u7446bd05-af3f-4&from=paste&height=265&id=u9a2921bc&originHeight=906&originWidth=1705&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=235821&status=done&style=none&taskId=u60afd7b6-4a26-467f-8d4c-346239b0105&title=&width=498.3333740234375)  
## 4 View the sample distribution of haplotypes within nodes, as well as the number of mutations and allele information along the branches  
After ticking Hover，hovering over a node and right-clicking, the haplotype information will be displayed on the node. Users can click button Save to save this information.   <br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/38378023/1691820046718-e92821d1-880b-4a48-a8bd-4912bd05fe73.png#averageHue=%23faf9f9&clientId=u7446bd05-af3f-4&from=paste&height=316&id=u19732214&originHeight=1347&originWidth=2140&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=286284&status=done&style=none&taskId=u6c8de85a-3526-48f9-8dc4-65033180868&title=&width=502.3333740234375)  <br />When hovering over a branch and right-clicking, the mutation information can be displayed.  <br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/38378023/1691820261384-f1510755-5172-4eed-b356-6692092613f7.png#averageHue=%23fafafa&clientId=u7446bd05-af3f-4&from=paste&height=314&id=u04f2f08f&originHeight=1341&originWidth=2137&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=252643&status=done&style=none&taskId=u3a3bbbc3-3908-4d95-ae02-c5a53c5cabb&title=&width=500.3333740234375)  

