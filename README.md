# RobotViewer
IMU、Gloves、MoCap Suit Viewer


## 1. clone工程
```python
# 1. clone工程到本地
git clone --recurse-submodules https://github.com/RichExplor/RobotViewer.git

# 2. 更新子模块
git submodule update --remote
```

## 2. 工程目录
```python
RobotViewer
├── libs
│   ├── GlovesViewer
│   │   └── README.md
│   ├── IMUViewer
│   │   ├── core
│   │   │   ├── algorithm.py
│   │   │   └── serial_thread.py
│   │   ├── favicon.ico
│   │   ├── logo.png
│   │   ├── main.py
│   │   ├── README.md
│   │   ├── requirements.txt
│   │   └── ui
│   │       ├── main_window.py
│   │       └── widgets.py
│   └── MoCapSuitViewer
│       └── README.md
└── README.md

```