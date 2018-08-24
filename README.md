# 九章算法 - 朴素贝叶斯

## 安装过程
1. 确认已经安装anaconda, 安装详情请参考之前的教程：https://www.jiuzhang.com/tutorial/ai-camp/477

## anaconda默认应该已经安装了本次实验所需要的库
2.1 输入命令行: git clone https://github.com/jiuzhangjiangzuo/naive_bayes.git 或直接下载压缩包[link](https://github.com/jiuzhangjiangzuo/naive_bayes/archive/master.zip)          
2.2 输入命令行: cd naive_bayes          
2.3 运行jupyter: jupyter notebook          
2.4 在notebook中尝试运行nb-sklearn-version.ipynb，看看是否会出错     
2.5 若成功运行，则忽略下面的内容      

## 如果anacoda的环境不包含所需要的库，请按照以下步骤安装
3.1 打开一个terminal，windows用户建议打开Anaconda Prompt.          
3.2 输入命令行: conda create --name nb python=3.5          
3.3 如果提示预装一些包，比如Proceed ([y]/n)?，选择:y          
3.4 输入命令行: conda activate nb   (有同学的环境激活命令是:source activate nb,注意看环境创建完成之后，terminal上面的提示信息)。             
如果激活环境遇到了问题，conda会自己提示解决方案，比如：          
```
CommandNotFoundError: Your shell has not been properly configured to use 'conda activate'.
If your shell is Bash or a Bourne variant, enable conda for the current user with

    $ echo ". /Users/Andrew/anaconda3/etc/profile.d/conda.sh" >> ~/.bash_profile
```
NOTE： 注意这是我环境给出的解决方案(里面的Andrew是我的用户名)，不同的机器可能会给出不同的方案，要仔细看执行conda activate nb之后, terminal里面给出的到底是什么内容。          

3.5. 输入命令行: git clone https://github.com/jiuzhangjiangzuo/naive_bayes.git 或直接下载压缩包[link](https://github.com/jiuzhangjiangzuo/naive_bayes/archive/master.zip)          
3.6 输入命令行: cd naive_bayes          
3.7 输入命令行: pip install -r requirements.txt          
3.8 运行jupyter: jupyter notebook          
