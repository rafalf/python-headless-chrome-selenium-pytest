## Python 3.6 docker image with chrome browser and chrome driver 
* ready to go with the following settings

```
  print("Run test in headless mode: --headless")
  chrome_options.add_argument("--headless")
  chrome_options.add_argument("--disable-gpu")
  chrome_options.add_argument("--no-sandbox")
  d = webdriver.Chrome(chrome_options=chrome_options)
```

### have installed the following test packages:
* pytest
* selenium
* requests
* pytest-rerunfailures
* pytest-xdist
* pyyaml
