- RCV1-v2 dataset are described at [http://www.ai.mit.edu/projects/jmlr/papers/volume5/lewis04a/lyrl2004_rcv1v2_README.htm](RCV1-v2 info)
- Because it is required signing Agreement to obtain data, this repo will contain no data. Personally, it only took me 1 day to be granted access to the data. 
- But the downloaded file are neither in handy format, nor obvious ways to extract desirable info from it, while all I expect is a `csv` files contains something likes `ID, text, labels`. As a result, this script serve that intent.

Basically, it outputs `csv` with command:
```yaml
python main.csv path_to_dir
```

where `path_to_dir` is absolute path to direction contains for file `rcv1.tar.xz`

