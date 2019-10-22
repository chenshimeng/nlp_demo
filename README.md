## 安装
````
pip install -U cherry
````
## 快速开始
````angular2
#见defualt_demo
````
## 定制
- 数据集
    - 数据集需要包含两个文件（参考 example/data_example 文件夹）
        1 数据集 data.xxx（需命名为 data开头，任意后缀的文件）
        ````
        这是一条正常数据,0
        这是赌博相关数据,1
        ```` 
        2 停止词 stop_words.xxx（需命名为 stop_words开头，任意后缀的文件）
        ````
        或者
        不只
        而且
        还有
        即使
        接着
        ````
        
#### 具体步骤
在 data 文件夹内新建 your_folder 文件夹，你的模型所有数据以及生成的缓存都会存放在此文件夹中。
把 data.xxx 以及 stop_words.xxx 放在文件夹中（可参考例子）。your_folder 用作调用 APIs 时需要的 model 参数。
````angular2
#见bytxt_demo
````
