数据集介绍：Lettuce Architectural Phenotypes from Multimodal Images
本数据集来自我们发表于 Computers and Electronics in Agriculture（2025年第232卷）的一篇论文：
《Lettuce architectural phenotypes extraction from multimodal images by low-light sensitivity and strong spatial perception》
（PDF见 论文原文）

本研究针对人工光照植物工厂中生菜的表型性状提取问题，构建了一个多模态图像数据集，包含 RGB、红外（IR）和深度（Depth）图像，并配套设计了融合模型，用于非接触、自动化地获取植物高度与冠幅等关键农艺性状。

📁 数据说明
图像来源：使用 Intel® RealSense™ D435i 相机，从培养架侧面拍摄。每小时采集一次图像，时间段为每天 9:00 至 23:00。
图像格式：RGB、IR 和 Depth，分辨率均为 1280x720，PNG 格式。
标注类别：所有图像使用 LabelImg 进行了手动标注，类别为 “lettuce”，包含目标边界框（bounding box）信息。
样本数量：
训练集：9,000 张图像
验证集：8,000 张图像
测试集：1,000 张图像
品种信息：包含三种生菜品种：碧霄（Bixiao）、琥乾（Huqian）和蒙黛（Mondai）
🔗 数据下载（百度网盘）
链接: https://pan.baidu.com/s/your-link


@article{lu2025lettuce,
  title={Lettuce architectural phenotypes extraction from multimodal images by low-light sensitivity and strong spatial perception},
  author={Lu, Shenglian and Lv, Yibo and Qian, Tingting and Ren, Wenyi and Li, Xiaoming and Li, Yiyang and Li, Guo},
  journal={Computers and Electronics in Agriculture},
  volume={232},
  pages={109928},
  year={2025},
  publisher={Elsevier},
  doi={10.1016/j.compag.2025.109928}
}
提取码: xxxx
