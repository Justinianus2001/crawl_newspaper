# Getting Started

This repository used to crawl and search for newspaper info (title, image, link) from website https://vietnamnet.vn use flask, sqlite3 and selenium library in python 3.

First, create a *.env* file in the root directory and fill some global environment variable:

```
DB_FILE=database.db
TIME_SLEEP=1
# WEBSITE=https://vietnamnet.vn/tim-kiem
WEBSITE=https://zingnews.vn/a-tim-kiem.html?date=30daysago
```

Next, run python file *crawl.py*. Take a coffee and do something else when the code crawl the newspaper automatically in your browser.

```
python crawl.py
```

Finally, run file *main.py* and search for the keywork you want to read.

```
python main.py
```

Have a nice day !!!