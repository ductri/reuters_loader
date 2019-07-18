- RCV1-v2 dataset are described at [RCV1-v2 info](http://www.ai.mit.edu/projects/jmlr/papers/volume5/lewis04a/lyrl2004_rcv1v2_README.htm)
- Because it is required signing __Agreement__ to obtain data, this repo contains no data. Personally, it only took me 1 day to be granted access the data. 
- Unfortunately, the downloaded file are neither in handy format, nor obvious ways to extract desirable info from it, while all I expect is a `csv` files contains something likes `ID, text, labels`. As a result, this script serves that intent.

Basically, it would output an `csv` file after running command:
```yaml
python main.py path_to_dir
```

where `path_to_dir` is absolute path to direction contains for file `rcv1.tar.xz`

All requirements are:
- Python3
- Pandas
