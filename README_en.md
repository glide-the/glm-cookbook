<h1>
   <img src="asset/glm.png" alt="glm" style="height: 1.5em; vertical-align: bottom;" />
   glm-cookbook
</h1>

[中文版本](README.md)

Welcome to the GLM API Model Beginner's Warehouse in Exploration 📘。 This is an open-source GLM API introductory code
textbook.

Here, you will find rich **code examples 👨**,**Practical Guide 🗺** And **resource links 🔗**， Perhaps it can help you
easily master the use of GLM API!

## Recent Update 🔥
+ 🔥 2024-07-26: This CookBook updates the [CogVideoX video generation model call tutorial](vision/cogvideox_pysdk.ipynb), welcome to check it out.
+ 🔥 2024-07-20: This CookBook updates the [CharacterGLM & Emohaa call tutorial](basic/character_glm_pysdk.ipynb) and [glm-4v small object recognition manual](vision/glm-v_small_text_recognition.ipynb).
+ 🔥 2024-07-13: This CookBook updates the [Simple usage manual](glm_langchain_glm_framework.ipynb) of the [LangChain-GLM](https://github.com/MetaGLM/langchain-glm)
framework.
+ 🔥 2024-06-25: This CookBook updates the [Tutorial](basic/openai2zhipu.ipynb) for quickly switching from the OpenAI API to the GLM API model adaptation. Welcome to check it out.
+ 🔥 2024-05-25: Batch API tutorial updated, you can view the tutorial [Here](basic/glm_batch_api.ipynb).
+ 🔥 2024-05-10: GLMs API basic call tutorial updated. Check [Here](glms/glms_api_call.md) to view the tutorial.
+ 🔥 2024-04-28: ZhipuAI Pyton SDK updated, please update the SDK to adapt to the latest tutorial.
+ 🔥 2024-04-23: GLM-4 now supports access using OpenAI SDK, greatly reducing development replacement costs!
+ 🔥 2024-03-16: The warehouse has started to be updated [Zhipu Qingyan](glms) Basic developer teaching document, welcome to experience it!
+ 🔥 2024-03-06: The organization where this Repos is
  located [MetaGLM](https://github.com/MetaGLM) has updated the SDKs of 4 languages (Python, Java, C#, Node.js).
  Comments and suggestions for the project are welcome Code improvements!

## Quick Start 🚀

1. To start using the GLM API, you first need a GLM API account and the corresponding API key.
   If you don’t have an account yet, you can register for free [here](https://open.bigmodel.cn/).

2. My code is based on **Python, Jupyter Note**, but the same concept can be applied to other programming languages (but
   you may have to implement it yourself).
   These code examples are intended to help me (and perhaps you) how to use the GLM API efficiently to complete common
   simple tasks. It is recommended to use `Python 3.9 - 3.12`
   version (my own is Python 3.10). You need to install the necessary dependencies to better use the Demo. You can use
   the following command to install total dependencies:

```bash
pip install -r requirements.txt
```

3. By the way, I usually use ✅GLM4 to complete tasks. I also recommend you to use this model!

## Warehouse file 📂

I have classified multiple folders, each of which has its own content. You can view it according to your needs!

+ 🌱`basic` The most basic content is just a successful call.

+ 👁️`vision` About multi-modal calls and basic applications.

+ 🔧`finetune` Maybe you can come here to find fine-tuning content?

+ 🎉`demo` Some interesting demos, which may inspire some inspiration.
    + 🤖`agent` Let’s see how powerful the agent at the press conference is!
    + 📚`data` The data needed to run the demo.

+ 📊`glms` GLMs (Zhipu Qingyan) area, even if you don’t know how to code, you can quickly get started!

+ 🏠`asset` Some related picture information.

You can quickly understand the structure of this warehouse through the following pictures. I will update the latest
experiments and teaching content of Zhipu AI SDK as soon as possible.

![Implementation schematic diagram](asset/plan.png)

## Open Source SDK

The GLM-4 series SDK has been open source. If you want to make modifications directly on our SDK, you can make the
modifications at the following address:

+ [Python SDK](https://github.com/MetaGLM/zhipuai-sdk-python-v4)
+ [Java SDK](https://github.com/MetaGLM/zhipuai-sdk-java-v4)
+ [C# SDK](https://github.com/MetaGLM/zhipuai-sdk-csharp-v4)
+ [Node.js SDK](https://github.com/MetaGLM/zhipuai-sdk-nodejs-v4)
+ If you have SDKs in other languages that you would like to contribute to the official repository, please submit a PR.

## Contribution Guide 🤝

Everyone is welcome to contribute your own ideas and code! If you have any suggestions or want to add your own code,
please feel free to submit a Pull Request or open an Issue for discussion.
If you like this repository, feel free to give it a ⭐, it will help me a lot!