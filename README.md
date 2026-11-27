# AshDeskAndroid

AshDesk 极帧的安卓客户端（筹备中）。

- 用 Kotlin 写的界面外壳，经 JNI 调引擎：连接页、会话画面、工具条、生命周期。
- 远程桌面的协议、会话和编解码都在引擎里。引擎不开源，以二进制（AAR / 各 ABI 的 .so）提供，这个仓库只放界面和平台相关的代码。
- 总库与发布页：[mrQzs/AshDesk](https://github.com/mrQzs/AshDesk)（本仓库是它的子模块）。

## 许可

本仓库的源码按 [Apache License 2.0](LICENSE) 发布，见 [NOTICE](NOTICE)。链接的 AshDesk 引擎是闭源的，只以二进制提供，不在 Apache-2.0 的范围内。
