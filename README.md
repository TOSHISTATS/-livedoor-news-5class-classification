# livedoor-news-5class-classification

livedoor-newsデータを用いた5クラスの判別問題を multilingual-BERTで90%超の精度を達成

Achieve more than 90% accuracy with multilingual-BERT for 5 class-classification problem using livedoor-news data

BERT, or Bidirectional Encoder Representations from Transformers by Google, is a new method of pre-training language representations which obtains state-of-the-art results on a wide array of Natural Language Processing (NLP) tasks.

finetuned with data of livedoor news corpus (training 3153 samples, test 826 samples)

Evaluation results
test_accuracy = 0.9281,




![Screenshot 2022-05-12 17 50 23](https://user-images.githubusercontent.com/28681557/168032499-c9a5cbd4-bc41-4278-a50c-c66e7011c9da.png)
![Screenshot 2022-05-12 17 47 28](https://user-images.githubusercontent.com/28681557/168032547-61ba73c1-d93e-4f76-80de-ca780e6aab45.png)


The academic paper by Google which describes BERT in detail and provides full results on a number of tasks can be found here: https://arxiv.org/abs/1810.04805.

(1) livedoor news corpus https://www.rondhuit.com/download.html#ldcc   
CC BY-ND 2.1 JP https://creativecommons.org/licenses/by-nd/2.1/jp/



This code is solely for educational purposes. The code cannot be used for investments or businesses in practice. Toshi Stats Co.,Ltd. and I do not accept any responsibility or liability for loss or damage occasioned to any person or property through using materials, instructions, methods, algorithm or ideas contained herein, or acting or refraining from acting as a result of such use. Toshi Stats Co.,Ltd. and I expressly disclaim all implied warranties, including merchantability or fitness for any particular purpose. There will be no duty on Toshi Stats Co.,Ltd. and me to correct any errors or defects in the codes and the software

Copyright © 2022 ToshiStats Co.,Ltd. All right reserved
