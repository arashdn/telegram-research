# Telegram
This repository contains dataset for our research on Telegram instant messaging service

### Published Papers:
1.

	Arash Dargahi Nobari, Negar Reshadatmand and Mahmood Neshati. “Analysis of Telegram, An Instant Messaging Service”,
	In proceedings of The 26th ACM International Conference on Information and Knowledge Management (CIKM ’17), Nov 2017.

You may check the [paper](https://dl.acm.org/citation.cfm?id=3133132) ([PDF](http://facultymembers.sbu.ac.ir/neshati/wp-content/uploads/2017/11/telegram.pdf) and [Poster](http://facultymembers.sbu.ac.ir/neshati/wp-content/uploads/2017/11/poster_CIKM.pdf)) for more information.

## Dataset

The dataset is stored in a MySQL database, which can be downloaded from [dropbox](https://www.dropbox.com/s/szcjfo5k4cxycxz/tg_public.zip) This file includes a dump of database in sql format.

There is five tables in this database:
- `posts`: All of crawled messages.
- `users`: All of users in messages (including members, groups and channels)
- `mentions`: All mention relationships
- `fwds`: All forward relationships
- `adv_tags`: randomly selected post and their spam or ham tag.

## Citation

Please cite the paper, If you used the data in this repository.

```
@inproceedings{DargahiNobari:2017:ATI:3132847.3133132,
 author = {Dargahi Nobari, Arash and Reshadatmand, Negar and Neshati, Mahmood},
 title = {Analysis of Telegram, An Instant Messaging Service},
 booktitle = {Proceedings of the 2017 ACM on Conference on Information and Knowledge Management},
 series = {CIKM '17},
 year = {2017},
 isbn = {978-1-4503-4918-5},
 location = {Singapore, Singapore},
 pages = {2035--2038},
 numpages = {4},
 url = {http://doi.acm.org/10.1145/3132847.3133132},
 doi = {10.1145/3132847.3133132},
 acmid = {3133132},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {classification, instant messaging, pagerank, spam detection, telegram},
} 
```
