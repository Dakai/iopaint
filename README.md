# Installation

Currently IOPaint supports Python 3.10 by 2024.11.11

install python 3.10
`yay -S python310` or `sudo pacman -S python310`

use python310 to create the virtual environment
`python3.10 -m venv venv`

and activate the virtual environment
`. venv/bin/activate`
install IOPaint
`pip3 install iopaint`

- In order to use GPU, install cuda version of pytorch first.
- pip3 install torch==2.1.2 torchvision==0.16.2 --index-url https://download.pytorch.org/whl/cu118
- AMD GPU users, please utilize the following command, only works on linux, as pytorch is not yet supported on Windows with ROCm.
- pip3 install torch==2.1.2 torchvision==0.16.2 --index-url https://download.pytorch.org/whl/rocm5.6
