# chatbot
A QA system based on tensorflow Seq2Seq model.

### 1 使用方法：
重新训练模型需要先删除sample下的.pkl和model下的一堆文件，否则会按照保存的模型继续
* <br>**训练模型:**
 <br>运行main.py，用data/lightweight/目录下的chat.txt中的语料训练RNN，
 <br>命令参数`--corpus lightweight --datasetTag chat`
* <br>**测试:**
<br>方法1：读data/test/目录下的sample.txt文件输出回复，命令参数:`--test` 
<br>方法2:交互模式，命令参数:`--test interactive`
