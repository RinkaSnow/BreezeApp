# BreezeApp

[![License: Pending](https://img.shields.io/badge/License-Pending-yellow.svg)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/mtkresearch/BreezeApp)](https://github.com/mtkresearch/BreezeApp/issues)
[![Google Play](https://img.shields.io/badge/Google_Play-Coming_Soon-green.svg?style=flat&logo=google-play)](https://play.google.com)
[![App Store](https://img.shields.io/badge/App_Store-Coming_Soon-blue.svg?style=flat&logo=app-store&logoColor=white)](https://apps.apple.com)

[繁體中文](../../README.md) | [English](README_en.md)

Text chatbot
<p align="center">
  <img src="../../assets/BreezeApp_npu_en.gif" width="300" alt="NPU Backend Demo"/>&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="../../assets/BreezeApp_cpu_en.gif" width="300" alt="CPU Backend Demo"/>
</p>
<p align="center">
  <em>Left: NPU Backend &nbsp;&nbsp;&nbsp;&nbsp; Right: CPU Backend</em>
</p>

Speech-to-Text

Text-to-Speech

Image QA

BreezeAPP is a mobile AI application developed for both Android and iOS platforms. Users can download it directly from the App Store and enjoy a variety of features offline, including speech-to-text, text-to-speech, text-based chatbot interactions, and image question-answering. Currently, BreezeApp supports the Breeze 2 series of models developed by MediaTek Research. Newer and better models will be supported in future updates.

## 📧 The intention of open source

We are [MediaTek Research](https://i.mediatek.com/mediatekresearch). MediaTek Research is a member of the [AI Alliance](https://thealliance.ai/).

The primary purpose of developing this application is to challenge the common perception about running Large Language Models (LLMs). Currently, many people believe that LLM can only run on super expensive computers, and large cloud service providers dictate what LLM functionalities are offered. We aim to raise public awareness about the capability of a smartphone to run an entire AI suite, LLM included, and to promote the concept that anyone should and indeed can freely choose what AI to run on their mobile devices. 

Another key objective in open sourcing the Kotlin portion of this application is to minimize the entry barriers for app developers in creating mobile AI applications. Through this, we hope to inspire app developers to create more innovative mobile AI applications. We look forward to future collaborations with app developers.

If you are interested in the BreezeApp, please feel free to contact us: [info@mtkresearch.com](info@mtkresearch.com)

## 🚀 Quick Start 

### Download & Try
- [Download the latest APK](https://huggingface.co/MediaTek-Research/BreezeApp/resolve/main/BreezeApp.apk)
- The app includes an in-app model download feature that will automatically prompt you to download required models on first launch.


## ✨ Features

- 💬 Text-based chat interface
- 🗣️ Voice input/output support
- 📸 Image understanding capabilities
- 🔄 Multiple backend support:

    | Model Type | Local CPU | MediaTek NPU | Default |
    |:---------:|:---------:|:-------:|:--------:|
    | LLM       |     ✅     |    ✅    |    -    |
    | VLM       |     🚧     |    ❌    |    -    |
    | ASR       |     🚧     |    ❌    |    -    |
    | TTS       |     ✅     |    ❌    |    -    |

## Compatible models

| Model Type | Available Models |
|:----------:|:----------------:|
| LLM        | Breeze 2         |
| VLM        | Breeze 2         |
| ASR        | Breeze 2         |
| TTS        | Breeze 2         |

 ## Compatible devices
Currently, the app has been successfully tested only on the Pixel 7a (8GB) and Samsung Flip 4. We welcome feedback from users on their actual experiences with different devices.

 
 ### Developer Settings
Want to build and contribute code? Check out our [Installation Guide](docs/setup/installation.md) for detailed instructions.



## 🆘 Help Wanted

We're looking for contributors to help with the following tasks:

1. **Promotion**
   - Increase visibility of BreezeApp
   - Multi-language support
   
2. **Performance Optimization**
   - Profile the app and enhance memory management
   - Optimize inference speed on various devices
   - Reduce app size and resource consumption

3. **Code Quality**
   - Refactor code to improve maintainability
   - Add unit and integration tests
   - Implement better error handling and logging

4. **Device Compatibility**
   - Test on more Android devices
   - Identify and fix device-specific issues
   - Support for different screen sizes and aspect ratios

5. **User Experience**
   - Improve UI responsiveness during model inference
   - Enhance accessibility features
   - Create more intuitive onboarding process

6. **Documentation**
   - Improve code documentation
   - Create developer tutorials
   - Add screenshots and demos to user guides

If you're interested in working on any of these tasks, please check out our issue tracker or open a new issue to discuss your approach before submitting a PR.

## 🤝 Contributing

Contributions are welcome! See our [Contributing Guide](/docs/contributing/guidelines.md) to get started.

## 📄 License

The license for this project is pending determination - see the [LICENSE](/LICENSE) file for details.

## 🙏 Acknowledgments

- [Executorch](https://github.com/pytorch/executorch) for LLM/VLM framework
- [k2-fsa/sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) for ASR/TTS capabilities
- MediaTek Research for core AI engines

## 🔗 Links

- [Known Issues](https://github.com/mtkresearch/BreezeApp/issues) 
