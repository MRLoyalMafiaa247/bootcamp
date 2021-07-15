<!-- PROJECT LOGO -->
<br />

<p align="center">
  <a href="https://github.com/milvus-io/bootcamp">
    <img src="images/logo.png" alt="Logo">
  </a>
  <p align="center">
    Bootcamp for Milvus, including benchmarking, solutions, and application scenarios.
    <br />
    <br />
    <a href="https://github.com/milvus-io/bootcamp "Demo</a>
    ·
    <a href="https://github.com/milvus-io/bootcamp/issues">Report Bug</a>
    ·
    <a href="https://github.com/milvus-io/bootcamp/issues">Request Feature</a>
  </p>
<!-- TABLE OF CONTENTS -->

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#mega-about-milvus-bootcamp">About Milvus Bootcamp</a>
    </li>
    <li>
      <a href="#mag-benchmark-tests">Benchmark Tests</a>
      <ul>
        <li><a href="#dart-1-million-benchmark-testing">1 million benchmark testing</a></li>
        <li><a href="#art-100-million-benchmark-testing">100 million benchmark testing</a></li>
      </ul>
    </li>
    <li><a href="#pencil-solutions">Solutions</a></li>
      <ul>
        <li><a href="#icecream-run-locally">Run locally</a></li>
        <li><a href="#clapper-live-demo">Live demo</a></li>
        <li><a href="#fries-have-a-try">Have a try</a></li>
      </ul>
    <li><a href="#two_women_holding_hands-collaborations">Collaborations</a></li>
      <ul>
        <li><a href="#clap-milvus_and_onnx">Milvus_and_ONNX</a></li>
      </ul>
    <li><a href="#fire-supports">Supports</a></li>
  </ol>
</details>
<!-- ABOUT MILVUS Bootcamp -->

## :mega: About Milvus Bootcamp
Milvus Bootcamp is designed to expose users to both the simplicity and depth of [**Milvus**](https://milvus.io/) vector database. Discover how to run **benchmark tests** as well as build similarity search applications spanning **chatbots**, **recommendation systems**, **reverse image search**, **molecular search**, **video search**, **audio saerch**, and much more.

<!-- BENCHMARK TESTS-->

## :mag: Benchmark Tests
The [Benchmark Test](https://github.com/milvus-io/bootcamp/tree/master/benchmark_test) contains 1 million and 100 million vector tests that indicate how your system will react to differently sized datasets.
 ### :dart: [1 million benchmark testing](https://github.com/milvus-io/bootcamp/blob/master/benchmark_test/lab1_sift1b_1m.md)

We extract one million vector data from [SIFT1B Dataset](http://corpus-texmex.irisa.fr/) for **accuracy test** and **performance test**. Through [this test](https://github.com/milvus-io/bootcamp/blob/master/benchmark_test/lab1_sift1b_1m.md), you can learn the basic operations of Milvus, including creating collection, inserting data, building indexes, searching, etc.

 ### :art: [100 million benchmark testing](https://github.com/milvus-io/bootcamp/blob/master/benchmark_test/lab2_sift1b_100m.md)

We extract 100 million vector data from [SIFT1B Dataset](http://corpus-texmex.irisa.fr/) for **accuracy test** and **performance test**. Through [this test](https://github.com/milvus-io/bootcamp/blob/master/benchmark_test/lab2_sift1b_100m.md), you can learn the basic operations of Milvus, including creating collection, inserting data, building indexes, searching, etc.

<!--ALL SOLUTIONS-->

## :pencil: Solutions

### :icecream: Run locally

Here are several solutions for vector similarity search solution based on **[Milvus](https://milvus.io/)**. Each solution contains a Jupyter Notebook and a Docker deployable solution, everyone can run it in your local machine. And there are also some related technical articles and live streams.

| <br />Solutions<img width=600/> | <br />Have fun with it<img width=300/>                    | <br />Article<img width=200/>                              | <br />Video<img width=200/>                          |
| ----------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------- |
| [**Reverse Image Search**](./solutions/reverse_image_search)<br />Build a reverse image search system using Milvus paired with YOLOv3 for object detection and ResNet-50 for feature extraction. | [Jupyter notebook](solutions/reverse_image_search/reverse_image_search.ipynb)<br />[Quick deploy](solutions/reverse_image_search/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/7lNuaI-eL3lsQlOq0eolkw)<br />[English](https://blog.milvus.io/milvus-application-1-building-a-reverse-image-search-system-based-on-milvus-and-vgg-aed4788dd1ea) | [Chinese](https://www.bilibili.com/video/BV1SN411o79n) |
| [**Question Answering System**](./solutions/question_answering_system)<br />Build an intelligent chatbot using Milvus and the BERT model for natural language processing (NLP). | [Jupyter notebook](solutions/question_answering_system/question_answering.ipynb)<br />[Quick deploy](solutions/question_answering_system/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/BZp4CMv2yuVb0oEyuDKNkw)<br />[English](https://medium.com/voice-tech-podcast/building-an-intelligent-qa-system-with-nlp-and-milvus-75b496702490) |                                                        |
| [**Recommendation System**](./solutions/recommendation_system)<br />Build an AI-powered movie recommendation system using Milvus paired with PaddlePaddle’s deep learning framework. | [Jupyter notebook](solutions/recommendation_system/recommendation_system.ipynb)<br />[Quick deploy](solutions/recommendation_system/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/nAr45u-ruvhWQ8LcVxbhOg) |                                                        |
| [**Molecular Similarity Search**](./solutions/molecular_similarity_search)<br />Build a molecule similarity search system using Milvus paired with RDKit for cheminformatics. | [Jupyter notebook](solutions/molecular_similarity_search/molecular_search.ipynb)<br />[Quick deploy](solutions/molecular_similarity_search/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/ZIH_zYltT6aJNQYMhOSsAg) |                                                        |
| [**Video Similarity Search**](./solutions/video_similarity_search)<br />Build a video similarity search engine using Milvus and Keras neural network. | [Jupyter notebook](solutions/video_similarity_search/video_similarity_search.ipynb)<br />[Quick deploy](solutions/video_similarity_search/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/DOfiGP5BG_9sD7zZair4ew)<br />[English](https://blog.milvus.io/4-steps-to-building-a-video-search-system-5a3ced633308) |                                                        |
| [**Audio Similarity Search**](./solutions/audio_similarity_search)<br />Build an audio search engine using Milvus paired with PANNs for audio pattern recognition. | [Jupyter notebook](solutions/audio_similarity_search/audio_similarity_search.ipynb)<br />[Quick deploy](solutions/video_similarity_search/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/PJfO71YOTW2gXO6SL-OOuA) |                                                        |
| [**Text Search Engine**](./solutions/text_search_engine)<br />Combining Milvus and BERT model for searching the similar texts. | [Jupyter notebook](solutions/text_search_engine/text_search_engine.ipynb)<br />[Quick deploy](solutions/text_search_engine/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/OUrBSCqnLuh9btyK3SxWgQ) | [Chinese](https://www.bilibili.com/video/BV1Xi4y1E7Tb) |

### :clapper: [Live demo](https://zilliz.com/milvus-demos?isZilliz=true)

We have built [online demos](https://zilliz.com/milvus-demos?isZilliz=true) of reverse image search, chatbot and molecular search that everyone can have fun wit it.

### :fries: [Have a Try](https://zilliz.com/solutions)

If you want to upload your own data for similarity search, you can [try it](https://zilliz.com/solutions). You can choose any solutions from image search, chatbot, audio search or video object detection.

<!--THE COLLABORATIONS-->

## :two_women_holding_hands: Collaborations

### :clap: [Milvus_and_ONNX](etc/onnx_and_milvus)

Build a reverse image search system with Milvus using various AI models in collaboration with the Open Neural Network Exchange (ONNX).

## :fire: Supports

Join the Milvus community on [Slack](https://join.slack.com/t/milvusio/shared_invite/zt-e0u4qu3k-bI2GDNys3ZqX1YCJ9OM~GQ) to share your suggestions, advice, and questions with our engineering team. Also, you can join our [WeChat group](https://github.com/milvus-io/milvus/discussions/4156).


