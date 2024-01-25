### 源代码：
>  https://threedle.github.io/text2mesh/

text2mesh-main是源代码，复现结果在results/demo/，obj文件是3D源网格或者风格化后的网格

### 环境要求
- Python 3.7
- CUDA 11
- GPU w/ minimum 8 GB ram

### 安装步骤
>	conda env create --file text2mesh.yml
>	conda activate text2mesh

如果安装失败的话打开文件一个个安装

### 运行
进入到主文件夹下：
>	./demo/run_xxx_xxxx.sh

注意要给sh文件相应的权限