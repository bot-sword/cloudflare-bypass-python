# cloudflare-bypass-python

20/09/2020
### environment
python 3.8<br>
js2py<br>

### success rate
63%

### workflow
1. call first challenge url and get javascript code
2. parse and run first challenge code, get **_cf_chl_ctx**
3. send encrypted context data and fetch second challenge code
4. get answers and cookies
5. post to real url with fetched answers and cookies
6. get real contents of site url
