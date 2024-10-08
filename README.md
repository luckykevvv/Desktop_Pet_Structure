# AIVtuber Framework

AIVtuber Framework. The character models are based on Live2D, and TTS uses Google's gTTS library. The current dialog API is calling GPT4o-mini. The way to interact with the voice model is through both a dialog box and speech recognition. The plan is to first adapt for Bilibili, followed by Twitch.
Considering that most computers are now 64-bit, the Live2D model will not be adapted for v2.  

   Features:  

   Direct voice interaction with the language model  
   Multilingual support  
   Conversations are played back through TTS  
   Lip sync between the language model's voice and the Live2D model  

## Demo
Default starting screen  
![image](https://github.com/user-attachments/assets/b767b169-9b6e-41d5-be05-f1093d1f974c)

In conversation
![image](https://github.com/user-attachments/assets/e2162c3e-54bc-4100-8f9d-f6d8bedcefa3)



## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/luckykevvv/Desktop_Pet_Structure.git

2. **Install dependencies**
      ```bash
      pip install -r requirements.txt
      ```
      Additionally, please install ffmpeg. 
3. **Register for OpenAI API and write your key in openai_key.json**
4. **Run main.py**

## Credits
The Live2D rendering and manipulation part of this project is based on https://github.com/Arkueid/live2d-py.  
Character model from: https://cubism.live2d.com/sample-data/bin/hiyori_free/hiyori_free_en.zip
## License

This project is licensed under the GNU General Public License v2.0 (GPL-2.0). For more details, please refer to the LICENSE file.

## Disclaimer

This project is open-source software, and its features and services are provided for learning and reference purposes only. There is no guarantee that it will be suitable for specific purposes. When using this framework, you assume all related risks.







# 桌宠框架

~~欢迎使用桌宠框架！这是一个用于创建桌面宠物的开源框架, 桌宠基于live-2d。你可以利用这个框架来开发各种有趣和互动的桌面宠物程序，增强你的桌面体验。~~
   计划有变，现在是AIVtuber框架，人物模型基于live-2d，tts基于谷歌的gTTS库，目前对话API调用的是gpt4o-mini。现在与语音模型对话的方式是通过对话框和语音识别，准备先适配bilibili，再是twitch。  
   考虑到现在电脑都是64位，因此live-2d模型不对v2做适配。  

   特性：  
   对语言模型通过语音直接对话  
   支持多语言  
   对话会经过tts播放出来  
   大模型的语音与live-2d模型嘴型适配  

## 展示
默认的开始界面  
![image](https://github.com/user-attachments/assets/b767b169-9b6e-41d5-be05-f1093d1f974c)

对话中
![image](https://github.com/user-attachments/assets/e2162c3e-54bc-4100-8f9d-f6d8bedcefa3)



## 安装

1. **克隆仓库**

   ```bash
   git clone https://github.com/luckykevvv/Desktop_Pet_Structure.git

2. **安装依赖项**
      ```bash
      pip install -r requirements.txt
      ```
      此外，请安装ffmpeg  
3. **注册openai-api并写进openai_key.json**
4. **运行main.py**

## 引用
本项目的live-2d渲染以及对live-2d模型的操控部分引用自 https://github.com/Arkueid/live2d-py. 
人物模型来自：https://cubism.live2d.com/sample-data/bin/hiyori_free/hiyori_free_en.zip
## 许可证

本项目使用 GNU 通用公共许可证 v2.0 (GPL-2.0) 进行许可。有关详细信息，请参阅 LICENSE 文件。

## 免责声明

本项目是开源软件，功能和服务仅供学习和参考，不保证适用于特定用途。使用本框架时，请自行承担相关风险。
