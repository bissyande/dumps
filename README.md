# dumps

This dump was obtained with: couchdb-backup.sh -b -H serval01 -d multi_class -f multi_class.json

Then, we split multi_class.json into segments of 99Mb.

So, you need to merge them back once with:
cat segmenta{a..z} segmentb{a..b}  > multi_class.json
