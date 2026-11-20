# Awesome Tech Books

AwesomeTechBooks 组织的公共入口，汇总组织里各本技术书籍的中文版。在线阅读地址：<https://awesometechbooks.github.io/>。

## 书目

<!-- catalog:start -->
| 书名 | 说明 | 许可证 | 目录 |
| --- | --- | --- | --- |
| [Rust 程序设计语言](https://awesometechbooks.github.io/rust-book-zh/) | [The Rust Programming Language](https://doc.rust-lang.org/book/) 的简体中文译本，译自 2026-09 上游版本（`1500248d`），21 章 + 7 个附录 | MIT / Apache-2.0 | [`AwesomeTechBooks/rust-book-zh`](https://github.com/AwesomeTechBooks/rust-book-zh) |
| [CUDA 编程：从并行模型到工程实践](https://awesometechbooks.github.io/cuda-programming-zh/) | 原创中文教程，每章围绕可运行的程序和实测数据，7 部分 36 章；不是 NVIDIA 官方文档 | 文字 CC BY 4.0，代码 MIT | [`AwesomeTechBooks/cuda-programming-zh`](https://github.com/AwesomeTechBooks/cuda-programming-zh) |
| [C++ 规则新编](https://awesometechbooks.github.io/cpp-rules-zh/) | 原创中文教程，把八本经典 C++ 规则书的 410 条规则按主题合并重讲，以 C++20 为基准补上新标准和工程实践，8 部分 36 章，512 个示例均用 Clang 21 实测 | 文字 CC BY 4.0，代码 MIT | [`AwesomeTechBooks/cpp-rules-zh`](https://github.com/AwesomeTechBooks/cpp-rules-zh) |
| [Swift 编程语言](https://awesometechbooks.github.io/swift-book-zh/) | [The Swift Programming Language](https://docs.swift.org/swift-book/) 的简体中文译本（Swift 6.4），译自 2026-09 上游版本（`1c05984`），语言指南 + 语言参考共 43 章 | Apache-2.0（附 Runtime Library Exception） | [`AwesomeTechBooks/swift-book-zh`](https://github.com/AwesomeTechBooks/swift-book-zh) |
| [容器与 Kubernetes 实践](https://awesometechbooks.github.io/container-k8s-zh/) | 原创中文教程，以 Kubernetes 1.37 / Docker Engine 29 官方文档为准，从 namespace、cgroup 讲到集群运维，9 部分 36 章，278 个示例均在 Docker-in-Docker 实验环境实测 | 文字 CC BY 4.0，代码 MIT | [`AwesomeTechBooks/container-k8s-zh`](https://github.com/AwesomeTechBooks/container-k8s-zh) |
| [四足机器人控制：从关节电机到自主行走](https://awesometechbooks.github.io/quadruped-control-zh/) | 原创中文教程，参考《四足机器人控制算法——建模、控制与实践》的章节结构、覆盖其全部 11 章内容，从关节电机讲到小跑和导航，70 个示例用 MuJoCo 仿真 Unitree A1 实测 | 文字 CC BY 4.0，代码 MIT | [`AwesomeTechBooks/quadruped-control-zh`](https://github.com/AwesomeTechBooks/quadruped-control-zh) |
| [C++ 并发与并行编程：线程、内存模型、并行计算与服务器](https://awesometechbooks.github.io/cpp-concurrency-zh/) | 原创中文教程，把三本并发与服务器编程书的内容按主题合编，C++20 标准库为主线，pthread、OpenMP、MPI 和 Linux 系统调用并排对照，10 部分 42 章，520 个示例均用 GCC 15 实测 | 文字 CC BY 4.0，代码 MIT | [`AwesomeTechBooks/cpp-concurrency-zh`](https://github.com/AwesomeTechBooks/cpp-concurrency-zh) |
| [AI Agent 工程：从一次模型调用到多 agent 系统](https://awesometechbooks.github.io/ai-agent-zh/) | 原创中文教程，把 Anthropic、OpenAI 的 agent 工程文章和 MCP、Agent Skills 规范、LangChain 资料按主题合编，从手写 agent 循环讲到多 agent 和生产，9 部分 27 章，205 个示例调用 DeepSeek 实际运行并录制 | 文字 CC BY 4.0，代码 MIT | [`AwesomeTechBooks/ai-agent-zh`](https://github.com/AwesomeTechBooks/ai-agent-zh) |
| [看得见的 CMake](https://awesometechbooks.github.io/cmake-visible-zh/) | 原创中文教程，以 CMake 4.2 为准，从三个阶段、作用域和缓存讲到目标与用法要求、依赖、安装导出、测试和工具链，8 部分 26 章；122 个示例都在 CMake 自带的调试器下实际运行并逐条命令录制，书中可以弹出查看器逐行回放变量、缓存、目标属性和文件的变化 | 文字 CC BY 4.0，代码 MIT | [`AwesomeTechBooks/cmake-visible-zh`](https://github.com/AwesomeTechBooks/cmake-visible-zh) |
<!-- catalog:end -->

## 新增一本书

书目数据在 `catalog.json`，首页、本文件和组织主页的书目表都由生成器生成。新增步骤见 [AwesomeTechBooks/platform](https://github.com/AwesomeTechBooks/platform)：建好书仓库并接入发布流水线，再到本仓库的 `catalog.json` 加一条，然后重新生成书目表。

## 许可证

站点本身（本仓库的页面、生成配置和静态资源）使用 MIT 许可证。各书的许可证见其各自仓库中的 `LICENSE` 文件。
