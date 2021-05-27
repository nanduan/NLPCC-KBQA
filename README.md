# NLPCC-KBQA

People frequently asked me "where can I download" the NLPCC-KBQA datesets used in previous NLPCC Open Domain QA Evaluations from 2016 to 2018. So I just put these 4 files here, including:
- **nlpcc2016-2018.kbqa.train**. This file includes 24,479 training instances, each of which is consist of (i) a knowledge triple in the form of <subject entity, relation, object entity> and (ii) a natural language question labeled by human based on the subject entity and relation, with the object entity as its answer.
- **nlpcc2016.kbqa.test, nlpcc2017.kbqa.test, nlpcc2018.kbqa.test**. These 3 files are used as the KBQA testsets in NLPCC 2016, 2017 and 2018, respectively. Please note that, the 2017 testset doesn't provide the knowledge triple infor for each test instance.

Please cite the follwing papers when you use the datasets:
@InProceedings{10.1007/978-3-319-50496-4_89,
author="Duan, Nan",
editor="Lin, Chin-Yew
and Xue, Nianwen
and Zhao, Dongyan
and Huang, Xuanjing
and Feng, Yansong",
title="Overview of the NLPCC-ICCPOL 2016 Shared Task: Open Domain Chinese Question Answering",
booktitle="Natural Language Understanding and Intelligent Applications",
year="2016",
publisher="Springer International Publishing",
address="Cham",
pages="942--948",
abstract="In this paper, we give the overview of the open domain Question Answering (or open domain QA) shared task in the NLPCC-ICCPOL 2016. We first review the background of QA, and then describe two open domain Chinese QA tasks in this year's NLPCC-ICCPOL, including the construction of the benchmark datasets and the evaluation metrics. The evaluation results of submissions from participating teams are presented in the experimental part.",
isbn="978-3-319-50496-4"
}
