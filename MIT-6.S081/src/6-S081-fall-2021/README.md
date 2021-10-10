**备份[6-S081-fall-2021](https://pdos.csail.mit.edu/6.S081/2021/lec/)**

```sh
$ wget -r -np -nH --cut-dirs=3 https://pdos.csail.mit.edu/6.S081/2021/lec/
```

Explanation:

- It will download all files and subfolders in *ddd* directory
- `-r` : recursively
- `-np` : not going to upper directories, like *ccc/…*
- `-nH` : not saving files to hostname folder
- `--cut-dirs=3` : but saving it to *ddd* by omitting first 3 folders *aaa*, *bbb*, *ccc*
- `-R index.html` : excluding *index.html* files

