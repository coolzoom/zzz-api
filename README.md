# 优质稳定的OpenAI的API接口-For企业和开发者

#### 介绍
为企业和开发者提供优质稳定的OpenAI相关的API调用接口。    
智增增-大模型的API接口服务商，提供ChatGPT的API调用，支持openai的API接口，支持：gpt-4-1106，gpt-4-vision, gpt-4，gpt-3.5。          
要买openai的账号？   
要科学上网？  
要美元的银行卡？  
通通不用的，直接调用就行，简单粗暴，关键稳定好用！！  
openai的国内代理，国内接口请求转发，api proxy        

- **项目主要优势**  
  * 不限制使用，可以用微信充值，没有封号风险。
  * 不用买openai的账号，不用美元的银行卡。 
  * 无需代理即可访问，没有任何的阻拦。  
  * 强大的接口能力，支持openai所有接口和模型（包括11.7号最新更新的模型）：支持gpt-4-1106，gpt-4-vision，GPT-3.5，GPT-4，Embedding，Whisper，TTS, Fine-tuning，DALL-E-3, Image等    
  * 最广泛的插件支持能力：Sidebar，沉浸式翻译，ChatHub，Chatbox，CodeGPT，ChatGPT-Next-Web等各类大模型插件。如果不想写代码，仅仅想在插件中使用，也可以使用我们这个[插件工具](https://github.com/xing61/chatgpt-plugin-key)      
  * 兼容OpenAI接口格式，可以做到平替。   
  * 支持对Embeddings支持，可以用接口运行Langchain、向量库、AutoGPT等应用。  
  * 支持对stream模式的支持，可以支持原生的各种应用   
  * 支持文字生成图片，支持最新的DALL-E-3   
  * 支持官方的Whisper模型，支持transcriptions和translations，可以做语音识别和翻译   
  * 支持fine-tune（微调），可以使用自己的数据来微调GPT的模型，详见示例
  * 支持函数调用(function_call)，详见示例
  * 支持官方的tts，支持tts-1模型和tts-1-hd模型，可以做语音合成，详见示例 
  * 更多特性支持，敬请期待。也可直接向我们提交需求哦  

- **项目地址**   
1、项目官方网址：http://gpt.zhizengzeng.com/#/login   
   智增增-大模型的API接口服务商   
   开发者单独的Secret Key、调用记录、微调模型、余额查询、示例代码等可以从管理后台中获取。        
2、微信交流群（如果你也对本项目感兴趣，欢迎加入群聊参与讨论交流）：    
![输入图片说明](https://flag.smarttrot.com/api_qunliao1.png)   
        
 
- **注意事项**   
1、以下所有接口的base_url: `https://flag.smarttrot.com/` （支持https）<br>
2、API通过HTTP请求调用。每次请求，需要在HTTP头中携带用户的API_KEY，用于认证。 开发者单独的API_KEY，请从智增增管理后台获得。 
   请求头形如：  
   ```
   Content-Type: application/json
   Authorization: Bearer $API_KEY
   ```
- **典型用法**    
1、设置OPENAI_API_KEY环境变量为：智增增后台获取的API_KEY，替换官方的API_KEY: sk-****** <br>
2、设置OPENAI_API_BASE_URL环境变量为：`https://flag.smarttrot.com/v1/`,  替换官方的域名:  `https://api.openai.com/v1/` <br>
![微信截图_20231109105329](https://github.com/xing61/xiaoyi-robot/assets/38256442/bfb8cbb5-c600-49eb-92eb-96c014ec3e37)


## 更详细的API说明 ## 
1、[openai的API说明](https://github.com/xing61/xiaoyi-robot/blob/main/openai%E6%8E%A5%E5%8F%A3%E8%AF%B4%E6%98%8E.md)<br>

2、[智增增API接口说明](https://github.com/xing61/xiaoyi-robot/blob/main/%E6%99%BA%E5%A2%9E%E5%A2%9EAPI%E6%8E%A5%E5%8F%A3.md)<br>

