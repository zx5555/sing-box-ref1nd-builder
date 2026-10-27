# sing-box-ref1nd-builder

本项目用于自动化追踪与构建 [reF1nd/sing-box](https://github.com/reF1nd/sing-box) 的 **Stable 稳定版** 与 **Testing 测试版**。

## 特色
- **极度精简**：剥离 Tailscale、OpenVPN、USBIP 等冗余，专为 Android eBPF 性能调优；
- **矩阵编译**：并行产出 Stable 与 Testing 两个渠道；
- **自动同步**：定时检测上游变动，有新提交才触发编译；
- **Discord 推送**：构建完成自动向 Discord 专属频道推送标签卡片与下载直链。
