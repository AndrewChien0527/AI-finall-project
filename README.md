# AI-fianl-project

### Overview
Datas augumented by match finding are stored match finding, and the approches for data augmenting.

#### match finding
The code of generating augmented data and the output aurmented data.

#### experiment data
The data of critical experiment I've done.

#### edit python files
The python file I've edit to do experiments.


### Code Usage
#### Train a model
```=bash
./script.sh
```

#### Generate predictions
```=bash
python generator.py {model_path}
```

#### Run evaluation metrics
- Both ground truth and prediction files are default in the `data` folder
```=bash
python evaluation.py
```
