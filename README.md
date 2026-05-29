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
│   │   ├── core
│   │   │   ├── ble_thread.py
│   │   │   ├── frame_parser.py
│   │   │   ├── hand_kinematics.py
│   │   │   ├── __init__.py
│   │   │   └── simulator.py
│   │   ├── favicon.ico
│   │   ├── logo.png
│   │   ├── main.py
│   │   ├── plans
│   │   │   └── gloves_viewer_architecture.md
│   │   ├── README.md
│   │   ├── requirements.txt
│   │   └── ui
│   │       ├── hand_3d_widget.py
│   │       ├── __init__.py
│   │       ├── main_window.py
│   │       └── widgets.py
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