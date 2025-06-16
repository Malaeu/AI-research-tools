<h1 align="center">AI Research Tools</h1>

<p align="center">
  <strong><a href="README.md">中文</a> | <a href="README_EN.md">English</a></strong>
</p>

<p align="center">
  <a href="http://kyonhuang.top" target="_blank"><img src="https://img.shields.io/badge/Author-KyonHuang-7AD6FD.svg" alt="Author"></a>
  <a href="https://github.com/bighuang624/AI-research-tools/blob/master/LICENSE" target="_blank"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT license"></a>
</p>

> * Recommendations for research tools I enjoy using (some specific to AI field)
> * Items marked with [To Try] are tools I haven't used yet but seem useful - will try them soon and decide whether to keep based on experience
> * Please suggest good AI research tools not on this list through issues, thank you

## Table of Contents  <!-- omit in toc -->

- [Trend Tracking](#trend-tracking)
  - [RSS Readers](#rss-readers)
- [Paper Discovery](#paper-discovery)
  - [Search Engines](#search-engines)
  - [arXiv Related](#arxiv-related)
  - [Code Implementation Search](#code-implementation-search)
- [Paper Reading](#paper-reading)
  - [Access & Download](#access--download)
  - [Reference Management](#reference-management)
  - [Reading Assistant](#reading-assistant)
  - [Translation Tools](#translation-tools)
  - [Note Taking](#note-taking)
- [Coding & Experiments](#coding--experiments)
  - [PyTorch Related](#pytorch-related)
    - [Feature & Config Wrappers](#feature--config-wrappers)
    - [Project References](#project-references)
    - [Project Management](#project-management)
    - [Style Guides](#style-guides)
    - [Project Templates](#project-templates)
    - [Neural Network Analyzers](#neural-network-analyzers)
    - [Visualization](#visualization)
  - [Experiment Tracking](#experiment-tracking)
  - [Dataset Search](#dataset-search)
  - [Dataset Download](#dataset-download)
  - [Feature Engineering](#feature-engineering)
  - [Hyperparameter Search](#hyperparameter-search)
- [AI Coding Assistants](#ai-coding-assistants)
  - [Autonomous Coding Agents](#autonomous-coding-agents)
  - [AI-Powered Development Tools](#ai-powered-development-tools)
  - [Medical AI Development](#medical-ai-development)
- [Academic Writing](#academic-writing)
  - [LaTeX Templates](#latex-templates)
  - [LaTeX Editors](#latex-editors)
  - [Language & Expression](#language--expression)
    - [Collocation Search](#collocation-search)
    - [Phrase Recommendations](#phrase-recommendations)
    - [Writing Check](#writing-check)
  - [Formula Editing](#formula-editing)
  - [Table to LaTeX](#table-to-latex)
  - [Diagram Drawing](#diagram-drawing)
    - [Drawing Tools](#drawing-tools)
    - [Drawing References](#drawing-references)
    - [PPT Plugins](#ppt-plugins)
    - [Image Conversion](#image-conversion)
    - [Image Editing](#image-editing)
- [Paper Submission](#paper-submission)
  - [Conference & Journal Search](#conference--journal-search)
  - [Anonymous Links](#anonymous-links)
  - [arXiv Submission](#arxiv-submission)
  - [Code Release](#code-release)
- [Others](#others)
  - [Patent Search](#patent-search)
  - [Focus Tools](#focus-tools)
  - [White Noise / Music](#white-noise--music)

## Trend Tracking

### RSS Readers

* [irreader](http://irreader.fatecore.com/): The RSS reader I currently use. A major advantage is that for websites without RSS feeds, irreader can create custom RSS feeds. Also provides popup notifications when subscribed RSS updates. Additionally supports podcast subscriptions and audio media playback that I don't currently need.

## Paper Discovery

### Search Engines

Generally, when I need to find PDF files based on paper titles or other information, I prefer using dblp (clear results, no VPN needed). For special cases, I use Google Scholar.

* [dblp: computer science bibliography](https://dblp.org/): Paper search site designed for CS, indexes top-tier and searchable papers. Can query authors' papers by conference, journal etc. Useful for searching all papers from a computer science conference.

* [Google Scholar](https://scholar.google.com/schhp?hl=en): Besides paper search, you can view paper statistics and citations, get alerts for new papers by following authors or papers, and use automated recommendations for a basic library.

* [Semantic Scholar](https://www.semanticscholar.org/): Can integrate external materials for semantic analysis of papers. Features include: showing citations and references, measuring paper impact, displaying paper figures, auto-generating keywords (from title), analyzing authors, finding additional resources online (e.g., related YouTube videos), and recommending papers.

### arXiv Related

* [arXiv](https://arxiv.org/): Paper preprint repository.

* [arXiv-sanity](http://arxiv-sanity.com/): Major improvements over arXiv including showing abstracts while browsing, comments and basic social features, recommendations, and library functions. Better search functionality.

* [Semantic Sanity: A Personalized Adaptive Feed](https://s2-sanity.apps.allenai.org): Create your own personalized arXiv reading feed. When creating each feed, you select a few papers first, then it recommends based on those papers. You can like or dislike recommendations to help adjust results.

* [Paper Digest – AI for tracking and summarizing papers](https://www.paperdigest.org/): Provides email subscriptions for previous day's papers with one-sentence summaries. More importantly for me, this site also organizes papers when all top conference papers are released.

### Code Implementation Search

* [Papers With Code](https://paperswithcode.com/): Automatically links papers to GitHub implementation repositories and datasets, sorted by GitHub stars. Shows SOTA for various tasks for comparison.

* [labmlai/annotated_deep_learning_paper_implementations](https://github.com/labmlai/annotated_deep_learning_paper_implementations): PyTorch implementations of many algorithms with online annotations. Downside is that shown parts aren't implemented from scratch - some code is in their own package.

## Paper Reading

### Access & Download

* [SCI-Hub Available URLs](http://tool.yovisun.com/scihub/)

### Reference Management

* [Mendeley](https://www.mendeley.com): What I currently use. Supports web, PC, Mac and mobile platforms, can directly annotate and highlight PDFs, with limited free cloud storage.

* [Zotero](https://www.zotero.org/): Can directly capture references from literature database webpages, often used with [Jianguoyun](https://www.jianguoyun.com/) for multi-device sync (supports MacOS, Windows, iPad, Linux, iOS).

### Reading Assistant

* [Kimi Chat](https://kimi.moonshot.cn/): ChatGPT-like product, should be familiar to everyone.

* [Cool Papers](https://papers.cool/): Paper browsing site developed by Su Jianlin. Explore usage according to [README](https://github.com/bojone/papers.cool).

### Translation Tools

* [CopyTranslator](https://copytranslator.github.io/): Main advantage is features like always-on-top, click-to-copy, clipboard monitoring, enabling seamless switching when reading papers, very convenient.

* [Saladict](https://saladict.crimx.com/): Browser translation plugin with rich settings to match user habits. Besides official docs, see [Saladict + Alfred for Best Literature Translation Experience!](https://zhuanlan.zhihu.com/p/113809716). Still exploring how to achieve out-of-browser translation on Windows.

### Note Taking

I previously used [Evernote](https://www.yinxiang.com/) but have stopped and am considering migration.

* [Yuque](https://www.yuque.com/): Very lightweight, I usually use the web version. Occasionally syncing lists to mobile is also useful. New users can use my invitation code QPFTUN for 30 days membership :kissing_heart:

* [Notion](https://www.notion.so/): If you need multi-person collaboration or project management, Notion might be more suitable.

## Coding & Experiments

### PyTorch Related

#### Feature & Config Wrappers

* [pytorch-lightning](https://github.com/williamFalcon/pytorch-lightning): Wraps various common configurations in PyTorch development (training/validation logic, hyperparameter search, distributed training etc.) in higher-level forms for rapid model building. Powerful but somewhat complex, still exploring.

#### Project References

* [the-incredible-pytorch](https://github.com/ritchieng/the-incredible-pytorch): Various PyTorch tutorials, projects, videos and other resources.

* [computervision-recipes](https://github.com/microsoft/computervision-recipes): Microsoft's PyTorch-based tutorials for various CV tasks.

#### Project Management

* [torchtracer](https://oidiotlin.com/torchtracer/): Tool for managing PyTorch AI experiment projects, mainly for saving various training data (model checkpoints, hyperparameter combinations, logs, loss curves etc.).

#### Style Guides

* [pytorch-styleguide](https://github.com/IgorSusmelj/pytorch-styleguide): An unofficial PyTorch style guide and best practices summary.

#### Project Templates

* [Pytorch-Project-Template](https://github.com/moemen95/Pytorch-Project-Template): An extensible PyTorch project template including examples for image segmentation, object classification, GANs and reinforcement learning.

* [pytorch-template](https://github.com/lyakaap/pytorch-template): Another PyTorch project template.

#### Neural Network Analyzers

* [torchinfo](https://github.com/TylerYep/torchinfo): Prints PyTorch model information including parameters and output tensor sizes for each layer.

* [flops-counter.pytorch](https://github.com/sovrasov/flops-counter.pytorch): Calculates total FLOPs (floating point operations, measuring algorithm/model complexity) and percentage per layer. Downside is it doesn't seem to support RNN layers, and printed information isn't very readable.

#### Visualization

* PyTorch latest version includes tensorboard. [Official tutorial](https://pytorch.org/tutorials/intermediate/tensorboard_tutorial.html).

* [visdom](https://github.com/facebookresearch/visdom): [To Try] Flexible tool for creating, organizing and sharing real-time rich data visualizations.

* [Convolution Visualizer](https://ezyang.github.io/convolution-visualizer/index.html): When convolution layer configuration is complex and output size is hard to calculate, this visualization tool can help.

### Experiment Tracking

* [fitlog](https://github.com/fastnlp/fitlog): [To Try] Architecture-agnostic experiment tracking tool, see [Prof. Qiu Xipeng's introduction on Zhihu](https://www.zhihu.com/question/384519338/answer/1181186086).

### Dataset Search

* [Google Dataset Search](https://toolbox.google.com/datasetsearch)

* [Data Search | Bifrost](https://datasets.bifrost.ai/): Visual dataset search.

### Dataset Download

* [gdown](https://github.com/wkentaro/gdown): Solves frequent failures when downloading large datasets from Google Drive.

### Feature Engineering

* [Featuretools](https://github.com/featuretools/featuretools): [To Try] Automated feature engineering library.

### Hyperparameter Search

* [optuna](https://github.com/optuna/optuna): Automatic hyperparameter optimization framework.

* [microsoft/nni](https://github.com/microsoft/nni/blob/master/README.md): [To Try] Open source AutoML toolkit for neural architecture search and hyperparameter tuning, supports most mainstream frameworks and environments.

* [Hyperopt](http://hyperopt.github.io/hyperopt/): [To Try] Distributed asynchronous hyperparameter optimization. Recommended on Zhihu, but according to docs, currently supports only two optimization algorithms, not including Bayesian optimization.

* [BoTorch](https://github.com/pytorch/botorch): [To Try] PyTorch-based Bayesian optimization library.

* [automl/Auto-PyTorch](https://github.com/automl/Auto-PyTorch): [To Try] PyTorch-based automatic architecture search and hyperparameter search.

## AI Coding Assistants

### Autonomous Coding Agents

* [Claude Code](https://claude.ai/code): Anthropic's official CLI for autonomous coding with Claude. The most capable AI pair programmer for complex software engineering tasks.
  
  **Pro Tips & Tricks:**
  - **Planning Mode**: Press `shift + tab` twice to enter planning mode for complex tasks
  - **Project Instructions**: Use `/init` to create Claude.md for project-specific guidelines
  - **Fresh Start**: Use `/clear` to begin new tasks with clean context
  - **Memory**: Use `#` to add important information to memory for future sessions
  - **Custom Commands**: Create slash commands like `/commit`, `/test`, `/deploy`
  - **Git Workflow**: Work on feature branches, commit often with descriptive messages
  
  **Thinking Modes** (increasing depth):
  - `think` - Basic reasoning
  - `think hard` - Deeper analysis
  - `think harder` - Complex problem solving
  - `ultrathink` - Maximum reasoning depth for hardest problems
  
  **Essential Extensions:**
  - [Peekaboo](https://peekaboo.dev/) - Vision superpowers for analyzing screenshots and diagrams
  - [llm.codes](https://llm.codes/) - Generate clean, professional documentation from code
  - [ccusage](https://github.com/claudeusercontent/ccusage) - Track Claude usage with max subscription

* [Cursor](https://cursor.sh/): AI-first code editor built on VSCode. Features include multi-file editing, codebase understanding, and natural language to code.

* [GitHub Copilot](https://github.com/features/copilot): AI pair programmer that suggests whole lines and functions. Integrates with VSCode, JetBrains IDEs, and Neovim.

### AI-Powered Development Tools

* [Codeium](https://codeium.com/): Free AI-powered code completion and chat. Supports 70+ languages and integrates with all major IDEs.

* [Tabnine](https://www.tabnine.com/): AI assistant for faster coding. Offers both cloud and local models for privacy-sensitive environments.

* [Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer/): AI coding companion optimized for AWS services. Free for individual developers.

* [Replit AI](https://replit.com/ai): Collaborative AI features in Replit including code generation, debugging, and explanation.

### Medical AI Development

* **Clinical Decision Support Tools**
  - [MIMIC-IV](https://physionet.org/content/mimiciv/): Critical care database for developing AI models
  - [ClinicalBERT](https://github.com/kexinhuang12345/clinicalBERT): Pre-trained BERT for clinical notes
  - [Med7](https://github.com/kormilitzin/med7): Clinical NLP for information extraction

* **Medical Image Analysis**
  - [MONAI](https://monai.io/): PyTorch-based framework for deep learning in healthcare imaging
  - [3D Slicer](https://www.slicer.org/): Platform for medical image analysis and visualization
  - [ITK-SNAP](http://www.itksnap.org/): Tool for segmentation of 3D medical images

* **Surgical AI Systems**
  - [SurgicalSAM](https://github.com/wenxi-yue/SurgicalSAM): Surgical instrument segmentation
  - [EndoNeRF](https://github.com/med-air/EndoNeRF): Neural rendering for endoscopic procedures
  - [Surgical Data Science](https://surgical-data-science.org/): Resources for computational surgery

## Academic Writing

### LaTeX Templates

Various LaTeX templates including papers, reports, posters etc.

* [Templates from Overleaf](https://www.overleaf.com/latex/templates)

* [LaTeX Templates](http://www.latextemplates.com/)

### LaTeX Editors

Recommend Overleaf for collaboration, which is my choice most of the time. For solo projects, use VSCode for offline LaTeX writing with GitHub private repos for version control.

* [Overleaf](https://www.overleaf.com/): **Online** LaTeX editor supporting collaboration. Requires decent internet connection.

### Language & Expression

#### Collocation Search

See recommendations in this article: [With These Websites, English Papers Are No Longer Difficult (15 English Paper Writing Assistant Websites)](https://zhuanlan.zhihu.com/p/35396232)

* [Linggle](https://linggle.com/): Search for most common English word collocations. Use when unsure if your expression is correct.

* [Corpus of Contemporary American English (COCA)](https://www.english-corpora.org/coca/): **American** English corpus for checking word collocations, can view specific sentences using the word. [British National Corpus (BYU-BNC)](https://www.english-corpora.org/bnc/): British English corpus with less data than American.

* [Thesaurus](https://www.thesaurus.com/): Convert basic vocabulary to synonymous advanced vocabulary.

* [ESODA](http://www.esoda.org/): A phrase collocation query tool suitable for Chinese English writers by Tsinghua HCI Lab. Can switch between specific research field paper corpora, show related replaceable usage, supports Chinese-English mixed search.

* [Words and phrases: frequency, genres, collocates, concordances, synonyms, and WordNet](https://www.wordandphrase.info/analyzeText.asp): Uses different colors to distinguish high/medium/low frequency words, shows vocabulary representing article types, and categorizes replaceable words. Though it's an English writing assistance tool, main use seems to be learning vocabulary and collocations commonly used in related field papers.

#### Phrase Recommendations

* [Academic Phrasebank](http://www.phrasebank.manchester.ac.uk/): Academic phrase bank telling you which phrases to use in each section.

#### Writing Check

Besides various ChatGPT-like options. Please note online detection tools' leakage risks, handle key text carefully.

* [Grammarly](https://www.grammarly.com/): Grammar, sentence structure, punctuation, word choice detection and correction, has browser plugin.

* [Nounplus.net](https://www.nounplus.net/): Free online English grammar checker.

### Formula Editing

* [Mathpix](https://mathpix.com/): Convert screenshots of complex mathematical equations to LaTeX code. Can handle printed PDFs and handwritten formulas in photos.

* [MyScript Webdemo](https://webdemo.myscript.com/): Math module converts handwritten formulas to LaTeX code; Diagram module converts hand-drawn diagrams to neat diagrams.

* [Detexify LaTeX handwritten symbol recognition](http://detexify.kirelabs.org/classify.html): When you forget how to represent certain characters in LaTeX, you can query by handwriting on this website.

### Table to LaTeX

* [Excel2LaTeX](https://ctan.org/tex-archive/support/excel2latex): Macro tool for Excel that converts Excel tables to LaTeX code, saving lots of time. Can handle most effects conversion, some effects may need fine-tuning.

### Diagram Drawing

#### Drawing Tools

* Mac OS users can use OmniGraffle.

* PPT is usually my first choice: quick to start, many types, high flexibility, supports vector export.

#### Drawing References

* [Paper-Picture-Writing-Code](https://github.com/MLNLP-World/Paper-Picture-Writing-Code): LaTeX-based drawing code including line charts, bar charts, scatter plots, attention visualization and structure diagrams.

* [academic-drawing](https://github.com/xinychen/academic-drawing): Matlab/Python drawing, mainly for time series data.

* [awesome-latex-drawing](https://github.com/xinychen/awesome-latex-drawing): LaTeX drawing, mainly for Bayesian networks, tensor decomposition etc.

* [PlotNeuralNet](https://github.com/HarisIqbal88/PlotNeuralNet): Python to get LaTeX-compatible diagrams, mainly for CNNs.

#### PPT Plugins

* [IguanaTex](http://www.jonathanleroux.org/software/iguanatex/): PPT plugin to help insert LaTeX formulas. Converts input LaTeX code to high-quality png or vector graphics for insertion.

#### Image Conversion

Many websites provide image format conversion services. This is just a simple list, you can find other similar websites through search engines.

* [Convert PNG/JPEG (Raster) to EPS/PDF (Vector) Format](http://www.tlhiv.org/rast2vec/): Convert jpg, png format images to eps files.

* [EPS to PDF Converter](https://convertio.co/eps-pdf/): Can also convert eps files to other image formats.

#### Image Editing

* [Crop PDF files online - PDF Tools](https://pdfresizer.com/crop): Crop white margins from PDF files.

* TexLive includes some command line tools:
  * Convert eps to pdf: `epstopdf <file.eps>`;
  * Auto-crop PDF white margins: `pdfcrop <file.pdf>`.

## Paper Submission

### Conference & Journal Search

* [ccf-deadlines](https://ccfddl.github.io/): Filter conferences with confirmed deadlines this year by research direction and CCF ranking. Friendly for Chinese colleagues.

* [AI Conference Deadlines](https://aideadlin.es/): Filter conferences by research direction. Seems to need VPN to see all information.

* [Conference List](http://www.conferencelist.info/upcoming.html): Sorted by submission deadline, expired conferences don't appear on homepage. Has a page showing conferences by research direction, but can't filter unexpired conferences by research direction.

* [Conference Partner](http://www.myhuiban.com/): Latest international computer science conferences and journals list. Can register to follow conferences or journals. Quite comprehensive but information updates aren't timely.

### Anonymous Links

For blind review considerations, sometimes file (e.g., source code) links need to be anonymous. Some choose to create anonymous accounts on GitHub, but creating an account for each paper at each conference might be too cumbersome. I found some tools supporting anonymous file sharing as follows.

* [Dropbox](https://www.dropbox.com/): Probably most commonly used.

* [Open Science Framework](http://help.osf.io/m/links_forks/l/783581-create-a-view-only-link-for-a-registration)

* [Figshare](https://knowledge.figshare.com/articles/item/how-to-share-cite-or-embed-my-data)

### arXiv Submission

* [Arxiv Paper Submission Process - This is All You Need](https://zhuanlan.zhihu.com/p/109405192): Article to understand the process of submitting papers to arXiv.

* [arxiv-latex-cleaner](https://github.com/google-research/arxiv-latex-cleaner): Cleans paper LaTeX code to meet arXiv submission requirements. A highlight is automatically removing all commented content from papers.

* [Overleaf -> arXiv Smooth Submission Process](https://zhuanlan.zhihu.com/p/558225069): If using Overleaf (rather than compiling LaTeX locally), refer to this article to download appropriate source packages, then consider using arxiv-latex-cleaner.

### Code Release

Providing clear, reproducible code for published papers effectively advances the field. Here are some helpful tools for open-sourcing code.

* [ReproducibilityChecklist-v2.0](https://www.cs.mcgill.ca/~jpineau/ReproducibilityChecklist.pdf): A machine learning reproducibility checklist listing what files you should provide to enhance your paper's reproducibility.

* [pigar](https://github.com/Damnever/pigar): Python project requirements file auto-generation tool.

## Others

### Patent Search

* [Google Patents](https://iseex.github.io//2020-05/Google-Patents/): Free search and download of Chinese and English patents. See [Google Patents, the Best Tool for Free Patent Search and Download!](https://iseex.github.io//2020-05/Google-Patents/).

### Focus Tools

* [Tomato Life](http://www.tomatolife.cn/index.html): Windows PC to-do software with Pomodoro timer.

### White Noise / Music

* [Rainyscope rain simulator](https://rainyscope.com): Rain sounds.

* [LofiGirl's Music Study Room](https://live.bilibili.com/27519423): Lo-Fi music livestream.