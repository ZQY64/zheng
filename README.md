# Weather-Web 天气预报单页应用
纯前端天气预报网页，无需后端、无需申请 API Key，打开即可使用，玻璃拟态现代化 UI，全端响应式适配 PC/平板/手机。

## ✨ 功能特性
1. 城市中英文搜索，自动解析经纬度获取气象数据
2. 浏览器原生定位，一键查看本地实时天气
3. 实时天气信息：当前温度、天气图标、更新时间、经纬度
4. 气象指标：体感温度、风速、降水概率、当日最高/最低温
5. 未来 5 天逐日天气预报（日期、天气图标、温区）
6. LocalStorage 持久缓存上次查询城市，打开自动加载
7. 加载状态、网络/定位/输入错误友好提示
8. 玻璃拟态毛玻璃风格，响应式布局，适配所有设备

## 🌐 免费第三方接口（无密钥、免费调用）
1. Open-Meteo Geocoding API：城市名称 ↔ 经纬度转换
2. Open-Meteo Forecast API：实时天气 + 5 日预报数据
3. BigDataCloud Reverse Geocode API：经纬度解析中文城市名

## 📦 运行方式
### 方式1：本地开发（推荐，解决跨域 CORS）
1. VS Code 安装 Live Server 插件
2. 打开项目文件夹，右键 `index.html` → Open with Live Server
3. 访问本地地址即可完整使用（定位功能正常）

### 方式2：GitHub Pages 在线预览
1. 将项目上传至 GitHub
2. 仓库 Settings → Pages 开启静态页面服务
3. 在线地址可正常使用定位、全部接口

### ⚠️ 注意事项
1. 直接双击 `file://` 打开本地文件会触发跨域拦截，接口无法请求
2. 浏览器定位仅支持 HTTPS / Live Server 本地服务环境
3. Open-Meteo 免费接口存在访问频率限制，请勿高频重复请求

## 🧱 技术栈
- HTML5 语义化页面结构
- CSS3：CSS变量、Grid、Flex、backdrop-filter 玻璃拟态、媒体查询响应式
- JavaScript ES6+：async/await、Fetch API、LocalStorage、Geolocation API
- 原生浏览器 API，无 Vue/React 等框架依赖，零第三方库

## 📁 项目结构
