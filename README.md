# Twitter-Finans-LSTM-Duygu-Analizi

Twitter Üzerindeki Finansal Tweetlerin LSTM Sinir Ağı Algoritması ile Duygu Analizi

Sentiment Analysis of Financial Twitter Posts on Twitter with the LSTM Neural Network Algorithm

Authors:

• Hakan Yusufoğlu

Department of Computer Engineering, Faculty of Engineering and Architecture, Istanbul Gelisim University, Istanbul, Turkey

• Hakan Aydın

Department of Computer Engineering, Faculty of Engineering, Istanbul Topkapı University, Istanbul, Turkey

• Ali Çetinkaya

Department of Electronics Technology, Istanbul Gelisim Vocational School, Istanbul Gelisim University, Istanbul, Turkey

For Correspondence: alcetinkaya@gelisim.edu.tr

Article Information

• Received: September 16, 2021

• Accepted: November 29, 2021

• Full Article Access Link: [Twitter Üzerindeki Finansal Tweetlerin LSTM Sinir Ağı Algoritması ile Duygu Analizi](https://dergipark.org.tr/en/pub/veri/issue/67424/996003)

Özet:

Bu çalışmada, duygu analizi yöntemiyle EUR/USD hareket yönünü tahmin etmek için geliştirilen Uzun-Kısa Vadeli Bellek (LSTM) Modeli sunulmaktadır. Çalışmada veri setlerinin belirlenmesi ile modelin eğitimi/testi olmak üzere iki uygulama yapılmıştır. Çalışmada yapılan ilk uygulama kullanılacak veri setinin oluşturulması aşamalarını içermektedir. Bu veri seti ilk defa bu çalışma kapsamında oluşturulmuştur. Veri setinin oluşturulmasında ilk olarak 2005 yılından günümüze kadar Twitter üzerindeki #eurusd konu etiketli veya eurusd kelimesini barındıran filtrelenmiş İngilizce tweet mesajları içeriklerine göre duygu analizi yöntemiyle sınıflandırılmıştır. Bu maksatla her bir tweetin olumlu, olumsuz veya tarafsız (nötr) olup olmadığı belirlenmiş ve günlük olarak bu tweetlerin duygu oranlarının ortalamaları hesaplanmıştır. Veri setinin oluşturulmasında ikinci olarak finance.yahoo.com sitesinden EUR/USD değerleri günlük bazda elde edilmiştir. Veri setinin oluşturulmasındaki son aşama ise anlatılan birinci ve ikinci adımlarda elde edilen zaman serisine dayalı veriler. csv formatında bir veri seti yapısında birleştirilmiştir. Böylelikle yüksek tahmin başarı oranına sahip LSTM modelinin eğitilmesi ve testi aşamalarında kullanılacak olan zaman serisi verilerine dayalı veri seti elde edilmiştir. Veri seti belirlendikten sonra LSTM tahmin modelinin eğitimi ve testi aşamasına geçilmiştir. Çalışmada yapılan ikinci uygulama modelin eğitimi/testi aşamalarını içermektedir. Bu aşamada en yüksek başarı oranına sahip LSTM tahmin modelini belirlemek maksadıyla eğitim adımlarının ve LSTM sinir ağı katman yapısının değiştirilmesi suretiyle farklı deneyler yapılmıştır. Yapılan bu deneyler sonucunda %94,48 başarı oranına sahip en iyi LSTM modeli belirlenmiştir. Çalışma neticesinde elde edilen sonuçlar geliştirilen LSTM tahmin modelinin para piyasalarında EUR/USD hareket yönünün yüksek doğrulukta tahmin edilmesinde yardımcı bir araç olarak kullanılabileceği yönündedir. Araştırmanın sonuçları Yapay zeka algoritmaları ile duygu analizi açısından önemli bilgiler içermesinin yanı sıra, gelecekte farklı sektörlerde uygulanması açısından değer taşımaktadır.

Anahtar Kelimeler: Derin öğrenme, LSTM, Finansal Analiz, EUR/USD Tahmini, Duygu Analizi.

Abstract:

This study presents the Long-Short-Term Memory (LSTM) model developed to predict the direction of movement of the EUR/USD through sentiment analysis. Two applications are carried out in the study, namely, determination of data sets and training/testing of the model. The first application in the study involves the stages of creating the dataset to be used. This dataset is created for the first time in this study. In creating the dataset, filtered English tweet messages with the hashtag #eurusd or the word eurosd on Twitter from 2005 to the present are first classified according to their content using sentiment analysis. For this purpose, each tweet is determined to be positive, negative or neutral (neutral) and the average of the sentiment scores of these tweets is calculated on a daily basis. Secondly, EUR/USD values are obtained from finance.yahoo.com on a daily basis to create the dataset. The last step in the creation of the dataset is to summarise the data based on the time series obtained in the first and second steps described in a dataset structure in csv format. In this way, a dataset based on time series data is obtained, which is used in the training and testing phase of the LSTM model and has a high prediction success rate. Once the dataset is determined, the training and testing phase of the LSTM prediction model is started. The second application in the study involves the training/testing phases of the model. In this phase, various experiments are conducted in which the training steps and the structure of the LSTM layers of the neural network are changed to determine the LSTM prediction model with the highest success rate. As a result of these experiments, the best LSTM model is determined with a success rate of 94.48%. The results of the study show that the developed LSTM prediction model can be used as a helpful tool for estimating the direction of movement of EUR/USD in money markets with high accuracy. The results of the research are valuable in terms of application in different sectors in the future, as well as containing important information in terms of Artificial Intelligence algorithms and sentiment analysis.

Keywords: Deep learning, LSTM, Financial Analysis, EUR/USD Forecast, Sentiment Analysis

How to Cite

• IEEE: H. Yusufoğlu, H. Aydin, and A. Çeti̇nkaya, “Twitter Üzerindeki Finansal Tweetlerin LSTM Sinir Ağı Algoritması ile Duygu Analizi”, Veri Bilimi, 4(3), 28-43., Nov. 2021.

• APA: Yusufoğlu, H., Aydın, H., & Çetinkaya, A. (2021). Twitter Üzerindeki Finansal Tweetlerin LSTM Sinir Ağı Algoritması ile Duygu Analizi. Veri Bilimi, 4(3), 28-43.	

• MLA: Yusufoğlu, Hakan, Hakan Aydın, and Ali Çetinkaya. "Twitter Üzerindeki Finansal Tweetlerin LSTM Sinir Ağı Algoritması ile Duygu Analizi." Veri Bilimi 4.3 (2021): 28-43.

License:

This work is licensed under a Creative Commons Attribution-Non Commercial 4.0 International License, allowing non-commercial sharing and adaptation with proper attribution.
