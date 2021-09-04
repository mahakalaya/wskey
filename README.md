### 使用方法

------------

**完美网络用户** **`ql repo https://github.com/Zy143L/wskey.git "wskey"`**

**国内网络用户 `ql repo https://ghproxy.com/github.com/Zy143L/wskey.git "wskey"`**

**使用建议 修改 定时计划 `15 */6 * * *`  默认为6小时15分执行一次 请按需修改**

----------
### 变量声明

```shell
变量名: JD_WSCK 参数: pin=xxxx;wskey=xxxx;
变量名: QL_PORT 参数: 端口号(int值)
```
--------------
###  更新记录

--------------------

**2021年9月4日 (Ver: 903)**

-------------------------------------------

1. **支持中文用户名的URL编码转换** 
2. **封闭查询参数 改进对相似账号的搜索准确性**
3. **HTTP请求加入异常捕捉, 并增加重试次数**
4. **增加云端变量 从云端读取 UA 防止 UA 失效**
5. **支持版本更新 有版本更新时 会提醒用户更新**
6. **支持自定义端口 参数 `export QL_PORT="端口号" `**
7. **优化逻辑部分 增加重试机制 对 API 接口增加备选方案**
8. **支持实时输出日志 不需要等待执行完成才能看到结果**

-----------------

### 程序特点

--------------

1. **使用云端Sign签名 防止固定Sign导致转换失败的问题**

2. **支持自定义端口的面板 例如`5800  6666  3721` 对应变量 `export QL_PORT="端口号"`**

3. **实时日志效果 无需全部执行完成返回**

4. **HTTP请求冗余机制 错误捕捉机制 最大限度防止出现因为容器没网 403错误 IP拉黑等情况导致脚本错误**

5. **智能化**

   > **自动转换 JD_COOKIE 保证账号不过期**
   >
   > **自动添加 JD_COOKIE 保证账号不漏加**
   >
   > **自动更新 JD_COOKIE 保证账号不重复**

### 程序优点

----------------

​	**底层逻辑**打通**信息屏障**，创建脚本**新生态**。**顶层设计**聚焦用户感受

​	**抽离透传归因分析**作为**抓手**为产品**赋能**，**体验度量**作为**闭环**评判标准。

​	亮点是**载体**，优势是**链路**。思考整个**生命周期**，完善**逻辑**，考虑资源**整合**

-------------

### 干啥用的?

​	 用组合拳**赋能智慧**，打通**生态闭环**，帮助客户延长**有效时间**，强化用户**感知**，打破**边界**，打造**生态化薅豆**

---------------



