# Backup of my contributions on Github

To update the backup, run the following:

```shell
pip install requests

TOKEN=github-token python ../github-contributions/main.py -o `pwd` -c commits.txt -i issues.txt -s 2022-07-22 conradkleinespel
```

Then update the date in the above `-s` option to prepare for the next update and commit the changes.
