# image--retrieval-by-python
a good image- retrieval code use for search  same or similar image 
python searchEngine.py -c colorindex.csv -s structureindex.csv -r c:\dataset\dizhi  -q query/1.jpg 
python index.py --dataset c:\dataset\dizhi  --colorindex colorindex.csv --structure structureindex.csv



首先运行(first step)

python index.py --dataset c:\dataset\dizhi  --colorindex colorindex.csv --structure structureindex.csv

再运行(last step)

python searchEngine.py -c colorindex.csv -s structureindex.csv -r dataset -q query/1.jpg 
