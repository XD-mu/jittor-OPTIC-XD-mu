| 第二届计图挑战赛开源

# Jittor 热身比赛 baseline
## 简介
本赛道将在数字图片数据集 MNIST 上训练 Conditional GAN（Conditional generative adversarial nets）模型，通过输入一个随机向量 z 和额外的辅助信息 y (如类别标签)，生成特定数字的图像。

## 安装 
本项目可在 1 张 A6000 上运行，训练时间约为 0.2 小时。

#### 运行环境
- ubuntu 20.04 LTS
- python >= 3.7
- jittor >= 1.3.0

#### 安装依赖
执行以下命令安装 python 依赖
```
pip install -r requirements.txt
```

#### 训练模型
训练模型为generator_last.pkl和discriminator_last.pkl

## 训练
训练可运行以下命令：
```
python CGAN.py
```

