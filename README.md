N-CURL Atari-100k
=======
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)



**Status**: Archive (code is provided as-is, no updates expected)

This is an implementation of N-CURL: Non-Contrastive Unsupervised Representations for Reinforcement Learning coupled with the Data Efficient Rainbow method for Atari games. The code by default uses the 100k timesteps benchmark and has not been tested for any other setting. Unlike [CURL](https://arxiv.org/abs/2004.04136), N-CURL replaces contrastive loss with Barlow Twins objective. N-CURL has 0.3721 Mean Human-Normalized Score and 0.2859 Median Human-Normalized Score. 

The code by default uses the 100k timesteps benchmark and has not been
tested for any other setting.

Run the following command (or `bash run_curl.sh`) with the game as an argument:

To install all dependencies, run `bash install.sh`.

## Atari-py
Download roms into atari_py package and prepare roms via pyton script in it.
```bash
wget http://www.atarimania.com/roms/Roms.rar
unrar x Roms.rar
python -m atari_py.import_roms .
```
