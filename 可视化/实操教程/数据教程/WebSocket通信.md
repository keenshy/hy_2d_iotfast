# WebSocket通信

### 创建websocket通信方式
<font style="color:rgb(36, 41, 47);">点击画布显示通信属性列，点击“添加”按钮添加通信数据。</font>

![1724752780425-609d1d0a-7dee-4424-b246-f1868ed7ff76.png](./img/Y3R8kTwvLe5xP7rV/1724752780425-609d1d0a-7dee-4424-b246-f1868ed7ff76-998797.png)

以下是配置界面

![1726653932275-ea67f4c0-e256-4629-9c05-82415b72208b.png](./img/Y3R8kTwvLe5xP7rV/1726653932275-ea67f4c0-e256-4629-9c05-82415b72208b-561064.png)

**<font style="color:rgb(36, 41, 47);">名称</font>**<font style="color:rgb(36, 41, 47);">：即当前连接名称，用户自定义。</font>

**<font style="color:rgb(36, 41, 47);">通信方式</font>**<font style="color:rgb(36, 41, 47);">：目前有 HTTP、MQTT、WebSocket、系统平台接口四种方式，当前选择WebSocket。</font>

**<font style="color:rgb(36, 41, 47);">URL</font>**<font style="color:rgb(36, 41, 47);">：即 WebSocket 接口地址，必须以 </font>`<font style="color:rgb(36, 41, 47);">ws://</font>`<font style="color:rgb(36, 41, 47);"> 或 </font>`<font style="color:rgb(36, 41, 47);">wss://</font>`<font style="color:rgb(36, 41, 47);"> 开头，否则无法保存。</font>

**<font style="color:rgb(36, 41, 47);">定时器</font>**<font style="color:rgb(36, 41, 47);">：开启后按设定的时间间隔自动发起请求。</font>

**<font style="color:rgb(36, 41, 47);">返回值</font>**<font style="color:rgb(36, 41, 47);">：点击【测试连接】按钮后返回的接口数据，显示接口响应的内容。</font>

**<font style="color:rgb(36, 41, 47);">过滤器</font>**<font style="color:rgb(36, 41, 47);">：用户可根据需求对返回结果进行整理和过滤输出，提取所需信息。</font>

**<font style="color:rgb(36, 41, 47);">处理结果</font>**<font style="color:rgb(36, 41, 47);">：即最终处理后的结果，展示经过过滤和整理后的数据。</font>

### 举例说明
| 基础配置 | 参数值 | 返回值 | 过滤器 | 处理结果 |
| --- | --- | --- | --- | --- |
| ![1726654052919-1db20330-5b98-406b-bf13-3e2a7533af64.png](./img/Y3R8kTwvLe5xP7rV/1726654052919-1db20330-5b98-406b-bf13-3e2a7533af64-982681.png) | 无 | ![1726654077278-503155e2-35be-4601-b561-836be050068a.png](./img/Y3R8kTwvLe5xP7rV/1726654077278-503155e2-35be-4601-b561-836be050068a-321196.png) | ![1726654112693-8ca8680d-8ca1-484d-9fa2-efed826e838a.png](./img/Y3R8kTwvLe5xP7rV/1726654112693-8ca8680d-8ca1-484d-9fa2-efed826e838a-728712.png) | ![1726654120964-483c2ddc-7c63-464a-95e8-40347a119376.png](./img/Y3R8kTwvLe5xP7rV/1726654120964-483c2ddc-7c63-464a-95e8-40347a119376-118754.png) |




> 更新: 2024-09-18 18:08:48  
> 原文: <https://www.yuque.com/iot-fast/ksh/euo5e0exhbqrntk9>