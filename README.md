# Qiskit 教學手冊
[![License](https://img.shields.io/github/license/Qiskit/qiskit-tutorials.svg?style=popout-square)](https://opensource.org/licenses/Apache-2.0)[![](https://img.shields.io/github/release/Qiskit/qiskit-tutorials.svg?style=popout-square)](https://github.com/Qiskit/qiskit-tutorials/releases)

歡迎來到 [Qiskit](https://www.qiskit.org/) 的教學手冊!

在這個專案中，有許多Jupyter notebooks的程式範本，用來幫助想學習qiskit以及量子計算的開發者，並可以在以下幾個backends之中執行(線上的量子處理器、線上模擬器或是本機的模擬器)。 此連結為IBM的線上量子處理器 [IBM Q](https://quantumexperience.ng.bluemix.net/qx/devices)。

## 安裝

這些notebooks的範本以及教學可以在Github瀏覽。為了使您有更好的學習過程以及體驗。您可以使用[the Binder image](https://mybinder.org/v2/gh/Qiskit/qiskit-tutorial/master?filepath=index.ipynb)，讓您透過瀏覽器使用jupyter notebooks，使您不用下載或安裝任何軟體，但建議您避免輸入私人訊息到notebooks之中(例如您的API金鑰)。 這篇[issue #231](https://github.com/Qiskit/qiskit-tutorial/issues/231)說明了您在使用完mybinder之後，應該立即重新建立一組新的token。

並請參考 [安裝手冊](INSTALL.md) 以順利安裝Qiskit在您的電腦上。

## 內容

我們將教學手冊分成兩個部分:

### 1. [Qiskit notebooks](qiskit/)<a id='qiskit'></a>

第一部分是一些核心內容，您將會大致瞭解Qiskit，我們將會持續更新這些教學至最新版本的Qiskit。
- [Basics](qiskit/basics)，適合初學者學習的開始。
- [Terra](qiskit/terra)，量子電路的基礎教學。
- [Ignis](qiskit/ignis)，noise噪音的基礎教學。
- [Aqua](qiskit/aqua)，在NISQ電腦上開發應用程式的教學。
- [Jupyter](qiskit/jupyter)，介紹一些特別的Jupyter功能。

### 2. [Community notebooks](community/)<a id='community'></a>

學習量子計算以及Qiskit有很多不同的學習方法。我們很熱愛也很歡迎社群的貢獻，因為Qiskit會不斷的大幅更新以及優化。
這裡是一些非常不錯的筆記:
- [Hello, Quantum World](community/hello_world/)，寫下您的第一個量子程式。
- [Quantum Games](community/games/)，透過遊戲開心得學習量子計算。
- [Quantum Information Science with Terra](community/terra/)，透過Qiskit Terra學習量子資訊科學。
- [Textbook Quantum Algorithms](community/algorithms/)，透過演算法筆記來學習Qiskit。
- [Quantum Algorithms](community/aqua/)，透過noisy near-term devices以及Qiskit Aqua來學習量子演算法。
- [Teach Me Qiskit 2018](community/awards/teach_me_qiskit_2018/)，從[Teach Me Qiskit award](https://www.ibm.com/blogs/research/2018/06/teach-qiskit-winner/)這個偉大的貢獻來學習Qiskit。

想完整查看教學手冊，可以至 [index.ipynb](index.ipynb)。

## 貢獻教學

如果您想參與貢獻Qiskit教學手冊，您可以查看[contribution guidelines](.github/CONTRIBUTING.rst). 此專案遵循[行為守則](.github/CODE_OF_CONDUCT.md). 如果您也能遵守此份守則。

我們並使用 [GitHub issues](https://github.com/Qiskit/qiskit-tutorials/issues) 來追蹤 requests 以及 bugs. 如果有相關問題可以至 [slack](https://qiskit.slack.com) 詢問。 此為Slack [連結](https://join.slack.com/t/qiskit/shared_invite/enQtNDc2NjUzMjE4Mzc0LTMwZmE0YTM4ZThiNGJmODkzN2Y2NTNlMDIwYWNjYzA2ZmM1YTRlZGQ3OGM0NjcwMjZkZGE0MTA4MGQ1ZTVmYzk). 並且可以在 [Stack Overflow](https://stackoverflow.com/questions/tagged/qiskit) 上詢問Qiskit的相關問題並tag qiskit.

## 作者群

Qiskit教學手冊是由[眾多人](https://github.com/Qiskit/qiskit-tutorials/graphs/contributors)在各方面的貢獻所完成的。

## 許可

[Apache 許可 2.0](LICENSE.txt)
