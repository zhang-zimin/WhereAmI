# WhereAmI CLI

这是一个简单的命令行工具，用于获取当前用户的经纬度位置信息。

## 安装

### 从PyPI安装
```bash
pip install whereami-cli
```

### 从源码安装
1. 确保您已安装Python 3.6或更高版本
2. 克隆仓库：
```bash
git clone https://github.com/zhangzimin/whereami.git
cd whereami
```
3. 安装依赖：
```bash
pip install -r requirements.txt
```

## 使用方法

安装后，您可以直接使用命令：
```bash
whereami
```

或者运行Python脚本：
```bash
python -m whereami_cli
```

## 项目结构
```
whereami/
├── whereami_cli/           # 主包目录
│   ├── __init__.py        # 包初始化文件
│   └── location.py        # 位置获取核心代码
├── setup.py               # 包安装配置
├── pyproject.toml         # 构建系统配置
├── requirements.txt       # 项目依赖
├── README.md             # 项目文档
└── LICENSE               # MIT许可证
```

## 输出示例

```
您当前的位置是：
纬度: 39.9042
经度: 116.4074
地址: 北京市, 中国
```

## 注意事项

- 需要网络连接
- 位置信息基于IP地址，可能不是非常精确
- 如果无法获取位置信息，请检查网络连接 