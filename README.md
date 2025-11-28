# robodriver-robot-realman-follower-dora
## Get Start
Clone the repository
```
git clone --recurse-submodules https://github.com/BAAI-EI-DATA/robodriver-robot-realman-follower-dora.git && cd robodriver-robot-realman-follower-dora
```
Install uv:
```
pip install uv
```
Create and activate a virtual environment for realman dora node:
```
uv venv .venv -p 3.9
source .venv/bin/activate
```
Install dependencies
```
uv pip install -e .
```
Install the project to Robodriver
```
cd /path/to/your/RoboDriver
source .venv/bin/activate
cd robodriver-robot-realman-follower-dora
uv pip install -e .
```
