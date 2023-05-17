# aura-model
## Usage

#### 1. Clone the repository
```bash
$ git clone https://github.com/awesome-davian/Text2Colors.git
$ cd Text2Colors/
```

#### 2. Dataset & Libraries install
```bash
$ bash install_pre.sh
```

#### 3. Train 
##### (i) Training Text-to-Palette Generation Networks (TPN) with PAT data

```bash
$ python main.py --mode train_TPN
```

##### (ii) Training Palette-Based Colorization Networks (PCN) with CUB-200-2011* data

```bash
$ python main.py --mode train_PCN
```
*Wah, Catherine, et al. "The caltech-ucsd birds-200-2011 dataset." (2011).

#### 4. Test
##### (i) Testing TPN

```bash
$ python main.py --mode test_TPN
```

##### (ii) Testing Text2Colors

```bash
$ python main.py --mode test_text2colors
```
