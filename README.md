# Awesome-Long-Term-Memory-on-RAG-Papers


Awesome-Long-Term-Memory-on-RAG is a collection of state-of-the-art, novel, exciting Long-Term Memory methods based on Retrieval-Augment Generation (RAG). It contains papers, codes, and datasets. Any additional things regarding memory, PRs, issues are welcome and we are glad to add you to the contributor list [here](#contributors). Any problems, please contact yiwen23-c@my.cityu.edu.hk or derongxu@mail.ustc.edu.cn. If you find this repository useful to your research or work, it is really appreciated to star this repository. :sparkles:





## Bookmarks

- [Survey Papers](#survey-papers)
- [Benchmark](#benchmark)
- [Unstructured Long Term Memory](#unstructured-memory)
- [Structural Long Term Memory](#structural-memory)



## Papers







### Survey Papers <span id="survey-papers"></span>

| Time | Title                                                        |  Venue  |                            Paper                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: |
| 2024.03 | **A survey on large language model based autonomous agents** | FCS | [link](https://link.springer.com/article/10.1007/s11704-024-40231-1)|
| 2024.04 | **A Survey on the Memory Mechanism of Large Language Model based Agents** |   Arxiv     | [link](https://arxiv.org/pdf/2404.13501)|
| 2025.01 | **Human-inspired Perspectives: A Survey on AI Long-term Memory** |   Arxiv    | [link](https://arxiv.org/pdf/2411.00489)|
| 2025.03 | **From Human Memory to AI Memory: A Survey on Memory Mechanisms in the Era of LLMs** |   Arxiv    | [link](https://arxiv.org/pdf/2504.15965)|
| 2025.04 | **Advances and Challenges in Foundation Agents: From Brain-Inspired Intelligence to Evolutionary, Collaborative, and Safe Systems** |   Arxiv     | [link](https://arxiv.org/pdf/2504.01990)|
| 2025.05 | **Rethinking Memory in AI: Taxonomy, Operations, Topics, and Future Directions** |   Arxiv     | [link](https://arxiv.org/pdf/2505.00675)|







### Benchmark <span id="benchmark"></span>

| Year    | Dataset | Paper           |      Venue       |                          #&nbsp;Sessions                            |                           #&nbsp;Queries                     | Discription |
| :-------: | :-------: | --------------------------------------------- | :--------------: | :-----------------------------------: | :-------------------------------------: |  :--------------------------------------------------------: |
| 2022 |[MSC](https://parl.ai/projects/msc/)|**Beyond Goldfish Memory: Long-Term Open-Domain Conversation** | ACL | 5 |1k|[link](https://aclanthology.org/2022.acl-long.356.pdf)      |
| 2022 |[CareCall](https://github.com/naver-ai/carecall-memory)|**Keep Me Updated! Memory Management in Long-term Conversations** | EMNLP |5|1k|[link](https://aclanthology.org/2022.findings-emnlp.276.pdf)      |
| 2023 |[MT-Bench+](https://github.com/LuJunru/MemoChat) |**MemoChat: Tuning LLMs to Use Memos for Consistent Long-Range Open-Domain Conversation** |Arxiv |  ||[link](https://arxiv.org/pdf/2308.08239)      |
| 2024 |[PerLTQA](https://github.com/Elvin-Yiming-Du/PerLTQA) |**PerLTQA: A Personal Long-Term Memory Dataset for Memory Classification, Retrieval, and Synthesis in Question Answering** |   ACL-SIGHAN    | 4K |      8593     |[link](https://aclanthology.org/2024.sighan-1.18.pdf)      |
| 2024 |[LoCoMo](https://github.com/snap-research/locomo) |**Evaluating Very Long-Term Conversational Memory of LLM Agents** |ACL | 1k |7512|[link](https://aclanthology.org/2024.acl-long.747.pdf)      |
| 2024 |[memdaily](https://github.com/nuster1128/MemSim) |**MemSim: A Bayesian Simulator for Evaluating Memory of LLM-based Personal Assistant** |Arxiv  |  ||[link](https://arxiv.org/pdf/2409.20163)      |
| 2024 |[MemoryBank](https://github.com/zhongwanjun/MemoryBank-SiliconFriend) |**Memorybank: Enhancing large language models with long-term memory** |AAAI |  ||[link](https://ojs.aaai.org/index.php/AAAI/article/view/29946)      |
| 2025 |[CarMem](https://github.com/johanneskirmayr/CarMem) |**CarMem: Enhancing Long-Term Memory in LLM Voice Assistants through Category-Bounding** |COLING | 1k |NA|[link](https://aclanthology.org/2025.coling-industry.29.pdf)      |
| 2025 |[madial-bench](https://github.com/hejunqing/MADial-Bench) |**MADial-Bench: Towards Real-world Evaluation of Memory-Augmented Dialogue Generation** |NAACL | 160 |NA|[link](https://aclanthology.org/2025.naacl-long.499.pdf)      |
| 2025 |[Long-MT-Bench+](https://github.com/Microsoft/secom) |**On Memory Construction and Retrieval for Personalized Conversational Agents** |ICLR |  ||[link](https://openreview.net/pdf?id=xKDZAW0He3)      |
| 2025 |[LongMemEval](https://github.com/xiaowu0162/LongMemEval) |**LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory** |   ICLR    | 50k |        500      |[link](https://openreview.net/pdf?id=pZiyCaVuti)      |
| 2025 |[Temporal Memory](https://github.com/Zyphra/TemporalMemoryDataset) |**Toward Conversational Agents with Context and Time Sensitive Long-term Memory** |   Arxiv    |  |              |[link](https://openreview.net/pdf?id=pZiyCaVuti)      |
| 2025 |[StoryBench] |**StoryBench: A Dynamic Benchmark for Evaluating Long-Term Memory with Multi Turns** |   Arxiv    |  |              |[link](https://arxiv.org/pdf/2506.13356v1)      |





### Unstructured Long Term Memory <span id="unstructured-memory"></span>
| Time | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2022 | **Keep me updated! memory management in long-term conversations** | EMNLP | [link](https://aclanthology.org/2022.findings-emnlp.276.pdf) | [link](https://github.com/naver-ai/carecall-memory) |
| 2023 | **MemoChat: Tuning LLMs to Use Memos for Consistent Long-Range Open-Domain Conversation** | Arxiv | [link](https://arxiv.org/pdf/2308.08239) | [link](https://github.com/LuJunru/MemoChat) |
| 2023 | **Recursively Summarizing Enables Long-Term Dialogue Memory in Large Language Models** | Neurocomputing | [link](https://arxiv.org/pdf/2308.15022) |  |
| 2023 | **Think-in-Memory: Recalling and Post-thinking Enable LLMs with Long-Term Memory** | Arxiv | [link](https://arxiv.org/pdf/2311.08719) |  |
| 2024 | **Memorybank: Enhancing large language models with long-term memory** | AAAI | [link](https://ojs.aaai.org/index.php/AAAI/article/view/29946) | [link](https://github.com/zhongwanjun/MemoryBank-SiliconFriend) |
| 2024 | **Cognitive Personalized Search Integrating Large Language Models with an Efficient Memory Mechanism** | WWW | [link](https://dl.acm.org/doi/pdf/10.1145/3589334.3645482) |  |
| 2025 | **Beyond Retrieval: Embracing Compressive Memory in Real-World Long-Term Conversations** | Coling | [link](https://aclanthology.org/2025.coling-main.51.pdf) | [link](https://github.com/nuochenpku/COMEDY) |
| 2025 | **Toward Conversational Agents with Context and Time Sensitive Long-term Memory** | Arxiv | [link](https://arxiv.org/pdf/2406.00057) | [link](https://github.com/Zyphra/TemporalMemoryDataset) |
| 2025 | **Towards Lifelong Dialogue Agents via Timeline-based Memory Management** | NAACL | [link](https://aclanthology.org/2025.naacl-long.435.pdf) | [link](https://huggingface.co/spaces/ResearcherScholar/Theanine) |
| 2025 | **SeCom: On Memory Construction and Retrieval for Personalized Conversational Agents** | ICLR | [link](https://openreview.net/pdf?id=xKDZAW0He3) | [link](https://github.com/Microsoft/secom) |




### Structural Long Term Memory <span id="structural-memory"></span>



| Time | Title                                                        |  Venue  | Structure |                           Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----: |:------------------------------------------------------: | :----------------------------------------------------------: |
| 2024 | **Crafting Personalized Agents through Retrieval-Augmented Generation on Editable Memory Graphs** | EMNLP | Graph | [link](https://aclanthology.org/2024.emnlp-main.281.pdf) |  |
| 2024 | **HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models** | NeurIPS | Knowledge Graph | [link](https://openreview.net/pdf?id=hkujvAPVsg) | [link](https://github.com/OSU-NLP-Group/HippoRAG) |
| 2025 | **From Isolated Conversations to Hierachical Schemas: Dynamic Tree Memory Representation for LLMs** | Arxiv | Tree | [link](https://openreview.net/pdf?id=moXtEmCleY) |  |
| 2025 | **From RAG to Memory: Non-Parametric Continual Learning for Large Language Models** | ICML | Knowledge Graph | [link](https://arxiv.org/pdf/2502.14802?) | [link](https://github.com/OSU-NLP-Group/HippoRAG) |











## Other Related Awesome Repository

- [Survey_Memory_in_AI](https://github.com/Elvin-Yiming-Du/Survey_Memory_in_AI)




## Contributors

<a href="https://wenyiwy99.github.io/" target="_blank"><img src="https://avatars.githubusercontent.com/u/49638683?v=4" alt="wywyddup" width="96" height="96"/></a> 
<a href="https://quqxui.github.io/" target="_blank"><img src="https://avatars.githubusercontent.com/u/41822324?v=4" alt="quqxui" width="96" height="96"/></a> 





<p align="right">(<a href="#top">back to top</a>)</p>






















