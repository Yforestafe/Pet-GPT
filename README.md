# Pet-GPT

![Language](https://img.shields.io/badge/language-python-brightgreen)  

Pet-GPT 是一个使用 PyQt 编写的桌面宠物程序，支持调用 OpenAI 的 GPT 进行上下文对话。

<img src="https://user-images.githubusercontent.com/46673445/232178202-3e4a7558-be9a-4708-b6e4-a8baff0080af.png" alt="dog" width="200"/>

bilibili连接


## 特点

- 一个简单的桌面小宠物，支持自定义图像和昵称
- 支持自由移动和主动发问等多种设置
- 使用 OpenAI GPT 进行上下文的单词对话
- 支持聊天界面的自定义插件热更新

## 安装与运行

1. 安装 Python 3.9 及以上版本和 PyQt5。

2. 在 OpenAI 上注册账号，并获取 API 密钥。

   在浏览器中打开 https://beta.openai.com/signup/，填写相关信息注册 OpenAI 账号，并获取 API 密钥。

3. 克隆或下载本项目。

   - 点击绿色的“Code”按钮，选择“Download ZIP”
   - 使用git命令`git clone https://github.com/Hanzoe/petgpt.git`下载。

4. 将`config.ini`修改为`private_config.ini` ，并且修改参数"OPENAI_API_KEY"、"LLM_MODEL"。

5. 安装依赖包

   ```
   conda create --name petgpt python=3.9
   conda activate petgpt
   pip install -r requirements.txt
   ```

   

6. 运行 `main.py`。

   ```
   python main.py
   ```

## 使用说明

- 无互动状态下，宠物自由移动、对话

  ![image](https://user-images.githubusercontent.com/46673445/232179367-46acb6c8-4eaf-45e5-86a2-fd92c1ef2fd3.png)

- 右键支持功能：打开聊天框、修改昵称、修改图像、设置移动以及对话

  ![image](https://user-images.githubusercontent.com/46673445/232179374-458f6fd5-85d3-41ee-889e-28b98174b240.png)

- 互动状态下，可实现基于GPT的聊天以及其他功能

  ![image](https://user-images.githubusercontent.com/46673445/232179379-ce3bc253-aae8-45f0-8312-15518c9cff1c.png)

## 完成清单

- [x] 通过设置修改宠物的移动、和主动发问
- [x] 完成无记忆的一次性对话
- [x] 使用进程解决访问和窗口的阻塞问题
- [ ] 保存对话记录，实现联系上下文进行对话
- [ ] 优化界面
- [ ] 聊天界面的热插件更新
- [ ] 增加一些互动效果
- [ ] 聊天界面的语音输入输出
- [ ] 聊天界面的图片生成
- [ ] 聊天界面的角色扮演

## 贡献者


## 许可证

本项目采用 [MIT](https://opensource.org/licenses/MIT) 许可证。

## 联系方式

一个人也许走的很快，但是一群人可以走得更远！

QQ:2500066889