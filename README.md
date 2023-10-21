![](./images/describe-en.png)
<p align="center">
  <a href="./README.md">English</a> |
  <a href="./README_CN.md">简体中文</a> |
  <a href="./README_JA.md">日本語</a> |
  <a href="./README_ES.md">Español</a>
</p>

#### [Website](https://dify.ai) • [Docs](https://docs.dify.ai) • [Deployment Docs](https://docs.dify.ai/getting-started/install-self-hosted) •  [FAQ](https://docs.dify.ai/getting-started/faq) • [Twitter](https://twitter.com/dify_ai) • [Discord](https://discord.gg/FngNHpbcY7)

**Dify** is an easy-to-use LLMOps platform designed to empower more people to create sustainable, AI-native applications. With visual orchestration for various application types, Dify offers out-of-the-box, ready-to-use applications that can also serve as Backend-as-a-Service APIs. Unify your development process with one API for plugins and datasets integration, and streamline your operations using a single interface for prompt engineering, visual analytics, and continuous improvement.

Applications created with Dify include:

Out-of-the-box web sites supporting form mode and chat conversation mode
A single API encompassing plugin capabilities, context enhancement, and more, saving you backend coding effort
Visual data analysis, log review, and annotation for applications


https://github.com/langgenius/dify/assets/100913391/f6e658d5-31b3-4c16-a0af-9e191da4d0f6


## Highlighted Features
**1. LLMs support:** Choose capabilities based on different models when building your Dify AI apps. Dify is compatible with Langchain, meaning it will support various LLMs. Currently supported:

- [x] **OpenAI**: GPT4, GPT3.5-turbo, GPT3.5-turbo-16k, text-davinci-003 
- [x] **Azure OpenAI Service**
- [x] **Anthropic**: Claude2, Claude-instant
- [x] **Replicate**
- [x] **Hugging Face Hub**
- [x] **ChatGLM**
- [x] **Llama2**
- [x] **MiniMax**
- [x] **Spark**
- [x] **Wenxin**
- [x] **Tongyi**


We provide the following free resources for registered Dify cloud users (sign up at [dify.ai](https://dify.ai)):
* 200 free OpenAI queries to build OpenAI-based apps

  
**2. Visual orchestration:** Build an AI app in minutes by writing and debugging prompts visually.

**3. Text embedding:** Fully automated text preprocessing embeds your data as context without complex concepts. Supports PDF, TXT, and syncing data from Notion, webpages, APIs.

**4. API-based:**  Backend-as-a-service. Access web apps directly or integrate via APIs without complex backend setup.

**5. Plugins:** Dify "Smart Chat" now supports first-party plugins like web browsing, Google search, Wikipedia to enable online lookup, analyzing web content, and explaining the AI's reasoning process conversationally.

**6. Team workspaces:** Team members can join workspaces to collaboratively edit, manage, and use team AI apps.

**7. Data labeling and improvement:**  Visually inspect AI app logs and improve data via labeling. Observe the AI's reasoning process to continuously enhance performance. (Coming soon)

## Use cases
* [Create an AI ChatBot with Business Data in Minutes.](https://docs.dify.ai/use-cases/create-an-ai-chatbot-with-business-data-in-minutes)
* [How to Build an Notion AI Assistant Based on Your Own Notes?](https://docs.dify.ai/use-cases/build-an-notion-ai-assistant)
* [Create a Midjoureny Prompt Bot Without Code in Just a Few Minutes.](https://docs.dify.ai/use-cases/create-a-midjoureny-prompt-bot-with-dify)

## Use Cloud Services

Visit [Dify.ai](https://dify.ai)

## Install the Community Edition

### System Requirements

Before installing Dify, make sure your machine meets the following minimum system requirements:

- CPU >= 2 Core
- RAM >= 4GB

### Quick Start

The easiest way to start the Dify server is to run our [docker-compose.yml](docker/docker-compose.yaml) file. Before running the installation command, make sure that [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/) are installed on your machine:

```bash
cd docker
docker compose up -d
```

After running, you can access the Dify dashboard in your browser at [http://localhost/install](http://localhost/install) and start the initialization installation process.

### Helm Chart

A big thanks to @BorisPolonsky for providing us with a [Helm Chart](https://helm.sh/) version, which allows Dify to be deployed on Kubernetes.
You can go to https://github.com/BorisPolonsky/dify-helm for deployment information.

### Configuration

If you need to customize the configuration, please refer to the comments in our [docker-compose.yml](docker/docker-compose.yaml) file and manually set the environment configuration. After making the changes, please run 'docker-compose up -d' again.

## Roadmap

Features under development:

- **Datasets**, supporting more datasets, e.g. syncing content from Notion or webpages
We will support more datasets, including text, webpages, and even Notion content. Users can build AI applications based on their own data sources.
- **Plugins**, introducing ChatGPT Plugin-standard plugins for applications, or using Dify-produced plugins
We will release plugins complying with ChatGPT standard, or Dify's own plugins to enable more capabilities in applications. 


## Q&A

**Q: What can I do with Dify?**

A: Dify is a simple yet powerful LLM development and operations tool. You can use it to build commercial-grade applications, personal assistants. If you want to develop your own applications, LangDifyGenius can save you backend work in integrating with OpenAI and offer visual operations capabilities, allowing you to continuously improve and train your GPT model.

**Q: How do I use Dify to "train" my own model?**

A: A valuable application consists of Prompt Engineering, context enhancement, and Fine-tuning. We've created a hybrid programming approach combining Prompts with programming languages (similar to a template engine), making it easy to accomplish long-text embedding or capturing subtitles from a user-input Youtube video - all of which will be submitted as context for LLMs to process. We place great emphasis on application operability, with data generated by users during App usage available for analysis, annotation, and continuous training. Without the right tools, these steps can be time-consuming.

**Q: What do I need to prepare if I want to create my own application?**

A: We assume you already have an OpenAI API Key; if not, please register for one. If you already have some content that can serve as training context, that's great!

**Q: What interface languages are available?**

A: English and Chinese are currently supported, and you can contribute language packs to us.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=langgenius/dify&type=Date)](https://star-history.com/#langgenius/dify&Date)


## Contributing 

We welcome you to contribute to Dify to help make Dify better. We welcome contributions in various ways, submitting code, issues, new ideas, or sharing the interesting and useful AI applications you have created based on Dify. At the same time, we also welcome you to share Dify at different events, conferences, and social media.

### Submit a Pull Request 

To ensure proper review, all code contributions, including from contributors with direct commit access, must be submitted as PR requests and approved by core developers before merging branches. 
We welcome PRs from everyone! If you're willing to help out, you can learn more about how to contribute code to the project in the [Contribution Guide](CONTRIBUTING.md).  

### Submit issues or ideas  

You can submit your issues or ideas by adding issues to the Dify repository. If you encounter issues, please describe the steps you took to encounter the issue as much as possible so we can better discover it. If you have any new ideas for our product, we also welcome your feedback. Please share your insights as much as possible so we can get more feedback and further discussion in the community.  

### Share your applications

We encourage all community members to share their AI applications built on Dify, which can be applied to different scenarios or different users. This will provide powerful inspiration for people who want to create AI capabilities! You can share your experience by [submitting an issue in the Dify-user-case repository](https://github.com/langgenius/dify-user-case/issues).  

### Share Dify with others

We encourage community contributors to actively demonstrate different aspects of using Dify. You can talk or share any feature of using Dify at  meetups and conferences, blogs or social media. We believe your unique sharing will be of great help to others!  Mention @Dify.AI on Twitter and/or communicate on [Discord](https://discord.gg/FngNHpbcY7) so we can give pointers and tips and help you spread the word by promoting your content on the different Dify communication channels.

### Help others 
You can also help people in need of help on Discord, GitHub issues or other social platforms, guide others to solve problems encountered during use and share usage experiences. This is also a great contribution! If you want to become a maintainer of the Dify community, please contact the official team via [Discord](https://discord.gg/FngNHpbcY7) or email us at support@dify.ai. 


## Contact Us

If you have any questions, suggestions, or partnership inquiries, feel free to contact us through the following channels:

- Submit an Issue or PR on our GitHub Repo
- Join the discussion in our [Discord](https://discord.gg/FngNHpbcY7) Community
- Send an email to hello@dify.ai

We're eager to assist you and together create more fun and useful AI applications!

## Security

To protect your privacy, please avoid posting security issues on GitHub. Instead, send your questions to security@dify.ai and we will provide you with a more detailed answer.

## Citation

This software uses the following open-source software:

- Chase, H. (2022). LangChain [Computer software]. https://github.com/hwchase17/langchain

For more information, please refer to the official website or license text of the respective software.

## License

This repository is available under the [Dify Open Source License](LICENSE).
