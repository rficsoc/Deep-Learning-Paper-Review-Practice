### 論文審查與程式碼實踐: Deep Learning Paper Review and Practice

* 這是一個完整的深度學習論文評論和程式碼實踐的儲存庫。
* 我們介紹各種熱門的深度學習論文，並專注於最新論文。

#### Image Recognition (影像辨識)

* End-to-End Object Detection with Transformers (ECCV 2020)
* Transformer:進行端對端物件偵測
    * [Original Paper Link](https://arxiv.org/abs/2005.12872) / [Paper Review Video](https://www.youtube.com/watch?v=hCWUTvVrG7E) / [Summary PDF](/lecture_notes/DETR.pdf) / Code Practice
* Searching for MobileNetV3 (ICCV 2019)
* MobileNetV3:搜尋 
    * [Original Paper Link](https://arxiv.org/abs/1905.02244) / Paper Review Video / Summary PDF / Code Practice
* Deep Residual Learning for Image Recognition (CVPR 2016)
* 影像辨識:深度殘差學習
    * [Original Paper Link](https://arxiv.org/abs/1512.03385) / [Paper Review Video](https://www.youtube.com/watch?v=671BsKl8d0E) / [Summary PDF](/lecture_notes/ResNet.pdf) / [MNIST](/code_practices/ResNet18_MNIST_Train.ipynb) / [CIFAR-10](/code_practices/ResNet18_CIFAR10_Train.ipynb) / [ImageNet](/code_practices/Pretrained_ResNet18_ImageNet_Test.ipynb)
* Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization (ICCV 2017)
* 即時風格轉換:透過歸一化實現
    * [Original Paper Link](https://arxiv.org/abs/1703.06868) / [Paper Review Video](https://www.youtube.com/watch?v=OM-6zYYRYfg) / [Summary PDF](/lecture_notes/AdaIN_Style_Transfer.pdf) / [Code Practice](/code_practices/AdaIN_Style_Transfer_Tutorial.ipynb)
* Image Style Transfer Using Convolutional Neural Networks (CVPR 2016)
* CNN:影像風格遷移
    * [Original Paper Link](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) / [Paper Review Video](https://www.youtube.com/watch?v=va3e2c4uKJk) / [Summary PDF](/lecture_notes/Style%20Transfer.pdf) / [Code Practice](/code_practices/Style_Transfer_Tutorial.ipynb)
* Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks (NIPS 2015)Faster R-CNN：
* R-CNN:透過區域提議網路實現即時目標偵測
    * [Original Paper Link](https://arxiv.org/abs/1506.01497) / Paper Review Video / [Summary PDF](/lecture_notes/Faster_R-CNN.pdf) / Code Practice

#### Natural Language Processing (自然語言處理)

* Single Headed Attention RNN: Stop Thinking With Your Head (2020)
* 單頭注意力RNN:停止用心思思考
    * [Original Paper Link](https://arxiv.org/abs/1911.11423) / Paper Review Video / Summary PDF / Code Practice
* BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (NAACL 2019)
* BERT:用於語言理解的深度雙向T的預訓練
    * [Original Paper Link](https://arxiv.org/abs/1810.04805) / Paper Review Video / Summary PDF / Code Practice
* Attention is All You Need (NIPS 2017)
* 關注力:就是你所需要的
    * [Original Paper Link](https://arxiv.org/abs/1706.03762) / [Paper Review Video](https://www.youtube.com/watch?v=AA621UofTUA) / [Summary PDF](/lecture_notes/Transformer.pdf) / [Code Practice](/code_practices/Attention_is_All_You_Need_Tutorial_(German_English).ipynb)
* Neural Machine Translation by Jointly Learning to Align and Translate (ICLR 2015 Oral)
* 翻譯:聯合學習對齊和翻譯進行神經機器翻譯
    * [Original Paper Link](https://arxiv.org/abs/1409.0473) / Paper Review Video / Summary PDF / [Code Practice](/code_practices/Sequence_to_Sequence_with_Attention_Tutorial.ipynb)
* Show and Tell: A Neural Image Caption Generator (CVPR 2015)
* 字幕產生器:展示
    * [Original Paper Link](https://arxiv.org/abs/1411.4555) / Paper Review Video / Summary PDF / [Code Practice](/code_practices/Neural_Image_Captioning_(NIC)_Using_ResNet_101.ipynb)
* Sequence to Sequence Learning with Neural Networks (NIPS 2014)
* 序列學習:使用神經網路
    * [Original Paper Link](https://arxiv.org/abs/1409.3215) / [Paper Review Video](https://www.youtube.com/watch?v=4DzKM0vgG1Y) / [Summary PDF](/lecture_notes/Seq2Seq.pdf) / [Code Practice](/code_practices/Sequence_to_Sequence_with_LSTM_Tutorial.ipynb)

#### Generative Model & Super Resolution (創建模型 & 恢復分辨率)

* Meta-Transfer Learning for Zero-Shot Super-Resolution (CVPR 2020)
* 零樣本超解析度:元遷移學習
    * [Original Paper Link](https://arxiv.org/abs/2002.12213) / [Paper Review Video](https://www.youtube.com/watch?v=PUtFz4vqXHQ) / [Summary PDF](/lecture_notes/MZSR.pdf) / Code Practice
* SinGAN: Learning a Generative Model from a Single Natural Image (ICCV 2019)
* SinGAN:從單一自然影像學習生成模型
    * [Original Paper Link](https://arxiv.org/abs/1905.01164) / Paper Review Video / Summary PDF / Code Practice
* A Style-Based Generator Architecture for Generative Adversarial Networks (CVPR 2019)
* 產生對抗網路:基於樣式的生成器架構
    * [Original Paper Link](https://arxiv.org/abs/1812.04948) / Paper Review Video / [Summary PDF](/lecture_notes/StyleGAN.pdf) / Code Practice
* StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation (CVPR 2018 Oral)
* StarGAN：用於多域圖像到圖像翻譯的統一生成對抗網絡
    * [Original Paper Link](https://arxiv.org/abs/1711.09020) / [Paper Review Video](https://www.youtube.com/watch?v=-r9M4Cj9o_8) / [Summary PDF](/lecture_notes/StarGAN.pdf) / [Code Practice](/code_practices/StarGAN_Tutorial.ipynb)
* Image-to-Image Translation with Conditional Adversarial Networks (CVPR 2017)
* 圖圖翻譯:條件對抗網路
    * [Original Paper Link](https://arxiv.org/abs/1611.07004) / [Paper Review Video](https://www.youtube.com/watch?v=ImiD4npRj7k) / [Summary PDF](/lecture_notes/Pix2Pix.pdf) / [Code Practice](/code_practices/Pix2Pix_for_Facades.ipynb)
* Generative Adversarial Nets (NIPS 2014)
* 生成對抗網路
    * [Original Paper Link](https://arxiv.org/abs/1406.2661) / [Paper Review Video](https://www.youtube.com/watch?v=AVvlDmhHgC4) / [Summary PDF](/lecture_notes/GAN.pdf) / [Code Practice](/code_practices/GAN_for_MNIST_Tutorial.ipynb)

#### Modeling & Optimization (建模 & 最佳化)

* Bag of Tricks for Image Classification (CVPR 2019)
* 影像分類:技巧
    * [Original Paper Link](https://arxiv.org/abs/1812.01187) / Paper Review Video / [Summary PDF](/lecture_notes/Bag_of_Tricks_for_Image_Classification.pdf)
    * [CIFAR-10](/code_practices/ResNet18_CIFAR10_Basic_Training.ipynb) / [CIFAR-10 with Label Smoothing](/code_practices/ResNet18_CIFAR10_Training_with_Label_Smoothing.ipynb) / [CIFAR-10 with Input Mixup](/code_practices/ResNet18_CIFAR10_Training_with_Input_Mixup.ipynb) / [CIFAR-10 with Label Smoothing and Input Mixup](/code_practices/ResNet18_CIFAR10_Training_with_Input_Mixup_and_Label_Smoothing.ipynb)
* Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding (ICLR 2016 Oral)
* 深度壓縮:深度神經網絡:透過剪枝、訓練量化和霍夫曼編碼
    * [Original Paper Link](https://arxiv.org/abs/1510.00149) / Paper Review Video / Summary PDF / Code Practice
* Batch normalization: Accelerating deep network training by reducing internal covariate shift (PMLR 2015)
* 批量歸一化：透過減少內部協變量偏移來加速深度網路訓練
    * [Original Paper Link](https://arxiv.org/abs/1502.03167) / [Paper Review Video](https://www.youtube.com/watch?v=58fuWVu5DVU) / [Summary PDF](/lecture_notes/Batch_Normalization.pdf) / [Code Practice](/code_practices/Batch_Normalization_Evaluation_(with_Residual_Connection).ipynb)

#### Adversarial Examples & Backdoor Attacks (對抗性範例 & 後門攻擊)

* HopSkipJumpAttack: A Query-Efficient Decision-Based Attack (S&P 2020)
* HopSkipJumpAttack:基於查詢的高效決策攻擊
    * [Original Paper Link](https://arxiv.org/abs/1904.02144) / Paper Review Video/ Summary PDF / [Targeted Attack](/code_practices/Targeted_HopSkipJumpAttack_Using_CIFAR10.ipynb) / [Untargeted Attack](/code_practices/Untargeted_HopSkipJumpAttack_Using_CIFAR10.ipynb)
* Breaking certified defenses: Semantic adversarial examples with spoofed robustness certificates (ICLR 2020)
* 打破經過認證的防禦：具有欺騙性穩健性證書的語義對抗範例
    * [Original Paper Link](https://arxiv.org/abs/2003.08937) / [Paper Review Video](https://www.youtube.com/watch?v=D1j3QiXPRag) / [Summary PDF](/lecture_notes/Shadow_Attack.pdf) / [Code Practice](/code_practices/Shadow_Attack_Tutorial.ipynb)
* Sign-OPT: A Query-Efficient Hard-label Adversarial Attack (ICLR 2020)
* Sign-OPT：查詢高效率的硬標籤對抗攻擊
    * [Original Paper Link](https://arxiv.org/abs/1909.10773) / Paper Review Video / Summary PDF / [MNIST](/code_practices/Sign_OPT_Attack_for_MNIST.ipynb) / [CIFAR-10](/code_practices/Sign_OPT_Attack_for_CIFAR_10.ipynb)
* Is BERT Really Robust? A Strong Baseline for Natural Language Attack on Text Classification and Entailment (AAAI 2020 Oral)
* BERT:Robust？自然語言攻擊文本分類與蘊涵的強大基線
    * [Original Paper Link](https://arxiv.org/abs/1907.11932) / [Paper Review Video](https://www.youtube.com/watch?v=EF-IYFTKZiE) / [Summary PDF](/lecture_notes/TextFooler.pdf) / [Code Practice](/code_practices/TextFooler_Tutorial.ipynb)
* Query-Efficient Hard-label Black-box Attack: An Optimization-based Approach (ICLR 2019)
* 查詢高效的硬標籤黑盒攻擊:最佳化的方法
    * [Original Paper Link](https://arxiv.org/abs/1807.04457) / Paper Review Video / [Summary PDF](/lecture_notes/OPT_Attack.pdf) / [MNIST](/code_practices/Opt_Attack_for_MNIST.ipynb) / [CIFAR-10](/code_practices/Opt_Attack_for_CIFAR_10.ipynb)
* Boosting Adversarial Attacks with Momentum (CVPR 2018 Spotlight)
* 對抗性攻擊:增強
    * [Original Paper Link](https://arxiv.org/abs/1710.06081) / Paper Review Video / [Summary PDF](/lecture_notes/Boosting_Adversarial_Attacks_with_Momentum.pdf) / [CIFAR-10](/code_practices/MI_FGSM_Attack_for_CIFAR_10.ipynb) / [ImageNet](/code_practices/MI_FGSM_Attack_for_ImageNet.ipynb)
* Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks (NIPS 2018)
* 毒蛙:神經網路的清潔標籤中毒攻擊
    * [Original Paper Link](https://arxiv.org/abs/1804.00792) / Paper Review Video / [Summary PDF](/lecture_notes/Poison_Frogs.pdf) / [ResNet](/code_practices/One_Shot_Kill_Poison_Attack_ResNet.ipynb) / [AlexNet](/code_practices/One_Shot_Kill_Poison_Attack_AlexNet.ipynb)
* Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models (ICLR 2018)
* 決策的對抗性攻擊:針對黑盒機器學習模型的可靠攻擊
    * [Original Paper Link](https://arxiv.org/abs/1712.04248) / [Paper Review Video](https://www.youtube.com/watch?v=3dX_SsO2mis) / [Summary PDF](/lecture_notes/Boundary_Attack.pdf) / Code Practice

### 往屆論文

* Explaining and Harnessing Adversarial Examples (ICLR 2015)
* 對抗性:解釋
    * [Original Paper Link](https://arxiv.org/abs/1412.6572) / [Paper Review Video](https://www.youtube.com/watch?v=99uxhAjNwps)
* Towards Evaluating the Robustness of Neural Networks (S&P 2017)
* 評估穩健性:神經網路
    * [Original Paper Link](https://arxiv.org/abs/1608.04644) / [Paper Review Video](https://www.youtube.com/watch?v=9kRWHKPyfwQ)
* Towards Deep Learning Models Resistant to Adversarial Attacks (ICLR 2018)
* 深度學習模式:抵抗對抗性攻擊
    * [Original Paper Link](https://arxiv.org/abs/1706.06083) / [Paper Review Video](https://www.youtube.com/watch?v=6RBpdAC9nwY)
* Adversarial Examples Are Not Bugs, They Are Features (NIPS 2019)
* 對抗性例子不是錯誤:是特徵
    * [Original Paper Link](https://arxiv.org/abs/1905.02175) / [Paper Review Video](https://www.youtube.com/watch?v=Y7O47Kq8pmU)
* Certified Robustness to Adversarial Examples with Differential Privacy (S&P 2019)
* 穩健性:差異隱私的對抗性
    * [Original Paper Link](https://arxiv.org/abs/1802.03471) / [Paper Review Video](https://www.youtube.com/watch?v=ySJUlEVlXfk)
* Obfuscated Gradients Give a False Sense of Security (ICML 2018)
* 模糊:錯誤的安全感
    * [Original Paper Link](https://arxiv.org/abs/1802.00420) / [Paper Review Video](https://www.youtube.com/watch?v=0O_Bxln9bTw)
* Constructing Unrestricted Adversarial Examples with Generative Models (NIPS 2018)
* 對抗性範例:使用生成模型建立
    * [Original Paper Link](https://arxiv.org/abs/1805.07894) / [Paper Review Video](https://www.youtube.com/watch?v=IDtaVjJoV4g)
* Adversarial Patch (NIPS 2018)
* 補丁:對抗性
    * [Original Paper Link](https://arxiv.org/abs/1712.09665) / [Paper Review Video](https://www.youtube.com/watch?v=pOlPlTCfCQE)
