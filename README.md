```
apt-get install libgl1

python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install pip=24.0

source $HOME/miniforge/bin/activate
conda create -n cq
conda activate cq
mamba install cadquery # also vtk==9.2.2?

pip install -r requirements

source $HOME/miniforge/bin/activate
conda activate cq
JUPYTER_TOKEN="949832720bb42ca1a43e19af4a43a8f5b3eeb28abddfc502" jupyter lab
```

Server URL: http://localhost:8888/lab?token=949832720bb42ca1a43e19af4a43a8f5b3eeb28abddfc502
