# Summary

Classical Chinese Universal Dependencies Treebank annotated and converted by Institute for Research in Humanities, Kyoto University.

# Introduction

This Treebank is taken under the full text of 論語 (Lunyu, 20 volumes), 孟子 (Mencius, 14 volumes), and 43 volumes from 禮記. In Classical Chinese we had no spaces or punctuations between words or sentences, so we did not include any spaces or punctuations in Treebank files:

* lzh_kyoto-ud-test.conllu
    - 學而篇第一 為政篇第二 and 八佾篇第三 from 論語
    - 梁惠王上 and 梁惠王下 from 孟子
    - 中庸 from 禮記

* lzh_kyoto-ud-dev.conllu
    - 顏淵篇第十二 子路篇第十三 and 憲問篇第十四 from 論語
    - 告子上 and 告子下 from 孟子
    - 大學 from 禮記

* lzh_kyoto-ud-train.conllu
    - 論語 (except for 學而篇第一 為政篇第二 八佾篇第三 顏淵篇第十二 子路篇第十三 憲問篇第十四)
    - 孟子 (except for 梁惠王上 梁惠王下 告子上 告子下)
    - 曲禮上 to 樂記 and 經解 to 喪服四制 from 禮記 (except for 中庸 大學)

# References

* Koichi Yasuoka: Universal Dependencies Treebank of the Four Books in Classical Chinese, DADH2019: 10th International Conference of Digital Archives and Digital Humanities, 1st ed. (December 5, 2019), pp.20-28.

# Changelog

* 2020-05-15 v2.6
  * 19 volumes from 禮記 added.

* 2019-11-15 v2.5
  * 22 volumes from 禮記 added.

* 2019-05-15 v2.4
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.4
License: PD
Includes text: yes
Genre: nonfiction
Lemmas: converted with corrections
UPOS: converted with corrections
XPOS: converted with corrections
Features: converted with corrections
Relations: manual native
Contributors: Yasuoka, Koichi; Wittern, Christian; Morioka, Tomohiko; Ikeda, Takumi; Yamazaki, Naoki; Nikaido, Yoshihiro; Suzuki, Shingo; Moro, Shigeki; Li, Yuan; Shirasu, Hiroyuki; Fujita, Kazunori
Contributing: elsewhere
Contact: yasuoka@kanji.zinbun.kyoto-u.ac.jp
===============================================================================
</pre>
