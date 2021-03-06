# 同文安卓輸入法平臺/Trime/android-rime
[![自動編譯](https://travis-ci.org/osfans/trime.svg?branch=master)](https://travis-ci.org/osfans/trime)

=====
源於開源的[注音倉頡輸入法](https://code.google.com/p/android-traditional-chinese-ime/)，
基於著名的[Rime]輸入法框架，
使用JNI的C語言和安卓的java語言書寫，
旨在保護漢語各地方言，
音碼形碼通用輸入法平臺。

## 歷史/History
- 最初，輸入法是寫給[泰如拼音](http://tieba.baidu.com/f?kw=%E6%B3%B0%E5%A6%82)（thae5 rv2）的，中文名爲“泰如輸入法”。
- 然後，添加了吳語等方言碼表，做成了一個輸入法平臺，更名爲“漢字方言輸入法”。
- 後來，兼容了五筆、兩筆等形碼，在太空衛士、徵羽的建議下，更名爲“同文輸入法平臺2.x”。寓意音碼形碼同臺，方言官話同文。
- 之後，藉助JNI技術，享受了[librime](https://github.com/rime/librime)的成果，升級爲“同文輸入法平臺3.x”，簡稱“同文輸入法”。
- 所以，TRIME是Tongwen RIME或是ThaeRvInputMEthod的縮寫。

## 許可協議/License
[Apache License 2.0](COPYING)

## 第三方庫/3rd Party Library
- [android-cmake](https://github.com/taka-no-me/android-cmake) (BSD 3-Clause License)
- [minilog](http://ceres-solver.org/) (New BSD License)
- [OpenCC](https://github.com/BYVoid/OpenCC) (Apache License 2.0)
- [RIME](http://rime.im)(BSD License)
 - [Boost C++ Libraries](http://www.boost.org/) (Boost Software License)
   - [libiconv](http://www.gnu.org/software/libiconv/) (LGPL License)
 - [darts-clone](https://code.google.com/p/darts-clone/) (New BSD License)
 - [marisa-trie](https://code.google.com/p/marisa-trie/) (BSD License)
 - [UTF8-CPP](http://utfcpp.sourceforge.net/) (Boost Software License)
 - [yaml-cpp](https://code.google.com/p/yaml-cpp/) (MIT License)
 - [LevelDB](https://github.com/google/leveldb) (New BSD License)
   - [snappy](https://google.github.io/snappy/)(BSD License)

## 編譯/Build
- [Arch Linux](https://www.archlinux.org/)
```bash
yaourt -S android-{ndk,sdk,sdk-build-tools,sdk-platform-tools,platform} apache-ant
make apk
```

## 鳴謝/Credits
- [Rime]: [佛振](https://github.com/lotem)
- [維基](https://github.com/osfans/trime/wiki)、圖文教程：[xiaoqun2016](https://github.com/xiaoqun2016)
- 鍵盤：天真可愛的滿滿、皛筱晓小笨鱼、吴琛11、熊貓阿Bo、默默ㄇㄛˋ
- 在[Issues](https://github.com/osfans/trime/issues)、貼吧、QQ羣中反饋意見的網友
- 依賴的第三方庫等開源項目

[Rime]: http://rime.im

