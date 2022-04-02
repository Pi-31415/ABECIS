# ABECIS
A Free and Open-source Automated Building Exterior Crack Inspection Software for Construction and Facility Managers

## Installation

> For everything below, if 'python3' does not work, replace 'python3' with 'python'

1. Clone this repository using

`git clone 'https://github.com/Pi-31415/ABECIS'`

and change working directory with

`cd ABECIS`

2. Download Python 3 at [Python Website](https://www.python.org/downloads/), and install. Also, download [Git](https://git-scm.com/) if you do not have it.

3. Then, upgrade pip using

`python3 -m pip install --upgrade pip `

4. Install torch using

`pip3 install torch torchvision torchaudio`

5. Run the python script named **setup.py** using the following command, to set up the dependencies.

`python3 ./setup.py`

Here, on Windows, installation of detectron 2 might fail. In such case, install it from a local clone using

`
git clone https://github.com/facebookresearch/detectron2.git
python -m pip install -e detectron2
 `

6. If everything ran smoothly, run ABECIS by

`python3 ./abecis.py`

> Note: When running for the first time, it will automatically download the pre-trained model, and will take some time.
