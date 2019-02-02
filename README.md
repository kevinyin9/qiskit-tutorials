# Qiskit 教學手冊
[![License](https://img.shields.io/github/license/Qiskit/qiskit-tutorials.svg?style=popout-square)](https://opensource.org/licenses/Apache-2.0)[![](https://img.shields.io/github/release/Qiskit/qiskit-tutorials.svg?style=popout-square)](https://github.com/Qiskit/qiskit-tutorials/releases)

歡迎來到 [Qiskit](https://www.qiskit.org/) 的教學手冊!

在這個專案中，有許多Jupyter notebooks的程式範本，用來幫助想使用qiskit學習量子計算的人，並可以在以下幾個backends之中執行(線上的量子處理器、線上模擬器或是本機的模擬器)。 此連結為IBM的線上量子處理器 [IBM Q](https://quantumexperience.ng.bluemix.net/qx/devices)。

## 安裝

這些notebooks的範本以及教學可以在Github瀏覽。為了讓您有更好的學習過程以及體驗。

您可以使用[the Binder image](https://mybinder.org/v2/gh/Qiskit/qiskit-tutorial/master?filepath=index.ipynb)可以讓您透過瀏覽器去使用jupyter notebooks，並使您不用下載或安裝任何東西，但這也代表您不該輸入私人訊息到notebooks中(例如您的API金鑰)。 這篇[issue #231](https://github.com/Qiskit/qiskit-tutorial/issues/231)說明了您在使用完mybinder之後，應該立即重新建立一組新的token。

並請參考 [安裝手冊](INSTALL.md) 以順利安裝Qiskit在您的電腦上。

## Contents

We have organized the tutorials into two sections:

### 1. [Qiskit notebooks](qiskit/)<a id='qiskit'></a>

We've collected a core reference set of notebooks in this section outlining the features of Qiskit. We will be keeping them up to date with the latest Qiskit version.  
- [Basics](qiskit/basics) is meant for those who are getting started.
- [Terra](qiskit/terra) is meant for those who want to study circuits.
- [Ignis](qiskit/ignis) is meant for those who want to study noise.
- [Aqua](qiskit/aqua) is meant for those who want to develop applications on NISQ computers.
- [Jupyter](qiskit/jupyter) is meant to highlight some cool Juypter features.

### 2. [Community notebooks](community/)<a id='community'></a>

Teaching quantum computing and qiskit has many different paths of learning. We love our community, and we love the contributions so keep them coming. Because Qiskit is changing so much, at the moment we cant keep this updated, but there are some great notebooks in here. See:
- [Hello, Quantum World](community/hello_world/) learn from the community how to write your first quantum program.
- [Quantum Games](community/games/), learn quantum computing by having fun.
- [Quantum Information Science with Terra](community/terra/), learn about quantum information science with Qiskit Terra.
- [Textbook Quantum Algorithms](community/algorithms/), learn Qiskit from the textbook algorithms.
- [Quantum Algorithms](community/aqua/), learn about quantum algorithms for noisy near-term devices with Qiskit Aqua.
- [Teach Me Qiskit 2018](community/awards/teach_me_qiskit_2018/), learn from the great contributions to the [Teach Me Qiskit award](https://www.ibm.com/blogs/research/2018/06/teach-qiskit-winner/).

To go through the tutorials, load up the [index.ipynb](index.ipynb) notebook and start learning.

## Contribution Guidelines

If you'd like to contribute to Qiskit Tutorials, please take a look at our
[contribution guidelines](.github/CONTRIBUTING.rst). This project adheres to Qiskit's [code of conduct](.github/CODE_OF_CONDUCT.md). By participating, you are expect to uphold to this code.

We use [GitHub issues](https://github.com/Qiskit/qiskit-tutorials/issues) for tracking requests and bugs. Please use our [slack](https://qiskit.slack.com) for discussion and simple questions. To join our Slack community use the [link](https://join.slack.com/t/qiskit/shared_invite/enQtNDc2NjUzMjE4Mzc0LTMwZmE0YTM4ZThiNGJmODkzN2Y2NTNlMDIwYWNjYzA2ZmM1YTRlZGQ3OGM0NjcwMjZkZGE0MTA4MGQ1ZTVmYzk). For questions that are more suited for a forum we use the Qiskit tag in the [Stack Overflow](https://stackoverflow.com/questions/tagged/qiskit).

## Authors

Qiskit Tutorials is the work of [many people](https://github.com/Qiskit/qiskit-tutorials/graphs/contributors) who contribute
to the project at different levels.

## License

[Apache License 2.0](LICENSE.txt)
