# Telegram
This repository contains dataset for our research on Telegram instant messaging service

### Published Papers:
1.

	Arash Dargahi Nobari, Negar Reshadatmand and Mahmood Neshati. “Analysis of Telegram, An Instant Messaging Service”,
	In proceedings of The 26th ACM International Conference on Information and Knowledge Management (CIKM ’17), Nov 2017.

You may check the [paper](to_be_added) ([PDF](to_be_added)) for more information.

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
