<p align="center">
  <a href="https://librechat.ai">
    <img src="client/public/assets/logo.svg" height="256">
  </a>
  <h1 align="center">
    <a href="https://librechat.ai">LibreChat</a>
  </h1>
</p>

<p align="center">
  <a href="https://discord.librechat.ai"> 
    <img
      src="https://img.shields.io/discord/1086345563026489514?label=&logo=discord&style=for-the-badge&logoWidth=20&logoColor=white&labelColor=000000&color=blueviolet">
  </a>
  <a href="https://www.youtube.com/@LibreChat"> 
    <img
      src="https://img.shields.io/badge/YOUTUBE-red.svg?style=for-the-badge&logo=youtube&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
  <a href="https://docs.librechat.ai"> 
    <img
      src="https://img.shields.io/badge/DOCS-blue.svg?style=for-the-badge&logo=read-the-docs&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
  <a aria-label="Sponsors" href="https://github.com/sponsors/danny-avila">
    <img
      src="https://img.shields.io/badge/SPONSORS-brightgreen.svg?style=for-the-badge&logo=github-sponsors&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
</p>

<p align="center">
<a href="https://railway.app/template/b5k2mn?referralCode=HI9hWz">
  <img src="https://railway.app/button.svg" alt="Deploy on Railway" height="30">
</a>
<a href="https://zeabur.com/templates/0X2ZY8">
  <img src="https://zeabur.com/button.svg" alt="Deploy on Zeabur" height="30"/>
</a>
<a href="https://template.cloud.sealos.io/deploy?templateName=librechat">
  <img src="https://raw.githubusercontent.com/labring-actions/templates/main/Deploy-on-Sealos.svg" alt="Deploy on Sealos" height="30">
</a>
</p>

<p align="center">
  <a href="https://www.librechat.ai/docs/translation">
    <img 
      src="https://img.shields.io/badge/dynamic/json.svg?style=for-the-badge&color=2096F3&label=locize&query=%24.translatedPercentage&url=https://api.locize.app/badgedata/4cb2598b-ed4d-469c-9b04-2ed531a8cb45&suffix=%+translated" 
      alt="Translation Progress">
  </a>
</p>


# ✨ 功能特性

- 🖥️ **UI 与体验**：灵感来自 ChatGPT，但拥有增强的设计和功能

- 🤖 **AI 模型选择**：  
  - Anthropic (Claude)、AWS Bedrock、OpenAI、Azure OpenAI、Google、Vertex AI、OpenAI Assistants API（包括 Azure）
  - [自定义端点](https://www.librechat.ai/docs/quick_start/custom_endpoints)：在 LibreChat 中使用任何兼容 OpenAI 的 API，无需代理
  - 兼容[本地和远程 AI 提供商](https://www.librechat.ai/docs/configuration/librechat_yaml/ai_endpoints)：
    - Ollama、groq、Cohere、Mistral AI、Apple MLX、koboldcpp、together.ai、
    - OpenRouter、Perplexity、ShuttleAI、Deepseek、Qwen 等等

- 🔧 **[代码解释器 API](https://www.librechat.ai/docs/features/code_interpreter)**：
  - 安全沙盒执行 Python、Node.js (JS/TS)、Go、C/C++、Java、PHP、Rust 和 Fortran
  - 无缝文件处理：直接上传、处理和下载文件
  - 无隐私顾虑：完全隔离和安全的执行环境

- 🔦 **代理和工具集成**：
  - **[LibreChat 代理](https://www.librechat.ai/docs/features/agents)**：
    - 无代码自定义助手：无需编码即可构建专业化的 AI 驱动助手
    - 灵活且可扩展：附加 DALL-E-3、文件搜索、代码执行等工具
    - 兼容自定义端点、OpenAI、Azure、Anthropic、AWS Bedrock 等
    - 支持[模型上下文协议 (MCP)](https://modelcontextprotocol.io/clients#librechat)工具
  - 使用 LibreChat 代理和 OpenAI Assistants 结合文件、代码解释器、工具和 API 操作

- 🪄 **生成式 UI 与代码构件**：
  - [代码构件](https://youtu.be/GfTj7O4gmd0?si=WJbdnemZpJzBrJo3)允许在聊天中直接创建 React、HTML 和 Mermaid 图表

- 💾 **预设和上下文管理**：
  - 创建、保存和共享自定义预设
  - 在对话中途切换 AI 端点和预设
  - 编辑、重新提交和继续消息，支持对话分支
  - [消息和对话分叉](https://www.librechat.ai/docs/features/fork)实现高级上下文控制

- 💬 **多模态和文件交互**：
  - 上传并分析图像：支持 Claude 3、GPT-4.5、GPT-4o、o1、Llama-Vision 和 Gemini 📸
  - 使用自定义端点、OpenAI、Azure、Anthropic、AWS Bedrock 和 Google 与文件聊天 🗃️

- 🌎 **多语言 UI**：
  - 英语、中文、德语、西班牙语、法语、意大利语、波兰语、巴西葡萄牙语
  - 俄语、日语、瑞典语、韩语、越南语、繁体中文、阿拉伯语、土耳其语、荷兰语、希伯来语

- 🧠 **推理 UI**：
  - 动态推理 UI，适用于思维链/推理 AI 模型，如 DeepSeek-R1

- 🎨 **可定制界面**：
  - 可定制的下拉菜单和界面，适应高级用户和新手

- 🗣️ **语音和音频**：
  - 通过语音转文本和文本转语音实现免提聊天
  - 自动发送和播放音频
  - 支持 OpenAI、Azure OpenAI 和 Elevenlabs

- 📥 **导入和导出对话**：
  - 从 LibreChat、ChatGPT、Chatbot UI 导入对话
  - 将对话导出为截图、Markdown、文本、JSON

- 🔍 **搜索与发现**：
  - 搜索所有消息/对话

- 👥 **多用户和安全访问**：
  - 多用户、安全认证，支持 OAuth2、LDAP 和电子邮件登录
  - 内置审核和令牌消费工具

- ⚙️ **配置和部署**：
  - 配置代理、反向代理、Docker 和多种部署选项
  - 可完全本地使用或部署在云端

- 📖 **开源和社区**：
  - 完全开源，公开构建
  - 社区驱动的开发、支持和反馈

[有关我们功能的详细介绍，请参阅此处的文档](https://docs.librechat.ai/) 📚

## 🪶 LibreChat 的全能 AI 对话体验

LibreChat 将未来的智能助手与 OpenAI 的 ChatGPT 革命性技术结合在一起。延续原始风格的同时，LibreChat 使您能够集成多种 AI 模型。它还集成并增强了原始客户端功能，如对话和消息搜索、提示模板和插件。

使用 LibreChat，您不再需要选择 ChatGPT Plus，而可以使用免费或按需付费的 API。我们欢迎贡献、克隆和分支，以增强这个先进聊天机器人平台的能力。

[![观看视频](https://raw.githubusercontent.com/LibreChat-AI/librechat.ai/main/public/images/changelog/v0.7.6.gif)](https://www.youtube.com/watch?v=ilfwGQtJNlI)

点击缩略图打开视频☝️

---

## 🌐 资源

**GitHub 仓库：**
  - **RAG API：** [github.com/danny-avila/rag_api](https://github.com/danny-avila/rag_api)
  - **网站：** [github.com/LibreChat-AI/librechat.ai](https://github.com/LibreChat-AI/librechat.ai)

**其他：**
  - **网站：** [librechat.ai](https://librechat.ai)
  - **文档：** [docs.librechat.ai](https://docs.librechat.ai)
  - **博客：** [blog.librechat.ai](https://blog.librechat.ai)

---

## 📝 更新日志

通过访问发布页面和说明来了解最新更新：
- [发布](https://github.com/danny-avila/LibreChat/releases)
- [更新日志](https://www.librechat.ai/changelog)

**⚠️ 更新前请查阅[更新日志](https://www.librechat.ai/changelog)了解重大变更。**

---

## ✨ 部署安装

LibreChat 支持多种部署方式。这里主要介绍使用 Docker 部署和在 Windows/Linux 上直接部署。

### 1. Windows部署

#### 1.1 安装 Docker Desktop 并指定数据路径

此方法适用于在 Windows 上全新安装 Docker Desktop 时，将 WSL 2 数据（Docker 镜像、容器、卷数据等）存放到指定路径，避免占用 C 盘空间。

1. **打开 PowerShell (以管理员身份运行)**。

2. **切换到 Docker Desktop 安装包所在的目录**。例如，如果安装包在 `D:\k8s` 下，运行：

   ```PowerShell
   cd D:\k8s
   ```

   可以使用 `ls` 命令确认 `Docker Desktop Installer.exe` 文件是否存在于当前目录。

3. **执行安装命令并指定路径**：

   PowerShell

   ```PowerShell
   Start-Process -FilePath "Docker Desktop Installer.exe" -ArgumentList 'install -accept-license --installation-dir="D:\Docker\Docker Desktop" --wsl-default-data-root="D:\Docker\data\wsl" --windows-containers-default-data-root="D:\Docker\data\windows"' -Wait
   ```

   - `Start-Process -FilePath "Docker Desktop Installer.exe"`: 启动 Docker Desktop 安装程序。
   - `-ArgumentList '...'`: 传递给安装程序的参数。
   - `install`: 执行安装操作。
   - `-accept-license`: 自动接受许可协议。
   - `--installation-dir="D:\Docker\Docker Desktop"`: 指定 Docker Desktop 程序本身的安装路径 (可修改)。
   - `--wsl-default-data-root="D:\Docker\data\wsl"`: **关键参数**，指定 WSL 2 数据根目录 (可修改到你想要的 D 盘路径)。安装程序会尝试将 WSL 的 `.vhdx` 文件放到这里。
   - `--windows-containers-default-data-root="D:\Docker\data\windows"`: 指定 Windows 容器数据路径 (如果需要使用 Windows 容器)。
   - `-Wait`: 等待安装程序完成。

   安装过程将静默进行，可能弹出 UAC 提示，请允许。安装完成后 Docker Desktop 可能会自动启动。

4. **验证安装路径**：安装完成后，以管理员身份运行 PowerShell，执行 `wsl --list --verbose`。查找名称类似 `docker-desktop-data` 的发行版，检查其 `INSTALL-LOCATION` 是否为你指定的 D 盘路径。

   **注意：** `--wsl-default-data-root` 参数旨在设置默认位置，但在某些版本或更新后可能被重置回 C 盘。如遇此情况或需迁移数据，请参考其他迁移方法。

#### 1.2. 使用 Docker 部署 LibreChat

Docker 部署方式十分简便，推荐在有长期运行 Docker 服务的环境中使用。

**前提条件：**

- 已安装 Git 和 Docker Compose。
- (Windows) 已安装 Docker Desktop。

**部署步骤：**

1. **克隆项目代码：** 打开命令行，使用 `git clone` 命令获取项目代码。为了稳定，推荐下载 release 版本：

   ```bash
   git clone https://github.com/danny-avila/LibreChat.git
   ```

   或克隆指定 release 版本：

   ```bash
   git clone --branch v0.7.2 https://github.com/danny-avila/LibreChat.git
   ```

2. **进入项目根目录：**

   ```bash
   cd LibreChat
   ```

3. **创建 `.env` 文件：** 复制示例环境文件。这是项目运行的小配置文件，初次运行可先不修改内容：

   ```bash
   cp .env.example .env
   ```

4. **启动 Docker 容器：** 运行以下命令自动拉取所需镜像并创建启动容器。国内用户建议先配置 Docker 镜像源（如阿里云）。

   ```bash
    docker-compose -f .\deploy-compose.yml up  --force-recreate
   ```

   `-d` 参数使容器在后台运行。

5. **访问 LibreChat：** 容器启动运行正常后，访问 `http://localhost:3080/`。正常情况下会看到注册登录界面。

#### 1.3 Docker 部署常见问题及解决：

- 页面右键刷新后跳转到登录界面： 这可能是 cookie 配置问题导致在非部署机器上登录后刷新跳转。临时的解决办法是：

  进入项目根目录，复制示例 override 文件：

  ```bash
  cp docker-compose.override.yml.example docker-compose.override.yml
  ```

  编辑 `docker-compose.override.yml`，在 `services: api:` 下添加 `command: npm run backend:dev`：

  ```YAML
  services:
    api:
      command: npm run backend:dev
  ```

  保存后重新运行 `docker compose up -d`。

- 配置了 librechat.yaml 但未生效： 这是因为 Docker 容器无法找到 librechat.yaml 文件。需要通过 Docker Volumes 进行映射。

  如果根目录没有 docker-compose.override.yml，先复制一个：

  ```bash
  cp docker-compose.override.yml.example docker-compose.override.yml
  ```

  编辑 `docker-compose.override.yml`，在 `services: api:` 下添加 volumes 映射：

  ```YAML
  services:
    api:
      volumes:
        - ./librechat.yaml:/app/librechat.yaml
  ```

  保存后重新运行 `docker compose up -d`。

### 2. LibreChat 基础配置

LibreChat 的主要配置通过 `.env` 和 `librechat.yaml` 文件进行。

#### 2.1. 配置 `librechat.yaml`

`librechat.yaml` 用于配置 AI 端点、界面显示等。在项目根目录执行以下命令创建该文件：

```bash
cp librechat.example.yaml librechat.yaml
```

然后编辑 `librechat.yaml` 进行配置。

##### 2.1.1. 模型配置 (AI Endpoints)

`librechat.yaml` 的 `endpoints` 部分用于配置不同的 AI 模型接口。

**Azure OpenAI 配置示例：**

以下是一个配置 Azure OpenAI 多个终结点和模型的示例：

```YAML
endpoints:
  azureOpenAI:
    # Endpoint-level configuration
    titleModel: "gpt-3.5-turbo" # 用于生成对话标题的模型
    titleMethod: "completion" # 生成标题的方法 (completion 或 functions)
    summarize: true # 是否开启对话摘要功能 (建议开启以节省 token)
    summaryModel: "gpt-4o" # 用于生成摘要的模型
    plugins: true # 是否开启插件功能 (true 表示插件使用此大模型配置)
    groups:
      # Group-level configuration
      - group: "sweden-central" # 组名称，用于标记，不影响实际功能
        apiKey: "your_sweden_central_key" # Azure OpenAI 密钥
        baseURL: "https://${INSTANCE_NAME}.openai.azure.com/openai/deployments/${DEPLOYMENT_NAME}/chat/completions?api-version=${version}" # API 请求基础 URL (建议照抄)
        instanceName: "your_sweden_central_instance_name" # Azure OpenAI 实例名称 (终结点前面部分)
        models:
          gpt-3.5-turbo: # 模型标识符，会显示在用户选择模型列表中
            deploymentName: gpt-35-turbo # Azure OpenAI 中的部署名
            version: "2024-02-01" # API 版本
          gpt-4:
            deploymentName: gpt-4-turbo
            version: "2024-02-15-preview"

      - group: "us-north-central"
        apiKey: "your_us_north_central_key"
        baseURL: "https://${INSTANCE_NAME}.openai.azure.com/openai/deployments/${DEPLOYMENT_NAME}/chat/completions?api-version=${version}"
        instanceName: "your_us_north_central_instance_name"
        models:
          gpt-4o:
            deploymentName: gpt-4o
            version: "2024-02-01"
```

**Azure OpenAI 参数解释：**

- Endpoint-level configuration (azureOpenAI 下的第一层缩进):

   应用于该端点的通用配置。

  - `titleModel`: 生成对话标题的模型。
  - `titleMethod`: 生成标题的方法 (`completion` 或 `functions`)。
  - `summarize`: 是否启用对话摘要。
  - `summaryModel`: 用于生成摘要的模型。
  - `plugins`: 是否启用插件功能并使用此配置的模型。

- Group-level configuration (groups 下的缩进):

   用于配置具有相同密钥和基础 URL 的一组模型。

  - `group`: 组的标识名。
  - `apiKey`: Azure OpenAI 的密钥。
  - `baseURL`: API 请求的基础 URL 格式。
  - `instanceName`: Azure OpenAI 终结点的实例名称。
  - `models`: 该组下的模型列表。

- Model Configuration (models 下的缩进):

   单个模型的配置。

  - `Model Identifier` (如 `gpt-3.5-turbo`): 在 LibreChat 界面中显示的模型名称。
  - `deploymentName`: Azure OpenAI 中的实际部署名称。
  - `version`: 调用该模型使用的 API 版本。

其他可选参数如 `additionalHeaders`, `serverless`, `addParams`, `dropParams`, `forcePrompt` 等，可根据需要配置，详细解释请参考提供的原文。

**注意 Azure OpenAI 流式输出：** Azure 默认的内容筛选器可能导致没有“打字机”效果的流式输出。需要进行特殊配置，具体方法请参考相关文档（如原文提到的“Azure OpenAI 生成内容流式输出”文章）。

**Ollama 配置示例：**

Ollama 配置相对简单，需要先部署好 Ollama 服务和对应模型。

```YAML
endpoints:
  custom: # Ollama 通常作为自定义端点配置
    - name: "Ollama" # 端点名称
      apiKey: "ollama" # 任意值，用于标识
      baseURL: "http://xx.xx.xxx.xxx:11434/v1/" # Ollama API 地址，需修改为实际 IP
      models:
        default: [
            "qwen:110b", # 可用模型列表
            "llama3:70b"
            ]
      fetch: false # Ollama 不支持列出模型，设为 false
      titleConvo: true
      titleModel: "qwen:110b"
      summarize: false # 根据需要配置摘要
      summaryModel: "qwen:110b"
      forcePrompt: false
      modelDisplayLabel: "Ollama" # 界面显示标签
      addParams: # Ollama 可能需要额外的参数，如 stopping criteria
        "stop": [
            "<|start_header_id|>",
            "<|end_header_id|>",
            "<|eot_id|>",
            "<|reserved_special_token"
            ]
```

**注意：** `baseURL` 需要修改为运行 Ollama 服务的机器的实际 IP 地址。

##### **2.1.2. 自定义界面配置**

`librechat.yaml` 的 `interface` 部分可以自定义隐私政策和服务条款的链接。

```YAML
# Custom interface configuration
interface:
  # Privacy policy settings
  privacyPolicy:
    externalUrl: 'https://XXX.github.io/plan/' # 修改为你的隐私政策链接
    openNewTab: true # 是否在新标签页打开

  # Terms of service
  termsOfService:
    externalUrl: 'https://XXX.github.io/plan/' # 修改为你的服务条款链接
    openNewTab: true
```

**2.1.3. 屏蔽不需要的 AI 产品**

默认情况下 LibreChat 会显示所有支持的 AI 产品。可以通过修改 `.env` 文件中的 `ENDPOINTS` 变量来控制显示哪些以及它们的顺序。

找到并取消注释 `ENDPOINTS` 行，然后修改为你想显示的端点列表，用逗号分隔：

```bash
# ENDPOINTS=openAI,assistants,azureOpenAI,bingAI,google,gptPlugins,anthropic # 默认注释
ENDPOINTS=azureOpenAI,gptPlugins,ollama # 只显示 Azure, Plugins, Ollama
```

#### 2.2. 配置 `.env` 文件

`.env` 文件包含环境变量，用于配置数据库、密钥、应用名称等。

在项目根目录执行以下命令创建该文件（如果不存在）：

```bash
cp .env.example .env
```

然后编辑 `.env` 进行配置。

- **MongoDB URI：** 参考前面部署步骤中的说明，配置 `MONGO_URI`。

- **项目 IP 地址：** 参考前面 Windows 直接部署步骤中的说明，如果需要局域网访问，配置 `HOST`, `DOMAIN_CLIENT`, `DOMAIN_SERVER`。

- **屏蔽不需要的 AI 产品：** 参考 2.1.3 节，修改 `ENDPOINTS`。

- **配置邮箱 (用于密码重置)：** 配置邮箱信息允许用户通过邮件重置密码。建议使用 Gmail，具体配置方法可参考 LibreChat 官方文档中关于 Gmail 的部分。

  ```bash
  # 邮箱配置示例 (使用 Gmail)
  MAIL_SERVICE=gmail
  MAIL_USERNAME=your_email@gmail.com
  MAIL_PASSWORD=your_gmail_app_password # 使用应用密码而非 Gmail 登录密码
  MAIL_FROM=your_email@gmail.com
  ALLOW_EMAIL_LOGIN=true # 允许邮箱登录
  ALLOW_REGISTER=true # 允许用户注册
  ```

  不配置邮箱会导致任何知道用户邮箱的人都可以发起密码重置请求（尽管没有邮箱无法接收重置链接）。

- **软件名修改：** 修改 `APP_TITLE` 可以更改 LibreChat 在浏览器标题、邮件等地方显示的名称。`CUSTOM_FOOTER` 可以添加自定义页脚。`HELP_AND_FAQ_URL` 可以修改帮助和 FAQ 链接。

  ```bash
  APP_TITLE=AIChat # 修改应用标题
  CUSTOM_FOOTER="Footer" # 添加自定义页脚
  HELP_AND_FAQ_URL=https://winxuan.github.io # 修改帮助链接
  ```

------

**参考文档：**

- LibreChat 官方文档：
  - [Docker 本地安装](https://www.librechat.ai/docs/local/docker)
  - [.env 文件配置](https://www.librechat.ai/docs/configuration/dotenv)
  - [`librechat.yaml` 配置](https://www.google.com/search?q=[https://www.librechat.ai/docs/configuration/librechat_yaml](https://www.librechat.ai/docs/configuration/librechat_yaml))
  - [AI 端点配置](https://www.librechat.ai/docs/configuration/librechat_yaml/ai_endpoints)
- (提及的) Azure OpenAI 生成内容流式输出配置文章。

希望这份整理后的文档能帮助您更好地部署和配置 LibreChat。

