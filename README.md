# Codet5-jb_task

Since the model weighs too much for the git, I attach a link to the disk where its weights are stored: https://disk.yandex.ru/d/cmwsNsThcpF5YA


**Tools and results.**

I have compiled a dataset of **java** methods only, it looks like this: two lines of code before the method ending with a dot, and in the response the method.

Because I have few technical capabilities, I chose a small caddy t5 model and trained it on 6 epochs.
As a result, I received the following improved estimates:
The average Levenshtein distance is 0.93 -> 0.35
Average bleu 0 -> 0.22


**How do I build the code?**

We launch jupiter, download the model from disk, configure the path to it, the dataset is already in the repository, you do not need to configure the path to it.
