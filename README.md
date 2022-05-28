- RCV1-v2 dataset is described at [RCV1-v2 info](http://www.ai.mit.edu/projects/jmlr/papers/volume5/lewis04a/lyrl2004_rcv1v2_README.htm)
- Because it is required signing __Agreement__ to obtain data, this repo contains no data. Personally, it only took me 1 day to be granted access to the data. 
- Unfortunately, the downloaded file is neither in handy format, nor there are obvious ways to extract desirable info from it, while all I expect is a `csv` file contains something likes `ID, text, labels`. As a result, this script serves that intent.

Basically, just run:
```yaml
python main.py path_to_dir
```

where `path_to_dir` is the absolute path to the directory containing file `rcv1.tar.xz`. It would output 2 `csv` files at `path_to_dir`:
- `rcv1_v2.csv`: your main interested data
- `rcv1_v2_topics_desc.csv`: description about topics

The content in column `text` are raw text in xml format. It can be parsed easily with `xml.etree.ElementTree.XML(text)`
