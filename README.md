# Fact-API


[Api Url](https://api.pixiej.xyz)

<h4>Ratelimit: 100 Requests Per Minute</h4>

# Imports

```py
import aiohttp
import requests
```
# simple example

```py
import requests

url = requests.get("The URL xd")
result = url.json()
a = result['question']
b = result['datetime']
c = result['joke']
d = result['fact']
data_set = 'question: ' + a, 'datetime: ' + b, 'joke: '+ c, 'fact: ' + d
print(data_set)
```

# there is 70% chance that I am not going to update this repo XD
