# Arxiv slack RSS feed

```
$ python main.py [arxiv rss url] [slack webhook url]
```

Edit crontab

```
crontab -e
```

Add cront job

```
0 * * * * * python3 /home/jjy0923/git/arXiv-slack-rss/main.py [arxiv rss url] [slack webhook url]
```


refer https://crontab.guru/examples.html


