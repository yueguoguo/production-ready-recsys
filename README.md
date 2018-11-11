# production-ready-recsys

A collection of production-ready recommendation system papers

## What is "production-ready" implementation of recommendation system?

Recommendation system is a pivotal technology for contemporary internet business. It helps on-line business to algorithmically identifies items that potentially draw interests of users, and thus boost stickiness of users to the site or service. 

Academic research in this realm has been active for ages. Many innovative ideas are witnessed during the past a few years which incorporate the cutting-edge techniques (e.g., deep learning, etc.) into a recommendation system. However, many of such proposals stopped at prototyping stage owing to issues in many different aspects. 

A production-ready recommendation system is not just algorithm implementations. It should be a systematic integral of models and relevant peripheral components that servers to performing recommendation tasks in a pragmatic and efficient way. It should be easily integrated into an enterprise-grade production pipeline such that collectively the system resolves a real-world business problem under architectural and engineering constraints such as scalability, latency, etc. 

## Criteria of production-ready recommendation system

As follows criteria of a production-ready recommendation system are listed. 

### Clear definition of real-world scenario

A clear definition of real-world scenarios guide developers and architects to understand business problems well and translate them into modeling problems. 

### Advantage in model performance

A good recommender excels in modeling performance. Performance can be measured by offline metrics like root mean squared error (RMSE), precision and recall at top-k recommended items, etc., and/or online business metrics as click-through rate (CTR), impression rate, etc. 

It is worth noting that there is usually no correlation between offline evaluation performance and online ones. Apparent reason for this is that usually an offline evaluation is based on a sample dataset which is biased. A production-ready requires online testing framework to evaluate recommender performance in actual application.

### Productization-readiness

#### Scalability

It is not rare to see a recommendation system is deployed to serve millions or even billions of users. To this end, the recommendation system must be scalable such that an increasing demand of user size and item size is still within its capacity. 

#### Latency

Latency is another critical criterion for the modern recommendation system, especially for particular on-line services that require immediate responsive feedbacks to engage service subscribers.

#### Model operationalisation and pipeline orchestration

On top of the model creation pipeline, a whole architecture that stream model inputs/outputs is needed.

#### Online testing

Online testing is essential to guarantee a recommender works as expected when it is deployed for actual use. 

### Proof of industrial application

A successful deployment of a recommendation in industry-grade solution or product proves the effectiveness and efficiency. 

## List of production-ready recommendation system

The list contains research work in production-ready recommendation systems in the past 10 years. The list is not exhaustive. Resources in the list are either from publicly available research articles or on-line resources. 

|Things to recommend|Author|Year|Text resources|Codes|Remarks|
|--------------|:-------------:|:--------:|--------------|--------------|--------------|
|Retail products|Overstock|2018|[Link](https://arxiv.org/pdf/1806.11226.pdf)|-|-|
|Online items|Pinterest|2018|[Link](https://arxiv.org/pdf/1711.07601.pdf)|-|-|
|Retail products|JD.com|2017|[Link](https://arxiv.org/ftp/arxiv/papers/1709/1709.00300.pdf)|-|-|
|Social network user interaction|LinkedIn|2017|[Link](https://arxiv.org/pdf/1706.03849.pdf)|-|-|
|Retail products|Sears|2017|[Link](https://arxiv.org/pdf/1705.06338.pdf)|-|-|
|Online items|Pinterest|2017|[Link](https://arxiv.org/pdf/1702.07969.pdf)|-|-|
|Fashion products|Zalando|2017|[Link](https://dl.acm.org/citation.cfm?id=3109897)|-|-|
|Product size|Amazon|2017|[Link](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/p243-sembium.pdf)|-|-|
|Ads|Microsoft|2017|[Link](https://pdfs.semanticscholar.org/e415/d1fc1ec9609dc4895cc4021b15fbc5c8c2e1.pdf)|-|-|
|Music|Clova|2017|[Link](http://ceur-ws.org/Vol-1905/recsys2017_poster18.pdf)|-|-|
|Meals|CornelTech|2016|[Link](https://arxiv.org/pdf/1605.07722.pdf)|-|-|
|Videos|Google|2016|[Link](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45530.pdf)|-|-|
|News article|Yahoo! Japan|2017|[Link](http://delivery.acm.org/10.1145/3100000/3098108/p1933-okura.pdf?ip=167.220.255.60&id=3098108&acc=OPENTOC&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E054E54E275136550&__acm__=1530368701_a1e53cb4a75e4af0a7d321832d16affd)|-|-|
|Display Ads|Alibaba|2017|[Link](http://delivery.acm.org/10.1145/3100000/3098089/p2091-yang.pdf?ip=167.220.255.60&id=3098089&acc=OPENTOC&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E054E54E275136550&__acm__=1530368508_72e99f64f98e923c74e6953a26b915a8)|-|-|
|Mobile App|Google|2016|[Link](https://arxiv.org/pdf/1606.07792.pdf)|-|-|
|Movie|Netflix|2015|[Link](https://dl.acm.org/citation.cfm?id=2843948)|-|-|
|Social media|Yahoo!|2011|[Link](http://www.ramb.ethz.ch/CDstore/www2011/companion/p101.pdf)|-|-| 
|News article|Yahoo!|2010|[Link](https://arxiv.org/abs/1003.0146)|-|-|
|Ads|Microsoft|2010|[Link](http://quinonero.net/Publications/AdPredictorICML2010-final.pdf)|-|-|
|Movie|Microsoft|2009|[Link](https://www.microsoft.com/en-us/research/wp-content/uploads/2009/01/www09.pdf)|-|-|
|News article|Google|2007|[Link](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/35599.pdf)|-|-|
|News article|Google|2007|[Link](https://www2007.org/papers/paper570.pdf)|-|-|