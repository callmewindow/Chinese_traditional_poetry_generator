# Chinese_traditional_portry_generator

基于RNN技术的中国古诗词生成器

## 初始环境

python：3.6

tensorflow：1.2.0

## 初始使用方法

### 模型训练

```
python generator.py --mode train
```

### 古诗词生成

#### 默认模式

```
python generator.py 或者 python generator.py --mode sample
```

#### 藏头模式

```
python generator.py --mode sample --head 明月别枝惊鹊
```

## 初始帮助

```
python generator.py --help 
```

```

  usage: generator.py [-h] [--mode MODE] [--head HEAD]

  optional arguments:
    -h, --help   show this help message and exit
    --mode MODE  usage: train or sample, sample is default
    --head HEAD  生成藏头诗
    
```
