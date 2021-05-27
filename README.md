# NLPCC-KBQA

People frequently asked me "where can I download" the NLPCC-KBQA datesets used in previous NLPCC Open Domain QA Evaluations from 2016 to 2018. So I just put these 4 files here, including:
- **nlpcc2016-2018.kbqa.train**. This file includes 24,479 training instances, each of which is consist of (i) a knowledge triple in the form of <subject entity, relation, object entity> and (ii) a natural language question labeled by human based on the subject entity and relation, with the object entity as its answer.
- **nlpcc2016.kbqa.test, nlpcc2017.kbqa.test, nlpcc2018.kbqa.test**. These 3 files are used as the KBQA testsets in NLPCC 2016, 2017 and 2018, respectively. Please note that, the 2017 testset doesn't provide the knowledge triple infor for each test instance.

Please cite the follwing 2 papers when you use the datasets:

<pre><code>@InProceedings{10.1007/978-3-319-50496-4_89,
author="Duan, Nan",
title="Overview of the NLPCC-ICCPOL 2016 Shared Task: Open Domain Chinese Question Answering",
booktitle="Natural Language Understanding and Intelligent Applications",
year="2016",
publisher="Springer International Publishing",
pages="942--948",
isbn="978-3-319-50496-4"}</code></pre>

<pre><code>@InProceedings{10.1007/978-3-319-73618-1_86,
author="Duan, Nan and Tang, Duyu",
title="Overview of the NLPCC 2017 Shared Task: Open Domain Chinese Question Answering",
booktitle="Natural Language Processing and Chinese Computing",
year="2018",
publisher="Springer International Publishing",
pages="954--961",
isbn="978-3-319-73618-1"}</code></pre>

Contact: Nan Duan (nanduan@microsoft.com)
