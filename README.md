# connect

```python
from http.server import HTTPServer, SimpleHTTPRequestHandler
import os

server_address = ('192.168.0.110', 3066)    
httpd = HTTPServer(server_address, SimpleHTTPRequestHandler)
print('Running server...')
httpd.serve_forever()

```
