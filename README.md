# Create Conda Env

```python
conda create --name fhlb-crawler python=3.9 ipykernel
conda activate fhlb-crawler
```

# Install Selenium

```python
pip install selenium
```

# Install Chrome Driver

Check your chrome version and download the corresponding driver at 
https://chromedriver.storage.googleapis.com/index.html

Unzip the driver and put them under a local path, i.e. mine is /Users/zjia/Downloads/chromedriver-105
This path will be used by webdriver.Chrome() to initialize the web browser

# Run script notebook

If Mac sends security warning on this driver, go to System Preferences -> Security & Privacy, allow the driver to Open Anyway.




