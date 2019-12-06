# learning-journey
---

## Programming Skills
- Visualization for DataScience
  - [DataCamp] Improving Your Visualizations in Python ([buy](https://www.datacamp.com/courses/improving-your-data-visualizations-in-python))([certificate](https://www.datacamp.com/statement-of-accomplishment/course/27cd42680aa2009e96d3e3d897a9031067aefd55)) (2019.3.29)


## ML platform/framework
- Distributed Tensorflow
  - TensorFlow Dev Summit 2017 ([video](https://youtu.be/la_M6bCV91M)) (2019.3.31)
  - A Gentle Introduction, Amid Fish ([blog](http://amid.fish/distributed-tensorflow-a-gentle-introduction)) (2019.3.31)
- Ray
  - documentation/tutorial ([html](https://ray.readthedocs.io/en/latest/index.html))
- Spark tuning
  - Tuning and Debugging Apache Spark, databricks, 2015 ([video](https://youtu.be/kkOG_aJ9KjQ)) (2019.3.31)
  - Spark Performance Tuning, 2018 ([video](https://youtu.be/LtcPhcHAvLw)) (2019.3.31)
- GCP, AutoML
  - AI explanation, [docs](https://storage.googleapis.com/cloud-ai-whitepapers/AI%20Explainability%20Whitepaper.pdf)
  
  

## NLP-based ML/DL
- [semi-supervised sequence learning](https://arxiv.org/abs/1511.01432) [code](https://github.com/dongjun-Lee/transfer-learning-text-tf) (2019.5.7)
- [fasttext](https://fasttext.cc/docs/en/support.html)
  - [word representation](https://fasttext.cc/docs/en/unsupervised-tutorial.html)
  
  
## Courses

- [cs224w 2018 graph ML](http://snap.stanford.edu/class/cs224w-2018/)
  - lec4 : Construction, Inference, Deconvolution  [slide](http://snap.stanford.edu/class/cs224w-2018/handouts/04-netconstruct.pdf) [video](http://snap.stanford.edu/class/cs224w-videos-2018/181004-cs224w-720.mp4)
- [cs294-158: Deep USL](https://sites.google.com/view/berkeley-cs294-158-sp19/home)  
  - lec6:  SSL [slide](https://drive.google.com/file/d/1qV7tIGc8HqTbho_0_3NGzygO7kovrdAP/view), [video1](https://youtu.be/5NMIUZ7_nrg), [video2](https://youtu.be/AC4l_MY2Dhc)
  - lec8 : Evaluation of SSL [slide](https://drive.google.com/file/d/1-QT3mstxpi4DTDj9y46JdOxSMpNBgXvi/view), [video](https://youtu.be/7o9dT6puHHg)
  - lec9 : Unsupervised Distribution Alignment [slide](https://drive.google.com/file/d/1bvn7ONQwW7Vno0iKPhd-sPyKYWEGiT8Q/view) [video](https://youtu.be/0AxgLbQfyjQ)

## Semi-supervised learning
- Constrative Predictive Coding ([paper](https://arxiv.org/abs/1807.03748)) ([code](https://github.com/davidtellez/contrastive-predictive-coding))
- Realistic Evaluation of Deep Semi-Supervised Learning Algorithms ([paper](https://arxiv.org/abs/1804.09170)) ([code:pytorch](https://github.com/perrying/realistic-ssl-evaluation-pytorch)) ([annotated](https://drive.google.com/open?id=1ta53xtLIWjMaysmFRwuYH7pxa5F2e5D7))

## Conferences

- CAMLIS 2019
 - Learning to Rank Relevant Malware Strings Using Weak Supervision, [link](https://www.camlis.org/2019/talks/tully)
   - strings 로 출력되는 문자열들의 악성 연관성에 따라 정렬(recommend, rank)하는 문제. snokel로 weak supervision
   - NDCG, rank 문제의 metric. [link](http://fastml.com/evaluating-recommender-systems/)
   - snokel, probabilistic label learning
 
- DerbyCon 2019
 - http://www.irongeek.com/i.php?page=videos%2Fderbycon9%2Fmainlist
 
## OpenSource
- LightGBM Util [code](https://github.com/hoondori/lightgbm_util)
  - tree to table converter
  
## Uncertainty
- Google의 Trust Score [annotated](https://drive.google.com/open?id=1SOY1WZvrxoF6bradFzR2YMofxCAjMmWJ) [code](https://github.com/google/TrustScore/)



# In Work
- Unsupervised Distribution Alignment를 이용해서 labeled/hugh In-company dataset과 unlabeled out-of-company dataset 사이의 연결성을 찾아보기 => SSL? or Generator?
- 도메인에 무관한 SSL 방식들 (Mean Teacher, Virtual Adversarial Training, Entropy Minimization) 사용 