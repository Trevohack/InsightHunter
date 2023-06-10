<div align="center">
  <h1>InsightHunter</h1>
  <img src="https://github.com/SpaceShuttleIO/InsightHunter/assets/136177431/e83a5842-8b4f-463a-a2f9-869b5de8c994">
</div>

* Grab social networks which a specific name is related to.
* Pure Python

## Installation

```linux
git clone https://github.com/SpaceShuttleIO/InsightHunter 
cd InsightHunter 
pip install -r requirements.txt
chmod +x main.py 
./main.py 
``` 

## Commands

```python
+---------------+-----------------------------------+
|   Commands    |               Usage               |
+---------------+-----------------------------------+
| setUsername   |      -Config a username to use    |
|   huntAll     |  -Hunt All social media platforms |
|  huntTarget   |     -Hunt a target social media   |
|  listAllMedia |     -list all available media     |
|     run       |          -runs the prgram         |
+---------------+-----------------------------------+

INSIGHTHUNTER > setUsername hacker 
Name => hacker 
INSIGHTHUNTER > listAllMedia
INSIGHTHUNTER > huntAll True 
huntAll => True 
INSIGHTHUNTER > run
-
INSIGHTHUNTER > huntTarget True https://instagram.com/hacker 
INSIGHTHUNTER > run
```
