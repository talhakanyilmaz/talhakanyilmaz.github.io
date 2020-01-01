---
title: Multilayer Perceptron
layout: post
date: 2019-12-26 05:48
tag:
 -image processing
 -perceptron
category: blog
author: talhakanyilmaz
description: Multilayer Perceptron
comment: false
---

Çok katmanlı perceptrons (Multilayer Perceptron), perceptrons olarak adlandırılan basit sinir hücreleri ağıdır. Temel fikir olan tek perceptron (single perceptron) ilk olarak 1958 yılında Rosenblatt tarafından tanıtılmıştır. Perceptron birçok değeri girdi olarak alıp tek bir çıktı üretir. Çıktıyı oluştururken girdi ağırlıklarına uygun olarak bir lineer kombinasyon oluşturulur ve bazı lineer olmayan etkinleştirme fonksiyonu yoluyla çıktılara yerleştirilir.

![](https://erdincuzun.com/wp-content/uploads/2017/2016/neural_network/percepton.png)

  

Etkinleştirme fonksiyonu olarak:

![](https://erdincuzun.com/wp-content/uploads/2017/2016/neural_network/percepton_01.png)

Matematiksel olarak elverişli oldukları için genelde bu fonksiyonlar kullanılır. Bu yapı çok katmanlı perceptrons ağları güçlü ve doğrusal olmayan eşleştirmeleri modellemeyi sağlar.Tek perceptron’un akış grafiği aşağıdaki gibidir.

![](https://erdincuzun.com/wp-content/uploads/2017/2016/neural_network/percepton_02.png)

Sınırlı sayıda eşleştirme olanak sağladığı için tek perceptron kullanışlı bir yöntem değildir. Çok katmanlı perceptron girdi, gizli ve çıktı katmanlarından oluşur. İşlemler ağda adım adım yürütülür. Çok katmanlı perceptron’un akış grafiği aşağıdaki gibidir.

![](https://erdincuzun.com/wp-content/uploads/2017/2016/neural_network/percepton_03.png)

Çok katmanlı perceptron formülasyonu:

![](https://erdincuzun.com/wp-content/uploads/2017/2016/neural_network/percepton_04.png)
