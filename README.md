# LaBei4DiffSinger

UTAU音库LaBei Rasubeku的DiffSinger（OpenSVIP维护版）移植，相关项目：https://github.com/openvpi/DiffSinger


# 概述

本项目为UTAU音源**翋呗ラスベク**中文OTT式CVVC_V3(中文CVVC2.0)向DiffSinger的移植，音源移植已获得授权

原音源相关详见[**原音源配布站**](https://labeirasubeku.lofter.com/)

暂按[UTAU中华组公共规约](https://utauchn.huijiwiki.com/wiki/公共规约) ，获得授权请以联系原音源音源管理者、声音提供者、角色设计者为主

1.0版本音库由DiffSinger多人训练实验trashbin训练后导出，**目前推荐使用1.1版本**

2.0版本音库为原音源外加[Opencpop](http://wenet.org.cn/opencpop/)和[M4Singers](https://github.com/M4Singer/M4Singer)进行多说话人训练后导出，作为音源移植可看作单独训练

1.0版本仍会继续随着trashbin实验以及其他多说话人混合训练试验的进一步开展继续更新，感谢[A60](https://github.com/djkcyl)进行的训练


# 转制进展

- [x] 简易流程数据集制作
- [x] 混合多说话人训练（1.0）
- [x] 只有标准开源数据集的多说话人训练（2.0）（路线正确性探索中，暂停）
- [ ] 更为准确的标注（非标准音素标注探索中）
- [ ] 试听曲
- [ ] 日文支持（待DiffSinger更新日文流程）
- [ ] 多语言支持（真的会有吗？）


# 如何获取

通过本仓库release页


# 如何使用

目前DiffSinger训练所得声库可使用OpenUTAU for Diffsinger作为编辑器进行创作，相关项目：https://github.com/xunmengshe/OpenUtau

本声库已完成打包，使用可以参照以下教程

https://www.yuque.com/openvpi/tutorial/ggn73v63tu74eqmv
