# Information comes from [tokenmill/awesome-nlg](https://github.com/tokenmill/awesome-nlg)
# Awesome Natural Language Generation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![Piscis Magnus from BL Harley 647](logo.png)

Natural Language Generation is a broad domain with applications in chat-bots, story generation, and data descriptions. There is a wide spectrum of different technologies addressing parts or the whole of the NLG process. This list aims to represent this deversity of NLG applications and techniques by providing links to various projects, tools, research papers, and learning materials.

## Contents

- [Datasets](#datasets)
- [Dialog](#dialog)
- [Evaluation](#evaluation)
- [Grammar](#grammar)
- [Libraries](#libraries)
- [Narrative Generation](#narrative-generation)
- [Neural natural language generation](#neural-net-nlg)
- [Papers and Articles](#papers)
- [Products](#products)
- [Realizers](#realizers)
- [Templating Languages](#templating-languages)
- [Videos](#videos)

## Datasets

- [Alex Context NLG Dataset](https://github.com/UFAL-DSG/alex_context_nlg_dataset) - A dataset for NLG in dialogue systems in the public transport information domain. :star:22
- [Box-score data](https://github.com/harvardnlp/boxscore-data/) - This dataset consists of (human-written) NBA basketball game summaries aligned with their corresponding box- and line-scores. :star:68
- [E2E](http://www.macs.hw.ac.uk/InteractionLab/E2E) - This shared task focuses on recent end-to-end (E2E), data-driven NLG methods, which jointly learn sentence planning and surface realisation from non-aligned data.
- [Neural-Wikipedian](https://github.com/pvougiou/Neural-Wikipedian) - The repository contains the code along with the required corpora that were used in order to build a system that "learns" how to generate English biographies for Semantic Web triples. :star:7
- [WeatherGov](https://cs.stanford.edu/~pliang/data/weather-data.zip) - Computer-generated weather forecasts from weather.gov (US public forecast), along with corresponding weather data.
- [WebNLG](https://github.com/ThiagoCF05/webnlg) - The enriched version of the WebNLG - a resource for evaluating common NLG tasks, including Discourse Ordering, Lexicalization and Referring Expression Generation. :star:30
- [WikiBio - wikipedia biography dataset](https://github.com/DavidGrangier/wikipedia-biography-dataset) - This dataset gathers 728,321 biographies from wikipedia. It aims at evaluating text generation algorithms. For each article, we provide the first paragraph and the infobox (both tokenized). :star:106
- [The Schema-Guided Dialogue Dataset](https://github.com/google-research-datasets/dstc8-schema-guided-dialogue) - The Schema-Guided Dialogue (SGD) dataset consists of over 20k annotated multi-domain, task-oriented conversations between a human and a virtual assistant. :star:201
- [The Wikipedia company corpus](https://gricad-gitlab.univ-grenoble-alpes.fr/getalp/wikipediacompanycorpus) - Company descriptions collected from Wikipedia. The dataset contains semantic representations, short, and long descriptions for 51K companies in English.
- [YelpNLG](https://nlds.soe.ucsc.edu/yelpnlg) - YelpNLG provides resources for natural language generation of restaurant reviews.

## Dialog

- [Chatito](https://github.com/rodrigopivi/Chatito) - Generate datasets for AI chatbots, NLP tasks, named entity recognition or text classification models using a simple DSL! :star:571
- [NNDIAL](https://github.com/shawnwun/NNDIAL) - NNDial is an open source toolkit for building end-to-end trainable task-oriented dialogue models. :star:313
- [Plato](https://github.com/uber-research/plato-research-dialogue-system) - This is the Plato Research Dialogue System, a flexible platform for developing conversational AI agents.  :star:800
- [RNNLG](https://github.com/shawnwun/RNNLG) - RNNLG is an open source benchmark toolkit for Natural Language Generation (NLG) in spoken dialogue system application domains. :star:477
- [TGen](https://github.com/UFAL-DSG/tgen) - Statistical NLG for spoken dialogue systems. :star:169

## Evaluation

- [compare-mt](https://github.com/neulab/compare-mt) - A tool for holistic analysis of language generations systems. :star:286
- [NLG-eval](https://github.com/Maluuba/nlg-eval) - Evaluation code for various unsupervised automated metrics for Natural Language Generation. :star:662
- [VizSeq](https://github.com/facebookresearch/vizseq) - A Visual Analysis Toolkit for Text Generation Tasks. :star:253

## Grammar

- [OpenCCG](https://github.com/OpenCCG/openccg) - OpenCCG library for parsing and realization with CCG. :star:180
- [GrammaticalFramework](http://www.grammaticalframework.org/) - A programming language for multilingual grammar applications.
- [EasyCCG](https://github.com/mikelewis0/easyccg) - CCG: All combinators, common grammar format, parsing to logical form, parameter estimation for probabilistic CCG. :star:51
- [CCG Lab](https://github.com/bozsahin/ccglab) - All combinators, common grammar format, parsing to logical form, parameter estimation for probabilistic CCG. :star:15
- [CCGweb](https://github.com/texttheater/ccgweb) - A Web platform for parsing and annotation. :star:5

## Libraries

- [Cron Expression Descriptor](https://github.com/bradymholt/cron-expression-descriptor) - A .NET library that converts cron expressions into human readable descriptions. :star:516
- [Number Words](https://github.com/tokenmill/numberwords) - Convert a number to an approximated text expression: from '0.23' to 'less than a quarter'. :star:178

## Narrative Generation

- [Random Story Generator](https://github.com/aherriot/story-generator) - Using Natural Language Generation (NLG) to create a random short story. :star:42
- [Tracery](https://github.com/galaxykate/tracery) - A story-grammar generation library for JavaScript. :star:1650

## Neural natural language generation

- [graph-2-text](https://github.com/diegma/graph-2-text) - Graph to sequence implemented in Pytorch combining Graph convolutional networks and opennmt-py. :star:110
- [Image Caption Generator](https://github.com/neural-nuts/image-caption-generator) - A Neural Network based generative model for captioning images using Tensorflow. :star:135
- [PPLM](https://github.com/uber-research/PPLM) - Plug and Play Language Model implementation. Allows to steer topic and attributes of GPT-2 models. :star:428
- [Texar](https://github.com/asyml/texar) - Texar is a toolkit aiming to support a broad set of machine learning, especially natural language processing and text generation tasks. :star:1918
- [textgenrnn](https://github.com/minimaxir/textgenrnn) - Easily train your own text-generating neural network of any size and complexity on any text dataset with a few lines of code. :star:3800
- [Transformers](https://github.com/huggingface/transformers) - State-of-the-art Natural Language Processing for TensorFlow 2.0 and PyTorch. :star:26821
- [Summary Generation From Structured Data](https://github.com/akanimax/natural-language-summary-generation-from-structured-data) - For converting information present in the form of structured data into natural language text. :star:155

## Papers and Articles
- [A Closer Look at Recent Results of Verb Selection for Data-to-Text NLG](https://www.inlg2019.com/assets/papers/178_Paper.pdf)
- [A Personalized Data-to-Text Support Tool for Cancer Patients](https://www.inlg2019.com/assets/papers/28_Paper.pdf)
- [Controlling Contents in Data-to-Document Generation with Human-Designed Topic Labels](https://www.inlg2019.com/assets/papers/79_Paper.pdf)
- [Generated Texts Must Be Accurate!](https://ehudreiter.com/2019/09/26/generated-texts-must-be-accurate/)
- [Hotel Scribe: Generating High Variation Hotel Descriptions](https://www.inlg2019.com/assets/papers/44_Paper.pdf)
- [How to generate text: using different decoding methods for language generation with Transformers](https://huggingface.co/blog/how-to-generate)
- [Natural Language Generation enhances human decision-making with uncertain information](https://arxiv.org/pdf/1606.03254.pdf)
- [NLP - Text Generation Reading List](https://github.com/zhongpeixiang/AI-NLP-Paper-Readings/blob/master/NLP/NLP_generation.md) :star:75
- [Survey of the State of the Art in NaturalLanguage Generation: Core tasks, applicationsand evaluation](https://arxiv.org/pdf/1703.09902.pdf)
- [Revisiting Challenges in Data-to-Text Generation with Fact Grounding](https://www.inlg2019.com/assets/papers/32_Paper.pdf)
- [Turing-NLG: A 17-billion-parameter language model by Microsoft](https://www.microsoft.com/en-us/research/blog/turing-nlg-a-17-billion-parameter-language-model-by-microsoft/)

## Products 

- [Accelerated Text](https://github.com/tokenmill/accelerated-text) - Automatically generate multiple natural language descriptions of your data varying in wording and structure. :star:145
- [RosaeNLG](https://rosaenlg.org) - An open-source library for node.js or client side (browser) execution, based on the Pug template engine, to generate texts in English, French, German and Italian.
- [Twine](http://twinery.org/) - An open-source tool for telling interactive, nonlinear stories.

## Realizers

- [Genl](https://github.com/kowey/GenI) - Surface realiser (part of a Natural Language Generation system) using Tree Adjoining Grammar. :star:22
- [JSrealB](https://github.com/rali-udem/JSrealB) - A JavaScript bilingual text realizer for web development. :star:9
- [SimpleNLG](https://github.com/simplenlg/simplenlg) - Java API for Natural Language Generation. :star:654
- [SimpleNLG DE](https://github.com/sebischair/SimpleNLG-DE) - German version of SimpleNLG 4. :star:6
- [SimpleNLG-EnFr](https://github.com/rali-udem/SimpleNLG-EnFr) - SimpleNLG-EnFr 1.1 is a bilingual English/French adaption of SimpleNLG v4.2. :star:20

## Templating Languages

- [calyx](https://github.com/maetl/calyx) - A Ruby library for generating text with recursive template grammars. :star:46
- [nalgene](https://github.com/spro/nalgene) - Natural language generation language. :star:45
- [StringTemplate](https://www.stringtemplate.org/) - Java template engine (with ports for C##, Objective-C, JavaScript, Scala) for generating source code, web pages, emails, or any other formatted text output. 

## Videos

- [Data-To-Text: Generating Textual Summaries of Complex Data - Ehud Reiter](https://www.youtube.com/watch?v=kFRw-wk5YOA)
- [Imitation Learning and its Application to Natural Language Generation](https://slideslive.com/38922816/imitation-learning-and-its-application-to-natural-language-generation)
- [Natural Language Generation (Introduction)](https://www.youtube.com/watch?v=4fjM72lbJaw)
- [Strata Data Conference | The future of natural language generation: 2017-2027](https://www.youtube.com/watch?v=Ls7elVbN8bI)
- [The Quest for Automated Story Generation - Mark Riedl](https://www.youtube.com/watch?v=wgcDUX_BPpk)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [TokenMill](https://www.tokenmill.ai) has waived all copyright and related or neighboring rights to this work.

