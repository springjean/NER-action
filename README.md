# NER-action
Named entity recognition project based on BiLSTM-CRF joint training Chinese word segmentation

The corpus can be changed to what you want, as long as the format is consistent with the train file format in the data folder. The embedding vector I used is a 100-dimensional word vector trained on Wikipedia by the word2vec tool. I have a word vector, and the file is too large to upload. If you need it, you can private me 1952004920@qq.com.
语料可以换成自己想用的，只要格式跟data文件夹下的train文件格式保持一致就可以。我是用的嵌入向量是word2vec工具在维基百科上训练好的100维字向量。本人有词向量，文件太大无法上传，需要的可以私我1952004920@qq.com。

The model embeds word boundary information and character information into the network at the same time. The dimensions are determined according to your own preferences, as long as you remove the comments at 91 in the model file.If you do not want to incorporate word boundary information and want to simply train the word model, you only need to set the word embedding dimension to 0.
该模型是将词语的边界信息与字符信息同时嵌入到网络中的，维度根据自己喜好定，只要将model文件中91处的注释去掉即可。如果不想融入词语边界信息，想单纯的训练字模型，只需将词嵌入维度设置为0即可。
