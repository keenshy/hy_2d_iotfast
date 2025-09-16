# MQTT通信

### 创建mqtt通信方式
<font style="color:rgb(36, 41, 47);">点击画布显示通信属性列，点击“添加”按钮添加通信数据。</font>

![1724752780425-609d1d0a-7dee-4424-b246-f1868ed7ff76.png](./img/Y-vJKSQ81ZCTkftW/1724752780425-609d1d0a-7dee-4424-b246-f1868ed7ff76-862853.png)

以下是配置界面

![1724809401570-8d89a74d-611f-41c0-a4be-21113b3f1d09.png](./img/Y-vJKSQ81ZCTkftW/1724809401570-8d89a74d-611f-41c0-a4be-21113b3f1d09-388929.png)

**<font style="color:rgb(36, 41, 47);">名称</font>**<font style="color:rgb(36, 41, 47);">：即当前连接名称，用户自定义。</font>

**<font style="color:rgb(36, 41, 47);">通信方式</font>**<font style="color:rgb(36, 41, 47);">：目前有 HTTP、MQTT、WebSocket、系统平台接口四种方式，当前选择mqtt。</font>

**<font style="color:rgb(36, 41, 47);">URL</font>**<font style="color:rgb(36, 41, 47);">：即 MQTT 接口地址，必须以 </font>`<font style="color:rgb(36, 41, 47);">ws://</font>`<font style="color:rgb(36, 41, 47);"> 或 </font>`<font style="color:rgb(36, 41, 47);">wss://</font>`<font style="color:rgb(36, 41, 47);"> 开头，否则无法保存。</font>

**<font style="color:rgb(36, 41, 47);">客户端 ID</font>**<font style="color:rgb(36, 41, 47);">：用于唯一标识客户端的标识符。</font>

**<font style="color:rgb(36, 41, 47);">用户名</font>**<font style="color:rgb(36, 41, 47);">：用于身份验证的用户名。</font>

**<font style="color:rgb(36, 41, 47);">密码</font>**<font style="color:rgb(36, 41, 47);">：用于身份验证的密码。</font>

**<font style="color:rgb(36, 41, 47);">主题</font>**<font style="color:rgb(36, 41, 47);">：用于订阅或发布消息的主题。消息将根据指定的主题进行分类和处理。</font>

**<font style="color:rgb(36, 41, 47);">定时器</font>**<font style="color:rgb(36, 41, 47);">：开启后按设定的时间间隔自动发起请求。与 HTTP 请求不同，MQTT 的定时器在请求的时间内如果有数据发送过来才会接收到。这意味着定时器控制了请求频率，但只有在有新数据时才会触发接收。</font>

**<font style="color:rgb(36, 41, 47);">参数值</font>**<font style="color:rgb(36, 41, 47);">：用于传递给接口的参数，用户可根据需要设置。</font>

**<font style="color:rgb(36, 41, 47);">返回值</font>**<font style="color:rgb(36, 41, 47);">：点击【测试连接】按钮后返回的接口数据，显示接口响应的内容。</font>

**<font style="color:rgb(36, 41, 47);">过滤器</font>**<font style="color:rgb(36, 41, 47);">：用户可根据需求对返回结果进行整理和过滤输出，提取所需信息。</font>

**<font style="color:rgb(36, 41, 47);">处理结果</font>**<font style="color:rgb(36, 41, 47);">：即最终处理后的结果，展示经过过滤和整理后的数据。</font>

### 举例说明
| 基础配置 | 参数值 | 返回值（无数据发送过来） | 返回值（有数据发送过来） | 过滤器 | 处理结果 |
| --- | --- | --- | --- | --- | --- |
| ![1724810406091-9b101374-e6cb-4c13-928d-df44aa7876d6.png](./img/Y-vJKSQ81ZCTkftW/1724810406091-9b101374-e6cb-4c13-928d-df44aa7876d6-544608.png) | 无 | ![1724810431722-bedf0fbb-472a-489e-b38e-81ccd0baa951.png](./img/Y-vJKSQ81ZCTkftW/1724810431722-bedf0fbb-472a-489e-b38e-81ccd0baa951-306077.png) | ![1724811321927-92323088-bdc9-4732-a34d-d75d5af357af.png](./img/Y-vJKSQ81ZCTkftW/1724811321927-92323088-bdc9-4732-a34d-d75d5af357af-600723.png) | ![1724811525281-22344abb-f02f-4705-9c42-700b124cbb82.png](./img/Y-vJKSQ81ZCTkftW/1724811525281-22344abb-f02f-4705-9c42-700b124cbb82-887348.png) | ![1724811536659-15ac4970-1131-467b-ae79-4d9a667dd647.png](./img/Y-vJKSQ81ZCTkftW/1724811536659-15ac4970-1131-467b-ae79-4d9a667dd647-328929.png) |




> 更新: 2024-09-18 18:09:14  
> 原文: <https://www.yuque.com/iot-fast/ksh/tma7kaws5nzhrfqd>