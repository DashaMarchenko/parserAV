# Parser av.by

It`s program to getting information from the web-site [av.by](https://av.by/)

---
##Quick start

1. Clon [repository](https://github.com/DashaMarchenko/parserAV): 
```
git clone https://github.com/DashaMarchenko/parserAV
```

2. Creating a [virtual environment](https://docs.python.org/3/library/venv.html) for windows
```
python -m virtualenv venv
cd venv/Scripts
activate.bat
```

3. Installing libraries and moduls
```
pip install -r requirements.txt
```

4. Run [parser_av_v2_0](https://github.com/DashaMarchenko/parserAV/blob/main/parser/parser_av_v2_0.py)
```
python parser_av_v2_0
```
---

# Imported Libraries 

There are libraries and frameworks there:

* [aiohttp](https://docs.aiohttp.org/en/stable/)
* [Beautiful Soup 4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [pandas](https://pandas.pydata.org/docs/)
* [requests](https://requests.readthedocs.io/en/latest/)
* [Xlsx Writer](https://xlsxwriter.readthedocs.io/)