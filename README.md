BarlowRL: Barlow Twins for Data-Efficient Reinforcement Learning
=======
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)



**Status**: Archive (code is provided as-is, no updates expected)

This is an implementation of [BarlowRL: Barlow Twins for Data-Efficient Reinforcement Learning](https://arxiv.org/abs/2308.04263). Unlike [CURL](https://arxiv.org/abs/2004.04136), BarlowRL replaces contrastive loss with the Barlow Twins objective. BarlowRLhas 0.378 Mean Human-Normalized Score and 0.296 Median Human-Normalized Score, 0.278 IQM and 0.651 Optimality Gap in Atari 100k Benchmark. This repository is mostly built from the [CURL repository](https://github.com/aravindsrinivas/curl_rainbow/tree/master).



### Dependencies
To install all dependencies, run `bash install.sh`.

### Atari-py
Download roms into atari_py package and prepare roms via pyton script in it. 
```bash
wget http://www.atarimania.com/roms/Roms.rar
unrar x Roms.rar
python -m atari_py.import_roms .
```
### Training

After installing all dependencies run following command for training.
```bash
bash run_train.sh
```
