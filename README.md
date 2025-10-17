# TeachingWindow 教学工具箱

一个简洁高效的 Windows 教学辅助工具，专为教师课堂管理设计。

## ✨ 主要功能

- **电脑** - 快速访问教室电脑
- **点名** - 随机点名系统（华丽动画）
- **TV/备课/班级** - 一键打开教学网页
- **配置** - 设置各项参数

## 🚀 快速开始

1. 双击运行 `TeachingWindow_Enhanced.exe`
2. 程序显示在屏幕右下角
3. 点击按钮使用各项功能

## ⚙️ 配置方法

### 方法 1：在线获取（推荐）
1. 点击"配置"按钮
2. 点击"📥 获取配置"
3. 点击"💾 保存"

### 方法 2：手动配置
1. 点击"配置"按钮
2. 填写各项设置
3. 点击"💾 保存"

### 方法 3：编辑配置文件
编辑 `config.json` 文件，格式如下：

```json
{
  "manual_ip": "192.168.6.79",
  "inner_url": "192.168.6.79",
  "students": "张三|李四|王五",
  "button3_url": "https://tv.cctv.com/live/cctv13/",
  "button4_url": "https://notion.site/...",
  "button5_url": "https://notion.site/...",
  "roll_duration": "800"
}
```

## 🎯 特色功能

### 随机点名
- 华丽的滚动动画
- 支持自定义学生名单
- 可调节动画速度

### 快捷访问
- 预设常用网页
- 自动添加 http:// 前缀
- 支持内网和外网地址

### 现代界面
- 圆角窗口设计
- 按钮悬停高亮
- 流畅无闪烁

## 📋 系统要求

- Windows 7 及以上
- 无需安装，绿色软件

## 🔧 编译

```bash
g++ TeachingWindow.cpp -o TeachingWindow_Enhanced.exe -std=c++17 -O2 -s -luser32 -lgdi32 -lshell32 -lwininet -lurlmon -mwindows
```

## 📄 许可证

MIT License

---

详细使用说明请查看 `使用说明.txt`
