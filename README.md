# SubscribePapers

### * 利用GitHub Action每天定时推送最新的cs.CV的论文 (也可以指定query)
### * 彩云小译翻译摘要
### * Server酱提供从服务器到微信端的推送

## 1.GitHub Actions 
是一项持续集成和部署服务，可用于自动化构建、测试和部署你的代码。
配置 GitHub Actions 主要包括以下步骤：
在你的代码仓库中创建 .github/workflows 目录。GitHub Actions 的配置文件将存放在这个目录下。
在 .github/workflows 目录中创建一个 YAML 格式的配置文件，命名为 <workflow-name>.yml，其中 <workflow-name> 是你自定义的工作流名称。
编辑工作流配置文件，使用 YAML 语法描述工作流程的结构和步骤。配置文件中可以包含触发条件、环境变量、任务步骤、依赖项等。
保存配置文件后，GitHub 将自动检测并运行你的工作流程。

在上述示例中，配置文件定义了一个名为 "My Workflow" 的工作流程。该工作流程在 push 和 pull_request 事件触发时执行。
工作流程中定义了一个名为 "build" 的作业（job），作业在 ubuntu-latest 环境下运行。
作业中包含了多个步骤（steps），每个步骤都有一个名称和要执行的命令或动作。
  
完成配置后，将配置文件推送到代码仓库中的 .github/workflows 目录中，GitHub 将会自动运行你的工作流程。

## 2.彩云小译翻译摘要
彩云小译提供翻译api
官网链接：https://platform.caiyunapp.com/

## 3.Server酱服务
https://sct.ftqq.com/
  

