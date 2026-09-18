# awesome-python

A curated list of awesome Python frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
	* [Awesome Lists and Collections](#awesome-lists-and-collections)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
	* [Editor and IDE Support](#editor-and-ide-support)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Scraping and Crawling](#scraping-and-crawling)
* Data and Storage
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Caching and Queues](#caching-and-queues)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Machine Learning Frameworks](#machine-learning-frameworks)
	* [Computer Vision](#computer-vision)
	* [Natural Language Processing](#natural-language-processing)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [GUI Toolkits](#gui-toolkits)
	* [Terminal and Console UI](#terminal-and-console-ui)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Image and Video](#image-and-video)
* Security
	* [Security Tools](#security-tools)
	* [Authentication and Authorization](#authentication-and-authorization)
	* [Reverse Engineering](#reverse-engineering)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Date and Time](#date-and-time)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Science and Math
	* [Mathematics](#mathematics)
	* [Scientific Computing](#scientific-computing)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) - Learn how to design large-scale systems. Prep for the system design interview. Includes Anki flashcards.
* [jackfrued/Python-100-Days](https://github.com/jackfrued/Python-100-Days) - Python - 100天从新手到大师
* [d2l-ai/d2l-zh](https://github.com/d2l-ai/d2l-zh) - 《动手学深度学习》：面向中文读者、能运行、可讨论。中英文版被70多个国家的500多所大学用于教学。
* [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) - Bash is all you need - A nano claude code–like 「agent harness」, built from 0 to 1
* [Asabeneh/30-Days-Of-Python](https://github.com/Asabeneh/30-Days-Of-Python) - The 30 Days of Python programming challenge is a step-by-step guide to learn the Python programming language in 30 days. This challenge may take more than 100 days. Follow your own pace. These videos may help too: https://www.youtube.com/channel/UC7PNRuno1rzYPb1xLa4yktw
* [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) - Learn it. Build it. Ship it for others.
* [apachecn/ailearning](https://github.com/apachecn/ailearning) - AiLearning：数据分析+机器学习实战+线性代数+PyTorch+NLTK+TF2
* [gto76/python-cheatsheet](https://github.com/gto76/python-cheatsheet) - Comprehensive Python Cheatsheet
* [mouredev/Hello-Python](https://github.com/mouredev/Hello-Python) - Curso para aprender el lenguaje de programación Python desde cero y para principiantes. 100 clases, 44 horas en vídeo, código, proyectos y grupo de chat. Fundamentos, frontend, backend, testing, IA...
* [satwikkansal/wtfpython](https://github.com/satwikkansal/wtfpython) - What the f*ck Python? 😱
* [d2l-ai/d2l-en](https://github.com/d2l-ai/d2l-en) - Interactive deep learning book with multi-framework code, math, and discussions. Adopted at 500 universities from 70 countries including Stanford, MIT, Harvard, and Cambridge.
* [walter201230/Python](https://github.com/walter201230/Python) - 小白 python 教程
* [wistbean/learn_python3_spider](https://github.com/wistbean/learn_python3_spider) - python爬虫教程系列、从0到1学习python爬虫，包括浏览器抓包，手机APP抓包，如 fiddler、mitmproxy，各种爬虫涉及的模块的使用，如：requests、beautifulSoup、selenium、appium、scrapy等，以及IP代理，验证码识别，Mysql，MongoDB数据库的python使用，多线程多进程爬虫的使用，css 爬虫加密逆向破解，JS爬虫逆向，分布式爬虫，爬虫项目实战实例等
* [stas00/ml-engineering](https://github.com/stas00/ml-engineering) - Machine Learning Engineering Open Book
* [trekhleb/learn-python](https://github.com/trekhleb/learn-python) - 📚 Playground and cheatsheet for learning Python. Collection of Python scripts that are split by topics and contain code examples with explanations.
* [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) - This open-source curriculum introduces the fundamentals of Model Context Protocol (MCP) through real-world, cross-language examples in .NET, Java, TypeScript, JavaScript, Rust and Python. Designed for developers, it focuses on practical techniques for building modular, scalable, and secure AI workflows from session setup to service orchestration.
* [dabeaz-course/python-mastery](https://github.com/dabeaz-course/python-mastery) - Advanced Python Mastery (course by @dabeaz)
* [MorvanZhou/tutorials](https://github.com/MorvanZhou/tutorials) - 机器学习相关教程
* [Jack-Cherish/PythonPark](https://github.com/Jack-Cherish/PythonPark) - Python 开源项目之「自学编程之路」，保姆级教程：AI实验室、宝藏视频、数据结构、学习指南、机器学习实战、深度学习实战、网络爬虫、大厂面经、程序人生、资源分享。
* [rougier/scientific-visualization-book](https://github.com/rougier/scientific-visualization-book) - An open access book on scientific visualization using python and matplotlib
* [dabeaz-course/practical-python](https://github.com/dabeaz-course/practical-python) - Practical Python Programming (course by @dabeaz)
* [datawhalechina/all-in-rag](https://github.com/datawhalechina/all-in-rag) - 🔍大模型应用开发实战一：RAG 技术全栈指南，在线阅读地址：https://datawhalechina.github.io/all-in-rag/
* [Yorko/mlcourse.ai](https://github.com/Yorko/mlcourse.ai) - Open Machine Learning Course
* [chiphuyen/stanford-tensorflow-tutorials](https://github.com/chiphuyen/stanford-tensorflow-tutorials) - This repository contains code examples for the Stanford's course: TensorFlow for Deep Learning Research. *(archived)*
* [MorvanZhou/Reinforcement-learning-with-tensorflow](https://github.com/MorvanZhou/Reinforcement-learning-with-tensorflow) - Simple Reinforcement learning tutorials, 莫烦Python 中文AI教学
* [mouredev/roadmap-retos-programacion](https://github.com/mouredev/roadmap-retos-programacion) - Ruta de estudio basada en ejercicios de código de la comunidad MoureDev para aprender y practicar lógica usando cualquier lenguaje de programación.
* [crazyguitar/pysheeet](https://github.com/crazyguitar/pysheeet) - Python Cheat Sheet
* [microsoft/Mastering-GitHub-Copilot-for-Paired-Programming](https://github.com/microsoft/Mastering-GitHub-Copilot-for-Paired-Programming) - A multi-module course teaching everything you need to know about using GitHub Copilot as an AI Peer Programming resource.
* [Rockyzsu/stock](https://github.com/Rockyzsu/stock) - 30天掌握量化交易 (持续更新)
* [MingchaoZhu/DeepLearning](https://github.com/MingchaoZhu/DeepLearning) - Python for《Deep Learning》，该书为《深度学习》(花书) 数学推导、原理剖析与源码级别代码实现
* [matplotlib/cheatsheets](https://github.com/matplotlib/cheatsheets) - Official Matplotlib cheat sheets
* [lining0806/PythonSpiderNotes](https://github.com/lining0806/PythonSpiderNotes) - Python入门网络爬虫之精华版
* [instillai/machine-learning-course](https://github.com/instillai/machine-learning-course) - :speech_balloon: Machine Learning Course with Python:
* [jerry-git/learn-python3](https://github.com/jerry-git/learn-python3) - Jupyter notebooks for teaching/learning Python 3
* [SmirkCao/Lihang](https://github.com/SmirkCao/Lihang) - Statistical learning methods, 统计学习方法(第2版)[李航] [笔记, 代码, notebook, 参考文献, Errata, lihang]
* [huangsam/ultimate-python](https://github.com/huangsam/ultimate-python) - Ultimate Python study guide 🐍 🐍 🐍
* [moranzcw/Computer-Networking-A-Top-Down-Approach-NOTES](https://github.com/moranzcw/Computer-Networking-A-Top-Down-Approach-NOTES) - 《计算机网络－自顶向下方法(原书第6版)》编程作业，Wireshark实验文档的翻译和解答。
* [navdeep-G/setup.py](https://github.com/navdeep-G/setup.py) - 📦 A Human's Ultimate Guide to setup.py.
* [zedr/clean-code-python](https://github.com/zedr/clean-code-python) - :bathtub: Clean Code concepts adapted for Python
* [iam-veeramalla/python-for-devops](https://github.com/iam-veeramalla/python-for-devops) - Learn Python from DevOps Engineer point of you.
* [Kr1s77/Python-crawler-tutorial-starts-from-zero](https://github.com/Kr1s77/Python-crawler-tutorial-starts-from-zero) - python爬虫教程，带你从零到一，包含js逆向，selenium, tesseract OCR识别,mongodb的使用，以及scrapy框架
* [skyzh/tiny-llm](https://github.com/skyzh/tiny-llm) - learn LLM inference system on Apple Silicon for systems engineers: build a tiny vLLM + Qwen
* [astorfi/TensorFlow-World](https://github.com/astorfi/TensorFlow-World) - :earth_americas: Simple and ready-to-use tutorials for TensorFlow
* [OmkarPathak/pygorithm](https://github.com/OmkarPathak/pygorithm) - A Python module for learning all major algorithms
* [MorvanZhou/Tensorflow-Tutorial](https://github.com/MorvanZhou/Tensorflow-Tutorial) - Tensorflow tutorial from basic to hard, 莫烦Python 中文AI教学
* [dabeaz/python-cookbook](https://github.com/dabeaz/python-cookbook) - Code samples from the "Python Cookbook, 3rd Edition", published by O'Reilly & Associates, May, 2013.
* [TarrySingh/Artificial-Intelligence-Deep-Learning-Machine-Learning-Tutorials](https://github.com/TarrySingh/Artificial-Intelligence-Deep-Learning-Machine-Learning-Tutorials) - A comprehensive list of Deep Learning / Artificial Intelligence and Machine Learning tutorials - rapidly expanding into areas of AI/Deep Learning / Machine Vision / NLP and industry specific areas such as Climate / Energy, Automotives, Retail, Pharma, Medicine, Healthcare, Policy, Ethics and more.
* [hunkim/PyTorchZeroToAll](https://github.com/hunkim/PyTorchZeroToAll) - Simple PyTorch Tutorials Zero to ALL!
* [cosmicpython/book](https://github.com/cosmicpython/book) - A Book about Pythonic Application Architecture Patterns for Managing Complexity. Cosmos is the Opposite of Chaos you see. O'R. wouldn't actually let us call it "Cosmic Python" tho.
* [ZiniuLu/Python-100-Days](https://github.com/ZiniuLu/Python-100-Days) - 出处：https://github.com/jackfrued/Python-100-Days.git
* [Wookai/paper-tips-and-tricks](https://github.com/Wookai/paper-tips-and-tricks) - Best practice and tips & tricks to write scientific papers in LaTeX, with figures generated in Python or Matlab.
* [chrisconlan/algorithmic-trading-with-python](https://github.com/chrisconlan/algorithmic-trading-with-python) - Source code for Algorithmic Trading with Python (2020) by Chris Conlan
* [iswbm/magic-python](https://github.com/iswbm/magic-python) - Python 黑魔法手册
* [scipy-lectures/scientific-python-lectures](https://github.com/scipy-lectures/scientific-python-lectures) - Tutorial material on the scientific Python ecosystem
* [rougier/matplotlib-tutorial](https://github.com/rougier/matplotlib-tutorial) - Matplotlib tutorial for beginner
* [PegasusWang/python_data_structures_and_algorithms](https://github.com/PegasusWang/python_data_structures_and_algorithms) - Python 中文数据结构和算法教程
* [rougier/matplotlib-cheatsheet](https://github.com/rougier/matplotlib-cheatsheet) - Matplotlib 3.1 cheat sheet.
* [bslatkin/effectivepython](https://github.com/bslatkin/effectivepython) - Effective Python: Third Edition — Source Code and Errata for the Book
* [luispedro/BuildingMachineLearningSystemsWithPython](https://github.com/luispedro/BuildingMachineLearningSystemsWithPython) - Source Code for the book Building Machine Learning Systems with Python

### Examples and Exercises

* [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) - All Algorithms implemented in Python
* [bregman-arie/devops-exercises](https://github.com/bregman-arie/devops-exercises) - Linux, Jenkins, AWS, SRE, Prometheus, Docker, Python, Ansible, Git, Kubernetes, Terraform, OpenStack, SQL, NoSQL, Azure, GCP, DNS, Elastic, Network, Virtualization. DevOps Interview Questions
* [fastapi/full-stack-fastapi-template](https://github.com/fastapi/full-stack-fastapi-template) - Full-stack web application template with FastAPI, React, SQLModel, PostgreSQL, Vite, Tailwind CSS, shadcn/ui, FastAPI Cloud, and Docker Compose.
* [faif/python-patterns](https://github.com/faif/python-patterns) - A collection of design patterns/idioms in Python
* [geekcomputers/Python](https://github.com/geekcomputers/Python) - My Python Examples
* [donnemartin/interactive-coding-challenges](https://github.com/donnemartin/interactive-coding-challenges) - 120+ interactive Python coding interview challenges (algorithms and data structures). Includes Anki flashcards.
* [AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) - Python sample codes and textbook for robotics algorithms.
* [donnemartin/data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) - Data science Python notebooks: Deep learning (TensorFlow, Theano, Caffe, Keras), scikit-learn, Kaggle, big data (Spark, Hadoop MapReduce, HDFS), matplotlib, pandas, NumPy, SciPy, Python essentials, AWS, and various command lines.
* [Ebazhanov/linkedin-skill-assessments-quizzes](https://github.com/Ebazhanov/linkedin-skill-assessments-quizzes) - Full reference of LinkedIn answers 2024 for skill assessments (aws-lambda, rest-api, javascript, react, git, html, jquery, mongodb, java, Go, python, machine-learning, power-point) linkedin excel test lösungen, linkedin machine learning test LinkedIn test questions and answers
* [keon/algorithms](https://github.com/keon/algorithms) - Minimal examples of data structures and algorithms in Python
* [Jack-Cherish/python-spider](https://github.com/Jack-Cherish/python-spider) - :rainbow:Python3网络爬虫实战：淘宝、京东、网易云、B站、12306、抖音、笔趣阁、漫画小说下载、音乐电影下载等
* [Python-World/python-mini-projects](https://github.com/Python-World/python-mini-projects) - A collection of simple python mini projects to enhance your python skills *(archived)*
* [ShangtongZhang/reinforcement-learning-an-introduction](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction) - Python Implementation of Reinforcement Learning: An Introduction
* [shengqiangzhang/examples-of-web-crawlers](https://github.com/shengqiangzhang/examples-of-web-crawlers) - 一些非常有趣的python爬虫例子,对新手比较友好,主要爬取淘宝、天猫、微信、微信读书、豆瓣、QQ等网站。(Some interesting examples of python crawlers that are friendly to beginners. )
* [rougier/numpy-100](https://github.com/rougier/numpy-100) - 100 numpy exercises (with solutions)
* [rushter/MLAlgorithms](https://github.com/rushter/MLAlgorithms) - Minimal and clean examples of machine learning algorithms implementations
* [injetlee/Python](https://github.com/injetlee/Python) - Python脚本。模拟登录知乎， 爬虫，操作excel，微信公众号，远程开机
* [Jack-Cherish/Machine-Learning](https://github.com/Jack-Cherish/Machine-Learning) - :zap:机器学习实战（Python3）：kNN、决策树、贝叶斯、逻辑回归、SVM、线性回归、树回归
* [lazyprogrammer/machine_learning_examples](https://github.com/lazyprogrammer/machine_learning_examples) - A collection of machine learning examples and tutorials.
* [Chalarangelo/30-seconds-of-python](https://github.com/Chalarangelo/30-seconds-of-python) - Short Python code snippets for all your development needs *(archived)*
* [miguelgrinberg/flasky](https://github.com/miguelgrinberg/flasky) - Companion code to my O'Reilly book "Flask Web Development", second edition.
* [lawlite19/MachineLearning_Python](https://github.com/lawlite19/MachineLearning_Python) - 机器学习算法python实现
* [jackzhenguo/python-small-examples](https://github.com/jackzhenguo/python-small-examples) - 告别枯燥，致力于打造 Python 实用小例子，更多Python良心教程见 https://ai-jupyter.com
* [itcharge/AlgoNote](https://github.com/itcharge/AlgoNote) - ⛽️「算法通关手册」：从零开始的「算法与数据结构」学习教程，200 道「算法面试热门题目」，1000+ 道「LeetCode 题目解析」，持续更新中！
* [PyQt5/PyQt](https://github.com/PyQt5/PyQt) - PyQt Examples（PyQt各种测试和例子） PyQt4 PyQt5
* [mouredev/retos-programacion-2023](https://github.com/mouredev/retos-programacion-2023) - Ejercicios de código semanales en 2023 de la comunidad MoureDev para practicar lógica en cualquier lenguaje de programación.
* [fluentpython/example-code](https://github.com/fluentpython/example-code) - Example code for the book Fluent Python, 1st Edition (O'Reilly, 2015) *(archived)*
* [gxcuizy/Python](https://github.com/gxcuizy/Python) - Python3编写的各种大小程序，包含从零学Python系列、12306抢票、省市区地址库以及系列网站爬虫等学习源码
* [TurboWay/bigdata_analyse](https://github.com/TurboWay/bigdata_analyse) - 大数据分析项目
* [qiyuangong/leetcode](https://github.com/qiyuangong/leetcode) - Python & JAVA Solutions for Leetcode
* [jaungiers/LSTM-Neural-Network-for-Time-Series-Prediction](https://github.com/jaungiers/LSTM-Neural-Network-for-Time-Series-Prediction) - LSTM built using Keras Python package to predict time series steps and sequences. Includes sin wave and stock market data
* [careercup/CtCI-6th-Edition-Python](https://github.com/careercup/CtCI-6th-Edition-Python) - Cracking the Coding Interview 6th Ed. Python Solutions
* [gregmalcolm/python_koans](https://github.com/gregmalcolm/python_koans) - Python Koans - Learn Python through TDD
* [miguelgrinberg/microblog](https://github.com/miguelgrinberg/microblog) - The microblogging application developed in my Flask Mega-Tutorial series. This version maps to the 2024 Edition of the tutorial.
* [cookiecutter-flask/cookiecutter-flask](https://github.com/cookiecutter-flask/cookiecutter-flask) - A flask template with Bootstrap, asset bundling+minification with webpack, starter templates, and registration/authentication. For use with cookiecutter.
* [pythonguis/pythonguis-examples](https://github.com/pythonguis/pythonguis-examples) - Build desktop apps built with Python. Examples for PyQt6, PySide6, Flet, DearPyGUI, Kivy, NiceGUI, Streamlit, Tkinter, PyQt5 & PySide2
* [audreyfeldroy/cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage) - Cookiecutter template for a Python package.
* [daveebbelaar/ai-cookbook](https://github.com/daveebbelaar/ai-cookbook) - Examples and tutorials to help developers build AI systems
* [ndleah/python-mini-project](https://github.com/ndleah/python-mini-project) - 🙌 Welcome open-source Python mini-project contributions!
* [Sentdex/pygta5](https://github.com/Sentdex/pygta5) - Explorations of Using Python to play Grand Theft Auto 5.
* [MTrajK/coding-problems](https://github.com/MTrajK/coding-problems) - Solutions for various coding/algorithmic problems and many useful resources for learning algorithms and data structures
* [wkunzhi/Python3-Spider](https://github.com/wkunzhi/Python3-Spider) - Python爬虫实战 - 模拟登陆各大网站 包含但不限于：滑块验证、拼多多、美团、百度、bilibili、大众点评、淘宝，如果喜欢请start ❤️
* [nsidnev/fastapi-realworld-example-app](https://github.com/nsidnev/fastapi-realworld-example-app) - Backend logic implementation for https://github.com/gothinkster/realworld with awesome FastAPI *(archived)*
* [prakhar1989/Algorithms](https://github.com/prakhar1989/Algorithms) - :computer: Data Structures and Algorithms in Python
* [brennerm/PyTricks](https://github.com/brennerm/PyTricks) - Collection of less popular features and tricks for the Python programming language
* [realpython/python-scripts](https://github.com/realpython/python-scripts) - because i'm tired of gists
* [csujedihy/lc-all-solutions](https://github.com/csujedihy/lc-all-solutions) - My own leetcode solutions by python
* [needleworm/bhban_rpa](https://github.com/needleworm/bhban_rpa) - <6개월 치 업무를 하루 만에 끝내는 업무 자동화(생능출판사, 2020)>의 예제 코드입니다. 파이썬을 한 번도 배워본 적 없는 분들을 위한 예제이며, 엑셀부터 디자인, 매크로, 크롤링까지 업무 자동화와 관련된 다양한 분야 예제가 제공됩니다.

### Awesome Lists and Collections

* [vinta/awesome-python](https://github.com/vinta/awesome-python) - The definitive list that answers "I want to do X in Python, which tool should I use?"
* [practical-tutorials/project-based-learning](https://github.com/practical-tutorials/project-based-learning) - Curated list of project-based tutorials
* [521xueweihan/HelloGitHub](https://github.com/521xueweihan/HelloGitHub) - :octocat: 分享 GitHub 上有趣、入门级的开源项目。Share interesting, entry-level open source projects on GitHub.
* [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) - 100+ AI Agents, Agent Skills and RAG Apps - Free and Open Source.
* [RunaCapital/awesome-oss-alternatives](https://github.com/RunaCapital/awesome-oss-alternatives) - Awesome list of open-source startup alternatives to well-known SaaS products 🚀
* [EvanLi/Github-Ranking](https://github.com/EvanLi/Github-Ranking) - :star:Github Ranking:star: Github stars and forks ranking list. Github Top100 stars list of different languages. Automatically update daily. | Github仓库排名，每日自动更新
* [EwingYangs/awesome-open-gpt](https://github.com/EwingYangs/awesome-open-gpt) - Collection of Open Source Projects Related to GPT，GPT相关开源项目合集🚀、精选🔥🔥
* [ujjwalkarn/DataSciencePython](https://github.com/ujjwalkarn/DataSciencePython) - common data analysis and machine learning tasks using python
* [dahlia/awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) - A curated list of awesome tools for SQLAlchemy

## Language and Tooling

### Compilers and Interpreters

* [python/cpython](https://github.com/python/cpython) - The Python programming language
* [exaloop/codon](https://github.com/exaloop/codon) - A high-performance, zero-overhead, extensible Python compiler with built-in NumPy support
* [Nuitka/Nuitka](https://github.com/Nuitka/Nuitka) - Nuitka is a Python compiler written in Python. It's fully compatible with Python 2.6, 2.7, 3.4-3.14. You feed it your Python app, it does a lot of clever things, and spits out an executable or extension module.
* [pyodide/pyodide](https://github.com/pyodide/pyodide) - Pyodide is a Python distribution for the browser and Node.js based on WebAssembly
* [numba/numba](https://github.com/numba/numba) - NumPy aware dynamic Python compiler using LLVM
* [cython/cython](https://github.com/cython/cython) - The most widely used Python to C compiler
* [samshadwell/TrumpScript](https://github.com/samshadwell/TrumpScript) - Make Python great again *(archived)*
* [brython-dev/brython](https://github.com/brython-dev/brython) - Brython (Browser Python) is an implementation of Python 3 running in the browser
* [lark-parser/lark](https://github.com/lark-parser/lark) - Lark is a parsing toolkit for Python, built with a focus on ergonomics, performance and modularity.
* [hylang/hy](https://github.com/hylang/hy) - A dialect of Lisp that's embedded in Python
* [vyperlang/vyper](https://github.com/vyperlang/vyper) - Pythonic Smart Contract Language for the EVM
* [evhub/coconut](https://github.com/evhub/coconut) - Simple, elegant, Pythonic functional programming.
* [eliben/pycparser](https://github.com/eliben/pycparser) - :snake: Complete C99 parser in pure Python
* [colesbury/nogil](https://github.com/colesbury/nogil) - Multithreaded Python without the GIL *(archived)*
* [dabeaz/ply](https://github.com/dabeaz/ply) - Python Lex-Yacc *(archived)*

### Build Systems

* [cookiecutter/cookiecutter](https://github.com/cookiecutter/cookiecutter) - A cross-platform command-line utility that creates projects from cookiecutters (project templates), e.g. Python package projects, C projects.
* [cookiecutter/cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django) - Cookiecutter Django is a framework for jumpstarting production-ready Django projects quickly.
* [pyinstaller/pyinstaller](https://github.com/pyinstaller/pyinstaller) - Freeze (package) Python programs into stand-alone executables
* [pyinvoke/invoke](https://github.com/pyinvoke/invoke) - Pythonic task management & command execution.
* [pex-tool/pex](https://github.com/pex-tool/pex) - A tool for generating .pex (Python EXecutable) files, lock files and venvs.
* [mherrmann/fbs](https://github.com/mherrmann/fbs) - Create Python GUIs with Qt in minutes
* [beeware/briefcase](https://github.com/beeware/briefcase) - Tools to support converting a Python project into a standalone native application.
* [blade-build/blade-build](https://github.com/blade-build/blade-build) - Blade is a powerful build system from Tencent, supports many mainstream programming languages, such as C/C++, java, scala, python, protobuf...

### Package Management

* [python-poetry/poetry](https://github.com/python-poetry/poetry) - Python packaging and dependency management made easy
* [pypa/pipenv](https://github.com/pypa/pipenv) - Python Development Workflow for Humans.
* [pypa/pipx](https://github.com/pypa/pipx) - Install and Run Python Applications in Isolated Environments
* [pypa/pip](https://github.com/pypa/pip) - The Python package installer
* [pdm-project/pdm](https://github.com/pdm-project/pdm) - A modern Python package and dependency manager supporting the latest PEP standards
* [jazzband/pip-tools](https://github.com/jazzband/pip-tools) - A set of tools to keep your pinned Python dependencies fresh.
* [hacs/integration](https://github.com/hacs/integration) - HACS gives you a powerful UI to handle downloads of all your custom needs.
* [conda/conda](https://github.com/conda/conda) - A system-level, binary package and environment manager running on all major operating systems and platforms.
* [pypa/hatch](https://github.com/pypa/hatch) - Modern, extensible Python project management
* [spack/spack](https://github.com/spack/spack) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers.
* [pypa/virtualenv](https://github.com/pypa/virtualenv) - Virtual Python Environment builder
* [astral-sh/python-build-standalone](https://github.com/astral-sh/python-build-standalone) - Produce redistributable builds of Python
* [fo40225/tensorflow-windows-wheel](https://github.com/fo40225/tensorflow-windows-wheel) - Tensorflow prebuilt binary for Windows
* [pypa/flit](https://github.com/pypa/flit) - Simplified packaging of Python modules

### Linters and Formatters

* [psf/black](https://github.com/psf/black) - The uncompromising Python code formatter
* [python/mypy](https://github.com/python/mypy) - Optional static typing for Python
* [astral-sh/ty](https://github.com/astral-sh/ty) - An extremely fast Python type checker and language server, written in Rust.
* [microsoft/pyright](https://github.com/microsoft/pyright) - Static Type Checker for Python
* [pre-commit/pre-commit](https://github.com/pre-commit/pre-commit) - A framework for managing and maintaining multi-language pre-commit hooks.
* [google/yapf](https://github.com/google/yapf) - A formatter for Python files
* [facebook/pyre-check](https://github.com/facebook/pyre-check) - Performant type-checking for python. *(archived)*
* [PyCQA/isort](https://github.com/PyCQA/isort) - A Python utility / library to sort imports.
* [pre-commit/pre-commit-hooks](https://github.com/pre-commit/pre-commit-hooks) - Some out-of-the-box hooks for pre-commit
* [repowise-dev/repowise](https://github.com/repowise-dev/repowise) - Codebase intelligence for AI and humans: code health scores, auto-generated docs, git analytics, dead code detection, and architectural decisions via MCP.
* [PyCQA/pycodestyle](https://github.com/PyCQA/pycodestyle) - Simple Python style checker in one Python file
* [python/typeshed](https://github.com/python/typeshed) - Collection of library stubs for Python, with static types
* [google/pytype](https://github.com/google/pytype) - A static type analyzer for Python code
* [Instagram/MonkeyType](https://github.com/Instagram/MonkeyType) - A Python library that generates static type annotations by collecting runtime types
* [jendrikseipp/vulture](https://github.com/jendrikseipp/vulture) - Find dead Python code
* [hhatto/autopep8](https://github.com/hhatto/autopep8) - A tool that automatically formats Python code to conform to the PEP 8 style guide.
* [asottile/pyupgrade](https://github.com/asottile/pyupgrade) - A tool (and pre-commit hook) to automatically upgrade syntax for newer versions of the language.
* [coala/coala](https://github.com/coala/coala) - coala provides a unified command-line interface for linting and fixing all your code, regardless of the programming languages you use.
* [beartype/beartype](https://github.com/beartype/beartype) - Unbearably fast near-real-time pure-Python runtime-static type-checker.

### Debugging and Profiling

* [cool-RR/PySnooper](https://github.com/cool-RR/PySnooper) - Never use print for debugging again
* [bloomberg/memray](https://github.com/bloomberg/memray) - Memray is a memory profiler for Python
* [plasma-umass/scalene](https://github.com/plasma-umass/scalene) - Scalene: a high-performance, high-precision CPU, GPU, and memory profiler for Python with AI-powered optimization proposals
* [cyrus-and/gdb-dashboard](https://github.com/cyrus-and/gdb-dashboard) - Modular visual interface for GDB in Python
* [gruns/icecream](https://github.com/gruns/icecream) - 🍦 Never use print() to debug again.
* [joerick/pyinstrument](https://github.com/joerick/pyinstrument) - 🚴 Call stack profiler for Python. Shows you why your code is slow!
* [gaogaotiantian/viztracer](https://github.com/gaogaotiantian/viztracer) - A debugging and profiling tool that can trace and visualize python code execution
* [snare/voltron](https://github.com/snare/voltron) - A hacky debugger UI for hackers
* [Qix-/better-exceptions](https://github.com/Qix-/better-exceptions) - Pretty and useful exceptions in Python, automatically.
* [pythonprofilers/memory_profiler](https://github.com/pythonprofilers/memory_profiler) - Monitor Memory usage of Python code
* [nvdv/vprof](https://github.com/nvdv/vprof) - Visual profiler for Python
* [rkern/line_profiler](https://github.com/rkern/line_profiler) - (OLD REPO) Line-by-line profiling for Python - Current repo -> *(archived)*
* [reloadware/reloadium](https://github.com/reloadware/reloadium) - Hot Reloading and Profiling for Python
* [what-studio/profiling](https://github.com/what-studio/profiling) - Was an interactive continuous Python profiler. *(archived)*
* [laike9m/Cyberbrain](https://github.com/laike9m/Cyberbrain) - Python debugging, redefined.
* [breuleux/jurigged](https://github.com/breuleux/jurigged) - Hot reloading for Python

### Editor and IDE Support

* [spyder-ide/spyder](https://github.com/spyder-ide/spyder) - Official repository for Spyder - The Scientific Python Development Environment
* [davidhalter/jedi](https://github.com/davidhalter/jedi) - Awesome autocompletion, static analysis and refactoring library for python
* [Shougo/deoplete.nvim](https://github.com/Shougo/deoplete.nvim) - :stars: Dark powered asynchronous completion framework for neovim/Vim8
* [thonny/thonny](https://github.com/thonny/thonny) - Python IDE for beginners
* [prompt-toolkit/pyvim](https://github.com/prompt-toolkit/pyvim) - Pure Python Vim clone.
* [DamnWidget/anaconda](https://github.com/DamnWidget/anaconda) - Anaconda turns your Sublime Text 3 in a full featured Python development IDE including autocompletion, code linting, IDE features, autopep8 formating, McCabe complexity checker Vagrant and Docker support for Sublime Text 3 using Jedi, PyFlakes, pep8, MyPy, PyLint, pep257 and McCabe that will never freeze your Sublime Text 3
* [Komodo/KomodoEdit](https://github.com/Komodo/KomodoEdit) - Komodo Edit is a fast and free multi-language code editor. Written in JS, Python, C++ and based on the Mozilla platform.
* [wuub/SublimeREPL](https://github.com/wuub/SublimeREPL) - SublimeREPL - run an interpreter inside ST2 (Clojure, CoffeeScript, F#, Groovy, Haskell, Lua, MozRepl, NodeJS, Python, R, Ruby, Scala, shell or configure one yourself)
* [duydao/Text-Pastry](https://github.com/duydao/Text-Pastry) - Extend the power of multiple selections in Sublime Text. Modify selections, insert numeric sequences, incremental numbers, generate uuids, date ranges, insert continuously from a word list and more.

## Web

### Web Frameworks

* [fastapi/fastapi](https://github.com/fastapi/fastapi) - FastAPI framework, high performance, easy to learn, fast to code, ready for production
* [django/django](https://github.com/django/django) - The Web framework for perfectionists with deadlines.
* [pallets/flask](https://github.com/pallets/flask) - The Python micro framework for building web applications.
* [reflex-dev/reflex](https://github.com/reflex-dev/reflex) - 🕸️ Web apps in pure Python 🐍
* [tornadoweb/tornado](https://github.com/tornadoweb/tornado) - Tornado is a Python web framework and asynchronous networking library, originally developed at FriendFeed.
* [wagtail/wagtail](https://github.com/wagtail/wagtail) - A Django content management system focused on flexibility and user experience
* [sanic-org/sanic](https://github.com/sanic-org/sanic) - Accelerate your web app development | Build fast. Run fast.
* [zauberzeug/nicegui](https://github.com/zauberzeug/nicegui) - Create web-based user interfaces with Python. The nice way.
* [Kludex/starlette](https://github.com/Kludex/starlette) - The little ASGI framework that shines. 🌟
* [frappe/frappe](https://github.com/frappe/frappe) - Low code web framework for real world applications, in Python and Javascript
* [falconry/falcon](https://github.com/falconry/falcon) - The no-magic web API and microservices framework for Python developers, with a focus on reliability and performance at scale.
* [bottlepy/bottle](https://github.com/bottlepy/bottle) - bottle.py is a fast and simple micro-framework for python web-applications.
* [litestar-org/litestar](https://github.com/litestar-org/litestar) - Light, flexible and extensible ASGI framework | Built to scale
* [sparckles/Robyn](https://github.com/sparckles/Robyn) - Robyn is a Super Fast Async Python Web Framework with a Rust runtime.
* [pallets/werkzeug](https://github.com/pallets/werkzeug) - The comprehensive WSGI web application library.
* [mesop-dev/mesop](https://github.com/mesop-dev/mesop) - Rapidly build AI apps in Python
* [webpy/webpy](https://github.com/webpy/webpy) - web.py is a web framework for python that is as simple as it is powerful.
* [vibora-io/vibora](https://github.com/vibora-io/vibora) - Fast, asynchronous and elegant Python web framework. *(archived)*
* [dpgaspar/Flask-AppBuilder](https://github.com/dpgaspar/Flask-AppBuilder) - Simple and rapid application development framework, built on top of Flask. includes detailed security, auto CRUD generation for your models, google charts and much more. Demo (login with guest/welcome) - http://flaskappbuilder.pythonanywhere.com/
* [h2oai/wave](https://github.com/h2oai/wave) - Realtime Web Apps and Dashboards for Python and R
* [Pylons/pyramid](https://github.com/Pylons/pyramid) - Pyramid - A Python web framework
* [pallets/quart](https://github.com/pallets/quart) - An async Python micro framework for building web applications.
* [kennethreitz/responder](https://github.com/kennethreitz/responder) - A familiar HTTP Service Framework for Python.
* [eudicots/Cactus](https://github.com/eudicots/Cactus) - Static site generator for designers. Uses Python and Django templates.
* [getnikola/nikola](https://github.com/getnikola/nikola) - A static website and blog generator
* [Fantomas42/django-blog-zinnia](https://github.com/Fantomas42/django-blog-zinnia) - Simple yet powerful and really extendable application for managing a blog within your Django Web site.

### HTTP and Networking Clients

* [psf/requests](https://github.com/psf/requests) - A simple, yet elegant, HTTP library.
* [httpie/cli](https://github.com/httpie/cli) - 🥧 HTTPie CLI — modern, user-friendly command-line HTTP client for the API era. JSON support, colors, sessions, downloads, plugins & more.
* [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo) - A simple Python Pydantic model for Honkai: Star Rail parsed data from the Mihomo API.
* [aio-libs/aiohttp](https://github.com/aio-libs/aiohttp) - Asynchronous HTTP client/server framework for asyncio and Python
* [encode/httpx](https://github.com/encode/httpx) - A next generation HTTP client for Python. 🦋
* [darrenburns/posting](https://github.com/darrenburns/posting) - The modern API client that lives in your terminal.
* [tweepy/tweepy](https://github.com/tweepy/tweepy) - Twitter for Python!
* [httpie/http-prompt](https://github.com/httpie/http-prompt) - An interactive command-line HTTP and API testing client built on top of HTTPie featuring autocomplete, syntax highlighting, and more. https://twitter.com/httpie
* [PyGithub/PyGithub](https://github.com/PyGithub/PyGithub) - Typed interactions with the GitHub API v3
* [burnash/gspread](https://github.com/burnash/gspread) - Google Sheets Python API
* [sammchardy/python-binance](https://github.com/sammchardy/python-binance) - Binance Exchange API python implementation for automated trading
* [lexiforest/curl_cffi](https://github.com/lexiforest/curl_cffi) - Python binding for curl-impersonate fork via cffi. A http client that can impersonate browser tls/ja3/http2 fingerprints.
* [spotipy-dev/spotipy](https://github.com/spotipy-dev/spotipy) - A light weight Python library for the Spotify Web API
* [googlemaps/google-maps-services-python](https://github.com/googlemaps/google-maps-services-python) - Python client library for Google Maps API Web Services
* [RomelTorres/alpha_vantage](https://github.com/RomelTorres/alpha_vantage) - A python wrapper for Alpha Vantage API for financial data.
* [geopy/geopy](https://github.com/geopy/geopy) - Geocoding library for Python.
* [jamalex/notion-py](https://github.com/jamalex/notion-py) - Unofficial Python API client for Notion.so
* [wechatpy/wechatpy](https://github.com/wechatpy/wechatpy) - WeChat SDK for Python
* [praw-dev/praw](https://github.com/praw-dev/praw) - PRAW, an acronym for "Python Reddit API Wrapper", is a python package that allows for simple access to Reddit's API.
* [urllib3/urllib3](https://github.com/urllib3/urllib3) - urllib3 is a user-friendly HTTP client library for Python
* [slackapi/python-slack-sdk](https://github.com/slackapi/python-slack-sdk) - Slack Developer Kit for Python
* [bear/python-twitter](https://github.com/bear/python-twitter) - A Python wrapper around the Twitter API. *(archived)*
* [python-twitter-tools/twitter](https://github.com/python-twitter-tools/twitter) - Python Twitter API *(archived)*
* [facebookarchive/python-instagram](https://github.com/facebookarchive/python-instagram) - Python Client for Instagram API *(archived)*
* [goldsmith/Wikipedia](https://github.com/goldsmith/Wikipedia) - A Pythonic wrapper for the Wikipedia API
* [picklepete/pyicloud](https://github.com/picklepete/pyicloud) - A Python + iCloud wrapper to access iPhone and Calendar data.
* [mobolic/facebook-sdk](https://github.com/mobolic/facebook-sdk) - Python SDK for Facebook's Graph API
* [simon-weber/gmusicapi](https://github.com/simon-weber/gmusicapi) - An unofficial client library for Google Music. *(archived)*
* [ValvePython/steam](https://github.com/ValvePython/steam) - ☁️ Python package for interacting with Steam
* [yoavaviram/python-amazon-simple-product-api](https://github.com/yoavaviram/python-amazon-simple-product-api) - A simple Python wrapper for the Amazon.com Product Advertising API ⛺

### API and GraphQL

* [encode/django-rest-framework](https://github.com/encode/django-rest-framework) - Web APIs for Django. 🎸
* [vitalik/django-ninja](https://github.com/vitalik/django-ninja) - 💨 Fast, Async-ready, Openapi, type hints based framework for building APIs
* [graphql-python/graphene](https://github.com/graphql-python/graphene) - GraphQL framework for Python
* [hugapi/hug](https://github.com/hugapi/hug) - Embrace the APIs of the future. Hug aims to make developing APIs as simple as possible, but no simpler.
* [pyeve/eve](https://github.com/pyeve/eve) - REST API framework designed for human beings
* [encode/apistar](https://github.com/encode/apistar) - The Web API toolkit. 🛠 *(archived)*
* [strawberry-graphql/strawberry](https://github.com/strawberry-graphql/strawberry) - A GraphQL library for Python that leverages type annotations 🍓
* [spec-first/connexion](https://github.com/spec-first/connexion) - Connexion is a modern Python web framework that makes spec-first and api-first development easy.
* [graphql-python/graphene-django](https://github.com/graphql-python/graphene-django) - Build powerful, efficient, and flexible GraphQL APIs with seamless Django integration.
* [toastdriven/restless](https://github.com/toastdriven/restless) - A lightweight REST miniframework for Python.

### Scraping and Crawling

* [browser-use/browser-use](https://github.com/browser-use/browser-use) - 🌐 Make websites accessible for AI agents. Automate tasks online with ease.
* [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) - 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl!
* [scrapy/scrapy](https://github.com/scrapy/scrapy) - Scrapy, a fast high-level web crawling & scraping framework for Python.
* [CloakHQ/CloakBrowser](https://github.com/CloakHQ/CloakBrowser) - Stealth Chromium that passes every bot detection test. Drop-in Playwright replacement with source-level fingerprint patches. 30/30 tests passed.
* [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) - Python scraper based on AI
* [jhao104/proxy_pool](https://github.com/jhao104/proxy_pool) - Python ProxyPool for web spider
* [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) - Automate browser based workflows with AI
* [Evil0ctal/Douyin_TikTok_Download_API](https://github.com/Evil0ctal/Douyin_TikTok_Download_API) - 🚀「Douyin_TikTok_Download_API」是一个开箱即用的高性能异步抖音、快手、TikTok、Bilibili数据爬取工具，支持API调用，在线批量解析及下载。
* [binux/pyspider](https://github.com/binux/pyspider) - A Powerful Spider(Web Crawler) System in Python. *(archived)*
* [Kr1s77/awesome-python-login-model](https://github.com/Kr1s77/awesome-python-login-model) - 😮python模拟登陆一些大型网站，还有一些简单的爬虫，希望对你们有所帮助❤️，如果喜欢记得给个star哦🌟
* [codelucas/newspaper](https://github.com/codelucas/newspaper) - newspaper3k is a news, full-text, and article metadata extraction in Python 3. Advanced docs:
* [psf/requests-html](https://github.com/psf/requests-html) - Pythonic HTML Parsing for Humans™
* [g1879/DrissionPage](https://github.com/g1879/DrissionPage) - Python based web automation tool. Powerful and elegant.
* [dataabc/weiboSpider](https://github.com/dataabc/weiboSpider) - 新浪微博爬虫，用python爬取新浪微博数据
* [apify/crawlee-python](https://github.com/apify/crawlee-python) - Crawlee—A web scraping and browser automation library for Python to build reliable crawlers. Extract data for AI, LLMs, RAG, or GPTs. Download HTML, PDF, JPG, PNG, and other files from websites. Works with Parsel, BeautifulSoup, Playwright, and raw HTTP. Both headful and headless mode. With proxy rotation.
* [hardikvasa/google-images-download](https://github.com/hardikvasa/google-images-download) - Python Script to download hundreds of images from 'Google Images'. It is a ready-to-run code!
* [mherrmann/helium](https://github.com/mherrmann/helium) - Lighter web automation with Python
* [jdepoix/youtube-transcript-api](https://github.com/jdepoix/youtube-transcript-api) - This is a python API which allows you to get the transcript/subtitles for a given YouTube video. It also works for automatically generated subtitles and it does not require an API key nor a headless browser, like other selenium based solutions do!
* [alirezamika/autoscraper](https://github.com/alirezamika/autoscraper) - A Smart, Automatic, Fast and Lightweight Web Scraper for Python
* [wbt5/real-url](https://github.com/wbt5/real-url) - 获取斗鱼&虎牙&哔哩哔哩&抖音&快手等 58 个直播平台的真实流媒体地址(直播源)和弹幕，直播源可在 PotPlayer、flv.js 等播放器中播放。
* [luyishisi/Anti-Anti-Spider](https://github.com/luyishisi/Anti-Anti-Spider) - 越来越多的网站具有反爬虫特性，有的用图片隐藏关键数据，有的使用反人类的验证码，建立反反爬虫的代码仓库，通过与不同特性的网站做斗争（无恶意）提高技术。（欢迎提交难以采集的网站）（因工作原因，项目暂停）
* [hect0x7/JMComic-Crawler-Python](https://github.com/hect0x7/JMComic-Crawler-Python) - Python API for JMComic | 提供Python API访问禁漫天堂，同时支持网页端和移动端 | 禁漫天堂GitHub Actions下载器🚀
* [autoscrape-labs/pydoll](https://github.com/autoscrape-labs/pydoll) - Pydoll is a library for automating chromium-based browsers without a WebDriver, offering realistic interactions.
* [adbar/trafilatura](https://github.com/adbar/trafilatura) - Python & Command-line tool to gather text and metadata on the Web: Crawling, scraping, extraction, output as CSV, JSON, HTML, MD, TXT, XML
* [subzeroid/instagrapi](https://github.com/subzeroid/instagrapi) - 🔥 The fastest and powerful Python library for Instagram Private API 2026 with HikerAPI SaaS
* [VeNoMouS/cloudscraper](https://github.com/VeNoMouS/cloudscraper) - A Python module to bypass Cloudflare's anti-bot page.
* [davidteather/TikTok-Api](https://github.com/davidteather/TikTok-Api) - The Unofficial TikTok API Wrapper In Python
* [qbittorrent/search-plugins](https://github.com/qbittorrent/search-plugins) - Search plugins for qBittorrent search feature
* [chyroc/WechatSogou](https://github.com/chyroc/WechatSogou) - 基于搜狗微信搜索的微信公众号爬虫接口
* [JustAnotherArchivist/snscrape](https://github.com/JustAnotherArchivist/snscrape) - A social networking service scraper in Python
* [MechanicalSoup/MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) - A Python library for automating interaction with websites.
* [d60/twikit](https://github.com/d60/twikit) - Twitter API Scraper | Without an API key | Twitter Internal API | Free | Twitter scraper | Twitter Bot
* [dataabc/weibo-crawler](https://github.com/dataabc/weibo-crawler) - 新浪微博爬虫，用python爬取新浪微博数据，并下载微博图片和微博视频
* [nghuyong/WeiboSpider](https://github.com/nghuyong/WeiboSpider) - 持续维护的新浪微博采集工具🚀🚀🚀
* [fake-useragent/fake-useragent](https://github.com/fake-useragent/fake-useragent) - Up-to-date simple useragent faker with real world database *(archived)*
* [MikeChongCan/scylla](https://github.com/MikeChongCan/scylla) - Intelligent proxy pool for Humans™ to extract content from the internet and build your own Large Language Models in this new AI era
* [bisguzar/twitter-scraper](https://github.com/bisguzar/twitter-scraper) - Scrape the Twitter Frontend API without authentication. *(archived)*
* [elliotgao2/toapi](https://github.com/elliotgao2/toapi) - Every web site provides APIs.
* [Anorov/cloudflare-scrape](https://github.com/Anorov/cloudflare-scrape) - A Python module to bypass Cloudflare's anti-bot page.
* [jeanphix/Ghost.py](https://github.com/jeanphix/Ghost.py) - Webkit based scriptable web browser for python.
* [gawel/pyquery](https://github.com/gawel/pyquery) - A jquery-like library for python
* [egrcc/zhihu-python](https://github.com/egrcc/zhihu-python) - 获取知乎内容信息，包括问题，答案，用户，收藏夹信息
* [openstates/openstates-scrapers](https://github.com/openstates/openstates-scrapers) - source for Open States scrapers

## Data and Storage

### Database Clients and ORMs

* [fastapi/sqlmodel](https://github.com/fastapi/sqlmodel) - SQL databases in Python, designed for simplicity, compatibility, and robustness.
* [redis/redis-py](https://github.com/redis/redis-py) - Redis Python client
* [dbcli/pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting
* [sqlalchemy/sqlalchemy](https://github.com/sqlalchemy/sqlalchemy) - The Database Toolkit for Python
* [coleifer/peewee](https://github.com/coleifer/peewee) - a small, expressive orm -- supports postgresql, mysql, sqlite, now with asyncio
* [dbcli/mycli](https://github.com/dbcli/mycli) - Rich MySQL Terminal Client with AutoCompletion, Syntax Highlighting, and Dataframes
* [tobymao/sqlglot](https://github.com/tobymao/sqlglot) - Python SQL Parser and Transpiler
* [MagicStack/asyncpg](https://github.com/MagicStack/asyncpg) - A fast PostgreSQL Database Client Library for Python/asyncio.
* [PyMySQL/PyMySQL](https://github.com/PyMySQL/PyMySQL) - MySQL client library for Python
* [kennethreitz/records](https://github.com/kennethreitz/records) - SQL for Humans™
* [tortoise/tortoise-orm](https://github.com/tortoise/tortoise-orm) - Familiar asyncio ORM for python, built with relations in mind
* [pudo/dataset](https://github.com/pudo/dataset) - Easy-to-use data handling for SQL data stores with support for implicit table creation, bulk loading, and transactions.
* [elastic/elasticsearch-py](https://github.com/elastic/elasticsearch-py) - Official Python client for Elasticsearch
* [mongodb/mongo-python-driver](https://github.com/mongodb/mongo-python-driver) - PyMongo - the Official MongoDB Python driver
* [MongoEngine/mongoengine](https://github.com/MongoEngine/mongoengine) - A Python Object-Document-Mapper for working with MongoDB
* [pallets-eco/flask-sqlalchemy](https://github.com/pallets-eco/flask-sqlalchemy) - Adds SQLAlchemy support to Flask
* [encode/databases](https://github.com/encode/databases) - Async database support for Python. 🗄 *(archived)*
* [elastic/elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - High level Python client for Elasticsearch *(archived)*
* [python-gino/gino](https://github.com/python-gino/gino) - GINO Is Not ORM - a Python asyncio ORM on SQLAlchemy core.

### Serialization and Formats

* [pydantic/pydantic](https://github.com/pydantic/pydantic) - Data validation using Python type hints
* [ijl/orjson](https://github.com/ijl/orjson) - Fast, correct Python JSON library supporting dataclasses, datetimes, and numpy
* [marshmallow-code/marshmallow](https://github.com/marshmallow-code/marshmallow) - A lightweight library for converting complex objects to and from simple Python datatypes.
* [martinblech/xmltodict](https://github.com/martinblech/xmltodict) - Python module that makes working with XML feel like you are working with JSON
* [python-openxml/python-docx](https://github.com/python-openxml/python-docx) - Create and modify Word documents with Python
* [euske/pdfminer](https://github.com/euske/pdfminer) - Python PDF Parser (Not actively maintained). Check out pdfminer.six. *(archived)*
* [mangiucugna/json_repair](https://github.com/mangiucugna/json_repair) - Repair malformed JSON from LLMs, APIs, logs, and user input in Python.
* [python-jsonschema/jsonschema](https://github.com/python-jsonschema/jsonschema) - An implementation of the JSON Schema specification for Python
* [jazzband/tablib](https://github.com/jazzband/tablib) - Python Module for Tabular Datasets in XLS, CSV, JSON, YAML, &c.
* [jmcnamara/XlsxWriter](https://github.com/jmcnamara/XlsxWriter) - A Python module for creating Excel XLSX files.
* [pyeve/cerberus](https://github.com/pyeve/cerberus) - Lightweight, extensible data validation library for Python
* [lxml/lxml](https://github.com/lxml/lxml) - The lxml XML toolkit for Python

### Caching and Queues

* [celery/celery](https://github.com/celery/celery) - Distributed Task Queue (development branch)
* [rq/rq](https://github.com/rq/rq) - Simple job queues for Python
* [hatchet-dev/hatchet](https://github.com/hatchet-dev/hatchet) - 🪓 An orchestration engine for background tasks, AI agents, and durable workflows
* [robinhood/faust](https://github.com/robinhood/faust) - Python Stream Processing
* [coleifer/huey](https://github.com/coleifer/huey) - a little task queue for python
* [dpkp/kafka-python](https://github.com/dpkp/kafka-python) - Python client for Apache Kafka
* [ag2ai/faststream](https://github.com/ag2ai/faststream) - Asynchronous Python framework for event-driven services. A thin client for Kafka, RabbitMQ, NATS, Redis and MQTT with full access to native broker features, plus AsyncAPI docs, in-memory tests and observability out of the box.
* [Bogdanp/dramatiq](https://github.com/Bogdanp/dramatiq) - A fast and reliable background task processing library for Python 3.
* [tschellenbach/Stream-Framework](https://github.com/tschellenbach/Stream-Framework) - Stream Framework is a Python library, which allows you to build news feed, activity streams and notification systems using Cassandra and/or Redis. The authors of Stream-Framework also provide a cloud service for feed technology:
* [pika/pika](https://github.com/pika/pika) - Pure Python RabbitMQ/AMQP 0-9-1 client library
* [confluentinc/confluent-kafka-python](https://github.com/confluentinc/confluent-kafka-python) - Confluent's Kafka Python Client

## Machine Learning and AI

### LLM and Inference

* [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - AutoGPT is the vision of accessible AI for everyone, to use and to build on. Our mission is to provide the tools, so that you can focus on what matters.
* [langgenius/dify](https://github.com/langgenius/dify) - Build Agentic workflows, RAG pipelines, with rich AI model and tool support on one collaborative workspace. Deploy on cloud, VPC, or self-hosted, so teams move from prototype to production without rebuilding the stack.
* [langflow-ai/langflow](https://github.com/langflow-ai/langflow) - Langflow is a powerful tool for building and deploying AI-powered agents and workflows.
* [langchain-ai/langchain](https://github.com/langchain-ai/langchain) - The agent engineering platform.
* [bytedance/deer-flow](https://github.com/bytedance/deer-flow) - An open-source long-horizon SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skill, subagents and message gateway, it handles different levels of tasks that could take minutes to hours.
* [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) - Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees.
* [unslothai/unsloth](https://github.com/unslothai/unsloth) - Local UI to run and train LLMs and diffusion models. Supports GGUF, MLX, Qwen3.8, DeepSeek-V4, MiniMax-H3, Gemma 4, FLUX and more.
* [binary-husky/gpt_academic](https://github.com/binary-husky/gpt_academic) - 为GPT/GLM等LLM大语言模型提供实用化交互接口，特别优化论文阅读/润色/写作体验，模块化设计，支持自定义快捷按钮&函数插件，支持Python和C++等项目剖析&自译解功能，PDF/LaTex论文翻译&总结功能，支持并行问询多种LLM模型，支持chatglm3等本地模型。接入通义千问, deepseekcoder, 讯飞星火, 文心一言, llama2, rwkv, claude2, moss等。
* [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) - Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 20% fewer tokens for coding agents, 60-95% fewer tokens for JSON, same answers. Library, proxy, MCP server.
* [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter) - A coding agent for open models like Kimi K3
* [xtekky/gpt4free](https://github.com/xtekky/gpt4free) - The official gpt4free repository | various collection of powerful language models | opus 4.6 gpt 5.3 kimi 2.5 deepseek v3.2 gemini 3
* [mem0ai/mem0](https://github.com/mem0ai/mem0) - The Memory Layer for AI Agents - Drop-in memory infrastructure for AI agents and apps. Context that persists. Built for production.
* [MemPalace/mempalace](https://github.com/MemPalace/mempalace) - The best-benchmarked open-source AI memory system. And it's free.
* [BerriAI/litellm](https://github.com/BerriAI/litellm) - The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format with cost tracking, guardrails, load balancing, and logging [Bedrock, Azure, OpenAI, Anthropic, OpenAI, VertexAI, vLLM, Nvidia NIM]
* [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) - World's first open-source, agentic video production system. 12 production pipelines, 100+ tools, 700+ agent skill and production-knowledge files. Turn your AI coding assistant into a full video production studio.
* [AntonOsika/gpt-engineer](https://github.com/AntonOsika/gpt-engineer) - CLI platform to experiment with codegen. Precursor to: https://lovable.dev *(archived)*
* [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - Ultra-lightweight, open-source, self-hosted personal AI agent framework in Python with WebUI, tools, memory, MCP, multi-agent workflows, automation, and chat apps
* [agno-agi/agno](https://github.com/agno-agi/agno) - Build, run, and manage agent platforms.
* [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) - Build resilient agents.
* [AstrBotDevs/AstrBot](https://github.com/AstrBotDevs/AstrBot) - AI Agent Assistant & development framework that integrates lots of IM platforms, LLMs, plugins and AI feature, and can be your openclaw alternative. ✨
* [google/langextract](https://github.com/google/langextract) - A Python library for extracting structured information from unstructured text using LLMs with precise source grounding and interactive visualization.
* [LAION-AI/Open-Assistant](https://github.com/LAION-AI/Open-Assistant) - OpenAssistant is a chat-based assistant that understands tasks, can interact with third-party systems, and retrieve information dynamically to do so.
* [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) - "Vibe-Trading: Your Personal Trading Agent"
* [onyx-dot-app/onyx](https://github.com/onyx-dot-app/onyx) - Open Source AI Platform - AI Chat with advanced features that works with every LLM
* [openai/openai-python](https://github.com/openai/openai-python) - The official Python library for the OpenAI API
* [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) - Local-first code intelligence graph for MCP and CLI. Builds a persistent map of your codebase so AI coding tools read only what matters, with benchmarked context reductions on reviews and large-repo workflows.
* [ComposioHQ/composio](https://github.com/ComposioHQ/composio) - Composio powers 1000+ toolkits, tool search, context management, authentication, and a sandboxed workbench to help you build AI agents that turn intent into action.
* [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) - An autonomous agent that conducts deep research on any data using any LLM providers
* [openai/openai-agents-python](https://github.com/openai/openai-agents-python) - A lightweight, powerful framework for multi-agent workflows
* [huggingface/smolagents](https://github.com/huggingface/smolagents) - 🤗 smolagents: a barebones library for agents that think in code.
* [langchain-ai/deepagents](https://github.com/langchain-ai/deepagents) - The batteries-included agent harness.
* [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) - 🚀 The fast, Pythonic way to build MCP servers and clients.
* [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) - Community plugin to control Blender 3D with any LLM of your choice
* [deepset-ai/haystack](https://github.com/deepset-ai/haystack) - Open-source AI orchestration framework for building context-engineered, production-ready LLM applications. Design modular pipelines and agent workflows with explicit control over retrieval, routing, memory, and generation. Built for scalable agents, RAG, multimodal applications, semantic search, and conversational systems.
* [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) - The official Python SDK for Model Context Protocol servers and clients
* [huggingface/peft](https://github.com/huggingface/peft) - 🤗 PEFT: State-of-the-art Parameter-Efficient Fine-Tuning.
* [google/adk-python](https://github.com/google/adk-python) - An open-source, code-first Python toolkit for building, evaluating, and deploying sophisticated AI agents with flexibility and control.
* [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) - How Python does AI. Agents, realtime voice, image generation, embeddings. Every model, every interface, typed end to end.
* [teng-lin/notebooklm-py](https://github.com/teng-lin/notebooklm-py) - Unofficial Python API and agentic skill for Google Gemini Notebook. Full programmatic access to NotebookLM's features—including capabilities the web UI doesn't expose—via Python, CLI, and AI agents like Claude Code, Codex, and OpenClaw.
* [emcie-co/parlant](https://github.com/emcie-co/parlant) - Build reliable customer-facing AI agents with Parlant: an interaction control harness optimized for controlled, consistent, and predictable LLM interactions.
* [arc53/DocsGPT](https://github.com/arc53/DocsGPT) - Private AI platform for agents, assistants and enterprise search. Built-in Agent Builder, Deep research, Document analysis, Multi-model support, and API connectivity for agents.
* [confident-ai/deepeval](https://github.com/confident-ai/deepeval) - The LLM Evaluation Framework
* [TransformerOptimus/SuperAGI](https://github.com/TransformerOptimus/SuperAGI) - <⚡️> SuperAGI - A dev-first open source autonomous AI agent framework. Enabling developers to build, manage & run useful autonomous agents quickly and reliably.
* [cft0808/edict](https://github.com/cft0808/edict) - 🏛️ 三省六部制 · OpenClaw Multi-Agent Orchestration System — 9 specialized AI agents with real-time dashboard, model config, and full audit trails
* [memvid/memvid](https://github.com/memvid/memvid) - Memory layer for AI Agents. Replace complex RAG pipelines with a serverless, single-file memory layer. Give your agents instant retrieval and long-term memory.
* [MemoriLabs/Memori](https://github.com/MemoriLabs/Memori) - Memori is agent-native memory infrastructure. A LLM-agnostic layer that turns agent execution and conversation into structured, persistent state for production systems. Built for enterprise, Memori works with the data infrastructure you already run, no rip-and-replace, and deploys across managed cloud, single-tenant cloud, VPC, and on-premises.
* [raga-ai-hub/RagaAI-Catalyst](https://github.com/raga-ai-hub/RagaAI-Catalyst) - Python SDK for Agent AI Observability, Monitoring and Evaluation Framework. Includes features like agent, llm and tools tracing, debugging multi-agentic system, self-hosted dashboard and advanced analytics with timeline and execution graph view
* [MODSetter/SurfSense](https://github.com/MODSetter/SurfSense) - Open-source NotebookLM alternative. Research the open web with live data(Reddit, YT, IG, TikTok, Indeed, Google Search, Maps etc) through one platform, API or MCP server. Join our Discord: https://discord.gg/ejRNvftDp9
* [yusufkaraaslan/Skill_Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) - Convert documentation websites, GitHub repositories, and PDFs into Claude AI skills with automatic conflict detection
* [NVIDIA/TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) - TensorRT LLM provides users with an easy-to-use Python API to define Large Language Models (LLMs) and supports state-of-the-art optimizations to perform inference efficiently on NVIDIA GPUs. TensorRT LLM also contains components to create Python and C++ runtimes that orchestrate the inference execution in a performant way.
* [lsdefine/GenericAgent](https://github.com/lsdefine/GenericAgent) - Self-evolving agent: grows skill tree from 3.3K-line seed, achieving full system control with 6x less token consumption
* [567-labs/instructor](https://github.com/567-labs/instructor) - structured outputs for llms
* [e2b-dev/E2B](https://github.com/e2b-dev/E2B) - Open-source, secure environment with real-world tools for enterprise-grade agents.
* [xszyou/Fay](https://github.com/xszyou/Fay) - fay是一个帮助数字人（2.5d、3d、移动、pc、网页）或大语言模型（openai兼容、deepseek）连通业务系统的agent框架。
* [microsoft/agent-framework](https://github.com/microsoft/agent-framework) - A framework for building, orchestrating and deploying AI agents and multi-agent workflows with support for Python and .NET.
* [StarTrail-org/LEANN](https://github.com/StarTrail-org/LEANN) - [MLsys2026 Best Paper]: https://arxiv.org/abs/2506.08276. RAG on Everything with LEANN. Enjoy 97% storage savings while running a fast, accurate, and 100% private RAG application on your personal device.
* [ifixai-ai/iFixAi](https://github.com/ifixai-ai/iFixAi) - Independent Auditing of AI Agents. Run by human or the agent itself, to answer the most crucial question in the AI Agent Economy. Is the agent doing what is supposed to do? With iFixAi you can have this answer in less than 120 seconds.
* [Chainlit/chainlit](https://github.com/Chainlit/chainlit) - Build Conversational AI in minutes ⚡️
* [dataelement/bisheng](https://github.com/dataelement/bisheng) - BISHENG is an open LLM devops platform for next generation Enterprise AI applications. Powerful and comprehensive features include: GenAI workflow, RAG, Agent, Unified model management, Evaluation, SFT, Dataset Management, Enterprise-level System Management, Observability and more.
* [semantica-agi/semantica](https://github.com/semantica-agi/semantica) - Graph-Native Infrastructure for Context and Accountable AI Systems
* [cocoindex-io/cocoindex](https://github.com/cocoindex-io/cocoindex) - Incremental engine for long horizon agents 🌟 Star if you like it!
* [aden-hive/hive](https://github.com/aden-hive/hive) - Multi-Agent Harness for Production AI
* [ValueCell-ai/valuecell](https://github.com/ValueCell-ai/valuecell) - ValueCell is a community-driven, multi-agent platform for financial applications.
* [abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python) - Python bindings for llama.cpp
* [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) - The fullstack MCP framework to develop MCP Apps for ChatGPT / Claude & MCP Servers for AI Agents.
* [ollama/ollama-python](https://github.com/ollama/ollama-python) - Ollama Python library
* [omnigent-ai/omnigent](https://github.com/omnigent-ai/omnigent) - Omnigent is an open-source AI agent framework and meta-harness: orchestrate Claude Code, Codex, Cursor, Pi, and custom agents — swap harnesses without rewriting, enforce policies and sandboxing, and collaborate in real time from any device.
* [intel/ipex-llm](https://github.com/intel/ipex-llm) - Accelerate local LLM inference and finetuning (LLaMA, Mistral, ChatGLM, Qwen, DeepSeek, Mixtral, Gemma, Phi, MiniCPM, Qwen-VL, MiniCPM-V, etc.) on Intel XPU (e.g., local PC with iGPU and NPU, discrete GPU such as Arc, Flex and Max); seamlessly integrate with llama.cpp, Ollama, HuggingFace, LangChain, LlamaIndex, vLLM, DeepSpeed, Axolotl, etc. *(archived)*
* [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) - Build effective agents using Model Context Protocol and simple workflow patterns
* [zilliztech/deep-searcher](https://github.com/zilliztech/deep-searcher) - Open Source Deep Research Alternative to Reason and Search on Private Data. Written in Python.
* [SciPhi-AI/R2R](https://github.com/SciPhi-AI/R2R) - SoTA production-ready AI retrieval system. Agentic Retrieval-Augmented Generation (RAG) with a RESTful API.
* [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) - Build autonomous AI agents in Python.
* [2FastLabs/agent-squad](https://github.com/2FastLabs/agent-squad) - Flexible and powerful framework for managing multiple AI agents and handling complex conversations
* [rocketride-org/rocketride-server](https://github.com/rocketride-org/rocketride-server) - High-performance AI pipeline engine with a C++ core and 50+ Python-extensible nodes. Build, debug, and scale LLM workflows with 13+ model providers, 8+ vector databases, and agent orchestration, all from your IDE. Includes VS Code extension, TypeScript/Python SDKs, and Docker deployment.
* [strands-agents/harness-sdk](https://github.com/strands-agents/harness-sdk) - Build an agent harness and control it end-to-end. Open-source SDK for production AI agents in Python & TypeScript - any model, any cloud.
* [plastic-labs/honcho](https://github.com/plastic-labs/honcho) - Memory library for building stateful agents
* [opensquilla/opensquilla](https://github.com/opensquilla/opensquilla) - OpenSquilla — Token-Efficient AI Agent with same budget, higher intelligence density
* [julep-ai/julep](https://github.com/julep-ai/julep) - Julep — durable, composable AI agents. Flows that crash and resume, retry safely, and explain every step.
* [Andyyyy64/whichllm](https://github.com/Andyyyy64/whichllm) - Find the local LLM that actually runs and performs best on your hardware. Ranked by real, recency-aware benchmarks, not parameter count. One command, run it instantly.
* [souzatharsis/podcastfy](https://github.com/souzatharsis/podcastfy) - An Open Source Python alternative to NotebookLM's podcast feature: Transforming Multimodal Content into Captivating Multilingual Audio Conversations with GenAI
* [crestalnetwork/intentkit](https://github.com/crestalnetwork/intentkit) - IntentKit is an open-source, self-hosted cloud agent cluster that manages a collaborative team of AI agents for you.
* [genkit-ai/genkit](https://github.com/genkit-ai/genkit) - Open-source framework for building agentic apps in JavaScript, Go, Dart, and Python, built and used in production by Google
* [nlweb-ai/NLWeb](https://github.com/nlweb-ai/NLWeb) - Main reference implementation for NLWeb, implemented in Python.
* [meta-pytorch/gpt-fast](https://github.com/meta-pytorch/gpt-fast) - Simple and efficient pytorch-native transformer text generation in <1000 LOC of python.
* [PrefectHQ/marvin](https://github.com/PrefectHQ/marvin) - an ambient intelligence library
* [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) - AI Agent Governance Toolkit — Policy enforcement, zero-trust identity, execution sandboxing, and reliability engineering for autonomous AI agents. Covers 10/10 OWASP Agentic Top 10.
* [Mai-with-u/MaiBot](https://github.com/Mai-with-u/MaiBot) - MaiSaka, an LLM-based intelligent agent, is a digital lifeform devoted to understanding you and interacting in the style of a real human. She does not pursue perfection, nor does she seek efficiency; instead, she values warmth, authenticity, and genuine connection.
* [AgentOps-AI/agentops](https://github.com/AgentOps-AI/agentops) - Python SDK for AI agent monitoring, LLM cost tracking, benchmarking, and more. Integrates with most LLMs and agent frameworks including CrewAI, Agno, OpenAI Agents SDK, Langchain, Autogen, AG2, and CamelAI
* [serge-chat/serge](https://github.com/serge-chat/serge) - A web interface for chatting with Alpaca through llama.cpp. Fully dockerized, with an easy to use API. *(archived)*
* [dograh-hq/dograh](https://github.com/dograh-hq/dograh) - Open source voice AI platform. Self-hosted alternative to Vapi and Retell. On Prem, BYOK across Speech to Speech or LLM/STT/TTS, with a visual workflow builder, MCP native and telephony support.
* [volcengine/MineContext](https://github.com/volcengine/MineContext) - MineContext is your proactive context-aware AI partner（Context-Engineering+ChatGPT Pulse）
* [superduper-io/superduper](https://github.com/superduper-io/superduper) - Superduper: End-to-end framework for building custom AI applications and agents.
* [dsdanielpark/Bard-API](https://github.com/dsdanielpark/Bard-API) - The unofficial python package that returns response of Google Bard through cookie value. *(archived)*
* [Marker-Inc-Korea/AutoRAG](https://github.com/Marker-Inc-Korea/AutoRAG) - AutoRAG: Now your agent can find anything in your computer. It gets smarter if you are using it frequently.
* [Kiln-AI/Kiln](https://github.com/Kiln-AI/Kiln) - Build, Evaluate, and Optimize AI Systems. Includes evals, RAG, agents, fine-tuning, synthetic data generation, dataset management, MCP, and more.
* [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) - The ultimate RAG for your monorepo. Query, understand, and edit multi-language codebases with the power of AI and knowledge graphs
* [ag2ai/ag2](https://github.com/ag2ai/ag2) - AG2 (formerly AutoGen): The Open-Source AgentOS.Join us at: https://discord.gg/sNGSwQME3x
* [TencentCloudADP/youtu-agent](https://github.com/TencentCloudADP/youtu-agent) - A simple yet powerful agent framework that delivers with open-source models
* [ruc-datalab/DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze) - DeepAnalyze is the first agentic LLM for autonomous data science. 🎈你的AI数据分析师，自动分析大量数据，一键生成专业分析报告！
* [FlowElement-xinliuyuansu/m_flow](https://github.com/FlowElement-xinliuyuansu/m_flow) - A bio-inspired cognitive memory engine — a new paradigm for Graph RAG.
* [truefoundry/cognita](https://github.com/truefoundry/cognita) - RAG (Retrieval Augmented Generation) Framework for building modular, open source applications for production by TrueFoundry *(archived)*
* [rawandahmad698/PyChatGPT](https://github.com/rawandahmad698/PyChatGPT) - ⚡️ Python client for the ChatGPT API with, conversation tracking, proxy support and more.
* [llm-workflow-engine/llm-workflow-engine](https://github.com/llm-workflow-engine/llm-workflow-engine) - Power CLI and Workflow manager for LLMs (core package)
* [zhaoyingjun/chatbot](https://github.com/zhaoyingjun/chatbot) - Chatbot继续沿着LLM前进，近期更新小参数量SLM的和训练脚本，支持本地训练。新增ChatAgent,实现各种有实际场景价值的Agent实现。
* [minimaxir/simpleaichat](https://github.com/minimaxir/simpleaichat) - Python package for easily interfacing with chat apps, with robust features and minimal code complexity.
* [ading2210/poe-api](https://github.com/ading2210/poe-api) - [UNMAINTAINED] A reverse engineered Python API wrapper for Quora's Poe, which provides free access to ChatGPT, GPT-4, and Claude. *(archived)*
* [approximatelabs/sketch](https://github.com/approximatelabs/sketch) - AI code-writing assistant that understands data content
* [YiVal/YiVal](https://github.com/YiVal/YiVal) - Your Automatic Prompt Engineering Assistant for GenAI Applications
* [NVIDIA-NeMo/Guardrails](https://github.com/NVIDIA-NeMo/Guardrails) - NeMo Guardrails is an open-source toolkit for easily adding programmable guardrails to LLM-based conversational systems.

### Machine Learning Frameworks

* [huggingface/transformers](https://github.com/huggingface/transformers) - 🤗 Transformers: the model-definition framework for state-of-the-art machine learning models in text, vision, audio, and multimodal models, for both inference and training.
* [pytorch/pytorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration
* [scikit-learn/scikit-learn](https://github.com/scikit-learn/scikit-learn) - scikit-learn: machine learning in Python
* [keras-team/keras](https://github.com/keras-team/keras) - Deep Learning for humans
* [jax-ml/jax](https://github.com/jax-ml/jax) - Composable transformations of Python+NumPy programs: differentiate, vectorize, JIT to GPU/TPU, and more
* [Lightning-AI/pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning) - Pretrain, finetune ANY AI model of ANY size on 1 or 10,000+ GPUs with zero code changes.
* [recommenders-team/recommenders](https://github.com/recommenders-team/recommenders) - Best Practices on Recommendation Systems
* [optuna/optuna](https://github.com/optuna/optuna) - A hyperparameter optimization framework
* [microsoft/nni](https://github.com/microsoft/nni) - An open source AutoML toolkit for automate machine learning lifecycle, including feature engineering, neural architecture search, model compression and hyper-parameter tuning. *(archived)*
* [dmlc/dgl](https://github.com/dmlc/dgl) - Python package built to ease deep learning on graph, on top of existing DL frameworks.
* [unifyai/ivy](https://github.com/unifyai/ivy) - Convert Machine Learning Code Between Frameworks
* [DLR-RM/stable-baselines3](https://github.com/DLR-RM/stable-baselines3) - PyTorch version of Stable Baselines, reliable implementations of reinforcement learning algorithms.
* [ludwig-ai/ludwig](https://github.com/ludwig-ai/ludwig) - Low-code framework for building custom LLMs, neural networks, and other AI models
* [autogluon/autogluon](https://github.com/autogluon/autogluon) - Fast and Accurate ML in 3 Lines of Code
* [vwxyzjn/cleanrl](https://github.com/vwxyzjn/cleanrl) - High-quality single file implementation of Deep Reinforcement Learning algorithms with research-friendly features (PPO, DQN, C51, DDPG, TD3, SAC, PPG)
* [EpistasisLab/tpot](https://github.com/EpistasisLab/tpot) - A Python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming.
* [OpenMined/PySyft](https://github.com/OpenMined/PySyft) - Perform data science on data that remains in someone else's server
* [Theano/Theano](https://github.com/Theano/Theano) - Theano was a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently. It is being continued as PyTensor: www.github.com/pymc-devs/pytensor
* [yzhao062/pyod](https://github.com/yzhao062/pyod) - A Python library for anomaly detection across tabular, time series, graph, text, image, and audio data. 60+ detectors, benchmark-backed ADEngine orchestration, and an agentic workflow for AI agents.
* [pycaret/pycaret](https://github.com/pycaret/pycaret) - Open-source, low-code AutoML platform for Python. PyCaret 4.0: sklearn-native engine + React control plane.
* [unit8co/darts](https://github.com/unit8co/darts) - A python library for user-friendly forecasting and anomaly detection on time series.
* [Lightricks/LTX-2](https://github.com/Lightricks/LTX-2) - Official Python inference and LoRA trainer package for the LTX-2 audio–video generative model.
* [keras-team/autokeras](https://github.com/keras-team/autokeras) - AutoML library for deep learning
* [modelscope/modelscope](https://github.com/modelscope/modelscope) - ModelScope: bring the notion of Model-as-a-Service to life.
* [catboost/catboost](https://github.com/catboost/catboost) - A fast, scalable, high performance Gradient Boosting on Decision Trees library, used for ranking, classification, regression and other machine learning tasks for Python, R, Java, C++. Supports computation on CPU and GPU.
* [pyro-ppl/pyro](https://github.com/pyro-ppl/pyro) - Deep universal probabilistic programming with Python and PyTorch
* [bentoml/BentoML](https://github.com/bentoml/BentoML) - The easiest way to serve AI apps and models - Build Model Inference APIs, Job queues, LLM apps, Multi-model pipelines, and more!
* [hyperopt/hyperopt](https://github.com/hyperopt/hyperopt) - Distributed Asynchronous Hyperparameter Optimization in Python
* [HIPS/autograd](https://github.com/HIPS/autograd) - Efficiently computes derivatives of NumPy code.
* [tensorlayer/TensorLayer](https://github.com/tensorlayer/TensorLayer) - Deep Learning and Reinforcement Learning Library for Scientists and Engineers
* [scikit-learn-contrib/imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn) - A Python Package to Tackle the Curse of Imbalanced Datasets in Machine Learning
* [flwrlabs/flower](https://github.com/flwrlabs/flower) - Flower: A Friendly Federated AI Framework
* [SerpentAI/SerpentAI](https://github.com/SerpentAI/SerpentAI) - Game Agent Framework. Helping you create AIs / Bots that learn to play any game you own! *(archived)*
* [NicolasHug/Surprise](https://github.com/NicolasHug/Surprise) - A Python scikit for building and analyzing recommender systems
* [aimhubio/aim](https://github.com/aimhubio/aim) - Aim 💫 — An easy-to-use & supercharged open-source experiment tracker.
* [online-ml/river](https://github.com/online-ml/river) - 🌊 Online machine learning in Python
* [snorkel-team/snorkel](https://github.com/snorkel-team/snorkel) - A system for quickly generating training data with weak supervision
* [chainer/chainer](https://github.com/chainer/chainer) - A flexible framework of neural networks for deep learning
* [awslabs/gluonts](https://github.com/awslabs/gluonts) - Probabilistic time series modeling in Python
* [rasbt/mlxtend](https://github.com/rasbt/mlxtend) - A library of extension and helper modules for Python's data analysis and machine learning libraries.
* [lyst/lightfm](https://github.com/lyst/lightfm) - A Python implementation of LightFM, a hybrid recommendation algorithm.
* [sktime/pytorch-forecasting](https://github.com/sktime/pytorch-forecasting) - Time series forecasting with PyTorch
* [hudson-and-thames/mlfinlab](https://github.com/hudson-and-thames/mlfinlab) - MlFinLab helps portfolio managers and traders who want to leverage the power of machine learning by providing reproducible, interpretable, and easy to use tools.
* [Nixtla/statsforecast](https://github.com/Nixtla/statsforecast) - Lightning ⚡️ fast forecasting with statistical and econometric models.
* [pytorch/ignite](https://github.com/pytorch/ignite) - High-level library to help with training and evaluating neural networks in PyTorch flexibly and transparently.
* [facebookincubator/AITemplate](https://github.com/facebookincubator/AITemplate) - AITemplate is a Python framework which renders neural network into high performance CUDA/HIP C++ code. Specialized for FP16 TensorCore (NVIDIA GPU) and MatrixCore (AMD GPU) inference.
* [huggingface/autotrain-advanced](https://github.com/huggingface/autotrain-advanced) - 🤗 AutoTrain Advanced
* [IDSIA/sacred](https://github.com/IDSIA/sacred) - Sacred is a tool to help you configure, organize, log and reproduce experiments developed at IDSIA.
* [NervanaSystems/neon](https://github.com/NervanaSystems/neon) - Intel® Nervana™ reference deep learning framework committed to best performance on all hardware *(archived)*
* [Lasagne/Lasagne](https://github.com/Lasagne/Lasagne) - Lightweight library to build and train neural networks in Theano
* [yahoo/TensorFlowOnSpark](https://github.com/yahoo/TensorFlowOnSpark) - TensorFlowOnSpark brings TensorFlow programs to Apache Spark clusters.
* [PetarV-/GAT](https://github.com/PetarV-/GAT) - Graph Attention Networks (https://arxiv.org/abs/1710.10903)
* [jmschrei/pomegranate](https://github.com/jmschrei/pomegranate) - Fast, flexible and easy to use probabilistic modelling in Python.
* [tensorflow/hub](https://github.com/tensorflow/hub) - A library for transfer learning by reusing parts of TensorFlow models.
* [hmmlearn/hmmlearn](https://github.com/hmmlearn/hmmlearn) - Hidden Markov Models in Python, with scikit-learn like API
* [pgmpy/pgmpy](https://github.com/pgmpy/pgmpy) - Python Toolkit for Causal and Probabilistic Reasoning
* [Jittor/jittor](https://github.com/Jittor/jittor) - Jittor is a high-performance deep learning framework based on JIT compiling and meta-operators.
* [tslearn-team/tslearn](https://github.com/tslearn-team/tslearn) - The machine learning toolkit for time series analysis in Python
* [maciejkula/spotlight](https://github.com/maciejkula/spotlight) - Deep recommender models using PyTorch.
* [bethgelab/foolbox](https://github.com/bethgelab/foolbox) - A Python toolbox to create adversarial examples that fool neural networks in PyTorch, TensorFlow, and JAX
* [Trusted-AI/AIF360](https://github.com/Trusted-AI/AIF360) - A comprehensive set of fairness metrics for datasets and machine learning models, explanations for these metrics, and algorithms to mitigate bias in datasets and models.
* [modAL-python/modAL](https://github.com/modAL-python/modAL) - A modular active learning framework for Python
* [google/tangent](https://github.com/google/tangent) - Source-to-Source Debuggable Derivatives in Pure Python *(archived)*
* [benelot/pybullet-gym](https://github.com/benelot/pybullet-gym) - Open-source implementations of OpenAI Gym MuJoCo environments for use with the OpenAI Gym Reinforcement Learning Research Platform.
* [vpj/python_autocomplete](https://github.com/vpj/python_autocomplete) - A simple neural network for python autocompletion

### Computer Vision

* [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) - Ultralytics YOLO26, YOLO11, YOLOv8 — object detection, instance segmentation, semantic segmentation, image classification, pose estimation, object tracking
* [ageitgey/face_recognition](https://github.com/ageitgey/face_recognition) - The world's simplest facial recognition api for Python and the command line
* [roboflow/supervision](https://github.com/roboflow/supervision) - We write your reusable computer vision tools. 💜
* [JaidedAI/EasyOCR](https://github.com/JaidedAI/EasyOCR) - Ready-to-use OCR with 80+ supported languages and all popular writing scripts including Latin, Chinese, Arabic, Devanagari, Cyrillic and etc.
* [serengil/deepface](https://github.com/serengil/deepface) - A Lightweight Face Recognition and Facial Attribute Analysis (Age, Gender, Emotion and Race) Library for Python
* [lukas-blecher/LaTeX-OCR](https://github.com/lukas-blecher/LaTeX-OCR) - pix2tex: Using a ViT to convert images of equations into LaTeX code.
* [wkentaro/labelme](https://github.com/wkentaro/labelme) - Image annotation with Python. Supports polygon, rectangle, circle, line, point, and AI-assisted annotation.
* [albumentations-team/albumentations](https://github.com/albumentations-team/albumentations) - Fast and flexible image augmentation library. Paper about the library: https://www.mdpi.com/2078-2489/11/2/125 *(archived)*
* [kornia/kornia](https://github.com/kornia/kornia) - 🐍 Geometric Computer Vision Library for Spatial AI
* [voxel51/fiftyone](https://github.com/voxel51/fiftyone) - Refine high-quality datasets and visual AI models
* [bytedance/Dolphin](https://github.com/bytedance/Dolphin) - The official repo for “Dolphin: Document Image Parsing via Heterogeneous Anchor Prompting”, ACL, 2025.
* [OlafenwaMoses/ImageAI](https://github.com/OlafenwaMoses/ImageAI) - A python library built to empower developers to build applications and systems with self-contained Computer Vision capabilities
* [rbgirshick/py-faster-rcnn](https://github.com/rbgirshick/py-faster-rcnn) - Faster R-CNN (Python implementation) -- see https://github.com/ShaoqingRen/faster_rcnn for the official MATLAB version
* [mikel-brostrom/boxmot](https://github.com/mikel-brostrom/boxmot) - BoxMOT: Pluggable Python and C++ SOTA multi-object tracking modules with support for axis-aligned and oriented bounding boxes
* [1adrianb/face-alignment](https://github.com/1adrianb/face-alignment) - :fire: 2D and 3D Face alignment library build using pytorch
* [madmaze/pytesseract](https://github.com/madmaze/pytesseract) - A Python wrapper for Google Tesseract
* [idealo/imagededup](https://github.com/idealo/imagededup) - 😎 Finding duplicate images made easy!
* [cchen156/Learning-to-See-in-the-Dark](https://github.com/cchen156/Learning-to-See-in-the-Dark) - Learning to See in the Dark. CVPR 2018
* [karpathy/neuraltalk](https://github.com/karpathy/neuraltalk) - NeuralTalk is a Python+numpy project for learning Multimodal Recurrent Neural Networks that describe images with sentences.
* [obss/sahi](https://github.com/obss/sahi) - Framework agnostic sliced/tiled inference + interactive ui + error analysis plots
* [opencv/opencv-python](https://github.com/opencv/opencv-python) - Automated CI toolchain to produce precompiled opencv-python, opencv-python-headless, opencv-contrib-python and opencv-contrib-python-headless packages.
* [zuruoke/watermark-removal](https://github.com/zuruoke/watermark-removal) - a machine learning image inpainting task that instinctively removes watermarks from image indistinguishable from the ground truth image
* [mdbloice/Augmentor](https://github.com/mdbloice/Augmentor) - Image augmentation library in Python for machine learning.
* [yanx27/Pointnet_Pointnet2_pytorch](https://github.com/yanx27/Pointnet_Pointnet2_pytorch) - PointNet and PointNet++ implemented by pytorch (pure python) and on ModelNet, ShapeNet and S3DIS.
* [kenshohara/3D-ResNets-PyTorch](https://github.com/kenshohara/3D-ResNets-PyTorch) - 3D ResNets for Action Recognition (CVPR 2018)
* [lightly-ai/lightly](https://github.com/lightly-ai/lightly) - A python library for self-supervised learning on images.
* [mapillary/OpenSfM](https://github.com/mapillary/OpenSfM) - Open source Structure-from-Motion pipeline
* [cleardusk/3DDFA](https://github.com/cleardusk/3DDFA) - The PyTorch improved version of TPAMI 2017 paper: Face Alignment in Full Pose Range: A 3D Total Solution.
* [podgorskiy/ALAE](https://github.com/podgorskiy/ALAE) - [CVPR2020] Adversarial Latent Autoencoders
* [nickliqian/cnn_captcha](https://github.com/nickliqian/cnn_captcha) - use cnn recognize captcha by tensorflow. 本项目针对字符型图片验证码，使用tensorflow实现卷积神经网络，进行验证码识别。
* [tryolabs/norfair](https://github.com/tryolabs/norfair) - Lightweight Python library for adding real-time multi-object tracking to any detector.
* [andersbll/neural_artistic_style](https://github.com/andersbll/neural_artistic_style) - Neural Artistic Style in Python
* [ITCoders/Human-detection-and-Tracking](https://github.com/ITCoders/Human-detection-and-Tracking) - Human-detection-and-Tracking

### Natural Language Processing

* [fighting41love/funNLP](https://github.com/fighting41love/funNLP) - 中英文敏感词、语言检测、中外手机/电话归属地/运营商查询、名字推断性别、手机号抽取、身份证抽取、邮箱抽取、中日文人名库、中文缩写库、拆字词典、词汇情感值、停用词、反动词表、暴恐词表、繁简体转换、英文模拟中文发音、汪峰歌词生成器、职业名称词库、同义词库、反义词库、否定词库、汽车品牌词库、汽车零件词库、连续英文切割、各种中文词向量、公司名字大全、古诗词库、IT词库、财经词库、成语词库、地名词库、历史名人词库、诗词词库、医学词库、饮食词库、法律词库、汽车词库、动物词库、中文聊天语料、中文谣言数据、百度中文问答数据集、句子相似度匹配算法集合、bert资源、文本生成&摘要相关工具、cocoNLP信息抽取工具、国内电话号码正则匹配、清华大学XLORE:中英文跨语言百科知识图谱、清华大学人工智能技术系列报告、自然语言生成、NLU太难了系列、自动对联数据及机器人、用户名黑名单列表、罪名法务名词及分类模型、微信公众号语料、cs224n深度学习自然语言处理课程、中文手写汉字识别、中文自然语言处理 语料/数据集、变量命名神器、分词语料库+代码、任务型对话英文数据集、ASR 语音数据集 + 基于深度学习的中文语音识别系统、笑声检测器、Microsoft多语言数字/单位/如日期时间识别包、中华新华字典数据库及api(包括常用歇后语、成语、词语和汉字)、文档图谱自动生成、SpaCy 中文模型、Common Voice语音识别数据集新版、神经网络关系抽取、基于bert的命名实体识别、关键词(Keyphrase)抽取包pke、基于医疗领域知识图谱的问答系统、基于依存句法与语义角色标注的事件三元组抽取、依存句法分析4万句高质量标注数据、cnocr：用来做中文OCR的Python3包、中文人物关系知识图谱项目、中文nlp竞赛项目及代码汇总、中文字符数据、speech-aligner: 从“人声语音”及其“语言文本”产生音素级别时间对齐标注的工具、AmpliGraph: 知识图谱表示学习(Python)库：知识图谱概念链接预测、Scattertext 文本可视化(python)、语言/知识表示工具：BERT & ERNIE、中文对比英文自然语言处理NLP的区别综述、Synonyms中文近义词工具包、HarvestText领域自适应文本挖掘工具（新词发现-情感分析-实体链接等）、word2word：(Python)方便易用的多语言词-词对集：62种语言/3,564个多语言对、语音识别语料生成工具：从具有音频/字幕的在线视频创建自动语音识别(ASR)语料库、构建医疗实体识别的模型（包含词典和语料标注）、单文档非监督的关键词抽取、Kashgari中使用gpt-2语言模型、开源的金融投资数据提取工具、文本自动摘要库TextTeaser: 仅支持英文、人民日报语料处理工具集、一些关于自然语言的基本模型、基于14W歌曲知识库的问答尝试--功能包括歌词接龙and已知歌词找歌曲以及歌曲歌手歌词三角关系的问答、基于Siamese bilstm模型的相似句子判定模型并提供训练数据集和测试数据集、用Transformer编解码模型实现的根据Hacker News文章标题自动生成评论、用BERT进行序列标记和文本分类的模板代码、LitBank：NLP数据集——支持自然语言处理和计算人文学科任务的100部带标记英文小说语料、百度开源的基准信息抽取系统、虚假新闻数据集、Facebook: LAMA语言模型分析，提供Transformer-XL/BERT/ELMo/GPT预训练语言模型的统一访问接口、CommonsenseQA：面向常识的英文QA挑战、中文知识图谱资料、数据及工具、各大公司内部里大牛分享的技术文档 PDF 或者 PPT、自然语言生成SQL语句（英文）、中文NLP数据增强（EDA）工具、英文NLP数据增强工具 、基于医药知识图谱的智能问答系统、京东商品知识图谱、基于mongodb存储的军事领域知识图谱问答项目、基于远监督的中文关系抽取、语音情感分析、中文ULMFiT-情感分析-文本分类-语料及模型、一个拍照做题程序、世界各国大规模人名库、一个利用有趣中文语料库 qingyun 训练出来的中文聊天机器人、中文聊天机器人seqGAN、省市区镇行政区划数据带拼音标注、教育行业新闻语料库包含自动文摘功能、开放了对话机器人-知识图谱-语义理解-自然语言处理工具及数据、中文知识图谱：基于百度百科中文页面-抽取三元组信息-构建中文知识图谱、masr: 中文语音识别-提供预训练模型-高识别率、Python音频数据增广库、中文全词覆盖BERT及两份阅读理解数据、ConvLab：开源多域端到端对话系统平台、中文自然语言处理数据集、基于最新版本rasa搭建的对话系统、基于TensorFlow和BERT的管道式实体及关系抽取、一个小型的证券知识图谱/知识库、复盘所有NLP比赛的TOP方案、OpenCLaP：多领域开源中文预训练语言模型仓库、UER：基于不同语料+编码器+目标任务的中文预训练模型仓库、中文自然语言处理向量合集、基于金融-司法领域(兼有闲聊性质)的聊天机器人、g2pC：基于上下文的汉语读音自动标记模块、Zincbase 知识图谱构建工具包、诗歌质量评价/细粒度情感诗歌语料库、快速转化「中文数字」和「阿拉伯数字」、百度知道问答语料库、基于知识图谱的问答系统、jieba_fast 加速版的jieba、正则表达式教程、中文阅读理解数据集、基于BERT等最新语言模型的抽取式摘要提取、Python利用深度学习进行文本摘要的综合指南、知识图谱深度学习相关资料整理、维基大规模平行文本语料、StanfordNLP 0.2.0：纯Python版自然语言处理包、NeuralNLP-NeuralClassifier：腾讯开源深度学习文本分类工具、端到端的封闭域对话系统、中文命名实体识别：NeuroNER vs. BertNER、新闻事件线索抽取、2019年百度的三元组抽取比赛：“科学空间队”源码、基于依存句法的开放域文本知识三元组抽取和知识库构建、中文的GPT2训练代码、ML-NLP - 机器学习(Machine Learning)NLP面试中常考到的知识点和代码实现、nlp4han:中文自然语言处理工具集(断句/分词/词性标注/组块/句法分析/语义分析/NER/N元语法/HMM/代词消解/情感分析/拼写检查、XLM：Facebook的跨语言预训练语言模型、用基于BERT的微调和特征提取方法来进行知识图谱百度百科人物词条属性抽取、中文自然语言处理相关的开放任务-数据集-当前最佳结果、CoupletAI - 基于CNN+Bi-LSTM+Attention 的自动对对联系统、抽象知识图谱、MiningZhiDaoQACorpus - 580万百度知道问答数据挖掘项目、brat rapid annotation tool: 序列标注工具、大规模中文知识图谱数据：1.4亿实体、数据增强在机器翻译及其他nlp任务中的应用及效果、allennlp阅读理解:支持多种数据和模型、PDF表格数据提取工具 、 Graphbrain：AI开源软件库和科研工具，目的是促进自动意义提取和文本理解以及知识的探索和推断、简历自动筛选系统、基于命名实体识别的简历自动摘要、中文语言理解测评基准，包括代表性的数据集&基准模型&语料库&排行榜、树洞 OCR 文字识别 、从包含表格的扫描图片中识别表格和文字、语声迁移、Python口语自然语言处理工具集(英文)、 similarity：相似度计算工具包，java编写、海量中文预训练ALBERT模型 、Transformers 2.0 、基于大规模音频数据集Audioset的音频增强 、Poplar：网页版自然语言标注工具、图片文字去除，可用于漫画翻译 、186种语言的数字叫法库、Amazon发布基于知识的人-人开放领域对话数据集 、中文文本纠错模块代码、繁简体转换 、 Python实现的多种文本可读性评价指标、类似于人名/地名/组织机构名的命名体识别数据集 、东南大学《知识图谱》研究生课程(资料)、. 英文拼写检查库 、 wwsearch是企业微信后台自研的全文检索引擎、CHAMELEON：深度学习新闻推荐系统元架构 、 8篇论文梳理BERT相关模型进展与反思、DocSearch：免费文档搜索引擎、 LIDA：轻量交互式对话标注工具 、aili - the fastest in-memory index in the East 东半球最快并发索引 、知识图谱车音工作项目、自然语言生成资源大全 、中日韩分词库mecab的Python接口库、中文文本摘要/关键词提取、汉字字符特征提取器 (featurizer)，提取汉字的特征（发音特征、字形特征）用做深度学习的特征、中文生成任务基准测评 、中文缩写数据集、中文任务基准测评 - 代表性的数据集-基准(预训练)模型-语料库-baseline-工具包-排行榜、PySS3：面向可解释AI的SS3文本分类器机器可视化工具 、中文NLP数据集列表、COPE - 格律诗编辑程序、doccano：基于网页的开源协同多语言文本标注工具 、PreNLP：自然语言预处理库、简单的简历解析器，用来从简历中提取关键信息、用于中文闲聊的GPT2模型：GPT2-chitchat、基于检索聊天机器人多轮响应选择相关资源列表(Leaderboards、Datasets、Papers)、(Colab)抽象文本摘要实现集锦(教程 、词语拼音数据、高效模糊搜索工具、NLP数据增广资源集、微软对话机器人框架 、 GitHub Typo Corpus：大规模GitHub多语言拼写错误/语法错误数据集、TextCluster：短文本聚类预处理模块 Short text cluster、面向语音识别的中文文本规范化、BLINK：最先进的实体链接库、BertPunc：基于BERT的最先进标点修复模型、Tokenizer：快速、可定制的文本词条化库、中文语言理解测评基准，包括代表性的数据集、基准(预训练)模型、语料库、排行榜、spaCy 医学文本挖掘与信息提取 、 NLP任务示例项目代码集、 python拼写检查库、chatbot-list - 行业内关于智能客服、聊天机器人的应用和架构、算法分享和介绍、语音质量评价指标(MOSNet, BSSEval, STOI, PESQ, SRMR)、 用138GB语料训练的法文RoBERTa预训练语言模型 、BERT-NER-Pytorch：三种不同模式的BERT中文NER实验、无道词典 - 有道词典的命令行版本，支持英汉互查和在线查询、2019年NLP亮点回顾、 Chinese medical dialogue data 中文医疗对话数据集 、最好的汉字数字(中文数字)-阿拉伯数字转换工具、 基于百科知识库的中文词语多词义/义项获取与特定句子词语语义消歧、awesome-nlp-sentiment-analysis - 情感分析、情绪原因识别、评价对象和评价词抽取、LineFlow：面向所有深度学习框架的NLP数据高效加载器、中文医学NLP公开资源整理 、MedQuAD：(英文)医学问答数据集、将自然语言数字串解析转换为整数和浮点数、Transfer Learning in Natural Language Processing (NLP) 、面向语音识别的中文/英文发音辞典、Tokenizers：注重性能与多功能性的最先进分词器、CLUENER 细粒度命名实体识别 Fine Grained Named Entity Recognition、 基于BERT的中文命名实体识别、中文谣言数据库、NLP数据集/基准任务大列表、nlp相关的一些论文及代码, 包括主题模型、词向量(Word Embedding)、命名实体识别(NER)、文本分类(Text Classificatin)、文本生成(Text Generation)、文本相似性(Text Similarity)计算等，涉及到各种与nlp相关的算法，基于keras和tensorflow 、Python文本挖掘/NLP实战示例、 Blackstone：面向非结构化法律文本的spaCy pipeline和NLP模型通过同义词替换实现文本“变脸” 、中文 预训练 ELECTREA 模型: 基于对抗学习 pretrain Chinese Model 、albert-chinese-ner - 用预训练语言模型ALBERT做中文NER 、基于GPT2的特定主题文本生成/文本增广、开源预训练语言模型合集、多语言句向量包、编码、标记和实现：一种可控高效的文本生成方法、 英文脏话大列表 、attnvis：GPT2、BERT等transformer语言模型注意力交互可视化、CoVoST：Facebook发布的多语种语音-文本翻译语料库，包括11种语言(法语、德语、荷兰语、俄语、西班牙语、意大利语、土耳其语、波斯语、瑞典语、蒙古语和中文)的语音、文字转录及英文译文、Jiagu自然语言处理工具 - 以BiLSTM等模型为基础，提供知识图谱关系抽取 中文分词 词性标注 命名实体识别 情感分析 新词发现 关键词 文本摘要 文本聚类等功能、用unet实现对文档表格的自动检测，表格重建、NLP事件提取文献资源列表 、 金融领域自然语言处理研究资源大列表、CLUEDatasetSearch - 中英文NLP数据集：搜索所有中文NLP数据集，附常用英文NLP数据集 、medical_NER - 中文医学知识图谱命名实体识别 、(哈佛)讲因果推理的免费书、知识图谱相关学习资料/数据集/工具资源大列表、Forte：灵活强大的自然语言处理pipeline工具集 、Python字符串相似性算法库、PyLaia：面向手写文档分析的深度学习工具包、TextFooler：针对文本分类/推理的对抗文本生成模块、Haystack：灵活、强大的可扩展问答(QA)框架、中文关键短语抽取工具
* [CorentinJ/Real-Time-Voice-Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning) - Clone a voice in 5 seconds to generate arbitrary speech in real-time
* [coqui-ai/TTS](https://github.com/coqui-ai/TTS) - 🐸💬 - a deep learning toolkit for Text-to-Speech, battle-tested in research and production
* [2noise/ChatTTS](https://github.com/2noise/ChatTTS) - A generative speech model for daily dialogue.
* [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM) - VoxCPM2: Tokenizer-Free TTS for Multilingual Speech Generation, Creative Voice Design, and True-to-Life Cloning
* [explosion/spaCy](https://github.com/explosion/spaCy) - 💫 Industrial-strength Natural Language Processing (NLP) in Python
* [facebookresearch/fairseq](https://github.com/facebookresearch/fairseq) - Facebook AI Research Sequence-to-Sequence Toolkit written in Python. *(archived)*
* [QwenAudio/CosyVoice](https://github.com/QwenAudio/CosyVoice) - Multi-lingual large voice generation model, providing inference, training and deployment full-stack ability.
* [piskvorky/gensim](https://github.com/piskvorky/gensim) - Topic Modelling for Humans
* [nltk/nltk](https://github.com/nltk/nltk) - NLTK Source
* [gunthercox/ChatterBot](https://github.com/gunthercox/ChatterBot) - ChatterBot is a machine learning, conversational dialog engine for creating chat bots
* [huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech) - Build voice agents with open-source models
* [allenai/allennlp](https://github.com/allenai/allennlp) - An open-source NLP research library, built on PyTorch. *(archived)*
* [rany2/edge-tts](https://github.com/rany2/edge-tts) - Use Microsoft Edge's online text-to-speech service from Python WITHOUT needing Microsoft Edge or Windows or an API key
* [QuentinFuxa/WhisperLiveKit](https://github.com/QuentinFuxa/WhisperLiveKit) - Real-time, local speech-to-text with streaming ASR, speaker diarization, translation, and OpenAI/Deepgram-compatible APIs.
* [KoljaB/RealtimeSTT](https://github.com/KoljaB/RealtimeSTT) - A robust, efficient, low-latency speech-to-text library with advanced voice activity detection, wake word activation and instant transcription.
* [sloria/TextBlob](https://github.com/sloria/TextBlob) - Simple, Pythonic, text processing--Sentiment analysis, part-of-speech tagging, noun phrase extraction, translation, and more.
* [QwenAudio/SenseVoice](https://github.com/QwenAudio/SenseVoice) - Open-source SenseVoiceSmall model for Mandarin, Cantonese, English, Japanese, and Korean ASR, language ID, emotion recognition, and audio event detection.
* [Uberi/speech_recognition](https://github.com/Uberi/speech_recognition) - Speech recognition module for Python, supporting several engines and APIs, online and offline.
* [clips/pattern](https://github.com/clips/pattern) - Web mining module for Python, with tools for scraping, natural language processing, machine learning, network analysis and visualization.
* [netease-youdao/EmotiVoice](https://github.com/netease-youdao/EmotiVoice) - EmotiVoice 😊: a Multi-Voice and Prompt-Controlled TTS Engine
* [nl8590687/ASRT_SpeechRecognition](https://github.com/nl8590687/ASRT_SpeechRecognition) - A Deep-Learning-Based Chinese Speech Recognition System 基于深度学习的中文语音识别系统
* [stanfordnlp/stanza](https://github.com/stanfordnlp/stanza) - Stanford NLP Python library for tokenization, sentence segmentation, NER, and parsing of many human languages
* [lancopku/pkuseg-python](https://github.com/lancopku/pkuseg-python) - pkuseg多领域中文分词工具; The pkuseg toolkit for multi-domain Chinese word segmentation
* [isnowfy/snownlp](https://github.com/isnowfy/snownlp) - Python library for processing Chinese text
* [argosopentech/argos-translate](https://github.com/argosopentech/argos-translate) - Open-source offline translation library written in Python
* [maziyarpanahi/openmed](https://github.com/maziyarpanahi/openmed) - Local-first healthcare AI: clinical NER & HIPAA PII de-identification that runs 100% on-device. 2,200+ medical models, 21 languages, Apple MLX + Python, no cloud, no patient data leaving your network. Apache-2.0
* [minimaxir/textgenrnn](https://github.com/minimaxir/textgenrnn) - Easily train your own text-generating neural network of any size and complexity on any text dataset with a few lines of code.
* [ssut/py-googletrans](https://github.com/ssut/py-googletrans) - (unofficial) Googletrans: Free and Unlimited Google translate API for Python. Translates totally free of charge.
* [snipsco/snips-nlu](https://github.com/snipsco/snips-nlu) - Snips Python library to extract meaning from text
* [dongrixinyu/JioNLP](https://github.com/dongrixinyu/JioNLP) - 中文 NLP 预处理、解析工具包，准确、高效、易用 A Chinese NLP Preprocessing & Parsing Package www.jionlp.com
* [sherjilozair/char-rnn-tensorflow](https://github.com/sherjilozair/char-rnn-tensorflow) - Multi-layer Recurrent Neural Networks (LSTM, RNN) for character-level language models in Python using Tensorflow
* [jameslyons/python_speech_features](https://github.com/jameslyons/python_speech_features) - This library provides common speech features for ASR including MFCCs and filterbank energies.
* [asyml/texar](https://github.com/asyml/texar) - Toolkit for Machine Learning, Natural Language Processing, and Text Generation, in TensorFlow. This is part of the CASL project: http://casl-project.ai/
* [r9y9/wavenet_vocoder](https://github.com/r9y9/wavenet_vocoder) - WaveNet vocoder
* [Rayhane-mamah/Tacotron-2](https://github.com/Rayhane-mamah/Tacotron-2) - DeepMind's Tacotron-2 Tensorflow implementation
* [chiphuyen/lazynlp](https://github.com/chiphuyen/lazynlp) - Library to scrape and clean web pages to create massive datasets.
* [PetrochukM/PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP) - Basic Utilities for PyTorch Natural Language Processing (NLP) *(archived)*
* [tensorlayer/seq2seq-chatbot](https://github.com/tensorlayer/seq2seq-chatbot) - Chatbot in 200 lines of code using TensorLayer
* [SlapBot/stephanie-va](https://github.com/SlapBot/stephanie-va) - Stephanie is an open-source platform built specifically for voice-controlled applications as well as to automate daily tasks imitating much of an virtual assistant's work.

### Data Science and Analytics

* [apache/superset](https://github.com/apache/superset) - Apache Superset is a Data Visualization and Data Exploration Platform
* [OpenBB-finance/OpenBB](https://github.com/OpenBB-finance/OpenBB) - Open Data Platform for analysts, quants and AI agents.
* [pathwaycom/pathway](https://github.com/pathwaycom/pathway) - Python ETL framework for stream processing, real-time analytics, LLM pipelines, and RAG.
* [pandas-dev/pandas](https://github.com/pandas-dev/pandas) - Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data.frame objects, statistical functions, and much more
* [microsoft/qlib](https://github.com/microsoft/qlib) - Qlib is an AI-oriented Quant investment platform that aims to use AI tech to empower Quant Research, from exploring ideas to implementing productions. Qlib supports diverse ML modeling paradigms, including supervised learning, market dynamics modeling, and RL, and is now equipped with https://github.com/microsoft/RD-Agent to automate R&D process.
* [apache/airflow](https://github.com/apache/airflow) - Apache Airflow - A platform to programmatically author, schedule, and monitor workflows
* [streamlit/streamlit](https://github.com/streamlit/streamlit) - Streamlit — A faster way to build and share data apps.
* [gradio-app/gradio](https://github.com/gradio-app/gradio) - Build and share delightful machine learning apps, all in Python. 🌟 Star to support our work!
* [PostHog/posthog](https://github.com/PostHog/posthog) - :hedgehog: PostHog is the leading platform for building self-driving products. Our developer tools – AI observability, analytics, session replay, flags, experiments, error tracking, logs, and more – capture all the context agents need to diagnose problems, uncover opportunities, and ship fixes. Steer it all from Slack, web, desktop, or the MCP.
* [getredash/redash](https://github.com/getredash/redash) - Make Your Company Data Driven. Connect to any data source, easily visualize, dashboard and share your data.
* [plotly/dash](https://github.com/plotly/dash) - Data Apps & Dashboards for Python. No JavaScript Required.
* [sinaptik-ai/pandas-ai](https://github.com/sinaptik-ai/pandas-ai) - Chat with your database or your datalake (SQL, CSV, parquet). PandasAI makes data analysis conversational using LLMs and RAG.
* [PrefectHQ/prefect](https://github.com/PrefectHQ/prefect) - Prefect is a workflow orchestration framework for building resilient data pipelines in Python.
* [matplotlib/matplotlib](https://github.com/matplotlib/matplotlib) - matplotlib: plotting with Python
* [marimo-team/marimo](https://github.com/marimo-team/marimo) - A reactive notebook for Python — run reproducible experiments, query with SQL, execute as a script, deploy as an app, and version with git. Stored as pure Python. All in a modern, AI-native editor.
* [airbytehq/airbyte](https://github.com/airbytehq/airbyte) - Open-source data movement for ELT pipelines and AI agents — from APIs, databases & files to warehouses, lakes, and AI applications. Both self-hosted and Cloud.
* [bokeh/bokeh](https://github.com/bokeh/bokeh) - Interactive Data Visualization in the browser, from Python
* [facebook/prophet](https://github.com/facebook/prophet) - Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth.
* [Avaiga/taipy](https://github.com/Avaiga/taipy) - Turns Data and AI algorithms into production-ready web applications in no time.
* [spotify/luigi](https://github.com/spotify/luigi) - Luigi is a Python module that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization etc. It also comes with Hadoop support built in.
* [plotly/plotly.py](https://github.com/plotly/plotly.py) - The interactive graphing library for Python :sparkles:
* [ipython/ipython](https://github.com/ipython/ipython) - Official repository for IPython itself. Other repos in the IPython organization contain things like the website, documentation builds, etc.
* [dagster-io/dagster](https://github.com/dagster-io/dagster) - An orchestration platform for the development, production, and observation of data assets.
* [treeverse/dvc](https://github.com/treeverse/dvc) - 🦉 Data Versioning and ML Experiments
* [pyecharts/pyecharts](https://github.com/pyecharts/pyecharts) - 🎨 Python Echarts Plotting Library
* [mwaskom/seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization in Python
* [Data-Centric-AI-Community/fg-data-profiling](https://github.com/Data-Centric-AI-Community/fg-data-profiling) - 1 Line of code data quality profiling & exploratory data analysis for Pandas and Spark DataFrames.
* [cleanlab/cleanlab](https://github.com/cleanlab/cleanlab) - Cleanlab's open-source library is the standard data-centric AI package for data quality and machine learning with messy, real-world data and labels.
* [simonw/datasette](https://github.com/simonw/datasette) - An open source multi-tool for exploring and publishing data
* [wandb/wandb](https://github.com/wandb/wandb) - The AI developer platform. Use Weights & Biases to train and fine-tune models, and manage models from experimentation to production.
* [kedro-org/kedro](https://github.com/kedro-org/kedro) - Kedro is a toolbox for production-ready data science. It uses software engineering best practices to help you create data engineering and data science pipelines that are reproducible, maintainable, and modular.
* [doccano/doccano](https://github.com/doccano/doccano) - Open source annotation tool for machine learning practitioners.
* [amueller/word_cloud](https://github.com/amueller/word_cloud) - A little word cloud generator in Python
* [vega/altair](https://github.com/vega/altair) - Declarative visualization library for Python
* [modin-project/modin](https://github.com/modin-project/modin) - Modin: Scale your Pandas workflows by changing a single line of code
* [Netflix/metaflow](https://github.com/Netflix/metaflow) - Build, Manage and Deploy AI/ML Systems
* [garrettj403/SciencePlots](https://github.com/garrettj403/SciencePlots) - Matplotlib styles for scientific plotting
* [mage-ai/mage-ai](https://github.com/mage-ai/mage-ai) - 🧙 Build, run, and manage data pipelines for integrating and transforming data.
* [vaexio/vaex](https://github.com/vaexio/vaex) - Out-of-Core hybrid Apache Arrow/NumPy DataFrame for Python, ML, visualization and exploration of big tabular data at a billion rows per second 🚀
* [jupyterhub/jupyterhub](https://github.com/jupyterhub/jupyterhub) - Multi-user server for Jupyter notebooks
* [py-why/dowhy](https://github.com/py-why/dowhy) - DoWhy is a Python library for causal inference that supports explicit modeling and testing of causal assumptions. DoWhy is based on a unified language for causal inference, combining causal graphical models and potential outcomes frameworks.
* [alteryx/featuretools](https://github.com/alteryx/featuretools) - An open source python library for automated feature engineering
* [python-visualization/folium](https://github.com/python-visualization/folium) - Python Data. Leaflet.js Maps.
* [feast-dev/feast](https://github.com/feast-dev/feast) - The Open Source Feature Store for AI/ML
* [jupytext/jupytext](https://github.com/jupytext/jupytext) - Jupyter Notebooks as Markdown Documents, Julia, Python or R scripts
* [ibis-project/ibis](https://github.com/ibis-project/ibis) - the portable Python dataframe library
* [nteract/papermill](https://github.com/nteract/papermill) - 📚 Parameterize, execute, and analyze notebooks
* [dlt-hub/dlt](https://github.com/dlt-hub/dlt) - data load tool (dlt) is an open source Python library that makes data loading easy 🛠️
* [holoviz/panel](https://github.com/holoviz/panel) - Panel: The powerful data exploration & web app framework for Python
* [biolab/orange3](https://github.com/biolab/orange3) - 🍊 :bar_chart: :bulb: Orange: Interactive data analysis
* [BIT-DataLab/Edit-Banana](https://github.com/BIT-DataLab/Edit-Banana) - Edit Banana: A framework for converting statistical formats into editable.
* [lux-org/lux](https://github.com/lux-org/lux) - Automatically visualize your pandas dataframe via a single print! 📊 💡
* [theOehrly/Fast-F1](https://github.com/theOehrly/Fast-F1) - FastF1 is a python package for accessing and analyzing Formula 1 results, schedules, timing data and telemetry
* [JerBouma/FinanceToolkit](https://github.com/JerBouma/FinanceToolkit) - Transparent and Efficient Financial Analysis
* [geopandas/geopandas](https://github.com/geopandas/geopandas) - Python tools for geographic data
* [has2k1/plotnine](https://github.com/has2k1/plotnine) - A Grammar of Graphics for Python
* [pyqtgraph/pyqtgraph](https://github.com/pyqtgraph/pyqtgraph) - Fast data visualization and GUI tools for scientific / engineering applications
* [DistrictDataLabs/yellowbrick](https://github.com/DistrictDataLabs/yellowbrick) - Visual analysis and diagnostic tools to facilitate machine learning model selection.
* [mljar/mercury](https://github.com/mljar/mercury) - Impress your boss and turn a Jupyter notebook into a beautiful, shareable web app — no callbacks, no frontend, no rewrite.
* [StructuredLabs/preswald](https://github.com/StructuredLabs/preswald) - Preswald is a WASM packager for Python-based interactive data apps: bundle full complex data workflows, particularly visualizations, into single files, runnable completely in-browser, using Pyodide, DuckDB, Pandas, and Plotly, Matplotlib, etc. Build dashboards, reports, and notebooks that run offline, load fast, and share like a document.
* [ResidentMario/missingno](https://github.com/ResidentMario/missingno) - Missing data visualization module for Python.
* [pydata/xarray](https://github.com/pydata/xarray) - N-D labeled arrays and datasets in Python
* [stumpy-dev/stumpy](https://github.com/stumpy-dev/stumpy) - STUMPY is a powerful and scalable Python library for modern time series analysis
* [orchest/orchest](https://github.com/orchest/orchest) - Build data pipelines, the easy way 🛠️ *(archived)*
* [aws/aws-sdk-pandas](https://github.com/aws/aws-sdk-pandas) - pandas on AWS - Easy integration with Athena, Glue, Redshift, Timestream, Neptune, OpenSearch, QuickSight, Chime, CloudWatchLogs, DynamoDB, EMR, SecretManager, PostgreSQL, MySQL, SQLServer and S3 (Parquet, CSV, JSON and EXCEL).
* [yhat/ggpy](https://github.com/yhat/ggpy) - ggplot port for python *(archived)*
* [spotify/chartify](https://github.com/spotify/chartify) - Python library that makes it easy for data scientists to create charts.
* [pydata/pandas-datareader](https://github.com/pydata/pandas-datareader) - Extract data from a wide range of Internet sources into a pandas DataFrame.
* [blockchain-etl/ethereum-etl](https://github.com/blockchain-etl/ethereum-etl) - Python scripts for ETL (extract, transform and load) jobs for Ethereum blocks, transactions, ERC20 / ERC721 tokens, transfers, receipts, logs, contracts, internal transactions. Data is available in Google BigQuery https://goo.gl/oY5BCQ
* [fbdesignpro/sweetviz](https://github.com/fbdesignpro/sweetviz) - Visualize and compare datasets, target values and associations, with one line of code.
* [mars-project/mars](https://github.com/mars-project/mars) - Mars is a tensor-based unified framework for large-scale data computation which scales numpy, pandas, scikit-learn and Python functions.
* [mito-ds/mito](https://github.com/mito-ds/mito) - Jupyter extensions that help you write code faster: Context aware AI Chat, Autocomplete, and Spreadsheet
* [nschloe/tikzplotlib](https://github.com/nschloe/tikzplotlib) - :bar_chart: Save matplotlib figures as TikZ/PGFplots for smooth integration into LaTeX.
* [justinzm/gopup](https://github.com/justinzm/gopup) - 数据接口：百度、谷歌、头条、微博指数,宏观数据，利率数据，货币汇率，千里马、独角兽公司，新闻联播文字稿，影视票房数据，高校名单，疫情数据…
* [peerchemist/finta](https://github.com/peerchemist/finta) - Common financial technical indicators implemented in Pandas. *(archived)*
* [wrobstory/vincent](https://github.com/wrobstory/vincent) - A Python to Vega translator *(archived)*
* [eliasdabbas/advertools](https://github.com/eliasdabbas/advertools) - advertools - online marketing productivity and analysis tools
* [vizzuhq/ipyvizzu](https://github.com/vizzuhq/ipyvizzu) - Build animated charts in Jupyter Notebook and similar environments with a simple Python syntax.

## Networking and Distributed

### Networking

* [netbox-community/netbox](https://github.com/netbox-community/netbox) - The premier source of truth powering network automation. Open source under Apache 2. Try NetBox Cloud free: https://netboxlabs.com/products/free-netbox-cloud/
* [fortra/impacket](https://github.com/fortra/impacket) - Impacket is a collection of Python classes for working with network protocols.
* [sivel/speedtest-cli](https://github.com/sivel/speedtest-cli) - Command line interface for testing internet bandwidth using speedtest.net *(archived)*
* [secdev/scapy](https://github.com/secdev/scapy) - Scapy: the Python-based interactive packet manipulation program & library.
* [paramiko/paramiko](https://github.com/paramiko/paramiko) - The leading native Python SSHv2 protocol library.
* [seemoo-lab/opendrop](https://github.com/seemoo-lab/opendrop) - An open Apple AirDrop implementation written in Python
* [shadowsocksr-backup/shadowsocksr](https://github.com/shadowsocksr-backup/shadowsocksr) - Python port of ShadowsocksR
* [twisted/twisted](https://github.com/twisted/twisted) - Event-driven networking engine written in Python.
* [mininet/mininet](https://github.com/mininet/mininet) - Emulator for rapid prototyping of Software Defined Networks
* [python-websockets/websockets](https://github.com/python-websockets/websockets) - Library for building WebSocket servers and clients in Python
* [miguelgrinberg/Flask-SocketIO](https://github.com/miguelgrinberg/Flask-SocketIO) - Socket.IO integration for Flask applications.
* [aiortc/aiortc](https://github.com/aiortc/aiortc) - WebRTC and ORTC implementation for Python using asyncio
* [blinker-iot/blinker-py](https://github.com/blinker-iot/blinker-py) - Blinker python library for hardware. Works with Raspberry Pi, Banan Pi, Linux devices
* [miguelgrinberg/python-socketio](https://github.com/miguelgrinberg/python-socketio) - Python Socket.IO server and client
* [ab77/netflix-proxy](https://github.com/ab77/netflix-proxy) - Smart DNS proxy to watch Netflix
* [feross/SpoofMAC](https://github.com/feross/SpoofMAC) - :briefcase: Change your MAC address for debugging
* [crossbario/autobahn-python](https://github.com/crossbario/autobahn-python) - WebSocket and WAMP in Python for Twisted and asyncio

### Cloud and Infrastructure

* [ansible/ansible](https://github.com/ansible/ansible) - Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy and maintain. Automate everything from code deployment to network configuration to cloud management, in a language that approaches plain English, using SSH, with no agents to install on remote systems. https://docs.ansible.com.
* [localstack/localstack](https://github.com/localstack/localstack) - 💻 A fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline *(archived)*
* [saltstack/salt](https://github.com/saltstack/salt) - Software to automate the management and configuration of infrastructure and applications at scale.
* [ansible/awx](https://github.com/ansible/awx) - AWX provides a web-based user interface, REST API, and task engine built on top of Ansible. It is one of the upstream projects for Red Hat Ansible Automation Platform.
* [meolu/walle-web](https://github.com/meolu/walle-web) - walle - 瓦力 Devops开源项目代码部署平台
* [Miserlou/Zappa](https://github.com/Miserlou/Zappa) - Serverless Python
* [aws/chalice](https://github.com/aws/chalice) - Python Serverless Microframework for AWS
* [boto/boto3](https://github.com/boto/boto3) - Boto3, an AWS SDK for Python
* [googleapis/google-api-python-client](https://github.com/googleapis/google-api-python-client) - 🐍 The official Python client library for Google's discovery based APIs.
* [jupyter/docker-stacks](https://github.com/jupyter/docker-stacks) - Ready-to-run Docker images containing Jupyter applications
* [ChristianLempa/boilerplates](https://github.com/ChristianLempa/boilerplates) - Create reusable templates and turn them into configurable workloads for homelabs and self-hosted infrastructure. Free and Open-Source.
* [kubernetes-client/python](https://github.com/kubernetes-client/python) - Official Python client library for kubernetes
* [docker/docker-py](https://github.com/docker/docker-py) - A Python library for the Docker Engine API
* [aws/aws-sam-cli](https://github.com/aws/aws-sam-cli) - CLI tool to build, test, debug, and deploy Serverless applications using AWS SAM
* [piku/piku](https://github.com/piku/piku) - The tiniest PaaS you've ever seen. Piku allows you to do git push deployments to your own servers.
* [boto/boto](https://github.com/boto/boto) - For the latest version of boto, see https://github.com/boto/boto3 -- Python interface to Amazon Web Services *(archived)*
* [pyinfra-dev/pyinfra](https://github.com/pyinfra-dev/pyinfra) - 🔧 pyinfra turns Python code into shell commands and runs them on your servers. Execute ad-hoc commands and write declarative operations. Target SSH servers, local machine and Docker containers. Fast and scales from one server to thousands.
* [Azure/azure-sdk-for-python](https://github.com/Azure/azure-sdk-for-python) - This repository is for active development of the Azure SDK for Python. For consumers of the SDK we recommend visiting our public developer docs at https://learn.microsoft.com/python/azure/ or our versioned developer docs at https://azure.github.io/azure-sdk-for-python.
* [buildbot/buildbot](https://github.com/buildbot/buildbot) - Python-based continuous integration testing framework; your pull requests are more than welcome!
* [googleapis/google-cloud-python](https://github.com/googleapis/google-cloud-python) - Google Cloud Client Libraries for Python
* [cloudtools/troposphere](https://github.com/cloudtools/troposphere) - troposphere - Python library to create AWS CloudFormation descriptions
* [hunvreus/devpush](https://github.com/hunvreus/devpush) - Like Vercel, but open source and for all languages.
* [guohongze/adminset](https://github.com/guohongze/adminset) - 自动化运维平台：CMDB、CD、DevOps、资产管理、任务编排、持续交付、系统监控、运维管理、配置管理
* [tiangolo/uwsgi-nginx-flask-docker](https://github.com/tiangolo/uwsgi-nginx-flask-docker) - Docker image with uWSGI and Nginx for Flask applications in Python running in a single container.
* [cobbler/cobbler](https://github.com/cobbler/cobbler) - Cobbler is a versatile Linux deployment server
* [dcos/dcos](https://github.com/dcos/dcos) - DC/OS - The Datacenter Operating System
* [vmware/pyvmomi](https://github.com/vmware/pyvmomi) - VMware vSphere API Python Bindings
* [couler-proj/couler](https://github.com/couler-proj/couler) - Unified Interface for Constructing and Managing Workflows on different workflow engines, such as Argo Workflows, Tekton Pipelines, and Apache Airflow.

### Monitoring and Observability

* [getsentry/sentry](https://github.com/getsentry/sentry) - Developer-first error tracking and performance monitoring
* [nicolargo/glances](https://github.com/nicolargo/glances) - Glances an Eye on your system. A top/htop alternative for GNU/Linux, BSD, macOS and Windows operating systems.
* [openreplay/openreplay](https://github.com/openreplay/openreplay) - Session replay, cobrowsing and product analytics you can self-host. Best for reproducing issues and iterating on your product.
* [keephq/keep](https://github.com/keephq/keep) - The open-source AIOps and alert management platform
* [healthchecks/healthchecks](https://github.com/healthchecks/healthchecks) - Open-source cron job and background task monitoring service, written in Python & Django
* [traceloop/openllmetry](https://github.com/traceloop/openllmetry) - Open-source observability for your GenAI or LLM application, based on OpenTelemetry
* [mher/flower](https://github.com/mher/flower) - Real-time monitor and web admin for Celery distributed task queue
* [pydantic/logfire](https://github.com/pydantic/logfire) - AI observability platform for production LLM and agent systems.
* [prometheus/client_python](https://github.com/prometheus/client_python) - Prometheus instrumentation library for Python applications
* [thp/urlwatch](https://github.com/thp/urlwatch) - Watch (parts of) webpages and get notified when something changes via e-mail, on your phone or via other means. Highly configurable.
* [huggingface/knockknock](https://github.com/huggingface/knockknock) - 🚪✊Knock Knock: Get notified when your training ends with only two additional lines of code

## User Interface

### GUI Toolkits

* [chriskiehl/Gooey](https://github.com/chriskiehl/Gooey) - Turn (almost) any Python command line program into a full GUI application with one line
* [kivy/kivy](https://github.com/kivy/kivy) - Open source UI framework written in Python, running on Windows, Linux, macOS, Android and iOS
* [flet-dev/flet](https://github.com/flet-dev/flet) - Build realtime web, mobile and desktop apps in Python only. No frontend experience required.
* [PySimpleGUI/PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) - Python GUIs for Humans! Create any GUI simple or complicated in a way that's intuitive. Launched in 2018. NEW for 2026 - the LGPL3 Version 6. Transforms tkinter, Qt, WxPython, and Remi into a simple, intuitive, and fun experience for both hobbyists and expert users.
* [TomSchimansky/CustomTkinter](https://github.com/TomSchimansky/CustomTkinter) - A modern and customizable python UI-library based on Tkinter
* [ParthJadhav/Tkinter-Designer](https://github.com/ParthJadhav/Tkinter-Designer) - An easy and fast way to create a Python GUI 🐍
* [zhiyiYo/PyQt-Fluent-Widgets](https://github.com/zhiyiYo/PyQt-Fluent-Widgets) - A fluent design widgets library based on C++ Qt/PyQt/PySide. Make Qt Great Again.
* [python-eel/Eel](https://github.com/python-eel/Eel) - A little Python library for making simple Electron-like HTML/JS GUI apps *(archived)*
* [r0x0r/pywebview](https://github.com/r0x0r/pywebview) - Build GUI for your Python program with JavaScript, HTML, and CSS
* [beeware/toga](https://github.com/beeware/toga) - A Python native, OS native GUI toolkit.
* [rawpython/remi](https://github.com/rawpython/remi) - Python REMote Interface library. Platform independent. In about 100 Kbytes, perfect for your diet.
* [flexxui/flexx](https://github.com/flexxui/flexx) - Write desktop and web apps in pure Python
* [jaredks/rumps](https://github.com/jaredks/rumps) - Ridiculously Uncomplicated macOS Python Statusbar apps

### Terminal and Console UI

* [Textualize/rich](https://github.com/Textualize/rich) - Rich is a Python library for rich text and beautiful formatting in the terminal.
* [Textualize/textual](https://github.com/Textualize/textual) - The lean application framework for Python. Build sophisticated user interfaces with a simple Python API. Run your apps in the terminal and a web browser.
* [tqdm/tqdm](https://github.com/tqdm/tqdm) - :zap: A Fast, Extensible Progress Bar for Python and CLI
* [powerline/powerline](https://github.com/powerline/powerline) - Powerline is a statusline plugin for vim, and provides statuslines and prompts for several other applications, including zsh, bash, tmux, IPython, Awesome and Qtile.
* [prompt-toolkit/python-prompt-toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) - Library for building powerful interactive command line applications in Python
* [rsalmei/alive-progress](https://github.com/rsalmei/alive-progress) - A new kind of Progress Bar, with real-time throughput, ETA, and very cool animations!
* [b-ryan/powerline-shell](https://github.com/b-ryan/powerline-shell) - A beautiful and useful prompt for your shell
* [peterbrittain/asciimatics](https://github.com/peterbrittain/asciimatics) - A cross platform package to do curses-like operations, plus higher level APIs and widgets to create text UIs and ASCII art animations
* [bchao1/bullet](https://github.com/bchao1/bullet) - 🚅 Interactive prompts made simple. Build a prompt like stacking blocks.

### Applications and End User Tools

* [yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp) - A feature-rich command-line audio/video downloader
* [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI) - The most powerful and modular diffusion model GUI, api and backend with a graph/nodes interface.
* [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) - 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow.
* [home-assistant/core](https://github.com/home-assistant/core) - :house_with_garden: Open source home automation that puts local control and privacy first.
* [sansan0/TrendRadar](https://github.com/sansan0/TrendRadar) - ⭐AI-driven public opinion & trend monitor with multi-platform aggregation, RSS, and smart alerts.🎯 告别信息过载，你的 AI 舆情监控助手与热点筛选工具！聚合多平台热点 + RSS 订阅，支持关键词精准筛选。AI 智能筛选新闻 + AI 翻译 + AI 分析简报直推手机，也支持接入 MCP 架构，赋能 AI 自然语言对话分析、情感洞察与趋势预测等。支持 Docker ，数据本地/云端自持。集成微信/飞书/钉钉/Telegram/邮件/ntfy/bark/slack 等渠道智能推送。
* [odoo/odoo](https://github.com/odoo/odoo) - Odoo. Open Source Apps To Grow Your Business.
* [freqtrade/freqtrade](https://github.com/freqtrade/freqtrade) - Free, open source crypto trading bot
* [frappe/erpnext](https://github.com/frappe/erpnext) - Free and Open Source Enterprise Resource Planning (ERP)
* [PDFMathTranslate/PDFMathTranslate](https://github.com/PDFMathTranslate/PDFMathTranslate) - [EMNLP 2025 Demo] PDF scientific paper translation with preserved formats - 基于 AI 完整保留排版的 PDF 文档全文双语翻译，支持 Google/DeepL/Ollama/OpenAI 等服务，提供 CLI/GUI/MCP/Docker/Zotero
* [searxng/searxng](https://github.com/searxng/searxng) - SearXNG is a free internet metasearch engine which aggregates results from various search services and databases. Users are neither tracked nor profiled.
* [kovidgoyal/kitty](https://github.com/kovidgoyal/kitty) - If you live in the terminal, kitty is made for you! Cross-platform, fast, feature-rich, GPU based.
* [ocrmypdf/OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) - OCRmyPDF adds an OCR text layer to scanned PDF files, allowing them to be searched
* [Fincept-Corporation/FinceptTerminal](https://github.com/Fincept-Corporation/FinceptTerminal) - FinceptTerminal is a modern finance application offering advanced market analytics, investment research, and economic data tools, designed for interactive exploration and data-driven decision-making in a user-friendly environment.
* [srbhr/Resume-Matcher](https://github.com/srbhr/Resume-Matcher) - The #1 AI Harness for Building Resumes, PDFs, Cover Letters & more, locally with 100+ LLMs support.
* [ArchiveBox/ArchiveBox](https://github.com/ArchiveBox/ArchiveBox) - 🗃 Open source self-hosted web archiving. Takes URLs/browser history/bookmarks/Pocket/Pinboard/etc., saves HTML, JS, PDFs, media, and more...
* [spotDL/spotify-downloader](https://github.com/spotDL/spotify-downloader) - Download your Spotify playlists and songs along with album art and metadata (from YouTube if a match is found).
* [zulip/zulip](https://github.com/zulip/zulip) - Zulip server and web application. Open-source team chat that helps teams stay productive and focused.
* [kovidgoyal/calibre](https://github.com/kovidgoyal/calibre) - The official source code repository for the calibre ebook manager
* [saleor/saleor](https://github.com/saleor/saleor) - Saleor Core: the high performance, composable, headless commerce API.
* [hummingbot/hummingbot](https://github.com/hummingbot/hummingbot) - Open source software that helps you create and deploy high-frequency crypto trading bots
* [leon-ai/leon](https://github.com/leon-ai/leon) - 🧠 Leon is your open-source personal assistant.
* [rendercv/rendercv](https://github.com/rendercv/rendercv) - Resume builder for academics and engineers
* [reddit-archive/reddit](https://github.com/reddit-archive/reddit) - historical code from reddit.com *(archived)*
* [JoeanAmier/TikTokDownloader](https://github.com/JoeanAmier/TikTokDownloader) - 抖音 / TikTok 平台作品下载/数据采集工具
* [beetbox/beets](https://github.com/beetbox/beets) - music library manager and MusicBrainz tagger
* [borgbackup/borg](https://github.com/borgbackup/borg) - Deduplicating archiver with compression and authenticated encryption.
* [searx/searx](https://github.com/searx/searx) - Privacy-respecting metasearch engine
* [pytube/pytube](https://github.com/pytube/pytube) - Lightweight, dependency-free Python library and CLI for downloading YouTube videos, playlists, and captions.
* [JoeanAmier/XHS-Downloader](https://github.com/JoeanAmier/XHS-Downloader) - 小红书（XiaoHongShu、RedNote）链接提取/作品采集工具
* [matrix-org/synapse](https://github.com/matrix-org/synapse) - Synapse: Matrix homeserver written in Python/Twisted. *(archived)*
* [qutebrowser/qutebrowser](https://github.com/qutebrowser/qutebrowser) - A keyboard-driven, vim-like browser based on Python and Qt.
* [benbusby/whoogle-search](https://github.com/benbusby/whoogle-search) - A self-hosted, ad-free, privacy-respecting metasearch engine *(archived)*
* [OpenByteInc/QuantDinger](https://github.com/OpenByteInc/QuantDinger) - Open-source AI Trading OS and commercial-ready multi-tenant SaaS platform — research markets, build Python strategies, backtest, paper/live trade, and monitor crypto, stocks, and forex, with built-in user management, billing, payments, and settlement to launch and operate your own trading service.
* [django-cms/django-cms](https://github.com/django-cms/django-cms) - The easy-to-use and developer-friendly enterprise CMS powered by Django
* [polarsource/polar](https://github.com/polarsource/polar) - Polar — A billing platform for the intelligence era
* [lutris/lutris](https://github.com/lutris/lutris) - Lutris desktop client
* [hanxi/xiaomusic](https://github.com/hanxi/xiaomusic) - 使用小爱音箱播放音乐，音乐使用 yt-dlp 下载。 *(archived)*
* [darknessomi/musicbox](https://github.com/darknessomi/musicbox) - 网易云音乐命令行版本
* [coursera-dl/coursera-dl](https://github.com/coursera-dl/coursera-dl) - Script for downloading Coursera.org videos and naming them.
* [MrS0m30n3/youtube-dl-gui](https://github.com/MrS0m30n3/youtube-dl-gui) - A cross platform front-end GUI of the popular youtube-dl written in wxPython.
* [saulpw/visidata](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for discovering and arranging data
* [Thysrael/Horizon](https://github.com/Thysrael/Horizon) - 📡 Your own AI-powered news radar. Generates daily briefings in English & Chinese. | 用 AI 构建你专属的新闻雷达
* [OctoPrint/OctoPrint](https://github.com/OctoPrint/OctoPrint) - OctoPrint is the snappy web interface for your 3D printer!
* [NAStool/nas-tools](https://github.com/NAStool/nas-tools) - NAS媒体库管理工具 *(archived)*
* [Johnserf-Seed/TikTokDownload](https://github.com/Johnserf-Seed/TikTokDownload) - 抖音去水印批量下载用户主页作品、喜欢、收藏、图文、音频
* [XiaoYouChR/Ghost-Downloader-3](https://github.com/XiaoYouChR/Ghost-Downloader-3) - The only downloader you need. 下载器的集大成者。
* [bottlesdevs/Bottles](https://github.com/bottlesdevs/Bottles) - Run Windows software and games on Linux
* [frappe/hrms](https://github.com/frappe/hrms) - Open Source HR and Payroll Software
* [houtianze/bypy](https://github.com/houtianze/bypy) - Python client for Baidu Yun (Personal Cloud Storage) 百度云/百度网盘Python客户端
* [spesmilo/electrum](https://github.com/spesmilo/electrum) - Electrum Bitcoin Wallet
* [mopidy/mopidy](https://github.com/mopidy/mopidy) - Mopidy is an extensible music server written in Python
* [vastsa/FileCodeBox](https://github.com/vastsa/FileCodeBox) - 文件快递柜-匿名口令分享文本，文件，像拿快递一样取文件（FileCodeBox - File Express Cabinet - Anonymous Passcode Sharing Text, Files, Like Taking Express Delivery for Files）
* [santinic/audiblez](https://github.com/santinic/audiblez) - Generate audiobooks from e-books
* [readthedocs/readthedocs.org](https://github.com/readthedocs/readthedocs.org) - The source code that powers readthedocs.org
* [EstrellaXD/Auto_Bangumi](https://github.com/EstrellaXD/Auto_Bangumi) - AutoBangumi - 全自动追番工具
* [LibrePhotos/librephotos](https://github.com/LibrePhotos/librephotos) - A self-hosted open source photo management service.
* [ajenti/ajenti](https://github.com/ajenti/ajenti) - Ajenti Core and stock plugins
* [arsenetar/dupeguru](https://github.com/arsenetar/dupeguru) - Find duplicate files
* [samuelclay/NewsBlur](https://github.com/samuelclay/NewsBlur) - NewsBlur is a personal news reader that brings people together to talk about the world. A new sound of an old instrument.
* [inventree/InvenTree](https://github.com/inventree/InvenTree) - Open Source Inventory Management System
* [persepolisdm/persepolis](https://github.com/persepolisdm/persepolis) - Persepolis is a download manager written in Python.
* [mvdctop/Movie_Data_Capture](https://github.com/mvdctop/Movie_Data_Capture) - Local Movies Organizer
* [liangliangyy/DjangoBlog](https://github.com/liangliangyy/DjangoBlog) - 🍺基于Django的博客系统
* [vladmandic/sdnext](https://github.com/vladmandic/sdnext) - SD.Next: All-in-one WebUI for AI generative image and video creation, captioning and processing
* [jrnl-org/jrnl](https://github.com/jrnl-org/jrnl) - Collect your thoughts and notes without leaving the command line.
* [onionshare/onionshare](https://github.com/onionshare/onionshare) - Securely and anonymously share files, host websites, and chat with friends using the Tor network
* [ScottSloan/Bili23-Downloader](https://github.com/ScottSloan/Bili23-Downloader) - 开源、免费、跨平台的 B 站视频下载工具，支持多线程加速、音视频分离、弹幕元数据获取、自定义命名与分类等功能。Open Source, Free, Cross-Platform Bilibili Video Downloader.
* [Ultimaker/Cura](https://github.com/Ultimaker/Cura) - 3D printer / slicing GUI built on top of the Uranium framework
* [yihong0618/xiaogpt](https://github.com/yihong0618/xiaogpt) - Play ChatGPT and other LLM with Xiaomi AI Speaker
* [zhinianboke/xianyu-auto-reply](https://github.com/zhinianboke/xianyu-auto-reply) - 闲鱼自动回复管理系统是一个基于 Python + FastAPI 开发的自动化客服系统，专为闲鱼平台设计。系统通过 WebSocket 连接闲鱼服务器，实时接收和处理消息，提供智能化的自动回复服务。同时集成闲鱼自动发货，自动评价，自动擦亮等功能，实现闲鱼虚拟商品自动化流程。
* [wger-project/wger](https://github.com/wger-project/wger) - Self hosted FLOSS fitness/workout, nutrition and weight tracker
* [oppia/oppia](https://github.com/oppia/oppia) - A free, online learning platform to make quality education accessible for all.
* [bleachbit/bleachbit](https://github.com/bleachbit/bleachbit) - BleachBit system cleaner for Windows and Linux
* [MycroftAI/mycroft-core](https://github.com/MycroftAI/mycroft-core) - Mycroft Core, the Mycroft Artificial Intelligence platform. *(archived)*
* [Tautulli/Tautulli](https://github.com/Tautulli/Tautulli) - A Python based monitoring and tracking tool for Plex Media Server.
* [Flagsmith/flagsmith](https://github.com/Flagsmith/flagsmith) - Flagsmith is an open source feature flagging and remote config service. Self-host or use our hosted version at https://app.flagsmith.com.
* [QingdaoU/OnlineJudge](https://github.com/QingdaoU/OnlineJudge) - Open source online judge based on Vue, Django and Docker. | 青岛大学开源 Online Judge | QQ群 496710125 | admin@qduoj.com
* [Drakkar-Software/OctoBot](https://github.com/Drakkar-Software/OctoBot) - Free open source crypto trading bot to automate AI, Grid, DCA and TradingView strategies on Binance, Hyperliquid and 15+ exchanges, with a simple interface.
* [happycola233/tchMaterial-parser](https://github.com/happycola233/tchMaterial-parser) - 国家中小学智慧教育平台 电子课本下载工具，帮助您从智慧教育平台中获取电子课本的 PDF 文件网址并进行下载，让您更方便地获取课本内容。
* [OpenShot/openshot-qt](https://github.com/OpenShot/openshot-qt) - OpenShot Video Editor is an award-winning free and open-source video editor for Linux, Mac, and Windows, and is dedicated to delivering high quality video editing and animation solutions to the world.
* [IAmTomShaw/f1-race-replay](https://github.com/IAmTomShaw/f1-race-replay) - An interactive Formula 1 race visualisation and data analysis tool built with Python! 🏎️
* [WeblateOrg/weblate](https://github.com/WeblateOrg/weblate) - Web based localization tool with tight version control integration.
* [dmunozv04/iSponsorBlockTV](https://github.com/dmunozv04/iSponsorBlockTV) - SponsorBlock client for all YouTube TV clients.
* [sngyai/Sequoia-X](https://github.com/sngyai/Sequoia-X) - A股自动选股系统 — 多种技术形态自动扫描，收盘后自动运行并推送飞书
* [CharlesPikachu/musicdl](https://github.com/CharlesPikachu/musicdl) - Musicdl: A lightweight music downloader written in pure python. (轻量级无损音乐下载器，支持数十个音乐/有声读物平台，例如网易云音乐，QQ音乐，酷狗音乐，酷我音乐，咪咕音乐，千千静听，汽水音乐，Bilibili，街声，喜马拉雅，懒人听书，荔枝FM，蜻蜓FM，JOOX，TIDAL，YouTube，Apple Music，Spotify，Qobuz，SoundCloud等主流音乐平台)
* [pdfarranger/pdfarranger](https://github.com/pdfarranger/pdfarranger) - Small python-gtk application, which helps the user to merge or split PDF documents and rotate, crop and rearrange their pages using an interactive and intuitive graphical interface.
* [aidlearning/AidLearning-FrameWork](https://github.com/aidlearning/AidLearning-FrameWork) - 🔥🔥🔥AidLearning is a powerful AIOT development platform, AidLearning builds a linux env supporting GUI, deep learning and visual IDE on Android...Now Aid supports CPU+GPU+NPU for inference with high performance acceleration...Linux on Android or HarmonyOS
* [blackboxo/CleanMyWechat](https://github.com/blackboxo/CleanMyWechat) - 自动删除 Windows 和 Mac 电脑端微信缓存数据，包括从所有聊天中自动下载的大量文件、视频、图片等数据内容，解放你的空间。
* [HisMax/RedInk](https://github.com/HisMax/RedInk) - Red Ink - A one-stop Xiaohongshu image-and-text generator based on the 🍌Nano Banana Pro🍌, "One Sentence, One Image: Generate Xiaohongshu Text and Images."
* [amnweb/yasb](https://github.com/amnweb/yasb) - A highly configurable Windows status bar written in Python.
* [liuzhao1225/YouDub-webui](https://github.com/liuzhao1225/YouDub-webui) - Open-source AI video localization and dubbing for YouTube/Bilibili: speech recognition, subtitle translation, voice cloning, audio mixing and rendering. 开源 AI 视频翻译配音工具。
* [Tribler/tribler](https://github.com/Tribler/tribler) - Privacy enhanced BitTorrent client with P2P content discovery
* [qtile/qtile](https://github.com/qtile/qtile) - :cookie: A full-featured, hackable tiling window manager written and configured in Python (X11 + Wayland)
* [RICHQAQ/PasteMD](https://github.com/RICHQAQ/PasteMD) - 一键将 Markdown 和网页 AI 对话（ChatGPT/DeepSeek等）完美粘贴到 Word、WPS 和 Excel 的效率工具 | One-click paste Markdown and AI responses (ChatGPT/DeepSeek) into Word, WPS, and Excel perfectly.
* [TomBadash/Mouser](https://github.com/TomBadash/Mouser) - A lightweight, open-source, fully local alternative to Logitech Options+ for remapping Logitech HID++ mice.
* [metabrainz/picard](https://github.com/metabrainz/picard) - Picard is a cross-platform music tagger powered by the MusicBrainz database
* [Yuukiy/JavSP](https://github.com/Yuukiy/JavSP) - 汇总多站点数据的AV元数据刮削器
* [automatic-ripping-machine/automatic-ripping-machine](https://github.com/automatic-ripping-machine/automatic-ripping-machine) - Automatic Ripping Machine (ARM) Scripts
* [huashengdun/webssh](https://github.com/huashengdun/webssh) - :seedling: Web based ssh client
* [ckan/ckan](https://github.com/ckan/ckan) - CKAN is an open-source DMS (data management system) for powering data hubs and data portals. CKAN makes it easy to publish, share and use data. It powers catalog.data.gov, open.canada.ca/data, data.humdata.org among many other sites.
* [lorenzodifuccia/safaribooks](https://github.com/lorenzodifuccia/safaribooks) - Download and generate EPUB of your favorite books from O'Reilly Learning (aka Safari Books Online) library.
* [r0oth3x49/udemy-dl](https://github.com/r0oth3x49/udemy-dl) - A cross-platform python based utility to download courses from udemy for personal offline use. *(archived)*
* [Kozea/Radicale](https://github.com/Kozea/Radicale) - A simple CalDAV (calendar) and CardDAV (contact) server.
* [Maxteabag/sqlit](https://github.com/Maxteabag/sqlit) - A user friendly TUI for SQL databases. Written in python. Supports SQL server, Mysql, PostreSQL, SQLite, Turso and more.
* [0x5e/wechat-deleted-friends](https://github.com/0x5e/wechat-deleted-friends) - 查看被删的微信好友 *(archived)*
* [motioneye-project/motioneye](https://github.com/motioneye-project/motioneye) - A web frontend for the motion daemon.
* [michael-lazar/rtv](https://github.com/michael-lazar/rtv) - Browse Reddit from your terminal *(archived)*
* [element-hq/synapse](https://github.com/element-hq/synapse) - Synapse: Matrix homeserver written in Python/Twisted + Rust
* [aaPanel/BaoTa](https://github.com/aaPanel/BaoTa) - 宝塔Linux面板 - 简单好用的服务器运维面板
* [oop7/YTSage](https://github.com/oop7/YTSage) - Modern YouTube downloader with a clean PySide6 interface. Download videos in any quality, extract audio, fetch subtitles, sponsorBlock, and view video metadata. Built with yt-dlp for reliable performance.
* [midoks/mdserver-web](https://github.com/midoks/mdserver-web) - Simple Linux Panel
* [Ulauncher/Ulauncher](https://github.com/Ulauncher/Ulauncher) - Feature rich application Launcher for Linux
* [schenkd/nginx-ui](https://github.com/schenkd/nginx-ui) - Nginx UI allows you to access and modify the nginx configurations files without cli.
* [amidaware/tacticalrmm](https://github.com/amidaware/tacticalrmm) - A remote monitoring & management tool, built with Django, Vue and Go.
* [leon-thomm/Ryven](https://github.com/leon-thomm/Ryven) - Flow-based visual scripting for Python *(archived)*
* [freedomofpress/securedrop](https://github.com/freedomofpress/securedrop) - GitHub repository for the SecureDrop whistleblower platform. Do not submit tips here!
* [gaubert/gmvault](https://github.com/gaubert/gmvault) - gmail backup software
* [Henryhaohao/Bilibili_video_download](https://github.com/Henryhaohao/Bilibili_video_download) - :rainbow:Bilibili_video_download-B站视频下载
* [modoboa/modoboa](https://github.com/modoboa/modoboa) - Mail hosting made simple
* [pinry/pinry](https://github.com/pinry/pinry) - Pinry, a tiling image board system for people who want to save, tag, and share images, videos and webpages in an easy to skim through format. It's open-source and self-hosted.
* [nyaadevs/nyaa](https://github.com/nyaadevs/nyaa) - Bittorrent software for cats
* [samschott/maestral](https://github.com/samschott/maestral) - Open-source Dropbox client for macOS and Linux *(archived)*
* [archivy/archivy](https://github.com/archivy/archivy) - Archivy is a self-hostable knowledge repository that allows you to learn and retain information in your own personal and extensible wiki.
* [atlas-comstock/NeteaseCloudMusicFlac](https://github.com/atlas-comstock/NeteaseCloudMusicFlac) - 根据网易云音乐的歌单, 下载flac无损音乐到本地. Download the FLAC music from Internet according to your NeteaseCloudMusic playlist.
* [cdhigh/KindleEar](https://github.com/cdhigh/KindleEar) - Aggregates RSS and web content(Calibre recipe), sends to Kindle, and includes an e-ink optimized online reader.
* [Serene-Arc/bulk-downloader-for-reddit](https://github.com/Serene-Arc/bulk-downloader-for-reddit) - Downloads and archives content from reddit
* [git-cola/git-cola](https://github.com/git-cola/git-cola) - git-cola: The highly caffeinated Git GUI
* [danmacnish/cartoonify](https://github.com/danmacnish/cartoonify) - python app to turn a photograph into a cartoon
* [GradienceTeam/Gradience](https://github.com/GradienceTeam/Gradience) - Change the look of Adwaita, with ease *(archived)*
* [DMOJ/judge-server](https://github.com/DMOJ/judge-server) - Judging backend server for the DMOJ online judge.
* [bilelmoussaoui/Hardcode-Tray](https://github.com/bilelmoussaoui/Hardcode-Tray) - Fixes Hardcoded tray icons in Linux
* [iawia002/Lulu](https://github.com/iawia002/Lulu) - [Unmaintained] A simple and clean video/music/image downloader 👾 *(archived)*

## Graphics and Media

### Graphics and Rendering

* [3b1b/manim](https://github.com/3b1b/manim) - Animation engine for explanatory math videos
* [ManimCommunity/manim](https://github.com/ManimCommunity/manim) - A community-maintained Python framework for creating mathematical animations.
* [marceloprates/prettymaps](https://github.com/marceloprates/prettymaps) - Draw pretty maps from OpenStreetMap data! Built with osmnx +matplotlib + shapely
* [originalankur/maptoposter](https://github.com/originalankur/maptoposter) - Transform your favorite cities into beautiful, minimalist designs. MapToPoster lets you create and export visually striking map posters with code.
* [domlysz/BlenderGIS](https://github.com/domlysz/BlenderGIS) - Blender addons to make the bridge between Blender and geographic data
* [a1studmuffin/SpaceshipGenerator](https://github.com/a1studmuffin/SpaceshipGenerator) - A Blender script to procedurally generate 3D spaceships
* [fonttools/fonttools](https://github.com/fonttools/fonttools) - A library to manipulate font files from Python.
* [pyvista/pyvista](https://github.com/pyvista/pyvista) - 3D visualization and mesh analysis for science and engineering
* [mikedh/trimesh](https://github.com/mikedh/trimesh) - Python library for loading and using triangular meshes.
* [vispy/vispy](https://github.com/vispy/vispy) - Main repository for Vispy
* [JacquesLucke/animation_nodes](https://github.com/JacquesLucke/animation_nodes) - Node based visual scripting system designed for motion graphics in Blender.

### Game Development

* [kitao/pyxel](https://github.com/kitao/pyxel) - A retro game engine for Python
* [SFTtech/openage](https://github.com/SFTtech/openage) - Clone of the Age of Empires II engine 🚀
* [fogleman/Minecraft](https://github.com/fogleman/Minecraft) - Simple Minecraft-inspired program using Python and Pyglet
* [CharlesPikachu/Games](https://github.com/CharlesPikachu/Games) - Games: Create interesting games in pure python.
* [Baekalfen/PyBoy](https://github.com/Baekalfen/PyBoy) - Game Boy emulator written in Python
* [thomasahle/sunfish](https://github.com/thomasahle/sunfish) - Sunfish: a Python Chess Engine in 111 lines of code
* [lxgr-linux/pokete](https://github.com/lxgr-linux/pokete) - A terminal based Pokemon like game

### Image and Video

* [danielgatis/rembg](https://github.com/danielgatis/rembg) - Rembg is a tool to remove images background
* [k4yt3x/video2x](https://github.com/k4yt3x/video2x) - A machine learning-based video super resolution and frame interpolation framework. Est. Hack the Valley II, 2018.
* [alievk/avatarify-python](https://github.com/alievk/avatarify-python) - Avatars for Zoom, Skype and other video-conferencing apps.
* [Zulko/moviepy](https://github.com/Zulko/moviepy) - Video editing with Python
* [python-pillow/Pillow](https://github.com/python-pillow/Pillow) - Python Imaging Library (fork)
* [streamlink/streamlink](https://github.com/streamlink/streamlink) - Streamlink is a CLI utility which pipes video streams from various services into a video player
* [kkroening/ffmpeg-python](https://github.com/kkroening/ffmpeg-python) - Python bindings for FFmpeg - with complex filtering support
* [linyqh/NarratoAI](https://github.com/linyqh/NarratoAI) - 利用 AI 大模型，一键解说并剪辑视频
* [x-hw/amazing-qr](https://github.com/x-hw/amazing-qr) - 💮 amazing QRCode generator in Python (supporting animated gif) - Python amazing 二维码生成器（支持 gif 动态图片二维码）
* [vietnh1009/ASCII-generator](https://github.com/vietnh1009/ASCII-generator) - ASCII generator (image to text, image to image, video to video)
* [brycedrennan/imaginAIry](https://github.com/brycedrennan/imaginAIry) - Pythonic AI generation of images and videos
* [nadermx/backgroundremover](https://github.com/nadermx/backgroundremover) - Background Remover lets you Remove Background from images and video using AI with a simple command line interface that is free and open source.
* [RayVentura/ShortGPT](https://github.com/RayVentura/ShortGPT) - 🚀🎬 ShortGPT - Experimental AI framework for youtube shorts / tiktok channel automation
* [scikit-image/scikit-image](https://github.com/scikit-image/scikit-image) - Image processing in Python
* [nuno-faria/tiler](https://github.com/nuno-faria/tiler) - 👷 Build images with images
* [wiltodelta/remove-ai-watermarks](https://github.com/wiltodelta/remove-ai-watermarks) - Remove visible and invisible AI watermarks and provenance metadata from images and video. Python library and CLI for SynthID, C2PA, EXIF, IPTC, XMP, and common generative-AI marks.
* [Breakthrough/PySceneDetect](https://github.com/Breakthrough/PySceneDetect) - :movie_camera: Python and OpenCV-based scene cut/transition detection program & library.
* [lincolnloop/python-qrcode](https://github.com/lincolnloop/python-qrcode) - Python QR Code image generator
* [PyImageSearch/imutils](https://github.com/PyImageSearch/imutils) - A series of convenience functions to make basic image processing operations such as translation, rotation, resizing, skeletonization, and displaying Matplotlib images easier with OpenCV and Python.
* [abhiTronix/vidgear](https://github.com/abhiTronix/vidgear) - A High-performance cross-platform Video Processing Python framework powerpacked with unique trailblazing features :fire:
* [ShieldMnt/invisible-watermark](https://github.com/ShieldMnt/invisible-watermark) - python library for invisible image watermark (blind image watermark)

## Security

### Security Tools

* [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock) - Hunt down social media accounts by username across social networks
* [mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy) - An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers.
* [sqlmapproject/sqlmap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool
* [soxoj/maigret](https://github.com/soxoj/maigret) - 🕵️‍♂️ Collect a dossier on a person by username from 3000+ sites
* [StevenBlack/hosts](https://github.com/StevenBlack/hosts) - 🔒 Consolidating and extending hosts files from several well-curated sources. Optionally pick extensions for porn, social media, and other categories.
* [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) - SpiderFoot automates OSINT for threat intelligence and mapping your attack surface.
* [bee-san/Ciphey](https://github.com/bee-san/Ciphey) - ⚡ Automatically decrypt encryptions without knowing the key or cipher, decode encodings, and crack hashes ⚡
* [fail2ban/fail2ban](https://github.com/fail2ban/fail2ban) - Daemon to ban hosts that cause multiple authentication errors
* [laramies/theHarvester](https://github.com/laramies/theHarvester) - E-mails, subdomains and names Harvester - OSINT
* [twintproject/twint](https://github.com/twintproject/twint) - An advanced Twitter scraping & OSINT tool written in Python that doesn't use Twitter's API, allowing you to scrape a user's followers, following, Tweets and more while evading most API limitations. *(archived)*
* [GreyDGL/PentestGPT](https://github.com/GreyDGL/PentestGPT) - Automated Penetration Testing Agentic Framework Powered by Large Language Models
* [HunxByts/GhostTrack](https://github.com/HunxByts/GhostTrack) - Useful tool to track location or mobile number
* [wifiphisher/wifiphisher](https://github.com/wifiphisher/wifiphisher) - The Rogue Access Point Framework
* [prowler-cloud/prowler](https://github.com/prowler-cloud/prowler) - Prowler is the world’s most widely used open-source cloud security platform that automates security and compliance across any cloud environment.
* [maurosoria/dirsearch](https://github.com/maurosoria/dirsearch) - Web path scanner
* [megadose/holehe](https://github.com/megadose/holehe) - holehe allows you to check if the mail is used on different sites like twitter, instagram and will retrieve information on sites with the forgotten password function.
* [Datalux/Osintgram](https://github.com/Datalux/Osintgram) - Osintgram is a OSINT tool on Instagram. It offers an interactive shell to perform analysis on Instagram account of any users by its nickname
* [Gallopsled/pwntools](https://github.com/Gallopsled/pwntools) - CTF framework and exploit development library
* [threat9/routersploit](https://github.com/threat9/routersploit) - Exploitation Framework for Embedded Devices
* [s0md3v/Photon](https://github.com/s0md3v/Photon) - Incredibly fast crawler designed for OSINT.
* [jopohl/urh](https://github.com/jopohl/urh) - Universal Radio Hacker: Investigate Wireless Protocols Like A Boss *(archived)*
* [Manisso/fsociety](https://github.com/Manisso/fsociety) - fsociety Hacking Tools Pack – A Penetration Testing Framework
* [data-privacy-stack/presidio](https://github.com/data-privacy-stack/presidio) - An open-source framework for detecting, redacting, masking, and anonymizing sensitive data (PII) across text, images, and structured data. Supports NLP, pattern matching, and customizable pipelines.
* [blacklanternsecurity/bbot](https://github.com/blacklanternsecurity/bbot) - The recursive internet scanner for hackers. 🧡
* [shmilylty/OneForAll](https://github.com/shmilylty/OneForAll) - OneForAll是一款功能强大的子域收集工具
* [byt3bl33d3r/CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) - A swiss army knife for pentesting networks *(archived)*
* [n1nj4sec/pupy](https://github.com/n1nj4sec/pupy) - Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) C2 and post-exploitation framework written in python and C *(archived)*
* [jofpin/trape](https://github.com/jofpin/trape) - People tracker on the Internet: OSINT analysis and research tool by Jose Pino
* [stamparm/maltrail](https://github.com/stamparm/maltrail) - Malicious traffic detection system
* [PyCQA/bandit](https://github.com/PyCQA/bandit) - Bandit is a tool designed to find common security issues in Python code.
* [p1ngul1n0/blackbird](https://github.com/p1ngul1n0/blackbird) - An OSINT tool to search for accounts by username and email in social networks.
* [bee-san/pyWhat](https://github.com/bee-san/pyWhat) - 🐸 Identify anything. pyWhat easily lets you identify emails, IP addresses, and more. Feed it a .pcap file or some text and it'll tell you what it is! 🧙‍♀️
* [infinition/Bjorn](https://github.com/infinition/Bjorn) - Bjorn is a powerful network scanning and offensive security tool for the Raspberry Pi with a 2.13-inch e-Paper HAT. It discovers network targets, identifies open ports, exposed services, and potential vulnerabilities. Bjorn can perform brute force attacks, file stealing, host zombification, and supports custom attack scripts.
* [Trusted-AI/adversarial-robustness-toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox) - Adversarial Robustness Toolbox (ART) - Python Library for Machine Learning Security - Evasion, Poisoning, Extraction, Inference - Red and Blue Teams
* [AzeemIdrisi/PhoneSploit-Pro](https://github.com/AzeemIdrisi/PhoneSploit-Pro) - An all-in-one hacking tool to remotely exploit Android devices using ADB and Metasploit-Framework to get a Meterpreter session.
* [commixproject/commix](https://github.com/commixproject/commix) - Automated All-in-One OS Command Injection Exploitation Tool
* [Pennyw0rth/NetExec](https://github.com/Pennyw0rth/NetExec) - The Network Execution Tool
* [TheSpeedX/TBomb](https://github.com/TheSpeedX/TBomb) - This is a SMS And Call Bomber For Linux And Termux *(archived)*
* [OWASP/Nettacker](https://github.com/OWASP/Nettacker) - Automated Penetration Testing Framework - Open-Source Vulnerability Scanner - Vulnerability Management
* [RhinoSecurityLabs/pacu](https://github.com/RhinoSecurityLabs/pacu) - The AWS exploitation framework, designed for testing the security of Amazon Web Services environments.
* [NullArray/AutoSploit](https://github.com/NullArray/AutoSploit) - Automated Mass Exploiter
* [dashingsoft/pyarmor](https://github.com/dashingsoft/pyarmor) - A tool used to obfuscate python scripts, bind obfuscated scripts to fixed machine or expire obfuscated scripts.
* [DedSecInside/TorBot](https://github.com/DedSecInside/TorBot) - Dark Web OSINT Tool
* [intelowlproject/IntelOwl](https://github.com/intelowlproject/IntelOwl) - IntelOwl: manage your Threat Intelligence at scale
* [GerbenJavado/LinkFinder](https://github.com/GerbenJavado/LinkFinder) - A python script that finds endpoints in JavaScript files
* [Netflix/security_monkey](https://github.com/Netflix/security_monkey) - Security Monkey monitors AWS, GCP, OpenStack, and GitHub orgs for assets and their changes over time. *(archived)*
* [knownsec/pocsuite3](https://github.com/knownsec/pocsuite3) - pocsuite3 is an open-sourced remote vulnerability testing framework developed by the Knownsec 404 Team.
* [nabla-c0d3/sslyze](https://github.com/nabla-c0d3/sslyze) - Fast and powerful SSL/TLS scanning library.
* [byt3bl33d3r/MITMf](https://github.com/byt3bl33d3r/MITMf) - Framework for Man-In-The-Middle attacks *(archived)*
* [gwen001/pentest-tools](https://github.com/gwen001/pentest-tools) - A collection of custom security tools for quick needs.
* [python-security/pyt](https://github.com/python-security/pyt) - A Static Analysis Tool for Detecting Security Vulnerabilities in Python Web Applications
* [xnl-h4ck3r/xnLinkFinder](https://github.com/xnl-h4ck3r/xnLinkFinder) - A python tool used to discover endpoints, potential parameters, a target specific wordlist for a given target and secrets
* [GamehunterKaan/AutoPWN-Suite](https://github.com/GamehunterKaan/AutoPWN-Suite) - AutoPWN Suite is a project for scanning vulnerabilities and exploiting systems automatically.
* [Python Obfuscator & Virtualizer](https://www.pelock.com/python-obfuscator/) - Obfuscate, virtualize & protect Python scripts with advanced obfuscations, code virtualization, finite-state automata transformations, self-integrity checks, anti-debugging.

### Authentication and Authorization

* [jumpserver/jumpserver](https://github.com/jumpserver/jumpserver) - JumpServer is an open-source Privileged Access Management (PAM) platform that provides DevOps and IT teams with on-demand and secure access to SSH, RDP, Kubernetes, Database and RemoteApp endpoints through a web browser.
* [pennersr/django-allauth](https://github.com/pennersr/django-allauth) - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party (social) account authentication. 🔁 Mirror of https://codeberg.org/allauth/django-allauth/
* [fastapi-users/fastapi-users](https://github.com/fastapi-users/fastapi-users) - Ready-to-use and customizable users management for FastAPI
* [jpadilla/pyjwt](https://github.com/jpadilla/pyjwt) - JSON Web Token implementation in Python
* [authlib/authlib](https://github.com/authlib/authlib) - The ultimate Python library in building OAuth, OpenID Connect clients and servers. JWS, JWE, JWK, JWA, JWT included.
* [django-oauth/django-oauth-toolkit](https://github.com/django-oauth/django-oauth-toolkit) - OAuth2 goodies for the Djangonauts!
* [joestump/python-oauth2](https://github.com/joestump/python-oauth2) - A fully tested, abstract interface to creating OAuth clients and servers.
* [oauthlib/oauthlib](https://github.com/oauthlib/oauthlib) - A generic, spec-compliant, thorough implementation of the OAuth request-signing logic
* [sunscrapers/djoser](https://github.com/sunscrapers/djoser) - REST implementation of Django authentication system.
* [googleapis/oauth2client](https://github.com/googleapis/oauth2client) - This is a Python library for accessing resources protected by OAuth 2.0. *(archived)*

### Reverse Engineering

* [pwndbg/pwndbg](https://github.com/pwndbg/pwndbg) - Exploit Development and Reverse Engineering with GDB & LLDB Made Easy
* [hugsy/gef](https://github.com/hugsy/gef) - GEF (GDB Enhanced Features) - a modern experience for GDB with advanced debugging capabilities for exploit devs & reverse engineers on Linux
* [volatilityfoundation/volatility](https://github.com/volatilityfoundation/volatility) - An advanced memory forensics framework *(archived)*
* [longld/peda](https://github.com/longld/peda) - PEDA - Python Exploit Development Assistance for GDB
* [charles2gan/GDA-android-reversing-Tool](https://github.com/charles2gan/GDA-android-reversing-Tool) - the fastest and most powerful android decompiler(native tool working without Java VM) for the APK, DEX, ODEX, OAT, JAR, AAR, and CLASS file. which supports malicious behavior detection, privacy leaking detection, vulnerability detection, path solving, packer identification, variable tracking, deobfuscation, python&java scripts, device memory extraction, data decryption, and encryption, etc.
* [extremecoders-re/pyinstxtractor](https://github.com/extremecoders-re/pyinstxtractor) - PyInstaller Extractor
* [rocky/python-uncompyle6](https://github.com/rocky/python-uncompyle6) - A cross-version Python bytecode decompiler
* [cea-sec/miasm](https://github.com/cea-sec/miasm) - Reverse engineering framework in Python
* [trailofbits/manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool *(archived)*
* [nongiach/arm_now](https://github.com/nongiach/arm_now) - arm_now is a qemu powered tool that allows instant setup of virtual machines on arm cpu, mips, powerpc, nios2, x86 and more, for reverse, exploit, fuzzing and programming purpose.

## Concurrency and Performance

### Concurrency and Parallelism

* [ray-project/ray](https://github.com/ray-project/ray) - Ray is an AI compute engine. Ray consists of a core distributed runtime and a set of AI Libraries for accelerating ML workloads.
* [dask/dask](https://github.com/dask/dask) - Parallel computing with task scheduling
* [python-trio/trio](https://github.com/python-trio/trio) - Trio – a friendly Python library for async concurrency and I/O
* [gevent/gevent](https://github.com/gevent/gevent) - Coroutine-based concurrency library for Python
* [ReactiveX/RxPY](https://github.com/ReactiveX/RxPY) - ReactiveX for Python
* [joblib/joblib](https://github.com/joblib/joblib) - Computing with Python functions.
* [nalepae/pandarallel](https://github.com/nalepae/pandarallel) - A simple and efficient tool to parallelize Pandas operations on all available CPUs

## Testing and Quality

### Testing

* [locustio/locust](https://github.com/locustio/locust) - Write scalable load tests in plain Python 🚗💨
* [joke2k/faker](https://github.com/joke2k/faker) - Faker is a Python package that generates fake data for you.
* [microsoft/playwright-python](https://github.com/microsoft/playwright-python) - Python version of the Playwright testing and automation library.
* [pytest-dev/pytest](https://github.com/pytest-dev/pytest) - The pytest framework makes it easy to write small tests, yet scales to support complex functional testing
* [postmanlabs/httpbin](https://github.com/postmanlabs/httpbin) - HTTP Request & Response Service, written in Python + Flask.
* [seleniumbase/SeleniumBase](https://github.com/seleniumbase/SeleniumBase) - APIs for browser automation, testing, and bypassing bot-detection. Includes CDP Mode: A stealthy configuration for chromium that passes every bot detection test.
* [robotframework/robotframework](https://github.com/robotframework/robotframework) - Generic automation framework for acceptance testing and RPA
* [HypothesisWorks/hypothesis](https://github.com/HypothesisWorks/hypothesis) - The property-based testing library for Python
* [lk-geimfari/mimesis](https://github.com/lk-geimfari/mimesis) - Mimesis is a Python library for generating fake but realistic data in multiple languages and locales.
* [spulec/freezegun](https://github.com/spulec/freezegun) - Let your Python tests travel through time
* [getsentry/responses](https://github.com/getsentry/responses) - A utility for mocking out the Python Requests library.
* [ansible/molecule](https://github.com/ansible/molecule) - An ansible-native testing framework for collections, playbooks, and roles with configurable workflows for testing any system or service
* [deepchecks/deepchecks](https://github.com/deepchecks/deepchecks) - Deepchecks: Tests for Continuous Validation of ML Models & Data. Deepchecks is a holistic open-source solution for all of your AI & ML validation needs, enabling to thoroughly test your data and models from research to production.
* [FactoryBoy/factory_boy](https://github.com/FactoryBoy/factory_boy) - A test fixtures replacement for Python
* [pytest-dev/pytest-testinfra](https://github.com/pytest-dev/pytest-testinfra) - Testinfra test your infrastructures

## Utilities

### Command Line Tools

* [nvbn/thefuck](https://github.com/nvbn/thefuck) - Magnificent app which corrects your previous console command.
* [google/python-fire](https://github.com/google/python-fire) - Python Fire is a library for automatically generating command line interfaces (CLIs) from absolutely any Python object.
* [fastapi/typer](https://github.com/fastapi/typer) - Typer, build great CLIs. Easy to code. Based on Python type hints.
* [pallets/click](https://github.com/pallets/click) - Python composable command line interface toolkit
* [wting/autojump](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line
* [TheR1D/shell_gpt](https://github.com/TheR1D/shell_gpt) - A command-line productivity tool powered by AI large language models like GPT-5, will help you accomplish your tasks faster and more efficiently.
* [harelba/q](https://github.com/harelba/q) - q - Run SQL directly on delimited files and multi-file sqlite databases
* [xonsh/xonsh](https://github.com/xonsh/xonsh) - 🐚 Python-powered shell. Full-featured, cross-platform and AI-friendly.
* [kellyjonbrazil/jc](https://github.com/kellyjonbrazil/jc) - CLI tool and python library that converts the output of popular command-line tools, file-types, and common strings to JSON, YAML, or Dictionaries. This allows piping of output to tools like jq and simplifying automation scripts.
* [docopt/docopt](https://github.com/docopt/docopt) - Create *beautiful* command-line interfaces with Python
* [donnemartin/gitsome](https://github.com/donnemartin/gitsome) - A supercharged Git/GitHub command line interface (CLI). An official integration for GitHub and GitHub Enterprise: https://github.com/works-with/category/desktop-tools
* [reorx/httpstat](https://github.com/reorx/httpstat) - curl statistics made simple
* [prompt-toolkit/ptpython](https://github.com/prompt-toolkit/ptpython) - A better Python REPL
* [wkentaro/gdown](https://github.com/wkentaro/gdown) - Google Drive public file downloader when curl/wget fails.
* [donnemartin/saws](https://github.com/donnemartin/saws) - A supercharged AWS command line interface (CLI).
* [s3tools/s3cmd](https://github.com/s3tools/s3cmd) - Official s3cmd repo -- Command line tool for managing S3 compatible storage services (including Amazon S3 and CloudFront).
* [initialcommit-com/git-sim](https://github.com/initialcommit-com/git-sim) - Visually simulate Git operations in your own repos with a single terminal command.
* [andreafrancia/trash-cli](https://github.com/andreafrancia/trash-cli) - Command line interface to the freedesktop.org trashcan.
* [tmux-python/tmuxp](https://github.com/tmux-python/tmuxp) - 🖥️ Session manager for tmux, built on libtmux.
* [wookayin/gpustat](https://github.com/wookayin/gpustat) - 📊 A simple command-line utility for querying and monitoring GPU status
* [shobrook/rebound](https://github.com/shobrook/rebound) - Instant Stack Overflow results whenever an exception is thrown
* [donnemartin/haxor-news](https://github.com/donnemartin/haxor-news) - Browse Hacker News like a haxor: A Hacker News command line interface (CLI).
* [emre/storm](https://github.com/emre/storm) - Manage your SSH like a boss. *(archived)*
* [ergonomica/ergonomica](https://github.com/ergonomica/ergonomica) - 🖥️ a cross-platform modern shell.
* [koenrh/delete-tweets](https://github.com/koenrh/delete-tweets) - Delete tweets from your timeline. *(archived)*

### Text Processing

* [microsoft/markitdown](https://github.com/microsoft/markitdown) - Python tool for converting files and office documents to Markdown.
* [opendatalab/MinerU](https://github.com/opendatalab/MinerU) - Transforms complex documents like PDFs and Office docs into LLM-ready markdown/JSON for your Agentic workflows.
* [mkdocs/mkdocs](https://github.com/mkdocs/mkdocs) - Project documentation with Markdown.
* [getpelican/pelican](https://github.com/getpelican/pelican) - Static site generator that supports Markdown and reST syntax. Powered by Python.
* [pallets/jinja](https://github.com/pallets/jinja) - A very fast and expressive template engine.
* [pymupdf/PyMuPDF](https://github.com/pymupdf/PyMuPDF) - PyMuPDF is a high performance Python library for data extraction, analysis, conversion & manipulation of PDF (and other) documents.
* [py-pdf/pypdf](https://github.com/py-pdf/pypdf) - A pure-python PDF library capable of splitting, merging, cropping, and transforming the pages of PDF files
* [Kozea/WeasyPrint](https://github.com/Kozea/WeasyPrint) - The awesome document factory
* [sphinx-doc/sphinx](https://github.com/sphinx-doc/sphinx) - The Sphinx documentation generator
* [google/latexify_py](https://github.com/google/latexify_py) - A library to generate LaTeX expression from Python code. *(archived)*
* [pdfminer/pdfminer.six](https://github.com/pdfminer/pdfminer.six) - Community maintained fork of pdfminer - we fathom PDF
* [joeyespo/grip](https://github.com/joeyespo/grip) - Preview GitHub README.md files locally before committing them.
* [mozillazg/python-pinyin](https://github.com/mozillazg/python-pinyin) - 汉字转拼音(pypinyin)
* [Python-Markdown/markdown](https://github.com/Python-Markdown/markdown) - A Python implementation of John Gruber’s Markdown with Extension support.
* [rspeer/python-ftfy](https://github.com/rspeer/python-ftfy) - Fixes mojibake and other glitches in Unicode text, after the fact.
* [andialbrecht/sqlparse](https://github.com/andialbrecht/sqlparse) - A non-validating SQL parser module for Python
* [daviddrysdale/python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - Python port of Google's libphonenumber
* [borb-pdf/borb](https://github.com/borb-pdf/borb) - borb is a library for reading, creating and manipulating PDF files in python.
* [trailofbits/graphtage](https://github.com/trailofbits/graphtage) - A semantic diff utility and library for tree-like files such as JSON, JSON5, XML, HTML, YAML, and CSV.
* [WZBSocialScienceCenter/pdftabextract](https://github.com/WZBSocialScienceCenter/pdftabextract) - A set of tools for extracting tables from PDF files helping to do data mining on (OCR-processed) scanned documents.

### Files and Operating System

* [giampaolo/psutil](https://github.com/giampaolo/psutil) - Cross-platform lib for process and system monitoring in Python
* [gorakhargosh/watchdog](https://github.com/gorakhargosh/watchdog) - Python library and shell utilities to monitor filesystem events.
* [amoffat/sh](https://github.com/amoffat/sh) - Python process launching
* [boppreh/keyboard](https://github.com/boppreh/keyboard) - Hook and simulate global keyboard events on Windows and Linux.
* [pyserial/pyserial](https://github.com/pyserial/pyserial) - Python serial port access library
* [piskvorky/smart_open](https://github.com/piskvorky/smart_open) - Utils for streaming large files (S3, HDFS, gzip, bz2...)
* [intoli/exodus](https://github.com/intoli/exodus) - Painless relocation of Linux binaries–and all of their dependencies–without containers.
* [jschneier/django-storages](https://github.com/jschneier/django-storages) - https://django-storages.readthedocs.io/
* [presslabs/gitfs](https://github.com/presslabs/gitfs) - Version controlled file system
* [not-kennethreitz/envoy](https://github.com/not-kennethreitz/envoy) - Python Subprocesses for Humans™. *(archived)*

### Date and Time

* [dbader/schedule](https://github.com/dbader/schedule) - Python job scheduling for humans.
* [arrow-py/arrow](https://github.com/arrow-py/arrow) - 🏹 Better dates & times for Python
* [agronholm/apscheduler](https://github.com/agronholm/apscheduler) - Task scheduling library for Python
* [python-pendulum/pendulum](https://github.com/python-pendulum/pendulum) - Python datetimes made easy
* [kennethreitz/maya](https://github.com/kennethreitz/maya) - Datetimes for Humans™
* [Miksus/rocketry](https://github.com/Miksus/rocketry) - Modern scheduling library for Python
* [dateutil/dateutil](https://github.com/dateutil/dateutil) - Useful extensions to the standard Python datetime features

### Automation and Scripting

* [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2) - Automate the process of making money online.
* [feder-cr/Jobs_Applier_AI_Agent_AIHawk](https://github.com/feder-cr/Jobs_Applier_AI_Agent_AIHawk) - Open source AI job application toolkit in Python: generate a resume and cover letter tailored to each job posting, and drive a stealth browser from any AI client over MCP.
* [python-telegram-bot/python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) - We have made you a wrapper you can't refuse
* [InstaPy/InstaPy](https://github.com/InstaPy/InstaPy) - 📷 Instagram Bot - Tool for automated Instagram interactions
* [caronc/apprise](https://github.com/caronc/apprise) - Apprise - Push Notifications that work with just about every platform!
* [Rapptz/discord.py](https://github.com/Rapptz/discord.py) - An API wrapper for Discord written in Python.
* [fabric/fabric](https://github.com/fabric/fabric) - Simple, Pythonic remote execution and deployment.
* [FujiwaraChoki/MoneyPrinter](https://github.com/FujiwaraChoki/MoneyPrinter) - Automate Creation of YouTube Shorts using MoviePy.
* [wangshub/wechat_jump_game](https://github.com/wangshub/wechat_jump_game) - 微信《跳一跳》Python 辅助
* [asweigart/pyautogui](https://github.com/asweigart/pyautogui) - A cross-platform GUI automation Python module for human beings. Used to programmatically control the mouse & keyboard.
* [LonamiWebs/Telethon](https://github.com/LonamiWebs/Telethon) - Pure Python 3 MTProto API Telegram client library, for bots too! *(archived)*
* [taojy123/KeymouseGo](https://github.com/taojy123/KeymouseGo) - 类似按键精灵的鼠标键盘录制和自动化操作 模拟点击和键入 | automate mouse clicks and keyboard input
* [sfyc23/EverydayWechat](https://github.com/sfyc23/EverydayWechat) - 微信助手：1.每日定时给好友（女友）发送定制消息。2.机器人自动回复好友。3.群助手功能（例如：查询垃圾分类、天气、日历、电影实时票房、快递物流、PM2.5等）
* [wangshub/Douyin-Bot](https://github.com/wangshub/Douyin-Bot) - 😍 Python 抖音机器人，论如何在抖音上找到漂亮小姐姐？
* [eternnoir/pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI) - Python Telegram bot api.
* [Sitoi/dailycheckin](https://github.com/Sitoi/dailycheckin) - 基于「Docker」/「青龙面板」/「群晖」的每日签到脚本（支持多账号）签到列表: ｜爱奇艺｜全民K歌｜有道云笔记｜百度贴吧｜Bilibili｜V2EX｜AcFun｜什么值得买｜阿里云盘｜i茅台申购｜小米运动｜百度搜索资源平台｜恩山论坛｜奥拉星｜
* [gelstudios/gitfiti](https://github.com/gelstudios/gitfiti) - abusing github commit history for the lulz
* [nonebot/nonebot2](https://github.com/nonebot/nonebot2) - 跨平台 Python 异步聊天机器人框架 / Asynchronous multi-platform chatbot framework written in Python
* [cluic/wxauto](https://github.com/cluic/wxauto) - Windows版本微信客户端（非网页版）自动化，可实现简单的发送、接收微信消息，简单微信机器人
* [EZFNDEV/EZFN-Lobbybot](https://github.com/EZFNDEV/EZFN-Lobbybot) - With EasyFNBot you can easily create you own Fortnite Lobby Bot in less than 5 minutes which will be online forever!
* [StackStorm/st2](https://github.com/StackStorm/st2) - StackStorm (aka "IFTTT for Ops") is event-driven automation for auto-remediation, incident responses, troubleshooting, deployments, and more for DevOps and SREs. Includes rules engine, workflow, 160 integration packs with 6000+ actions (see https://exchange.stackstorm.org) and ChatOps. Installer at https://docs.stackstorm.com/install/index.html
* [donnemartin/dev-setup](https://github.com/donnemartin/dev-setup) - macOS development environment setup: Easy-to-understand instructions with automated setup scripts for developer tools like Vim, Sublime Text, Bash, iTerm, Python data analysis, Spark, Hadoop MapReduce, AWS, Heroku, JavaScript web development, Android development, common data stores, and dev-based OS X defaults.
* [pywinauto/pywinauto](https://github.com/pywinauto/pywinauto) - Windows GUI Automation with Python (based on text properties)
* [aiogram/aiogram](https://github.com/aiogram/aiogram) - aiogram is a modern and fully asynchronous framework for Telegram Bot API written in Python using asyncio
* [Cog-Creators/Red-DiscordBot](https://github.com/Cog-Creators/Red-DiscordBot) - A multi-function Discord bot
* [father-bot/chatgpt_telegram_bot](https://github.com/father-bot/chatgpt_telegram_bot) - 💬 Telegram bot with ChatGPT & Claude Python-based, using OpenAI's API.
* [iflytek/astron-rpa](https://github.com/iflytek/astron-rpa) - Agent-ready RPA suite with out-of-the-box automation tools. Built for individuals and enterprises.
* [tebelorg/RPA-Python](https://github.com/tebelorg/RPA-Python) - Python package for doing RPA
* [ohld/igbot](https://github.com/ohld/igbot) - 🐙 Free scripts, bots and Python API wrapper. Get free followers with our auto like, auto follow and other scripts!
* [offu/WeRoBot](https://github.com/offu/WeRoBot) - WeRoBot 是一个微信公众号开发框架
* [pyrogram/pyrogram](https://github.com/pyrogram/pyrogram) - Elegant, modern and asynchronous Telegram MTProto API framework in Python for users and bots *(archived)*
* [PokemonGoF/PokemonGo-Bot](https://github.com/PokemonGoF/PokemonGo-Bot) - The Pokemon Go Bot, baking with community.
* [pandolia/qqbot](https://github.com/pandolia/qqbot) - QQBot: A conversation robot base on Tencent's SmartQQ *(archived)*
* [automagica/automagica](https://github.com/automagica/automagica) - AI-powered Smart Robotic Process Automation 🤖
* [ianmiell/shutit](https://github.com/ianmiell/shutit) - Automation framework for programmers
* [python-kasa/python-kasa](https://github.com/python-kasa/python-kasa) - 🏠🤖 Python API for TP-Link smarthome products

### General Purpose Libraries

* [jd/tenacity](https://github.com/jd/tenacity) - Retrying library for Python
* [mahmoud/boltons](https://github.com/mahmoud/boltons) - 🔩 Like builtins, but boltons. 250+ constructs, recipes, and snippets which extend (and rely on nothing but) the Python standard library. Nothing like Michael Bolton.
* [pytransitions/transitions](https://github.com/pytransitions/transitions) - A lightweight, object-oriented finite state machine implementation in Python with many extensions
* [python-attrs/attrs](https://github.com/python-attrs/attrs) - Python Classes Without Boilerplate
* [pytoolz/toolz](https://github.com/pytoolz/toolz) - A functional standard library for Python.
* [ets-labs/python-dependency-injector](https://github.com/ets-labs/python-dependency-injector) - Dependency injection framework for Python
* [dry-python/returns](https://github.com/dry-python/returns) - Make your functions return something meaningful, typed, and safe!
* [grantjenks/python-sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) - Python Sorted Container Types: Sorted List, Sorted Dict, and Sorted Set
* [santinic/pampy](https://github.com/santinic/pampy) - Pampy: The Pattern Matching for Python you always dreamed of.
* [Suor/funcy](https://github.com/Suor/funcy) - A fancy and practical functional tools
* [kachayev/fn.py](https://github.com/kachayev/fn.py) - Functional programming in Python: implementation of missing features to enjoy FP
* [mewwts/addict](https://github.com/mewwts/addict) - The Python Dict that's better than heroin.
* [abseil/abseil-py](https://github.com/abseil/abseil-py) - Abseil Common Libraries (Python)
* [tylerlaberge/PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) - A simple library for implementing common design patterns. *(archived)*
* [anthonynsimon/timeflake](https://github.com/anthonynsimon/timeflake) - Timeflake is a 128-bit, roughly-ordered, URL-safe UUID.

## Science and Math

### Mathematics

* [numpy/numpy](https://github.com/numpy/numpy) - The fundamental package for scientific computing with Python.
* [networkx/networkx](https://github.com/networkx/networkx) - Network Analysis in Python
* [scipy/scipy](https://github.com/scipy/scipy) - SciPy library main repository
* [sympy/sympy](https://github.com/sympy/sympy) - A computer algebra system written in pure Python
* [cupy/cupy](https://github.com/cupy/cupy) - NumPy & SciPy for GPU
* [statsmodels/statsmodels](https://github.com/statsmodels/statsmodels) - Statsmodels: statistical modeling and econometrics in Python
* [pymc-devs/pymc](https://github.com/pymc-devs/pymc) - Bayesian Modeling and Probabilistic Programming in Python
* [bayesian-optimization/BayesianOptimization](https://github.com/bayesian-optimization/BayesianOptimization) - A Python implementation of global optimization with gaussian processes.
* [google/tf-quant-finance](https://github.com/google/tf-quant-finance) - High-performance TensorFlow library for quantitative finance.
* [neozhaoliang/pywonderland](https://github.com/neozhaoliang/pywonderland) - A tour in the wonderland of math with python.
* [facebookresearch/nevergrad](https://github.com/facebookresearch/nevergrad) - A Python toolbox for performing gradient-free optimization
* [rlabbe/filterpy](https://github.com/rlabbe/filterpy) - Python Kalman filtering and optimal estimation library. Implements Kalman filter, particle filter, Extended Kalman filter, Unscented Kalman filter, g-h (alpha-beta), least squares, H Infinity, smoothers, and more. Has companion book 'Kalman and Bayesian Filters in Python'.
* [CamDavidsonPilon/lifelines](https://github.com/CamDavidsonPilon/lifelines) - Survival analysis in Python

### Scientific Computing

* [Qiskit/qiskit](https://github.com/Qiskit/qiskit) - Qiskit is an open-source SDK for working with quantum computers at the level of extended quantum circuits, operators, and primitives.
* [DEAP/deap](https://github.com/DEAP/deap) - Distributed Evolutionary Algorithms in Python
* [gboeing/osmnx](https://github.com/gboeing/osmnx) - Download, model, analyze, and visualize street networks and other geospatial features from OpenStreetMap.
* [CadQuery/cadquery](https://github.com/CadQuery/cadquery) - A python parametric CAD scripting framework based on OCCT
* [astropy/astropy](https://github.com/astropy/astropy) - Astronomy and astrophysics core library
* [biopython/biopython](https://github.com/biopython/biopython) - Official git repository for Biopython (originally converted from CVS)
* [quantumlib/Cirq](https://github.com/quantumlib/Cirq) - Python framework for creating, editing, and running Noisy Intermediate-Scale Quantum (NISQ) circuits.
* [gee-community/geemap](https://github.com/gee-community/geemap) - A Python package for interactive geospatial analysis and visualization with Google Earth Engine.
* [Chakazul/Lenia](https://github.com/Chakazul/Lenia) - Lenia - Mathematical Life Forms
* [hamuchiwa/AutoRCCar](https://github.com/hamuchiwa/AutoRCCar) - OpenCV Python Neural Network Autonomous RC Car
* [NVIDIA/warp](https://github.com/NVIDIA/warp) - A Python framework for GPU-accelerated simulation, robotics, and machine learning.

## Other

* [public-apis/public-apis](https://github.com/public-apis/public-apis) - A collective list of free APIs
* [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books) - :books: Freely available programming books
* [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) - The agent that grows with you
* [anthropics/skills](https://github.com/anthropics/skills) - Public repository for Agent Skills
* [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) - Stable Diffusion web UI
* [open-webui/open-webui](https://github.com/open-webui/open-webui) - User-friendly AI Interface (Supports Ollama, OpenAI API, ...)
* [anthropics/claude-code](https://github.com/anthropics/claude-code) - Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.
* [ytdl-org/youtube-dl](https://github.com/ytdl-org/youtube-dl) - Command-line program to download videos from YouTube.com and other video sites
* [github/spec-kit](https://github.com/github/spec-kit) - 💫 Toolkit to help you get started with Spec-Driven Development
* [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - An AI skill that provides design intelligence for building professional UI/UX across multiple platforms.
* [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) - Turn any codebase, with its docs, SQL schemas, configs, and PDFs, into a queryable knowledge graph. A /graphify skill for Claude Code, Cursor, Codex, and Gemini CLI: local deterministic AST parsing, every edge explained, no vector store.
* [openai/whisper](https://github.com/openai/whisper) - Robust Speech Recognition via Large-Scale Weak Supervision
* [deepseek-ai/DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3)
* [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) - TradingAgents: Multi-Agents LLM Financial Trading Framework
* [hacksider/Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam) - real time face swap and one-click video deepfake with only a single image
* [karpathy/autoresearch](https://github.com/karpathy/autoresearch) - AI agents running research on single-GPU nanochat training automatically
* [vllm-project/vllm](https://github.com/vllm-project/vllm) - A high-throughput and memory-efficient inference and serving engine for LLMs
* [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) - Turn any PDF or image document into structured data for your AI. A powerful, lightweight OCR toolkit that bridges the gap between images/PDFs and LLMs. Supports 100+ languages.
* [odysseus-dev/odysseus](https://github.com/odysseus-dev/odysseus) - Self-hosted AI workspace.
* [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai) - 🚀🤖 Crawl4AI: Open-source LLM Friendly Web Crawler & Scraper. Don't be shy, join here: https://discord.gg/jP8KfhDhyN
* [swisskyrepo/PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - A list of useful payloads and bypass for Web Application Security and Pentest/CTF
* [Z4nzu/hackingtool](https://github.com/Z4nzu/hackingtool) - ALL IN ONE Hacking Tool For Hackers
* [tensorflow/models](https://github.com/tensorflow/models) - Models and examples built with TensorFlow
* [abi/screenshot-to-code](https://github.com/abi/screenshot-to-code) - Drop in a screenshot and convert it to clean code (HTML/Tailwind/React/Vue)
* [datawhalechina/hello-agents](https://github.com/datawhalechina/hello-agents) - 📚 《从零开始构建智能体》——从零开始的智能体原理与实践教程
* [hiyouga/LlamaFactory](https://github.com/hiyouga/LlamaFactory) - Unified Efficient Fine-Tuning of 100+ LLMs & VLMs (ACL 2024)
* [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) - A curated list of awesome Claude Skills, resources, and tools for customizing Claude AI workflows
* [josephmisiti/awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning) - A curated list of awesome Machine Learning frameworks, libraries and software.
* [666ghj/MiroFish](https://github.com/666ghj/MiroFish) - A Simple and Universal Swarm Intelligence Engine, Predicting Anything. 简洁通用的群体智能引擎，预测万物
* [FoundationAgents/MetaGPT](https://github.com/FoundationAgents/MetaGPT) - 🌟 The Multi-Agent Framework: First AI Software Company, Towards Natural Language Programming
* [labmlai/annotated_deep_learning_paper_implementations](https://github.com/labmlai/annotated_deep_learning_paper_implementations) - 🧑‍🏫 60+ Implementations/tutorials of deep learning papers with side-by-side notes 📝; including transformers (original, xl, switch, feedback, vit, ...), optimizers (adam, adabelief, sophia, ...), gans(cyclegan, stylegan2, ...), 🎮 reinforcement learning (ppo, dqn), capsnet, distillation, ... 🧠
* [docling-project/docling](https://github.com/docling-project/docling) - Get your documents ready for gen AI
* [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) - LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行。 LLM-powered multi-market stock analysis system with multi-source market data, real-time news, decision dashboard, automated notifications, and cost-free scheduled runs.
* [NanmiCoder/MediaCrawler](https://github.com/NanmiCoder/MediaCrawler) - 小红书笔记 | 评论爬虫、抖音视频 | 评论爬虫、快手视频 | 评论爬虫、B 站视频 ｜ 评论爬虫、微博帖子 ｜ 评论爬虫、百度贴吧帖子 ｜ 百度贴吧评论回复爬虫 | 知乎问答文章｜评论爬虫
* [commaai/openpilot](https://github.com/commaai/openpilot) - openpilot is an operating system for robotics. Currently, it upgrades the driver assistance system on 300+ supported cars.
* [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) - An AI Hedge Fund Team
* [karpathy/nanoGPT](https://github.com/karpathy/nanoGPT) - The simplest, fastest repository for training/finetuning medium-sized GPTs.
* [RVC-Boss/GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) - 1 min voice data can also be used to train a good TTS model! (few shot voice cloning)
* [1c7/chinese-independent-developer](https://github.com/1c7/chinese-independent-developer) - 👩🏿‍💻👨🏾‍💻👩🏼‍💻👨🏽‍💻👩🏻‍💻中国独立开发者项目列表 -- 分享大家都在做什么
* [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) - AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary
* [microsoft/autogen](https://github.com/microsoft/autogen) - A programming framework for agentic AI
* [usestrix/strix](https://github.com/usestrix/strix) - Open-source AI penetration testing tool to find and fix your app’s vulnerabilities.
* [meta-llama/llama](https://github.com/meta-llama/llama) - Inference code for Llama models
* [FoundationAgents/OpenManus](https://github.com/FoundationAgents/OpenManus) - No fortress, purely open ground. OpenManus is Coming.
* [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) - Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work together seamlessly, tackling complex tasks.
* [ultralytics/yolov5](https://github.com/ultralytics/yolov5) - Ultralytics YOLOv5 in PyTorch for object detection, instance segmentation, classification, training, and export.
* [karpathy/nanochat](https://github.com/karpathy/nanochat) - The best ChatGPT that $100 can buy.
* [jingyaogong/minimind](https://github.com/jingyaogong/minimind) - 🧠 Train a 64M-parameter LLM from scratch in just 2h!
* [deepfakes/faceswap](https://github.com/deepfakes/faceswap) - Deepfakes Software For All
* [zylon-ai/private-gpt](https://github.com/zylon-ai/private-gpt) - Complete API layer for private AI applications on local models: RAG, skills, tools, MCP, text-to-sql, and more. Works with any OpenAI-compatible inference server.
* [soimort/you-get](https://github.com/soimort/you-get) - :arrow_double_down: Dumb downloader that scrapes the web
* [Zie619/n8n-workflows](https://github.com/Zie619/n8n-workflows) - all of the workflows of n8n i could find (also from the site itself)
* [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) - Open-Source Frontier Voice AI
* [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) - A hand-picked collection of the finest of resources for the most awesome of agents, Claude Code, the undisputed champion of coding companions, from the unstoppable team at Anthropic PBC. A delectable showcase of top tier skills, ambidextrous agents, scintillating status lines, top notch developer tooling, and also we have plugins
* [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code) - Use Claude Code, Codex, Pi, and OpenCode and more for free (1.3B+ free tokens) from your terminal, app, IDE, or phone like OpenClaw (voice supported + ToS friendly)
* [lllyasviel/Fooocus](https://github.com/lllyasviel/Fooocus) - Focus on prompting and generating
* [xai-org/grok-1](https://github.com/xai-org/grok-1) - Grok open release
* [run-llama/llama_index](https://github.com/run-llama/llama_index) - LlamaIndex is the leading document agent and OCR platform
* [charlax/professional-programming](https://github.com/charlax/professional-programming) - A collection of learning resources for curious software engineers
* [hugohe3/ppt-master](https://github.com/hugohe3/ppt-master) - AI turns documents or topics into real, native PowerPoint decks—with native shapes, transitions and animations, data-backed charts and tables on demand, audio narration from speaker notes, and support for your own .pptx templates. · by Hugo He
* [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything) - "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/
* [Aider-AI/aider](https://github.com/Aider-AI/aider) - aider is AI pair programming in your terminal
* [minimaxir/big-list-of-naughty-strings](https://github.com/minimaxir/big-list-of-naughty-strings) - The Big List of Naughty Strings is a list of strings which have a high probability of causing issues when used as user-input data.
* [oobabooga/textgen](https://github.com/oobabooga/textgen) - Open-source desktop app for local LLMs. Text, vision, tool-calling, OpenAI/Anthropic-compatible API. 100% private.
* [exo-explore/exo](https://github.com/exo-explore/exo) - Run frontier AI locally.
* [SimplifyJobs/Summer2027-Internships](https://github.com/SimplifyJobs/Summer2027-Internships) - Summer 2027 software engineering, data science, AI, quant, product management, and hardware internship postings. Updated daily by Simplify and Pitt CSC.
* [hiroi-sora/Umi-OCR](https://github.com/hiroi-sora/Umi-OCR) - OCR software, free and offline. 开源、免费的离线OCR软件。支持截屏/批量导入图片，PDF文档识别，排除水印/页眉页脚，扫描/生成二维码。内置多国语言库。
* [zhayujie/CowAgent](https://github.com/zhayujie/CowAgent) - Open-source super AI assistant & Agent Harness. Plans tasks, runs tools and skills, self-evolves with memory and knowledge. Multi-model, multi-channel. Lightweight, extensible, one-line install. (formerly chatgpt-on-wechat)
* [9001/copyparty](https://github.com/9001/copyparty) - Portable file server with accelerated resumable uploads, dedup, WebDAV, SFTP, FTP, TFTP, zeroconf, media indexer, thumbnails++ all in one file
* [sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) - AAS Core is the local, agent-first control plane for complete catalog discovery, agent-owned selection, stack validation, and planning, backed by 2,005+ agentic skills. Includes CLI, local MCP, catalog, plugins, and Workbench.
* [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) - Academic Research Skills for Claude Code: research → write → review → revise → finalize
* [vnpy/vnpy](https://github.com/vnpy/vnpy) - 基于Python的开源量化交易平台开发框架
* [paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) - A community-supported supercharged document management system: scan, index and archive all your documents
* [bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book) - 《深入理解 AI Agent：设计原理与工程实践》（李博杰 著）开源主仓库：全书正文、编译版 PDF 与按章配套代码
* [ccxt/ccxt](https://github.com/ccxt/ccxt) - A unified trading API with more than 100 crypto exchanges and prediction markets in JavaScript / TypeScript / Python / C# / PHP / Go / Java
* [deepspeedai/DeepSpeed](https://github.com/deepspeedai/DeepSpeed) - DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective.
* [mingrammer/diagrams](https://github.com/mingrammer/diagrams) - :art: Diagram as Code for prototyping cloud system architectures
* [666ghj/BettaFish](https://github.com/666ghj/BettaFish) - 微舆：人人可用的多Agent舆情分析助手，打破信息茧房，还原舆情原貌，预测未来走向，辅助决策！从0实现，不依赖任何框架。
* [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) - Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 190,000+ scientists worldwide. 165 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.
* [chubin/cheat.sh](https://github.com/chubin/cheat.sh) - the only cheat sheet you need
* [hpcaitech/ColossalAI](https://github.com/hpcaitech/ColossalAI) - Making large AI models cheaper, faster and more accessible
* [luongnv89/claude-howto](https://github.com/luongnv89/claude-howto) - A visual, example-driven guide to Claude Code — from basic concepts to advanced agents, with copy-paste templates that bring immediate value.
* [zai-org/ChatGLM-6B](https://github.com/zai-org/ChatGLM-6B) - ChatGLM-6B: An Open Bilingual Dialogue Language Model | 开源双语对话语言模型
* [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search) - The job search that runs on your machine. AI job application framework built on Claude Code: evaluate postings, tailor CVs, write cover letters, prep interviews. Fork it and own it.
* [google-research/bert](https://github.com/google-research/bert) - TensorFlow code and pre-trained models for BERT *(archived)*
* [blader/humanizer](https://github.com/blader/humanizer) - Agent skill that removes signs of AI-generated writing from text
* [floodsung/Deep-Learning-Papers-Reading-Roadmap](https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap) - Deep Learning papers reading roadmap for anyone who are eager to learn this amazing tech!
* [lm-sys/FastChat](https://github.com/lm-sys/FastChat) - An open platform for training, serving, and evaluating large language models. Release repo for Vicuna and Chatbot Arena.
* [datalab-to/marker](https://github.com/datalab-to/marker) - Convert PDF to markdown + JSON quickly with high accuracy
* [The-Vibe-Company/quivr](https://github.com/The-Vibe-Company/quivr) - Opiniated RAG for integrating GenAI in your apps 🧠 Focus on your product rather than the RAG. Easy integration in existing products with customisation! Any LLM: GPT4, Groq, Llama. Any Vectorstore: PGVector, Faiss. Any Files. Anyway you want.
* [wshobson/agents](https://github.com/wshobson/agents) - Multi-harness agentic plugin marketplace for Claude Code, Codex, Cursor, OpenCode, GitHub Copilot, and Google Antigravity
* [HKUDS/LightRAG](https://github.com/HKUDS/LightRAG) - [EMNLP2025] LightRAG: Simple and Fast Retrieval-Augmented Generation
* [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) - 符合nature论文学术表达和科研绘图的Skill
* [chatchat-space/Langchain-Chatchat](https://github.com/chatchat-space/Langchain-Chatchat) - Langchain-Chatchat（原Langchain-ChatGLM）基于 Langchain 与 ChatGLM, Qwen 与 Llama 等语言模型的 RAG 与 Agent 应用 | Langchain-Chatchat (formerly langchain-ChatGLM), local knowledge based LLM (like ChatGLM, Qwen and Llama) RAG and Agent app with langchain
* [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor) - DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/.
* [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) - Kronos: A Foundation Model for the Language of Financial Markets
* [RVC-Project/Retrieval-based-Voice-Conversion-WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI) - Easily train a good VC model with voice data <= 10 mins!
* [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy) - DSPy: The framework for programming—not prompting—language models
* [TencentARC/GFPGAN](https://github.com/TencentARC/GFPGAN) - GFPGAN aims at developing Practical Algorithms for Real-world Face Restoration.
* [myshell-ai/OpenVoice](https://github.com/myshell-ai/OpenVoice) - Instant voice cloning by MIT and MyShell. Audio foundation model.
* [ashishpatel26/500-AI-Agents-Projects](https://github.com/ashishpatel26/500-AI-Agents-Projects) - The 500 AI Agents Projects is a curated collection of AI agent use cases across various industries. It showcases practical applications and provides links to open-source projects for implementation, illustrating how AI agents are transforming sectors such as healthcare, finance, education, retail, and more.
* [openai/gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms. *(archived)*
* [0voice/interview_internal_reference](https://github.com/0voice/interview_internal_reference) - 2025年最新总结，阿里，腾讯，百度，美团，头条等技术面试题目，以及答案，专家出题人分析汇总。
* [huggingface/pytorch-image-models](https://github.com/huggingface/pytorch-image-models) - The largest collection of PyTorch image encoders / backbones. Including train, eval, inference, export scripts, and pretrained weights -- ResNet, ResNeXT, EfficientNet, NFNet, Vision Transformer (ViT), MobileNetV4, MobileNet-V3 & V2, RegNet, DPN, CSPNet, Swin Transformer, MaxViT, CoAtNet, ConvNeXt, and more
* [khoj-ai/khoj](https://github.com/khoj-ai/khoj) - Your AI second brain. Self-hostable. Get answers from the web or your docs. Build custom agents, schedule automations, do deep research. Turn any online or local LLM into your personal, autonomous AI (gpt, claude, gemini, llama, qwen, mistral). Get started - free.
* [babysor/MockingBird](https://github.com/babysor/MockingBird) - 🚀Clone a voice in 5 seconds to generate arbitrary speech in real-time
* [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) - Real-ESRGAN aims at developing Practical Algorithms for General Image/Video Restoration.
* [hankcs/HanLP](https://github.com/hankcs/HanLP) - 中文分词 词性标注 命名实体识别 依存句法分析 成分句法分析 语义依存分析 语义角色标注 指代消解 风格转换 语义相似度 新词发现 关键词短语提取 自动摘要 文本分类聚类 拼音简繁转换 自然语言处理
* [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) - Official, Anthropic-managed directory of high quality Claude Code Plugins.
* [microsoft/graphrag](https://github.com/microsoft/graphrag) - A modular graph-based Retrieval-Augmented Generation (RAG) system
* [XingangPan/DragGAN](https://github.com/XingangPan/DragGAN) - Official Code for DragGAN (SIGGRAPH 2023)
* [VectifyAI/PageIndex](https://github.com/VectifyAI/PageIndex) - 📑 PageIndex: Document Index for Vectorless, Reasoning-based RAG
* [fxsjy/jieba](https://github.com/fxsjy/jieba) - 结巴中文分词
* [volcengine/OpenViking](https://github.com/volcengine/OpenViking) - Self-evolving Context Database for AI Agents. Unify Agent Memory, Knowledge RAG and Skills.
* [agentscope-ai/QwenPaw](https://github.com/agentscope-ai/QwenPaw) - Your Personal AI Assistant; easy to install, deploy on your own machine or on the cloud; supports multiple chat apps with easily extensible capabilities.
* [facebookresearch/detectron2](https://github.com/facebookresearch/detectron2) - Detectron2 is a platform for object detection, segmentation and other visual recognition tasks.
* [anthropics/financial-services](https://github.com/anthropics/financial-services)
* [huggingface/diffusers](https://github.com/huggingface/diffusers) - 🤗 Diffusers: State-of-the-art diffusion models for image, video, and audio generation in PyTorch.
* [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev) - ChatDev 2.0: Dev All through LLM-powered Multi-Agent Collaboration
* [lllyasviel/ControlNet](https://github.com/lllyasviel/ControlNet) - Let us control diffusion models!
* [testerSunshine/12306](https://github.com/testerSunshine/12306) - 12306智能刷票，订票 *(archived)*
* [chenfei-wu/TaskMatrix](https://github.com/chenfei-wu/TaskMatrix)
* [Pythagora-io/gpt-pilot](https://github.com/Pythagora-io/gpt-pilot) - The first real AI developer
* [shadowsocks/shadowsocks](https://github.com/shadowsocks/shadowsocks)
* [tinygrad/tinygrad](https://github.com/tinygrad/tinygrad) - You like pytorch? You like micrograd? You love tinygrad! ❤️
* [dgtlmoon/changedetection.io](https://github.com/dgtlmoon/changedetection.io) - Best and simplest tool for website change detection, web page monitoring, and website change alerts. Perfect for tracking content changes, price drops, restock alerts, and website defacement monitoring—all for free or enjoy our SaaS plan!
* [XX-net/XX-Net](https://github.com/XX-net/XX-Net) - A proxy tool to bypass GFW.
* [sgl-project/sglang](https://github.com/sgl-project/sglang) - SGLang is a high-performance serving framework for large language models and multimodal models.
* [certbot/certbot](https://github.com/certbot/certbot) - Certbot is EFF's tool to obtain certs from Let's Encrypt and (optionally) auto-enable HTTPS on your server. It can also act as a client for any other CA that uses the ACME protocol.
* [OWASP/CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries) - The OWASP Cheat Sheet Series was created to provide a concise collection of high value information on specific application security topics.
* [0xAX/linux-insides](https://github.com/0xAX/linux-insides) - A book-in-progress about the Linux kernel and its insides.
* [open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection) - OpenMMLab Detection Toolbox and Benchmark
* [eriklindernoren/ML-From-Scratch](https://github.com/eriklindernoren/ML-From-Scratch) - Machine Learning From Scratch. Bare bones NumPy implementations of machine learning models and algorithms with a focus on accessibility. Aims to cover everything from linear regression to deep learning.
* [fishaudio/fish-speech](https://github.com/fishaudio/fish-speech) - SOTA Open Source TTS
* [yunjey/pytorch-tutorial](https://github.com/yunjey/pytorch-tutorial) - PyTorch Tutorial for Deep Learning Researchers
* [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) - 817 structured cybersecurity skills for AI agents · Mapped to 6 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND, NIST AI RMF & MITRE F3 (Fight Fraud) · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 29 security domains · Apache 2.0
* [alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill) - 你想蒸馏的下一个员工，何必是同事。蒸馏任何人的思维方式——心智模型、决策启发式、表达DNA。Distill how anyone thinks.
* [hsliuping/TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN) - 基于多智能体LLM的中文金融交易框架 - TradingAgents中文增强版
* [stanford-oval/storm](https://github.com/stanford-oval/storm) - An LLM-powered knowledge curation system that researches a topic and generates a full-length report with citations.
* [iperov/DeepFaceLive](https://github.com/iperov/DeepFaceLive) - Real-time face swap for PC streaming or video calls *(archived)*
* [getzep/graphiti](https://github.com/getzep/graphiti) - Build Real-Time Knowledge Graphs for AI Agents
* [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) - CLI tool for configuring and monitoring Claude Code
* [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) - Build and run agents you can see, understand and trust.
* [topoteretes/cognee](https://github.com/topoteretes/cognee) - Cognee is the open-source AI memory platform for agents. Give your AI agents persistent long-term memory across sessions with a self-hosted knowledge graph engine.
* [trailofbits/algo](https://github.com/trailofbits/algo) - Set up a personal VPN in the cloud
* [tatsu-lab/stanford_alpaca](https://github.com/tatsu-lab/stanford_alpaca) - Code and documentation to train Stanford's Alpaca models, and generate the data.
* [p-e-w/heretic](https://github.com/p-e-w/heretic) - Fully automatic censorship removal for language models
* [Genesis-Embodied-AI/genesis-world](https://github.com/Genesis-Embodied-AI/genesis-world) - Simulation platform for general-purpose robotics & embodied AI learning.
* [facefusion/facefusion](https://github.com/facefusion/facefusion) - Industry leading face manipulation platform
* [deepinsight/insightface](https://github.com/deepinsight/insightface) - State-of-the-art 2D and 3D Face Analysis Project
* [521xueweihan/GitHub520](https://github.com/521xueweihan/GitHub520) - :kissing_heart: 让你“爱”上 GitHub，解决访问时图裂、加载慢的问题。（无需安装）
* [hpcaitech/Open-Sora](https://github.com/hpcaitech/Open-Sora) - Open-Sora: Democratizing Efficient Video Production for All
* [google-research/timesfm](https://github.com/google-research/timesfm) - TimesFM (Time Series Foundation Model) is a pretrained time-series foundation model developed by Google Research for time-series forecasting.
* [meta-llama/llama3](https://github.com/meta-llama/llama3) - The official Meta Llama 3 GitHub site *(archived)*
* [oraios/serena](https://github.com/oraios/serena) - A powerful MCP toolkit for coding, providing semantic retrieval and editing capabilities - the IDE for your agent
* [subframe7536/maple-font](https://github.com/subframe7536/maple-font) - Maple Mono: Open source monospace font with round corner, ligatures and Nerd-Font icons for IDE and terminal, fine-grained customization options. 带连字和控制台图标的圆角等宽字体，中英文宽度完美2:1，细粒度的自定义选项
* [deezer/spleeter](https://github.com/deezer/spleeter) - Deezer source separation library including pretrained models.
* [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader) - Production-grade Rust-native trading engine with deterministic event-driven architecture
* [svc-develop-team/so-vits-svc](https://github.com/svc-develop-team/so-vits-svc) - SoftVC VITS Singing Voice Conversion *(archived)*
* [invoke-ai/InvokeAI](https://github.com/invoke-ai/InvokeAI) - Invoke is a leading creative engine for Stable Diffusion models, empowering professionals, artists, and enthusiasts to generate and create visual media using the latest AI-driven technologies. The solution offers an industry leading WebUI, and serves as the foundation for multiple commercial products.
* [harvard-edge/cs249r_book](https://github.com/harvard-edge/cs249r_book) - Machine Learning Systems
* [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) - Turn any technical book PDF into a Claude Code skill — ready to study, reference, and use while you work.
* [acheong08/ChatGPT](https://github.com/acheong08/ChatGPT) - Reverse engineered ChatGPT API *(archived)*
* [microsoft/cascadia-code](https://github.com/microsoft/cascadia-code) - This is a fun, new monospaced font that includes programming ligatures and is designed to enhance the modern look and feel of the Windows Terminal.
* [mlflow/mlflow](https://github.com/mlflow/mlflow) - The open source AI engineering platform for agents, LLMs, and ML models. MLflow enables teams of all sizes to debug, evaluate, monitor, and optimize production-quality AI applications while controlling costs and managing access to models and data.
* [ATH-MaaS/Pixelle-Video](https://github.com/ATH-MaaS/Pixelle-Video) - 🚀 AI 全自动短视频引擎 | AI Fully Automated Short Video Engine
* [QwenLM/Qwen3](https://github.com/QwenLM/Qwen3) - Qwen3 is the large language model series developed by Qwen team, Alibaba Cloud.
* [ungoogled-software/ungoogled-chromium](https://github.com/ungoogled-software/ungoogled-chromium) - Google Chromium, sans integration with Google
* [squidfunk/mkdocs-material](https://github.com/squidfunk/mkdocs-material) - Documentation that simply works
* [Stability-AI/generative-models](https://github.com/Stability-AI/generative-models) - Generative Models by Stability AI
* [huggingface/lerobot](https://github.com/huggingface/lerobot) - 🤗 LeRobot: Making AI for Robotics more accessible with end-to-end learning
* [Fosowl/agenticSeek](https://github.com/Fosowl/agenticSeek) - Fully Local Manus AI. No APIs, No $200 monthly bills. Enjoy an autonomous agent that thinks, browses the web, and code for the sole cost of electricity.
* [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) - A skill to stop your coding agent from burying the answer. ADHD-friendly output.
* [littlecodersh/ItChat](https://github.com/littlecodersh/ItChat) - A complete and graceful API for Wechat. 微信个人号接口、微信机器人及命令行微信，三十行即可自定义个人号机器人。
* [huggingface/open-r1](https://github.com/huggingface/open-r1) - Fully open reproduction of DeepSeek-R1
* [emmabostian/developer-portfolios](https://github.com/emmabostian/developer-portfolios) - A list of developer portfolios for your inspiration
* [WZMIAOMIAO/deep-learning-for-image-processing](https://github.com/WZMIAOMIAO/deep-learning-for-image-processing) - deep learning for image processing including classification and object-detection etc.
* [facebookresearch/Detectron](https://github.com/facebookresearch/Detectron) - FAIR's research platform for object detection research, implementing popular algorithms like Mask R-CNN and RetinaNet. *(archived)*
* [OpenBMB/MiniCPM-V](https://github.com/OpenBMB/MiniCPM-V) - A Pocket-Sized MLLM for Ultra-Efficient Image and Video Understanding on Your Phone
* [resemble-ai/chatterbox](https://github.com/resemble-ai/chatterbox) - SoTA open-source TTS
* [zai-org/Open-AutoGLM](https://github.com/zai-org/Open-AutoGLM) - An Open Phone Agent Model & Framework. Unlocking the AI Phone for Everyone
* [Anjok07/ultimatevocalremovergui](https://github.com/Anjok07/ultimatevocalremovergui) - GUI for a Vocal Remover that uses Deep Neural Networks.
* [black-forest-labs/flux](https://github.com/black-forest-labs/flux) - Official inference repo for FLUX.1 models
* [ycm-core/YouCompleteMe](https://github.com/ycm-core/YouCompleteMe) - A code-completion engine for Vim
* [Cinnamon/kotaemon](https://github.com/Cinnamon/kotaemon) - An open-source RAG-based tool for chatting with your documents.
* [Vision-CAIR/MiniGPT-4](https://github.com/Vision-CAIR/MiniGPT-4) - Open-sourced codes for MiniGPT-4 and MiniGPT-v2 (https://minigpt-4.github.io, https://minigpt-v2.github.io/)
* [matterport/Mask_RCNN](https://github.com/matterport/Mask_RCNN) - Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow
* [lucidrains/vit-pytorch](https://github.com/lucidrains/vit-pytorch) - Implementation of Vision Transformer, a simple way to achieve SOTA in vision classification with only a single transformer encoder, in Pytorch
* [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) - 380 Claude Code skills & agent skills & plugins (30+ Agents, 70+ custom commands, 380+ skills, customizable references, scripts)for Claude Code, Codex, Gemini CLI, Cursor, and 8 more coding agents — engineering, marketing, product, compliance, C-level advisory, research, business operations, commercial & finance, and your daily productivity skills.
* [openai/skills](https://github.com/openai/skills) - Skills Catalog for Codex
* [goauthentik/authentik](https://github.com/goauthentik/authentik) - The authentication glue you need.
* [junyanz/pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) - Image-to-Image Translation in PyTorch
* [microsoft/JARVIS](https://github.com/microsoft/JARVIS) - JARVIS, a system to connect LLMs with ML community. Paper: https://arxiv.org/pdf/2303.17580.pdf
* [SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper) - Faster Whisper transcription with CTranslate2
* [ranaroussi/yfinance](https://github.com/ranaroussi/yfinance) - Download market data from Yahoo! Finance's API
* [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) - Unlimited OCR Works: Welcome the Era of One-shot Long-horizon Parsing.
* [Guovin/iptv-api](https://github.com/Guovin/iptv-api) - ⚡️ IPTV直播源自动更新工具：自动采集、校验、测速并生成可播放结果，支持 M3U/TXT/API 输出、自定义频道、IPv4/IPv6、Docker、GitHub Actions、CLI 与 GUI 多端部署
* [HumanSignal/labelImg](https://github.com/HumanSignal/labelImg) - LabelImg is now part of the Label Studio community. The popular image annotation tool created by Tzutalin is no longer actively being developed, but you can check out Label Studio, the open source data labeling tool for images, text, hypertext, audio, video and time-series data. *(archived)*
* [openai/gpt-2](https://github.com/openai/gpt-2) - Code for the paper "Language Models are Unsupervised Multitask Learners" *(archived)*
* [haotian-liu/LLaVA](https://github.com/haotian-liu/LLaVA) - [NeurIPS'23 Oral] Visual Instruction Tuning (LLaVA) built towards GPT-4V level capabilities and beyond.
* [agentskills/agentskills](https://github.com/agentskills/agentskills) - Specification and documentation for Agent Skills
* [karpathy/minGPT](https://github.com/karpathy/minGPT) - A minimal PyTorch re-implementation of the OpenAI GPT (Generative Pretrained Transformer) training
* [Dao-AILab/flash-attention](https://github.com/Dao-AILab/flash-attention) - Fast and memory-efficient exact attention
* [karpathy/llm-council](https://github.com/karpathy/llm-council) - LLM Council works together to answer your hardest questions
* [titanwings/distilly](https://github.com/titanwings/distilly) - Distilly — Distill how they think into reusable Skills for any Agent or Bot. Formerly Colleague Skill（原同事 Skill）.
* [deepseek-ai/DeepSeek-Coder](https://github.com/deepseek-ai/DeepSeek-Coder) - DeepSeek Coder: Let the Code Write Itself
* [Delgan/loguru](https://github.com/Delgan/loguru) - Python logging made (stupidly) simple
* [pyg-team/pytorch_geometric](https://github.com/pyg-team/pytorch_geometric) - Graph Neural Network Library for PyTorch
* [pytorch/examples](https://github.com/pytorch/examples) - A set of examples around pytorch in Vision, Text, Reinforcement Learning, etc.
* [timqian/chinese-independent-blogs](https://github.com/timqian/chinese-independent-blogs) - 中文独立博客列表
* [deepseek-ai/DeepSeek-OCR](https://github.com/deepseek-ai/DeepSeek-OCR) - Contexts Optical Compression
* [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) - A configuration framework that enhances Claude Code with specialized commands, cognitive personas, and development methodologies.
* [m-bain/whisperX](https://github.com/m-bain/whisperX) - WhisperX: Automatic Speech Recognition with Word-level Timestamps (& Diarization)
* [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) - Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork
* [vanna-ai/vanna](https://github.com/vanna-ai/vanna) - 🤖 Chat with your SQL database 📊. Accurate Text-to-SQL Generation via LLMs using Agentic Retrieval 🔄. *(archived)*
* [graphdeco-inria/gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting) - Original reference implementation of "3D Gaussian Splatting for Real-Time Radiance Field Rendering"
* [index-tts/index-tts](https://github.com/index-tts/index-tts) - An Industrial-Level Controllable and Efficient Zero-Shot Text-To-Speech System
* [Vonng/ddia](https://github.com/Vonng/ddia) - 《Designing Data-Intensive Application》DDIA 第一版 / 第二版 中文翻译
* [browser-use/video-use](https://github.com/browser-use/video-use) - Edit videos with coding agents
* [Sanster/IOPaint](https://github.com/Sanster/IOPaint) - Image inpainting tool powered by SOTA AI Model. Remove any unwanted object, defect, people from your pictures or erase and replace(powered by stable diffusion) any thing on your pictures. *(archived)*
* [verl-project/verl](https://github.com/verl-project/verl) - verl/HybridFlow: A Flexible and Efficient RL Post-Training Framework
* [HKUDS/RAG-Anything](https://github.com/HKUDS/RAG-Anything) - "RAG-Anything: All-in-One RAG Framework"
* [wangzheng0822/algo](https://github.com/wangzheng0822/algo) - 数据结构和算法必知必会的50个代码实现
* [mlc-ai/mlc-llm](https://github.com/mlc-ai/mlc-llm) - Universal LLM Deployment Engine with ML Compilation
* [mementum/backtrader](https://github.com/mementum/backtrader) - Python Backtesting library for trading strategies
* [sebastianruder/NLP-progress](https://github.com/sebastianruder/NLP-progress) - Repository to track the progress in Natural Language Processing (NLP), including the datasets and the current state-of-the-art for the most common NLP tasks.
* [magic-wormhole/magic-wormhole](https://github.com/magic-wormhole/magic-wormhole) - get things from one computer to another, safely
* [2025Emma/vibe-coding-cn](https://github.com/2025Emma/vibe-coding-cn)
* [1Panel-dev/MaxKB](https://github.com/1Panel-dev/MaxKB) - 🔥 MaxKB is an open-source platform for building enterprise-grade agents. 强大易用的开源企业级智能体平台。
* [akfamily/akshare](https://github.com/akfamily/akshare) - AKShare is an elegant and simple financial data interface library for Python, built for human beings! 开源财经数据接口库
* [yoheinakajima/babyagi](https://github.com/yoheinakajima/babyagi)
* [PromtEngineer/localGPT](https://github.com/PromtEngineer/localGPT) - Chat with your documents on your local device using GPT models. No data leaves your device and 100% private.
* [microsoft/unilm](https://github.com/microsoft/unilm) - Large-scale Self-supervised Pre-training Across Tasks, Languages, and Modalities
* [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) - Hindsight: Agent Memory That Learns
* [HKUDS/AI-Trader](https://github.com/HKUDS/AI-Trader) - "AI-Trader: 100% Fully-Automated Agent-Native Trading"
* [XiaoMi/ha_xiaomi_home](https://github.com/XiaoMi/ha_xiaomi_home) - Xiaomi Home Integration for Home Assistant
* [openai/swarm](https://github.com/openai/swarm) - Educational framework exploring ergonomic, lightweight multi-agent orchestration. Managed by OpenAI Solution team.
* [huggingface/datasets](https://github.com/huggingface/datasets) - 🤗 The largest hub of ready-to-use datasets for AI models with fast, easy-to-use and efficient data manipulation tools
* [jina-ai/serve](https://github.com/jina-ai/serve) - ☁️ Build multimodal AI applications with cloud-native stack
* [comet-ml/opik](https://github.com/comet-ml/opik) - Debug, evaluate, and monitor your LLM applications, RAG systems, and agentic workflows with comprehensive tracing, automated evaluations, and production-ready dashboards.
* [anderspitman/awesome-tunneling](https://github.com/anderspitman/awesome-tunneling) - List of ngrok, Cloudflare Tunnel, Tailscale, and ZeroTier alternatives and other tunneling software and services. Focus on self-hosting.
* [QwenLM/Qwen](https://github.com/QwenLM/Qwen) - The official repo of Qwen (通义千问) chat & pretrained large language model proposed by Alibaba Cloud.
* [Zeyi-Lin/HivisionIDPhotos](https://github.com/Zeyi-Lin/HivisionIDPhotos) - ⚡️HivisionIDPhotos: a lightweight and efficient AI ID photos tools. 一个轻量级的AI证件照制作算法。
* [onnx/onnx](https://github.com/onnx/onnx) - Open standard for machine learning interoperability
* [datalab-to/surya](https://github.com/datalab-to/surya) - OCR, layout analysis, reading order, table recognition in 90+ languages
* [jundot/omlx](https://github.com/jundot/omlx) - LLM inference server with continuous batching & SSD caching for Apple Silicon — managed from the macOS menu bar
* [RasaHQ/rasa](https://github.com/RasaHQ/rasa) - 💬 Open source machine learning framework to automate text- and voice-based conversations: NLU, dialogue management, connect to Slack, Facebook, and more - Create chatbots and voice assistants
* [chidiwilliams/buzz](https://github.com/chidiwilliams/buzz) - Buzz transcribes and translates audio offline on your personal computer. Powered by OpenAI's Whisper.
* [LiLittleCat/awesome-free-chatgpt](https://github.com/LiLittleCat/awesome-free-chatgpt) - 🆓免费的 ChatGPT 镜像网站列表，持续更新。List of free ChatGPT mirror sites, continuously updated.
* [openai/chatgpt-retrieval-plugin](https://github.com/openai/chatgpt-retrieval-plugin) - The ChatGPT Retrieval Plugin lets you easily find personal or work documents by asking questions in natural language.
* [w-okada/voice-changer](https://github.com/w-okada/voice-changer) - リアルタイムボイスチェンジャー Realtime Voice Changer
* [KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills) - 数字生命卡兹克开源的 AI Skills 合集 | Agent Skills: leader（帮你定义目标）, neat-freak 洁癖, hv-analysis, khazix-writer & more — Claude Code, Codex & 40+ agents
* [openai/gpt-oss](https://github.com/openai/gpt-oss) - gpt-oss-120b and gpt-oss-20b are two open-weight language models by OpenAI
* [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) - SWE-agent takes a GitHub issue and tries to automatically fix it, using your LM of choice. It can also be employed for offensive cybersecurity or competitive coding challenges. [NeurIPS 2024]
* [Free-TV/IPTV](https://github.com/Free-TV/IPTV) - M3U Playlist for free TV channels
* [modelscope/FunASR](https://github.com/modelscope/FunASR) - Open-source speech recognition toolkit for training, inference, streaming ASR, VAD, punctuation, speaker diarization pipelines, and OpenAI-compatible/MCP serving.
* [camel-ai/owl](https://github.com/camel-ai/owl) - 🦉 OWL: Optimized Workforce Learning for General Multi-Agent Assistance in Real-World Task Automation
* [DrewThomasson/ebook2audiobook](https://github.com/DrewThomasson/ebook2audiobook) - Generate audiobooks from e-books, voice cloning & 1158+ languages!
* [quantopian/zipline](https://github.com/quantopian/zipline) - Zipline, a Pythonic Algorithmic Trading Library
* [guillaumemeyer/watermarks-remover](https://github.com/guillaumemeyer/watermarks-remover) - A privacy-first app that strips AI watermarks from content you own.
* [Alibaba-NLP/DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) - Tongyi Deep Research, the Leading Open-source Deep Research Agent
* [nginx-proxy/nginx-proxy](https://github.com/nginx-proxy/nginx-proxy) - Automated Nginx Reverse Proxy for Docker
* [rsms/inter](https://github.com/rsms/inter) - The Inter font family
* [eosphoros-ai/DB-GPT](https://github.com/eosphoros-ai/DB-GPT) - open-source agentic AI data assistant for the next generation of AI + Data products.
* [magenta/magenta](https://github.com/magenta/magenta) - Magenta: Music and Art Generation with Machine Intelligence *(archived)*
* [kaixindelele/ChatPaper](https://github.com/kaixindelele/ChatPaper) - Use ChatGPT to summarize the arXiv papers. 全流程加速科研，利用chatgpt进行论文全文总结+专业翻译+润色+审稿+审稿回复
* [pluja/awesome-privacy](https://github.com/pluja/awesome-privacy) - Awesome Privacy - A curated list of services and alternatives that respect your privacy because PRIVACY MATTERS.
* [stitionai/devika](https://github.com/stitionai/devika) - Devika is the first open-source implementation of an Agentic Software Engineer. Initially started as an open-source alternative to Devin.
* [mxrch/GHunt](https://github.com/mxrch/GHunt) - 🕵️‍♂️ Offensive Google framework.
* [kvcache-ai/ktransformers](https://github.com/kvcache-ai/ktransformers) - A Flexible Framework for Experiencing Heterogeneous LLM Inference/Fine-tune Optimizations
* [allenai/olmocr](https://github.com/allenai/olmocr) - Toolkit for linearizing PDFs for LLM datasets/training
* [mikf/gallery-dl](https://github.com/mikf/gallery-dl) - Command-line program to download image galleries and collections from several image hosting sites
* [nari-labs/dia](https://github.com/nari-labs/dia) - A TTS model capable of generating ultra-realistic dialogue in one pass.
* [openai/evals](https://github.com/openai/evals) - Evals is a framework for evaluating LLMs and LLM systems, and an open-source registry of benchmarks.
* [iperov/DeepFaceLab](https://github.com/iperov/DeepFaceLab) - DeepFaceLab is the leading software for creating deepfakes. *(archived)*
* [google/skills](https://github.com/google/skills) - Agent Skills for Google products and technologies
* [huggingface/trl](https://github.com/huggingface/trl) - Train transformer language models with reinforcement learning.
* [openai/tiktoken](https://github.com/openai/tiktoken) - tiktoken is a fast BPE tokeniser for use with OpenAI's models.
* [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers) - State-of-the-Art Embeddings, Retrieval, and Reranking
* [agent0ai/agent-zero](https://github.com/agent0ai/agent-zero) - Agent Zero AI framework
* [KlingAIResearch/LivePortrait](https://github.com/KlingAIResearch/LivePortrait) - Bring portraits to life!
* [lss233/kirara-ai](https://github.com/lss233/kirara-ai) - 🤖 可 DIY 的 多模态 AI 聊天机器人 | 🚀 快速接入 微信、 QQ、Telegram、等聊天平台 | 🦈支持DeepSeek、Grok、Claude、Ollama、Gemini、OpenAI | 工作流系统、网页搜索、AI画图、人设调教、虚拟女仆、语音对话 |
* [ymcui/Chinese-LLaMA-Alpaca](https://github.com/ymcui/Chinese-LLaMA-Alpaca) - 中文LLaMA&Alpaca大语言模型+本地CPU/GPU训练部署 (Chinese LLaMA & Alpaca LLMs)
* [jianchang512/pyvideotrans](https://github.com/jianchang512/pyvideotrans) - Translate the video from one language to another and embed dubbing & subtitles.
* [state-spaces/mamba](https://github.com/state-spaces/mamba) - Mamba SSM architecture
* [ActivityWatch/activitywatch](https://github.com/ActivityWatch/activitywatch) - The best free and open-source automated time tracker. Cross-platform, extensible, privacy-focused.
* [miloyip/game-programmer](https://github.com/miloyip/game-programmer) - A Study Path for Game Programmer
* [pyscript/pyscript](https://github.com/pyscript/pyscript) - An open source platform for Python in the browser. https://pyscript.net Docs: https://docs.pyscript.net/ Try it: https://pyscript.com/ Community: https://discord.gg/HxvBtukrg2
* [iii-hq/iii](https://github.com/iii-hq/iii) - Effortlessly compose, extend, and observe every service in real-time for the first time ever.
* [bbfamily/abu](https://github.com/bbfamily/abu) - 阿布量化交易系统(股票，期权，期货，比特币，机器学习) 基于python的开源量化交易，量化投资架构
* [jantic/DeOldify](https://github.com/jantic/DeOldify) - A Deep Learning based project for colorizing and restoring old images (and video!) *(archived)*
* [NVIDIA-NeMo/Speech](https://github.com/NVIDIA-NeMo/Speech) - A scalable generative AI framework built for researchers and developers working on Large Language Models, Multimodal, and Speech AI (Automatic Speech Recognition and Text-to-Speech)
* [Huanshere/VideoLingo](https://github.com/Huanshere/VideoLingo) - Netflix-level subtitle cutting, translation, alignment, and even dubbing - one-click fully automated AI video subtitle team | Netflix级字幕切割、翻译、对齐、甚至加上配音，一键全自动视频搬运AI字幕组
* [MustardChef/WSABuilds](https://github.com/MustardChef/WSABuilds) - Run Windows Subsystem For Android on your Windows 10 and Windows 11 PC using prebuilt binaries with Google Play Store (MindTheGapps) and/or Magisk or KernelSU (root solutions) built in.
* [xming521/WeClone](https://github.com/xming521/WeClone) - 🚀 One-stop solution for creating your AI twin from chat history 💡 Fine-tune LLMs with your chat logs to capture your unique style, then bind to a chatbot to bring your digital self to life.
* [dortania/OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher) - Experience macOS just like before
* [sczhou/CodeFormer](https://github.com/sczhou/CodeFormer) - [NeurIPS 2022] Towards Robust Blind Face Restoration with Codebook Lookup Transformer
* [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) - Hermes WebUI: The best way to use Hermes Agent from the web or from your phone!
* [google/magika](https://github.com/google/magika) - Fast and accurate AI powered file content types detection
* [apple/ml-stable-diffusion](https://github.com/apple/ml-stable-diffusion) - Stable Diffusion with Core ML on Apple Silicon
* [microsoft/agent-lightning](https://github.com/microsoft/agent-lightning) - The absolute trainer to light up AI agents.
* [mnielsen/neural-networks-and-deep-learning](https://github.com/mnielsen/neural-networks-and-deep-learning) - Code samples for my book "Neural Networks and Deep Learning"
* [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering) - A comprehensive collection of Agent Skills for context engineering, multi-agent architectures, and production agent systems. Use when building, optimizing, or debugging agent systems that require effective context management.
* [pytorch/vision](https://github.com/pytorch/vision) - Datasets, Transforms and Models specific to Computer Vision
* [AsyncFuncAI/deepwiki-open](https://github.com/AsyncFuncAI/deepwiki-open) - Open Source DeepWiki: AI-Powered Wiki Generator for GitHub/Gitlab/Bitbucket Repositories. Join the discord: https://discord.gg/gMwThUMeme
* [Mikubill/sd-webui-controlnet](https://github.com/Mikubill/sd-webui-controlnet) - WebUI extension for ControlNet
* [deepseek-ai/Janus](https://github.com/deepseek-ai/Janus) - Janus-Series: Unified Multimodal Understanding and Generation Models
* [Diolinux/PhotoGIMP](https://github.com/Diolinux/PhotoGIMP) - A Patch for GIMP 3+ for Photoshop Users
* [NVIDIA/Megatron-LM](https://github.com/NVIDIA/Megatron-LM) - Ongoing research training transformer models at scale
* [camel-ai/camel](https://github.com/camel-ai/camel) - 🐫 CAMEL: The first and the best multi-agent framework. Finding the Scaling Law of Agents. https://www.camel-ai.org
* [langbot-app/LangBot](https://github.com/langbot-app/LangBot) - Production-grade platform for building agentic IM bots - 生产级多平台智能机器人开发平台/ Agent、知识库编排、插件系统 / Bots for Discord / Slack / LINE / Telegram / WeChat(企业微信, 企微智能机器人, 公众号) / 飞书 / 钉钉 / QQ / Matrix e.g. Integrated with ChatGPT(GPT), DeepSeek, Dify, n8n, Langflow, Coze, Claude, Gemini, GLM, Ollama, SiliconFlow, Moonshot, openclaw / hermes agent, deerflow
* [tensorflow/tensor2tensor](https://github.com/tensorflow/tensor2tensor) - Library of deep learning models and datasets designed to make deep learning more accessible and accelerate ML research. *(archived)*
* [Canner/WrenAI](https://github.com/Canner/WrenAI) - GenBI (Generative BI) for AI agents, an open-source, governed text-to-SQL through an open context layer that turns natural-language questions into trusted dashboards, charts, and SQL across 20+ data sources, such as BigQuery, Snowflake, PostgreSQL, ClickHouse, Amazon Redshift, Databricks and more.
* [eriklindernoren/PyTorch-GAN](https://github.com/eriklindernoren/PyTorch-GAN) - PyTorch implementations of Generative Adversarial Networks.
* [ranger/ranger](https://github.com/ranger/ranger) - A VIM-inspired filemanager for the console
* [Wan-Video/Wan2.2](https://github.com/Wan-Video/Wan2.2) - Wan: Open and Advanced Large-Scale Video Generative Models
* [browser-use/browser-harness](https://github.com/browser-use/browser-harness) - Browser Harness | Self-healing harness that enables LLMs to complete any task.
* [lllyasviel/FramePack](https://github.com/lllyasviel/FramePack) - Lets make video diffusion practical!
* [andrewyng/openworker](https://github.com/andrewyng/openworker)
* [aws/aws-cli](https://github.com/aws/aws-cli) - Universal Command Line Interface for Amazon Web Services
* [adobe-fonts/source-han-sans](https://github.com/adobe-fonts/source-han-sans) - Source Han Sans | 思源黑体 | 思源黑體 | 思源黑體 香港 | 源ノ角ゴシック | 본고딕
* [jbiaojerry/ebook-treasure-chest](https://github.com/jbiaojerry/ebook-treasure-chest) - 欢迎来到电子书下载宝库，一个汇聚了各类电子书下载链接的地方。无论你是喜欢阅读经典文学、经管励志、终身学习、职场创业、技术手册还是其他类型的书籍，这里都能满足你的需求。 该库涵盖了帆书app(原樊登读书)、微信读书、京东读书、喜马拉雅等读书app的大部分电子书。
* [microsoft/data-formulator](https://github.com/microsoft/data-formulator) - 🪄 Data Formulator is an interactive AI-powered data analysis system makes it easy to connect, explore and visualize data.
* [EvoLinkAI/awesome-gpt-image-2-API-and-Prompts](https://github.com/EvoLinkAI/awesome-gpt-image-2-API-and-Prompts) - GPT-Image-2 API and Prompts
* [QwenLM/Qwen-Agent](https://github.com/QwenLM/Qwen-Agent) - Agent framework and applications built upon Qwen>=3.0, featuring Function Calling, MCP, Code Interpreter, RAG, Chrome extension, etc.
* [Wan-Video/Wan2.1](https://github.com/Wan-Video/Wan2.1) - Wan: Open and Advanced Large-Scale Video Generative Models
* [QwenLM/Qwen3-Coder](https://github.com/QwenLM/Qwen3-Coder) - Qwen3-Coder is the code version of Qwen3, the large language model series developed by Qwen team.
* [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map) - A feed-forward 3D foundation model for reconstructing scenes from streaming data
* [openai/baselines](https://github.com/openai/baselines) - OpenAI Baselines: high-quality implementations of reinforcement learning algorithms
* [suitenumerique/docs](https://github.com/suitenumerique/docs) - Docs is an open-source text editor: web-native, made for real-time collaboration, cleanly structured documents and sub-documents with full ownership of your data. Built to scale with Django and React.
* [h2y/Shadowrocket-ADBlock-Rules](https://github.com/h2y/Shadowrocket-ADBlock-Rules) - 提供多款 Shadowrocket 规则，带广告过滤功能。用于 iOS 未越狱设备选择性地自动翻墙。 *(archived)*
* [bradautomates/claude-video](https://github.com/bradautomates/claude-video) - Give Claude the ability to watch any video. /watch downloads, extracts frames, transcribes, hands it all to Claude.
* [RyanCodrai/turbovec](https://github.com/RyanCodrai/turbovec) - A vector index built on TurboQuant, written in Rust with Python bindings
* [MatrixTM/MHDDoS](https://github.com/MatrixTM/MHDDoS) - Best DDoS Attack Script Python3, (Cyber / DDos) Attack With 56 Methods
* [cvat-ai/cvat](https://github.com/cvat-ai/cvat) - Computer Vision Annotation Tool (CVAT) is a leading platform for building high-quality visual datasets for vision AI. It offers open-source, cloud, and enterprise products, as well as labeling services, for image, video, and 3D annotation with AI-assisted labeling, quality assurance, team collaboration, analytics, and developer APIs.
* [microsoft/SkillOpt](https://github.com/microsoft/SkillOpt) - SkillOpt is a text-space optimizer that trains reusable natural-language skills for frozen LLM agents through trajectory-driven edits, validation-gated updates, and deployable best_skill.md artifacts.
* [HKUDS/DeepCode](https://github.com/HKUDS/DeepCode) - "DeepCode: Open Agentic Coding (Agent Harness & Loop Engineering & Multi-Agent Orchestration)"
* [ddbourgin/numpy-ml](https://github.com/ddbourgin/numpy-ml) - Machine learning, in numpy
* [browser-use/web-ui](https://github.com/browser-use/web-ui) - 🖥️ Run AI Agent in your browser.
* [owainlewis/awesome-artificial-intelligence](https://github.com/owainlewis/awesome-artificial-intelligence) - A curated list of Artificial Intelligence (AI) courses, books, video lectures and papers.
* [LibreTranslate/LibreTranslate](https://github.com/LibreTranslate/LibreTranslate) - Free and Open Source Machine Translation API. Self-hosted, offline capable and easy to setup.
* [meta-llama/codellama](https://github.com/meta-llama/codellama) - Inference code for CodeLlama models *(archived)*
* [tgbot-collection/YYeTsBot](https://github.com/tgbot-collection/YYeTsBot) - 🎬 人人影视 机器人和网站，包含人人影视全部资源以及众多网友的网盘分享
* [rossant/awesome-math](https://github.com/rossant/awesome-math) - A curated list of awesome mathematics resources
* [andrewyng/aisuite](https://github.com/andrewyng/aisuite) - Simple, unified interface to multiple Generative AI providers
* [composio-community/awesome-codex-skills](https://github.com/composio-community/awesome-codex-skills) - A curated list of practical Codex skills for automating workflows across the Codex CLI and API.
* [jaakkopasanen/AutoEq](https://github.com/jaakkopasanen/AutoEq) - Automatic headphone equalization from frequency responses
* [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) - Universal SEO skill for Claude Code. 25 sub-skills + 18 sub-agents covering technical SEO, E-E-A-T, schema, GEO/AEO, backlinks, local SEO, maps intelligence, semantic clustering, e-commerce SEO, international SEO, Google APIs, and PDF/Excel reporting. Optional DataForSEO, Firecrawl, and Banana extensions.
* [xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire) - AI 时代的伯克希尔：基于 Claude Code / Codex 的价值投资研究框架。巴菲特·芒格·段永平·李录四大师方法论 + 多Agent并行研究。| AI-era Berkshire: a value investing research framework built for Claude Code / Codex. 4 masters' methodologies + multi-agent adversarial analysis.
* [microsoft/Swin-Transformer](https://github.com/microsoft/Swin-Transformer) - This is an official implementation for "Swin Transformer: Hierarchical Vision Transformer using Shifted Windows".
* [Comfy-Org/ComfyUI-Manager](https://github.com/Comfy-Org/ComfyUI-Manager) - ComfyUI-Manager is an extension designed to enhance the usability of ComfyUI. It offers management functions to install, remove, disable, and enable various custom nodes of ComfyUI. Furthermore, this extension provides a hub feature and convenience functions to access a wide range of information within ComfyUI.
* [avgupta456/github-trends](https://github.com/avgupta456/github-trends) - 🚀 Level up your GitHub profile readme with customizable cards including LOC statistics! *(archived)*
* [Kanaries/pygwalker](https://github.com/Kanaries/pygwalker) - PyGWalker: Turn your dataframe into an interactive UI for visual analysis
* [WEIFENG2333/VideoCaptioner](https://github.com/WEIFENG2333/VideoCaptioner) - 🎬 卡卡字幕助手 | VideoCaptioner - 基于 LLM 的智能字幕助手 - 视频字幕生成、断句、校正、字幕翻译全流程处理！- A powered tool for easy and efficient video subtitling.
* [budtmo/docker-android](https://github.com/budtmo/docker-android) - Android in docker solution with noVNC supported, video recording and mcp server
* [dottxt-ai/outlines](https://github.com/dottxt-ai/outlines) - Structured Outputs
* [microsoft/Bringing-Old-Photos-Back-to-Life](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life) - Bringing Old Photo Back to Life (CVPR 2020 oral)
* [ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui) - AG-UI: the Agent-User Interaction Protocol. Bring Agents into Frontend Applications.
* [mindverse/Second-Me](https://github.com/mindverse/Second-Me) - Train your AI self, amplify you, bridge the world
* [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) - ARIS ⚔️ (Auto-Research-In-Sleep) — Lightweight Markdown-only skills for autonomous ML research: cross-model review loops, idea discovery, and experiment automation. No framework, no lock-in — works with Claude Code, Codex, OpenClaw, or any LLM agent.
* [HKUDS/OpenHarness](https://github.com/HKUDS/OpenHarness) - "OpenHarness: Open Agent Harness with a Built-in Personal Agent--Ohmo!"
* [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) - Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, security risks, prompt injection, data exfiltration, and supply-chain risks in Claude Code, Codex, and MCP skills before you install them.
* [vibrantlabsai/ragas](https://github.com/vibrantlabsai/ragas) - Supercharge Your LLM Application Evaluations 🚀
* [zai-org/ChatGLM2-6B](https://github.com/zai-org/ChatGLM2-6B) - ChatGLM2-6B: An Open Bilingual Chat LLM | 开源双语对话语言模型
* [modelscope/ms-swift](https://github.com/modelscope/ms-swift) - Use PEFT or Full-parameter to CPT/SFT/DPO/GRPO 600+ LLMs (Qwen3.6, DeepSeek-V4, GLM-5.1, InternLM3, Llama4, ...) and 300+ MLLMs (Qwen3-VL, Qwen3-Omni, InternVL3.5, Ovis2.5, GLM4.5v, Gemma4, Llava, Phi4, ...) (AAAI 2025).
* [KittenML/KittenTTS](https://github.com/KittenML/KittenTTS) - State-of-the-art TTS model under 25MB 😻
* [mail-in-a-box/mailinabox](https://github.com/mail-in-a-box/mailinabox) - Mail-in-a-Box helps individuals take back control of their email by defining a one-click, easy-to-deploy SMTP+everything else server: a mail server in a box.
* [andkret/Cookbook](https://github.com/andkret/Cookbook) - The Data Engineering Cookbook
* [FlareSolverr/FlareSolverr](https://github.com/FlareSolverr/FlareSolverr) - Proxy server to bypass Cloudflare protection
* [edent/SuperTinyIcons](https://github.com/edent/SuperTinyIcons) - Under 1KB each! Super Tiny Icons are miniscule SVG versions of your favourite website and app logos
* [waditu/tushare](https://github.com/waditu/tushare) - TuShare is a utility for crawling historical data of China stocks
* [coderamp-labs/gitingest](https://github.com/coderamp-labs/gitingest) - Replace 'hub' with 'ingest' in any GitHub URL to get a prompt-friendly extract of a codebase
* [facebookresearch/detr](https://github.com/facebookresearch/detr) - End-to-End Object Detection with Transformers *(archived)*
* [jupyter/jupyter](https://github.com/jupyter/jupyter) - Jupyter metapackage for installation and documentation
* [apprenticeharper/DeDRM_tools](https://github.com/apprenticeharper/DeDRM_tools) - DeDRM tools for ebooks
* [lra/mackup](https://github.com/lra/mackup) - Backup and keep your application settings in sync.
* [GeeeekExplorer/nano-vllm](https://github.com/GeeeekExplorer/nano-vllm) - Nano vLLM
* [GaiZhenbiao/ChuanhuChatGPT](https://github.com/GaiZhenbiao/ChuanhuChatGPT) - GUI for ChatGPT API and many LLMs. Supports agents, file-based QA, GPT finetuning and query with web search. All with a neat UI.
* [trustedsec/social-engineer-toolkit](https://github.com/trustedsec/social-engineer-toolkit) - The Social-Engineer Toolkit (SET) repository from TrustedSec - All new versions of SET will be deployed here.
* [SWivid/F5-TTS](https://github.com/SWivid/F5-TTS) - Official code for "F5-TTS: A Fairytaler that Fakes Fluent and Faithful Speech with Flow Matching"
* [s0md3v/XSStrike](https://github.com/s0md3v/XSStrike) - Most advanced XSS scanner.
* [OpenEthan/SMSBoom](https://github.com/OpenEthan/SMSBoom) - SMSBoom - Deprecate: Due to judicial reasons, the repository has been suspended! *(archived)*
* [pipecat-ai/pipecat](https://github.com/pipecat-ai/pipecat) - Open Source framework for voice agents, multimodal apps, and realtime AI. Maintained by Daily and the community.
* [img2threejs/img2threejs](https://github.com/img2threejs/img2threejs) - Rebuild the object in a reference image as a code-only, procedural, quality-gated, animation-ready Three.js model. Token-efficient image-to-3D.
* [pjialin/py12306](https://github.com/pjialin/py12306) - 🚂 12306 购票助手，支持集群，多账号，多任务购票以及 Web 页面管理
* [kyegomez/OpenMythos](https://github.com/kyegomez/OpenMythos) - A theoretical reconstruction of the Claude Mythos architecture, built from first principles using the available research literature.
* [llmware-ai/llmware](https://github.com/llmware-ai/llmware) - Unified framework for building enterprise RAG pipelines with small, specialized models
* [google-deepmind/alphafold](https://github.com/google-deepmind/alphafold) - Open source code for AlphaFold 2.
* [LlamaChinese/Llama-Chinese](https://github.com/LlamaChinese/Llama-Chinese) - Llama中文社区，实时汇总最新Llama学习资料，构建最好的中文Llama大模型开源生态，完全开源可商用
* [aleju/imgaug](https://github.com/aleju/imgaug) - Image augmentation for machine learning experiments.
* [guofei9987/blind_watermark](https://github.com/guofei9987/blind_watermark) - Blind&Invisible Watermark ，图片盲水印，提取水印无须原图！
* [borisdayma/dalle-mini](https://github.com/borisdayma/dalle-mini) - DALL·E Mini - Generate images from a text prompt
* [dreammis/social-auto-upload](https://github.com/dreammis/social-auto-upload) - 自动化上传视频到社交媒体：抖音、小红书、视频号、tiktok、youtube、bilibili
* [SesameAILabs/csm](https://github.com/SesameAILabs/csm) - A Conversational Speech Generation Model
* [Tencent-Hunyuan/Hunyuan3D-2](https://github.com/Tencent-Hunyuan/Hunyuan3D-2) - High-Resolution 3D Assets Generation with Large Scale Hunyuan3D Diffusion Models.
* [sml2h3/ddddocr](https://github.com/sml2h3/ddddocr) - 带带弟弟 通用验证码识别OCR pypi版
* [BlinkDL/RWKV-LM](https://github.com/BlinkDL/RWKV-LM) - RWKV (pronounced RwaKuv) is an RNN with great LLM performance, which can also be directly trained like a GPT transformer (parallelizable). We are at RWKV-7 "Goose". So it's combining the best of RNN and transformer - great performance, linear time, constant space (no kv-cache), fast training, infinite ctx_len, and free sentence embedding.
* [hindupuravinash/the-gan-zoo](https://github.com/hindupuravinash/the-gan-zoo) - A list of all named GANs!
* [fauxpilot/fauxpilot](https://github.com/fauxpilot/fauxpilot) - FauxPilot - an open-source alternative to GitHub Copilot server
* [horovod/horovod](https://github.com/horovod/horovod) - Distributed training framework for TensorFlow, Keras, PyTorch, and Apache MXNet. *(archived)*
* [nikopueringer/CorridorKey](https://github.com/nikopueringer/CorridorKey) - Perfect Green Screen Keys
* [alexta69/metube](https://github.com/alexta69/metube) - Self-hosted video downloader for YouTube and other sites (web UI for yt-dlp)
* [AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian) - Self-organizing AI second brain for Obsidian + Claude Code. Drop any source and Claude reads, links, and files it into one connected knowledge graph of plain Markdown you own. AI note-taking, personal knowledge management (PKM), and an open-source Notion alternative. Based on Karpathy's LLM Wiki pattern.
* [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) - Research and development (R&D) is crucial for the enhancement of industrial productivity, especially in the AI era, where the core aspects of R&D are mainly focused on data and models. We are committed to automating these high-value generic R&D processes through R&D-Agent, which lets AI drive data-driven AI. 🔗https://aka.ms/RD-Agent-Tech-Report
* [NVlabs/stylegan](https://github.com/NVlabs/stylegan) - StyleGAN - Official TensorFlow Implementation
* [PaddlePaddle/PaddleDetection](https://github.com/PaddlePaddle/PaddleDetection) - Object Detection toolkit based on PaddlePaddle. It supports object detection, instance segmentation, multiple object tracking and real-time multi-person keypoint detection.
* [flairNLP/flair](https://github.com/flairNLP/flair) - A very simple framework for state-of-the-art Natural Language Processing (NLP)
* [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Personal memory across agents
* [jindongwang/transferlearning](https://github.com/jindongwang/transferlearning) - Transfer learning / domain adaptation / domain generalization / multi-task learning etc. Papers, codes, datasets, applications, tutorials.-迁移学习
* [davidsandberg/facenet](https://github.com/davidsandberg/facenet) - Face recognition using Tensorflow
* [facebookresearch/vggt](https://github.com/facebookresearch/vggt) - [CVPR 2025 Best Paper Award] VGGT: Visual Geometry Grounded Transformer
* [aiming-lab/AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) - Fully autonomous & self-evolving research from idea to paper. Chat an Idea. Get a Paper. 🦞
* [Usagi-org/ai-goofish-monitor](https://github.com/Usagi-org/ai-goofish-monitor) - 基于 Playwright 和AI实现的闲鱼多任务实时/定时监控与智能分析系统，配备了功能完善的后台管理UI。帮助用户从闲鱼海量商品中，找到心仪产品。 *(archived)*
* [youfou/wxpy](https://github.com/youfou/wxpy) - 微信机器人 / 可能是最优雅的微信个人号 API ✨✨ *(archived)*
* [myhhub/stock](https://github.com/myhhub/stock) - stock股票.获取股票数据,计算股票指标,筹码分布,识别股票形态,综合选股,选股策略,股票验证回测,股票自动交易,支持PC及移动设备。
* [idank/explainshell](https://github.com/idank/explainshell) - match command-line arguments to their help text
* [awesome-dsh-plugin/awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) - A curated list of plugins for DeepSeek Harness (dsh) · DeepSeek Harness 插件精选列表
* [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio) - VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages.
* [geldata/gel](https://github.com/geldata/gel) - Gel supercharges Postgres with a modern data model, graph queries, Auth & AI solutions, and much more.
* [donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws) - A curated list of awesome Amazon Web Services (AWS) libraries, open source repos, guides, blogs, and other resources. Featuring the Fiery Meter of AWSome.
* [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) - A library of agent skills for CAD, CAE and CAM
* [mlfoundations/open_clip](https://github.com/mlfoundations/open_clip) - An open source implementation of CLIP.
* [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading) - A curated list of awesome libraries, packages, strategies, books, blogs, tutorials for systematic trading.
* [netease-youdao/QAnything](https://github.com/netease-youdao/QAnything) - Question and Answer based on Anything.
* [OpenTalker/SadTalker](https://github.com/OpenTalker/SadTalker) - [CVPR 2023] SadTalker：Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation
* [programthink/zhao](https://github.com/programthink/zhao) - 【编程随想】整理的《太子党关系网络》，专门揭露赵国的权贵
* [evilsocket/opensnitch](https://github.com/evilsocket/opensnitch) - OpenSnitch is a GNU/Linux interactive application firewall inspired by Little Snitch.
* [ethereum/EIPs](https://github.com/ethereum/EIPs) - The Ethereum Improvement Proposal repository
* [livekit/agents](https://github.com/livekit/agents) - A framework for building realtime voice AI agents 🤖🎙️📹
* [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) - A framework for few-shot evaluation of language models.
* [coleam00/context-engineering-intro](https://github.com/coleam00/context-engineering-intro) - Context engineering is the new vibe coding - it's the way to actually make AI coding assistants work. Claude Code is the best for this so that's what this repo is centered around, but you can apply this strategy with any AI coding assistant!
* [microsoft/LoRA](https://github.com/microsoft/LoRA) - Code for loralib, an implementation of "LoRA: Low-Rank Adaptation of Large Language Models"
* [qazbnm456/awesome-web-security](https://github.com/qazbnm456/awesome-web-security) - 🐶 A curated list of Web Security materials and resources.
* [apache/tvm](https://github.com/apache/tvm) - Open Machine Learning Compiler Framework
* [zai-org/ChatGLM3](https://github.com/zai-org/ChatGLM3) - ChatGLM3 series: Open Bilingual Chat LLMs | 开源双语对话语言模型
* [Lightning-AI/litgpt](https://github.com/Lightning-AI/litgpt) - 20+ high-performance LLMs with recipes to pretrain, finetune and deploy at scale.
* [Physical-Intelligence/openpi](https://github.com/Physical-Intelligence/openpi)
* [Open-LLM-VTuber/Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber) - Talk to any LLM with hands-free voice interaction, voice interruption, and Live2D taking face running locally across platforms
* [microsoft/TRELLIS](https://github.com/microsoft/TRELLIS) - Official repo for paper "Structured 3D Latents for Scalable and Versatile 3D Generation" (CVPR'25 Spotlight).
* [Arindam200/awesome-ai-apps](https://github.com/Arindam200/awesome-ai-apps) - A collection of projects showcasing RAG, agents, workflows, and other AI use cases
* [bobeff/open-source-games](https://github.com/bobeff/open-source-games) - A list of open source games.
* [sshuttle/sshuttle](https://github.com/sshuttle/sshuttle) - Transparent proxy server that works as a poor man's VPN. Forwards over ssh. Doesn't require admin. Works with Linux and MacOS. Supports DNS tunneling.
* [BasedHardware/omi](https://github.com/BasedHardware/omi) - AI that sees your screen, listens to your conversations and tells you what to do
* [ytisf/theZoo](https://github.com/ytisf/theZoo) - A repository of LIVE malwares for your own joy and pleasure. theZoo is a project created to make the possibility of malware analysis open and available to the public.
* [instaloader/instaloader](https://github.com/instaloader/instaloader) - Download pictures (or videos) along with their captions and other metadata from Instagram.
* [QwenLM/Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS) - Qwen3-TTS is an open-source series of TTS models developed by the Qwen team at Alibaba Cloud, supporting stable, expressive, and streaming speech generation, free-form voice design, and vivid voice cloning.
* [Jiayi-Pan/TinyZero](https://github.com/Jiayi-Pan/TinyZero) - Minimal reproduction of DeepSeek R1-Zero
* [newren/git-filter-repo](https://github.com/newren/git-filter-repo) - Quickly rewrite git repository history (filter-branch replacement)
* [Rudrabha/Wav2Lip](https://github.com/Rudrabha/Wav2Lip) - This repository contains the codes of "A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild", published at ACM Multimedia 2020. For HD commercial model, please try out Sync Labs
* [OWASP/mastg](https://github.com/OWASP/mastg) - The OWASP Mobile Application Security Testing Guide (MASTG) is a comprehensive manual for mobile app security testing and reverse engineering. It describes technical processes for verifying the OWASP Mobile Security Weakness Enumeration (MASWE) weaknesses, which are in alignment with the OWASP MASVS.
* [mealie-recipes/mealie](https://github.com/mealie-recipes/mealie) - Mealie is a self hosted recipe manager and meal planner with a RestAPI backend and a reactive frontend application built in Vue for a pleasant user experience for the whole family. Easily add recipes into your database by providing the url and mealie will automatically import the relevant data or add a family recipe with the UI editor
* [modelscope/DiffSynth-Studio](https://github.com/modelscope/DiffSynth-Studio) - Enjoy the magic of Diffusion models!
* [ShishirPatil/gorilla](https://github.com/ShishirPatil/gorilla) - Gorilla: Training and Evaluating LLMs for Function Calls (Tool Calls)
* [mvt-project/mvt](https://github.com/mvt-project/mvt) - MVT (Mobile Verification Toolkit) helps with conducting forensics of mobile devices in order to find signs of a potential compromise.
* [zai-org/CogVideo](https://github.com/zai-org/CogVideo) - text and image to video generation: CogVideoX (2024) and CogVideo (ICLR 2023)
* [PaddlePaddle/PaddleFormers](https://github.com/PaddlePaddle/PaddleFormers) - PaddleFormers is an easy-to-use library of pre-trained large language model zoo based on PaddlePaddle.
* [lllyasviel/stable-diffusion-webui-forge](https://github.com/lllyasviel/stable-diffusion-webui-forge)
* [PaddlePaddle/PaddleNLP](https://github.com/PaddlePaddle/PaddleNLP) - Easy-to-use and powerful LLM and SLM library with awesome model zoo.
* [jacobgil/pytorch-grad-cam](https://github.com/jacobgil/pytorch-grad-cam) - Advanced AI Explainability for computer vision. Support for CNNs, Vision Transformers, Classification, Object detection, Segmentation, Image similarity and more.
* [alicevision/Meshroom](https://github.com/alicevision/Meshroom) - Node-based Visual Programming Toolbox
* [neuml/txtai](https://github.com/neuml/txtai) - 💡 All-in-one AI framework for semantic search, LLM orchestration and language model workflows
* [goldmansachs/gs-quant](https://github.com/goldmansachs/gs-quant) - Python toolkit for quantitative finance
* [jina-ai/clip-as-service](https://github.com/jina-ai/clip-as-service) - 🏄 Scalable embedding, reasoning, ranking for images and sentences with CLIP
* [facebookresearch/AnimatedDrawings](https://github.com/facebookresearch/AnimatedDrawings) - Code to accompany "A Method for Animating Children's Drawings of the Human Figure" *(archived)*
* [ultrafunkamsterdam/undetected-chromedriver](https://github.com/ultrafunkamsterdam/undetected-chromedriver) - Custom Selenium Chromedriver | Zero-Config | Passes ALL bot mitigation systems (like Distil / Imperva/ Datadadome / CloudFlare IUAM)
* [The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent) - 🚀 PR Agent: The Original Open-Source PR Reviewer. This project is not the Qodo free tier.
* [thuml/Time-Series-Library](https://github.com/thuml/Time-Series-Library) - A Library for Advanced Deep Time Series Models for General Time Series Analysis.
* [zalandoresearch/fashion-mnist](https://github.com/zalandoresearch/fashion-mnist) - A MNIST-like fashion product database. Benchmark :point_down:
* [abus-aikorea/voice-pro](https://github.com/abus-aikorea/voice-pro) - Gradio WebUI for creators and developers, featuring key TTS (Edge-TTS, kokoro) and zero-shot Voice Cloning (E2 & F5-TTS, CosyVoice), with Whisper audio processing, YouTube download, Demucs vocal isolation, and multilingual translation.
* [YaoFANGUK/video-subtitle-remover](https://github.com/YaoFANGUK/video-subtitle-remover) - 基于AI的图片/视频硬字幕去除、文本水印去除，无损分辨率生成去字幕、去水印后的图片/视频文件。无需申请第三方API，本地实现。AI-based tool for removing hard-coded subtitles and text-like watermarks from videos or Pictures.
* [langchain-ai/open_deep_research](https://github.com/langchain-ai/open_deep_research) - *(archived)*
* [PaddlePaddle/PaddleSpeech](https://github.com/PaddlePaddle/PaddleSpeech) - Easy-to-use Speech Toolkit including Self-Supervised Learning model, SOTA/Streaming ASR with punctuation, Streaming TTS with text frontend, Speaker Verification System, End-to-End Speech Translation and Keyword Spotting. Won NAACL2022 Best Demo Award.
* [EverMind-AI/EverOS](https://github.com/EverMind-AI/EverOS) - One portable memory layer for every AI agent: local-first, Markdown-native, user-owned, and self-evolving across apps, tools, and workflows.
* [The-Pocket/PocketFlow-Tutorial-Codebase-Knowledge](https://github.com/The-Pocket/PocketFlow-Tutorial-Codebase-Knowledge) - Pocket Flow: Codebase to Tutorial
* [sapientinc/HRM](https://github.com/sapientinc/HRM) - Hierarchical Reasoning Model Official Release
* [datahub-project/datahub](https://github.com/datahub-project/datahub) - The Context Platform for your Data and AI Stack
* [bmaltais/kohya_ss](https://github.com/bmaltais/kohya_ss)
* [rommapp/romm](https://github.com/rommapp/romm) - A beautiful, powerful, self-hosted ROM manager and player.
* [elebumm/RedditVideoMakerBot](https://github.com/elebumm/RedditVideoMakerBot) - Create Reddit Videos with just✨ one command ✨
* [bentoml/OpenLLM](https://github.com/bentoml/OpenLLM) - Run any open-source LLMs, such as DeepSeek and Llama, as OpenAI compatible API endpoint in the cloud.
* [ace-step/ACE-Step-1.5](https://github.com/ace-step/ACE-Step-1.5) - The most powerful local music generation model that outperforms almost all commercial alternatives, supporting Mac, AMD, Intel, and CUDA devices.
* [selierlin/Share-SSR-V2ray](https://github.com/selierlin/Share-SSR-V2ray) - 机场推荐、Clash / V2ray 客户端配置与代理工具指南
* [Tencent-Hunyuan/HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) - HunyuanVideo: A Systematic Framework For Large Video Generation Model
* [simonw/llm](https://github.com/simonw/llm) - Access large language models from the command-line
* [Farama-Foundation/Gymnasium](https://github.com/Farama-Foundation/Gymnasium) - A standard API for single-agent reinforcement learning environments, with popular reference environments and related utilities (formerly Gym)
* [axolotl-ai-cloud/axolotl](https://github.com/axolotl-ai-cloud/axolotl) - Go ahead and axolotl questions
* [openai/shap-e](https://github.com/openai/shap-e) - Generate 3D objects conditioned on text or images
* [dwyl/english-words](https://github.com/dwyl/english-words) - :memo: A text file containing 479k English words for all your dictionary/word-based projects e.g: auto-completion / autosuggestion
* [OpenMOSS/MOSS](https://github.com/OpenMOSS/MOSS) - An open-source, tool-augmented conversational language model from Fudan University
* [guoyww/AnimateDiff](https://github.com/guoyww/AnimateDiff) - Official implementation of AnimateDiff.
* [Embedding/Chinese-Word-Vectors](https://github.com/Embedding/Chinese-Word-Vectors) - 100+ Chinese Word Vectors 上百种预训练中文词向量
* [HKUDS/ViMax](https://github.com/HKUDS/ViMax) - "ViMax: Agentic Video Generation (Director, Screenwriter, Producer, and Video Generator All-in-One)"
* [simular-ai/Agent-S](https://github.com/simular-ai/Agent-S) - Agent S: an open agentic framework that uses computers like a human
* [RUCAIBox/LLMSurvey](https://github.com/RUCAIBox/LLMSurvey) - The official GitHub page for the survey paper "A Survey of Large Language Models".
* [datalab-to/chandra](https://github.com/datalab-to/chandra) - OCR model that handles complex tables, forms, handwriting with full layout.
* [PKU-YuanGroup/Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan) - This project aim to reproduce Sora (Open AI T2V model), we wish the open source community contribute to this project.
* [icloud-photos-downloader/icloud_photos_downloader](https://github.com/icloud-photos-downloader/icloud_photos_downloader) - A command-line tool to download photos from iCloud
* [smol-ai/developer](https://github.com/smol-ai/developer) - the first library to let you embed a developer agent in your own app!
* [xmu-xiaoma666/External-Attention-pytorch](https://github.com/xmu-xiaoma666/External-Attention-pytorch) - 🍀 Pytorch implementation of various Attention Mechanisms, MLP, Re-parameter, Convolution, which is helpful to further understand papers.⭐⭐⭐
* [FlagOpen/FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding) - Retrieval and Retrieval-augmented LLMs
* [waydroid/waydroid](https://github.com/waydroid/waydroid) - Waydroid uses a container-based approach to boot a full Android system on a regular GNU/Linux system like Ubuntu.
* [bytedance/trae-agent](https://github.com/bytedance/trae-agent) - Trae Agent is an LLM-based agent for general purpose software engineering tasks.
* [tonybeltramelli/pix2code](https://github.com/tonybeltramelli/pix2code) - pix2code: Generating Code from a Graphical User Interface Screenshot
* [tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) - Expose your FastAPI endpoints as Model Context Protocol (MCP) tools, with Auth!
* [instantX-research/InstantID](https://github.com/instantX-research/InstantID) - InstantID: Zero-shot Identity-Preserving Generation in Seconds 🔥
* [Tongyi-MAI/Z-Image](https://github.com/Tongyi-MAI/Z-Image)
* [h2oai/h2ogpt](https://github.com/h2oai/h2ogpt) - Private chat with local GPT with document, images, video, etc. 100% private, Apache 2.0. Supports oLLaMa, Mixtral, llama.cpp, and more. Demo: https://gpt.h2o.ai/ https://gpt-docs.h2o.ai/ *(archived)*
* [nerfstudio-project/nerfstudio](https://github.com/nerfstudio-project/nerfstudio) - A collaboration friendly studio for NeRFs
* [openai/spinningup](https://github.com/openai/spinningup) - An educational resource to help anyone learn deep reinforcement learning.
* [ostris/ai-toolkit](https://github.com/ostris/ai-toolkit) - The ultimate training toolkit for finetuning diffusion models
* [alexjc/neural-enhance](https://github.com/alexjc/neural-enhance) - Super Resolution for images using deep learning. *(archived)*
* [speechbrain/speechbrain](https://github.com/speechbrain/speechbrain) - A PyTorch-based Speech Toolkit
* [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) - AI-powered reverse engineering assistant that bridges IDA Pro with language models through MCP.
* [fivetran/great_expectations](https://github.com/fivetran/great_expectations) - Always know what to expect from your data.
* [BeehiveInnovations/pal-mcp-server](https://github.com/BeehiveInnovations/pal-mcp-server) - The power of Claude Code / GeminiCLI / CodexCLI + [Gemini / OpenAI / OpenRouter / Azure / Grok / Ollama / Custom Model / All Of The Above] working as one.
* [qubvel-org/segmentation_models.pytorch](https://github.com/qubvel-org/segmentation_models.pytorch) - Semantic segmentation models with 500+ pretrained convolutional and transformer-based backbones.
* [jxxghp/MoviePilot](https://github.com/jxxghp/MoviePilot) - NAS媒体库自动化管理工具
* [EmbraceAGI/awesome-chatgpt-zh](https://github.com/EmbraceAGI/awesome-chatgpt-zh) - ChatGPT 中文指南🔥，ChatGPT 中文调教指南，指令指南，应用开发指南，精选资源清单，更好的使用 chatGPT 让你的生产力 up up up! 🚀
* [pwxcoo/chinese-xinhua](https://github.com/pwxcoo/chinese-xinhua) - :orange_book: 中华新华字典数据库。包括歇后语，成语，词语，汉字。
* [Dod-o/Statistical-Learning-Method_Code](https://github.com/Dod-o/Statistical-Learning-Method_Code) - 手写实现李航《统计学习方法》书中全部算法
* [milesial/Pytorch-UNet](https://github.com/milesial/Pytorch-UNet) - PyTorch implementation of the U-Net for image semantic segmentation with high quality images
* [LMCache/LMCache](https://github.com/LMCache/LMCache) - LMCache: Supercharge Your LLM with the Fastest KV Cache Layer
* [QuipNetwork/quip-miner](https://github.com/QuipNetwork/quip-miner) - The quip network mining stack. This includes a coordinator and links all of the official quip network miners.
* [facebookresearch/sam3](https://github.com/facebookresearch/sam3) - The repository provides code for running inference and finetuning with the Meta Segment Anything Model 3 (SAM 3), links for downloading the trained model checkpoints, and example notebooks that show how to use the model.
* [0x4m4/hexstrike-ai](https://github.com/0x4m4/hexstrike-ai) - HexStrike AI MCP Agents is an advanced MCP server that lets AI agents (Claude, GPT, Copilot, etc.) autonomously run 150+ cybersecurity tools for automated pentesting, vulnerability discovery, bug bounty automation, and security research. Seamlessly bridge LLMs with real-world offensive security capabilities.
* [iam-veeramalla/aws-devops-zero-to-hero](https://github.com/iam-veeramalla/aws-devops-zero-to-hero) - AWS zero to hero repo for devops engineers to learn AWS in 30 Days. This repo includes projects, presentations, interview questions and real time examples.
* [bytedance/UI-TARS](https://github.com/bytedance/UI-TARS) - Pioneering Automated GUI Interaction with Native Agents
* [moesnow/March7thAssistant](https://github.com/moesnow/March7thAssistant) - 崩坏：星穹铁道全自动 三月七小助手
* [hoya012/deep_learning_object_detection](https://github.com/hoya012/deep_learning_object_detection) - A paper list of object detection using deep learning.
* [THU-MIG/yolov10](https://github.com/THU-MIG/yolov10) - YOLOv10: Real-Time End-to-End Object Detection [NeurIPS 2024]
* [IdreesInc/Monocraft](https://github.com/IdreesInc/Monocraft) - A monospaced programming font inspired by the Minecraft typeface
* [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli) - Kimi Code CLI is your next CLI agent.
* [lucidrains/DALLE2-pytorch](https://github.com/lucidrains/DALLE2-pytorch) - Implementation of DALL-E 2, OpenAI's updated text-to-image synthesis neural network, in Pytorch
* [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) - 67 Specialized Skills for Full-Stack Developers. Transform Claude Code into your expert pair programmer.
* [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix) - AI Observability & Evaluation
* [microsoft/promptflow](https://github.com/microsoft/promptflow) - Build high-quality LLM apps - from prototyping, testing to production deployment and monitoring.
* [wsvincent/awesome-django](https://github.com/wsvincent/awesome-django) - A curated list of awesome things related to Django
* [Doriandarko/claude-engineer](https://github.com/Doriandarko/claude-engineer) - Claude Engineer is an interactive command-line interface (CLI) that leverages the power of Anthropic's Claude-3.5-Sonnet model to assist with software development tasks.This framework enables Claude to generate and manage its own tools, continuously expanding its capabilities through conversation. Available both as a CLI and a modern web interface
* [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) - FreeToken brings datacenter-scale model serving to your desktop. Run massive models locally, fast and efficiently.
* [QuipNetwork/hashsigs-py](https://github.com/QuipNetwork/hashsigs-py)
* [NVlabs/stylegan2](https://github.com/NVlabs/stylegan2) - StyleGAN2 - Official TensorFlow Implementation
* [3b1b/videos](https://github.com/3b1b/videos) - Code for the manim-generated scenes used in 3blue1brown videos
* [NVIDIA/FastPhotoStyle](https://github.com/NVIDIA/FastPhotoStyle) - Style transfer, deep learning, feature transform
* [The-Pocket/PocketFlow](https://github.com/The-Pocket/PocketFlow) - Pocket Flow: 100-line LLM framework. Let Agents build Agents!
* [sissbruecker/linkding](https://github.com/sissbruecker/linkding) - Self-hosted bookmark manager that is designed be to be minimal, fast, and easy to set up using Docker.
* [TEN-framework/ten-framework](https://github.com/TEN-framework/ten-framework) - Open-source framework for conversational voice AI agents
* [offa/android-foss](https://github.com/offa/android-foss) - A list of Free and Open Source Software (FOSS) for Android – saving Freedom and Privacy.
* [yizhiyanhua-ai/fireworks-tech-graph](https://github.com/yizhiyanhua-ai/fireworks-tech-graph) - Generate production-quality SVG+PNG technical diagrams from natural language. 7 styles, UML support, and AI/Agent workflow patterns.
* [yutiansut/QUANTAXIS](https://github.com/yutiansut/QUANTAXIS) - QUANTAXIS 支持任务调度 分布式部署的 股票/期货/期权 数据/回测/模拟/交易/可视化/多账户 纯本地量化解决方案
* [vipstone/faceai](https://github.com/vipstone/faceai) - 一款入门级的人脸、视频、文字检测以及识别的项目.
* [aboul3la/Sublist3r](https://github.com/aboul3la/Sublist3r) - Fast subdomains enumeration tool for penetration testers
* [BigBodyCobain/Shadowbroker](https://github.com/BigBodyCobain/Shadowbroker) - Open-source intelligence for the global theater. Track everything from the corporate/private jets of the wealthy, and spy satellites, to seismic events in one unified interface. Hook an AI agent up to have it parse through data and find previously unseen correlations. The knowledge is available to all but rarely aggregated in the open, until now.
* [SparkAudio/Spark-TTS](https://github.com/SparkAudio/Spark-TTS) - Spark-TTS Inference Code
* [huggingface/skills](https://github.com/huggingface/skills) - Give your agents the power of the Hugging Face ecosystem
* [kyutai-labs/moshi](https://github.com/kyutai-labs/moshi) - Moshi is a speech-text foundation model and full-duplex spoken dialogue framework. It uses Mimi, a state-of-the-art streaming neural audio codec.
* [Tracer-Cloud/opensre](https://github.com/Tracer-Cloud/opensre) - Build your own AI SRE agents. The open source toolkit for the AI era.
* [microsoft/TRELLIS.2](https://github.com/microsoft/TRELLIS.2) - Native and Compact Structured Latents for 3D Generation
* [SigmaHQ/sigma](https://github.com/SigmaHQ/sigma) - Main Sigma Rule Repository
* [AlessandroZ/LaZagne](https://github.com/AlessandroZ/LaZagne) - Credentials recovery project
* [lengstrom/fast-style-transfer](https://github.com/lengstrom/fast-style-transfer) - TensorFlow CNN for fast style transfer ⚡🖥🎨🖼
* [triton-inference-server/server](https://github.com/triton-inference-server/server) - The Triton Inference Server provides an optimized cloud and edge inferencing solution.
* [thu-ml/tianshou](https://github.com/thu-ml/tianshou) - An elegant PyTorch deep reinforcement learning library.
* [Kludex/uvicorn](https://github.com/Kludex/uvicorn) - An ASGI web server, for Python. 🦄
* [aristocratos/bpytop](https://github.com/aristocratos/bpytop) - Linux/OSX/FreeBSD resource monitor
* [Lightricks/LTX-Video](https://github.com/Lightricks/LTX-Video) - Official repository for LTX-Video
* [magic-research/magic-animate](https://github.com/magic-research/magic-animate) - [CVPR 2024] Official repository for "MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model"
* [bunkerity/bunkerweb](https://github.com/bunkerity/bunkerweb) - 🛡️ Open-source and cloud-native Web Application Firewall (WAF)
* [huggingface/text-generation-inference](https://github.com/huggingface/text-generation-inference) - Large Language Model Text Generation Inference *(archived)*
* [gleitz/howdoi](https://github.com/gleitz/howdoi) - instant coding answers via the command line
* [openai/DALL-E](https://github.com/openai/DALL-E) - PyTorch package for the discrete VAE used for DALL·E. *(archived)*
* [ihmily/DouyinLiveRecorder](https://github.com/ihmily/DouyinLiveRecorder) - 可循环值守和多人录制的直播录制软件，支持抖音、TikTok、Youtube、快手、虎牙、斗鱼、B站、小红书、pandatv、sooplive、flextv、popkontv、twitcasting、winktv、百度、微博、酷狗、17Live、Twitch、Acfun、CHZZK、shopee等40+平台直播录制
* [databrickslabs/dolly](https://github.com/databrickslabs/dolly) - Databricks’ Dolly, a large language model trained on the Databricks Machine Learning Platform
* [cumulo-autumn/StreamDiffusion](https://github.com/cumulo-autumn/StreamDiffusion) - StreamDiffusion: A Pipeline-Level Solution for Real-Time Interactive Generation
* [Chia-Network/chia-blockchain](https://github.com/Chia-Network/chia-blockchain) - Chia blockchain python implementation (full node, farmer, harvester, timelord, and wallet)
* [huggingface/ml-intern](https://github.com/huggingface/ml-intern) - 🤗 ml-intern: an open-source ML engineer that reads papers, trains models, and ships ML models
* [jsvine/pdfplumber](https://github.com/jsvine/pdfplumber) - Plumb a PDF for detailed information about each char, rectangle, line, et cetera — and easily extract text and tables.
* [karpathy/minbpe](https://github.com/karpathy/minbpe) - Minimal, clean code for the Byte Pair Encoding (BPE) algorithm commonly used in LLM tokenization.
* [nodejs/node-gyp](https://github.com/nodejs/node-gyp) - Node.js native addon build tool
* [OpenPipe/ART](https://github.com/OpenPipe/ART) - Agent Reinforcement Trainer: train multi-step agents for real-world tasks using GRPO. Give your agents on-the-job training. Reinforcement learning for Qwen3.6, GPT-OSS, Llama, and more!
* [lucidrains/denoising-diffusion-pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch) - Implementation of Denoising Diffusion Probabilistic Model in Pytorch
* [je-suis-tm/quant-trading](https://github.com/je-suis-tm/quant-trading) - Python quantitative trading strategies including VIX Calculator, Pattern Recognition, Commodity Trading Advisor, Monte Carlo, Options Straddle, Shooting Star, London Breakout, Heikin-Ashi, Pair Trading, RSI, Bollinger Bands, Parabolic SAR, Dual Thrust, Awesome, MACD
* [benoitc/gunicorn](https://github.com/benoitc/gunicorn) - gunicorn 'Green Unicorn' is a WSGI HTTP Server for UNIX, fast clients and sleepy applications.
* [langchain-ai/open-swe](https://github.com/langchain-ai/open-swe) - An Open-Source Asynchronous Coding Agent
* [hydra-ecosystem/hydra](https://github.com/hydra-ecosystem/hydra) - Hydra is a framework for elegantly configuring complex applications
* [facebookresearch/ParlAI](https://github.com/facebookresearch/ParlAI) - A framework for training and evaluating AI models on a variety of openly available dialogue datasets. *(archived)*
* [ultralytics/yolov3](https://github.com/ultralytics/yolov3) - PyTorch implementation of YOLOv3, YOLOv3-SPP, and YOLOv3-tiny for real-time object detection with training, validation, inference, and multi-format export.
* [Megvii-BaseDetection/YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) - YOLOX is a high-performance anchor-free YOLO, exceeding yolov3~v5 with MegEngine, ONNX, TensorRT, ncnn, and OpenVINO supported. Documentation: https://yolox.readthedocs.io/
* [twitter/the-algorithm-ml](https://github.com/twitter/the-algorithm-ml) - Source code for Twitter's Recommendation Algorithm
* [eeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee/eeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee](https://github.com/eeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee/eeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee) - eeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee *(archived)*
* [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot) - The AI Compute Platform for frontier teams. SkyPilot turns fragmented AI compute into one AI supercomputer, so frontier AI teams build custom intelligence faster.
* [facebookresearch/xformers](https://github.com/facebookresearch/xformers) - Hackable and optimized Transformers building blocks, supporting a composable construction.
* [paralax/awesome-honeypots](https://github.com/paralax/awesome-honeypots) - an awesome list of honeypot resources
* [Acly/krita-ai-diffusion](https://github.com/Acly/krita-ai-diffusion) - Streamlined interface for generating images with AI in Krita. Inpaint and outpaint with optional text prompt, no tweaking required.
* [IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) - [ECCV 2024] Official implementation of the paper "Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection"
* [bigscience-workshop/petals](https://github.com/bigscience-workshop/petals) - 🌸 Run LLMs at home, BitTorrent-style. Fine-tuning and inference up to 10x faster than offloading
* [thumbor/thumbor](https://github.com/thumbor/thumbor) - thumbor is an open-source photo thumbnail service by globo.com
* [pcqpcq/open-source-android-apps](https://github.com/pcqpcq/open-source-android-apps) - Open-Source Android Apps
* [NVIDIA/personaplex](https://github.com/NVIDIA/personaplex) - PersonaPlex code.
* [zyddnys/manga-image-translator](https://github.com/zyddnys/manga-image-translator) - Translate manga/image 一键翻译各类图片内文字 https://cotrans.touhou.ai/ (no longer working)
* [facebookresearch/demucs](https://github.com/facebookresearch/demucs) - Code for the paper Hybrid Spectrogram and Waveform Source Separation *(archived)*
* [CVHub520/X-AnyLabeling](https://github.com/CVHub520/X-AnyLabeling) - X-AnyLabeling: A lightweight, efficient, and unified cross-platform desktop application for annotating text, image, video, and multimodal data, combining versatile built-in tools with state-of-the-art AI models and flexible multi-format export.
* [rwv/chinese-dos-games](https://github.com/rwv/chinese-dos-games) - 🎮 Chinese DOS games collections.
* [OthersideAI/self-operating-computer](https://github.com/OthersideAI/self-operating-computer) - A framework to enable a multimodal model to operate a computer.
* [fossasia/visdom](https://github.com/fossasia/visdom) - Tool for real-time visualization, monitoring and collaborative analysis of AI/ML experiments and live data. Supports Python, PyTorch/Torch, NumPy, TensorFlow/Keras https://visdom.dev
* [open-mmlab/Amphion](https://github.com/open-mmlab/Amphion) - Amphion (/æmˈfaɪən/) is a toolkit for Audio, Music, and Speech Generation. Its purpose is to support reproducible research and help junior researchers and engineers get started in the field of audio, music, and speech generation research and development.
* [google/adk-samples](https://github.com/google/adk-samples) - A collection of sample agents built with Agent Development Kit (ADK)
* [ymcui/Chinese-BERT-wwm](https://github.com/ymcui/Chinese-BERT-wwm) - Pre-Training with Whole Word Masking for Chinese BERT（中文BERT-wwm系列模型）
* [pathwaycom/arc-task-gen](https://github.com/pathwaycom/arc-task-gen) - Generates original ARC-AGI-1-style tasks distribution-matched to the public eval set.
* [AIGC-Audio/AudioGPT](https://github.com/AIGC-Audio/AudioGPT) - AudioGPT: Understanding and Generating Speech, Music, Sound, and Talking Head
* [zubair-trabzada/geo-seo-claude](https://github.com/zubair-trabzada/geo-seo-claude) - GEO-first SEO skill for Claude Code. Comprehensive AI search optimization for any website — citability scoring, AI crawler analysis, brand authority, schema markup, platform-specific optimization, and PDF reports. If you want learn how to sell this to real businesses, check out the skool community
* [mouredev/hello-sql](https://github.com/mouredev/hello-sql) - Curso para aprender los fundamentos del lenguaje SQL y bases de datos relacionales desde cero y para principiantes.
* [OpenGVLab/InternVL](https://github.com/OpenGVLab/InternVL) - [CVPR 2024 Oral] InternVL Family: A Pioneering Open-Source Alternative to GPT-4o. 接近GPT-4o表现的开源多模态对话模型
* [shidenggui/easytrader](https://github.com/shidenggui/easytrader) - 提供同花顺客户端/miniqmt/雪球的股票量化交易，支持跟踪 joinquant /ricequant 模拟交易 和 实盘雪球组合
* [snakers4/silero-vad](https://github.com/snakers4/silero-vad) - Silero VAD: pre-trained enterprise-grade Voice Activity Detector
* [microsoft/fluentui-emoji](https://github.com/microsoft/fluentui-emoji) - A collection of familiar, friendly, and modern emoji from Microsoft
* [makerspet/oomwoo](https://github.com/makerspet/oomwoo) - Open-source vacuum robot cleaner
* [microsoft/magentic-ui](https://github.com/microsoft/magentic-ui) - MagenticLite is an experimental agent that works across the browser and local file system
* [facebookresearch/nougat](https://github.com/facebookresearch/nougat) - Implementation of Nougat Neural Optical Understanding for Academic Documents
* [cactus-compute/needle](https://github.com/cactus-compute/needle) - 14MB foundation model for tiny devices; phones, wearables, smart home, and robots.
* [seatgeek/fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy String Matching in Python *(archived)*
* [activeloopai/deeplake](https://github.com/activeloopai/deeplake) - Deeplake is AI Data Runtime for Agents. It provides serverless postgres with a multimodal datalake, enabling scalable retrieval and training.
* [pydantic/FastUI](https://github.com/pydantic/FastUI) - Build better UIs faster. *(archived)*
* [kernc/backtesting.py](https://github.com/kernc/backtesting.py) - 🔎 📈 🐍 💰 Backtest trading strategies in Python.
* [kivy/python-for-android](https://github.com/kivy/python-for-android) - Turn your Python application into an Android APK
* [theskumar/python-dotenv](https://github.com/theskumar/python-dotenv) - Reads key-value pairs from a .env file and can set them as environment variables. It helps in developing applications following the 12-factor principles.
* [librosa/librosa](https://github.com/librosa/librosa) - Python library for audio and music analysis
* [JerBouma/FinanceDatabase](https://github.com/JerBouma/FinanceDatabase) - This is a database of 300.000+ symbols containing Equities, ETFs, Funds, Indices, Currencies, Cryptocurrencies and Money Markets.
* [jesse-ai/jesse](https://github.com/jesse-ai/jesse) - An advanced crypto trading bot written in Python
* [openatx/uiautomator2](https://github.com/openatx/uiautomator2) - Android Uiautomator2 Python Wrapper
* [firerpa/lamda](https://github.com/firerpa/lamda) - Android Full-Stack Device Control Platform: WebRTC/H.264 remote desktop, UI/OCR/image-matching automation, one-click MITM, built-in Frida, proxy/VPN/frp/P2P networking, MCP/Agent, 160+ APIs, designed for multi-device clusters and engineered deployments.
* [reactive-python/reactpy](https://github.com/reactive-python/reactpy) - It's React, but in Python
* [pythonstock/stock](https://github.com/pythonstock/stock) - stock，股票系统。使用python进行开发。
* [pyca/cryptography](https://github.com/pyca/cryptography) - cryptography is a package designed to expose cryptographic primitives and recipes to Python developers.
* [ranaroussi/quantstats](https://github.com/ranaroussi/quantstats) - Portfolio analytics for quants, written in Python
* [msiemens/tinydb](https://github.com/msiemens/tinydb) - TinyDB is a lightweight document oriented database optimized for your happiness :)
* [lbryio/lbry-sdk](https://github.com/lbryio/lbry-sdk) - The LBRY SDK for building decentralized, censorship resistant, monetized digital content apps.
* [worldveil/dejavu](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition in Python
* [ricequant/rqalpha](https://github.com/ricequant/rqalpha) - A extendable, replaceable Python algorithmic backtest && trading framework supporting multiple securities
* [tyiannak/pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) - Python Audio Analysis Library: Feature Extraction, Classification, Segmentation and Applications
* [erikbern/ann-benchmarks](https://github.com/erikbern/ann-benchmarks) - Benchmarks of approximate nearest neighbor libraries in Python
* [spotify/basic-pitch](https://github.com/spotify/basic-pitch) - A lightweight yet powerful audio-to-MIDI converter with pitch bend detection
* [ApeWorX/web3.py](https://github.com/ApeWorX/web3.py) - A python interface for interacting with the Ethereum blockchain and ecosystem.
* [liuwons/wxBot](https://github.com/liuwons/wxBot) - Deprecated
* [ajalt/fuckitpy](https://github.com/ajalt/fuckitpy) - The Python error steamroller.
* [gitpython-developers/GitPython](https://github.com/gitpython-developers/GitPython) - GitPython is a python library used to interact with Git repositories.
* [shinnytech/tqsdk-python](https://github.com/shinnytech/tqsdk-python) - 天勤量化开发包, 期货量化, 实时行情/历史数据/实盘交易
* [hynek/structlog](https://github.com/hynek/structlog) - Simple, powerful, and fast logging for Python.
* [nameko/nameko](https://github.com/nameko/nameko) - Python framework for building microservices
* [gbeced/pyalgotrade](https://github.com/gbeced/pyalgotrade) - Python Algorithmic Trading Library *(archived)*
* [dedupeio/dedupe](https://github.com/dedupeio/dedupe) - :id: A python library for accurate and scalable fuzzy matching, record deduplication and entity-resolution.
* [novnc/websockify](https://github.com/novnc/websockify) - Websockify is a WebSocket to TCP proxy/bridge. This allows a browser to connect to any application/server/service.
* [zeromq/pyzmq](https://github.com/zeromq/pyzmq) - PyZMQ: Python bindings for zeromq
* [bigchaindb/bigchaindb](https://github.com/bigchaindb/bigchaindb) - Meet BigchainDB. The blockchain database.
* [cuemacro/finmarketpy](https://github.com/cuemacro/finmarketpy) - Python library for backtesting trading strategies & analyzing financial markets (formerly pythalesians)
* [drathier/stack-overflow-import](https://github.com/drathier/stack-overflow-import) - Import arbitrary code from Stack Overflow as Python modules.
* [pst-group/pysystemtrade](https://github.com/pst-group/pysystemtrade) - Systematic Trading in python
* [wal-e/wal-e](https://github.com/wal-e/wal-e) - Continuous Archiving for Postgres
* [sc0tfree/updog](https://github.com/sc0tfree/updog) - Updog is a replacement for Python's SimpleHTTPServer. It allows uploading and downloading via HTTP/S, can set ad hoc SSL certificates and use http basic auth.
* [man-group/arctic](https://github.com/man-group/arctic) - High performance datastore for time series and tick data
* [HBNetwork/python-decouple](https://github.com/HBNetwork/python-decouple) - Strict separation of config from code.
* [golemfactory/clay](https://github.com/golemfactory/clay) - Golem is creating a global market for computing power. *(archived)*
* [Netflix/bless](https://github.com/Netflix/bless) - Repository for BLESS, an SSH Certificate Authority that runs as a AWS Lambda function
* [eth-brownie/brownie](https://github.com/eth-brownie/brownie) - A Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine.
* [mitogen-hq/mitogen](https://github.com/mitogen-hq/mitogen) - Distributed self-replicating programs in Python
* [pycrypto/pycrypto](https://github.com/pycrypto/pycrypto) - The Python Cryptography Toolkit *(archived)*
* [jazzband/django-push-notifications](https://github.com/jazzband/django-push-notifications) - Send push notifications to mobile devices through GCM or APNS in Django.
* [ranaroussi/qtpylib](https://github.com/ranaroussi/qtpylib) - QTPyLib, Pythonic Algorithmic Trading *(archived)*
* [tlsfuzzer/python-ecdsa](https://github.com/tlsfuzzer/python-ecdsa) - pure-python ECDSA signature/verification and ECDH key agreement
* [pyca/pyopenssl](https://github.com/pyca/pyopenssl) - A Python wrapper around the OpenSSL library
