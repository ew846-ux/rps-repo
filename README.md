# rps-repo
Rock Paper Scissors Project

## Setup
1. Clone the repo from GitHub
2. Access the repo within the command line
```
cd ~/Desktop/rps-repo
``` 
3. Create and access an Anaconda virtual environment to access the game:
```
conda create -n rps-env python=3.11
conda activate rps-env
```
4. Install package dependencies:
```
pip install -r requirements.txt
```

## Running the game
1. Run the Rock, Paper, Scissors game from the command line:
```
python -m app.rps
# or
python app/rps.py
```
## Testing
```
pytest app/rps_test.py
```


