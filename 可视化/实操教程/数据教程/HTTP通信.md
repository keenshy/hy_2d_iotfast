# HTTP通信

### 创建http通信方式
<font style="color:rgb(36, 41, 47);">点击画布显示通信属性列，点击“添加”按钮添加通信数据。</font>

![1724752780425-609d1d0a-7dee-4424-b246-f1868ed7ff76.png](./img/Unq6ObX6ksGq88QX/1724752780425-609d1d0a-7dee-4424-b246-f1868ed7ff76-538745.png)

以下是配置界面

![1724753100465-d61a0e99-ea76-40ea-b70a-1a2f9bc383f2.png](./img/Unq6ObX6ksGq88QX/1724753100465-d61a0e99-ea76-40ea-b70a-1a2f9bc383f2-922674.png)

**<font style="color:rgb(36, 41, 47);">名称</font>**<font style="color:rgb(36, 41, 47);">：即当前连接名称，用户自定义。</font>

**<font style="color:rgb(36, 41, 47);">通信方式</font>**<font style="color:rgb(36, 41, 47);">：目前有 HTTP、MQTT、WebSocket、系统平台接口四种方式，当前选择 HTTP。</font>

**<font style="color:rgb(36, 41, 47);">URL</font>**<font style="color:rgb(36, 41, 47);">：即 HTTP 接口地址。</font>

**<font style="color:rgb(36, 41, 47);">请求方式</font>**<font style="color:rgb(36, 41, 47);">：有 GET 和 POST 两种方式，默认 GET。</font>

**<font style="color:rgb(36, 41, 47);">定时器</font>**<font style="color:rgb(36, 41, 47);">：开启后数据可按照设置的时间间隔传递。</font>

**<font style="color:rgb(36, 41, 47);">参数值</font>**<font style="color:rgb(36, 41, 47);">：用于传递给接口的参数，用户可根据需要设置，支持通过自定义脚本获取。</font>

**<font style="color:rgb(36, 41, 47);">请求头</font>**<font style="color:rgb(36, 41, 47);">：设置请求时的头部信息，用于传递附加的元数据，支持通过自定义脚本获取。</font>

**<font style="color:rgb(36, 41, 47);">返回值</font>**<font style="color:rgb(36, 41, 47);">：点击【测试连接】按钮后返回的接口数据，显示接口响应的内容。</font>

**<font style="color:rgb(36, 41, 47);">过滤器</font>**<font style="color:rgb(36, 41, 47);">：用户可根据需求对返回结果进行整理和过滤输出，提取所需信息。</font>

**<font style="color:rgb(36, 41, 47);">处理结果</font>**<font style="color:rgb(36, 41, 47);">：即最终处理后的结果，展示经过过滤和整理后的数据。</font>

### 举例说明
| 基础配置 | 参数值 | 请求头 | 返回值 | 过滤器 | 处理结果 |
| --- | --- | --- | --- | --- | --- |
| ![1724809022739-16f7c493-aa8b-4e00-b74b-c851050d2716.png](./img/Unq6ObX6ksGq88QX/1724809022739-16f7c493-aa8b-4e00-b74b-c851050d2716-685453.png) | ![1738916962575-5986361a-3d49-4f81-96a3-c194b4203a03.png](./img/Unq6ObX6ksGq88QX/1738916962575-5986361a-3d49-4f81-96a3-c194b4203a03-340581.png) | ![1738916989872-e2c45ebb-3209-4863-bef6-09dee1e1344d.png](./img/Unq6ObX6ksGq88QX/1738916989872-e2c45ebb-3209-4863-bef6-09dee1e1344d-706049.png)<br/>获取token例子如下：<br/>![1738922271699-73945ada-a7f9-4c67-8500-2d860e42400f.png](./img/Unq6ObX6ksGq88QX/1738922271699-73945ada-a7f9-4c67-8500-2d860e42400f-303524.png) | ![1724809043568-ed07a0d2-a1b3-4a32-ac20-2fa46e00eaa2.png](./img/Unq6ObX6ksGq88QX/1724809043568-ed07a0d2-a1b3-4a32-ac20-2fa46e00eaa2-165776.png) | ![1724809065446-11bbf4ad-35f8-4761-8dc9-b6892716b978.png](./img/Unq6ObX6ksGq88QX/1724809065446-11bbf4ad-35f8-4761-8dc9-b6892716b978-802081.png) | ![1724809075004-3504d343-f187-4512-a60e-1035e113361c.png](./img/Unq6ObX6ksGq88QX/1724809075004-3504d343-f187-4512-a60e-1035e113361c-621957.png) |




> 更新: 2025-02-07 17:57:53  
> 原文: <https://www.yuque.com/iot-fast/ksh/ga24p2zw3gm6zg55>