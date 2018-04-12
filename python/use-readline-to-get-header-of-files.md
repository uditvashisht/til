# Use readline() to get header of the files

If you are reading a txt, csv or anyother file, using readline() can help you make the first line as header.\
Usage:
```
with open("somfile.txt", "r") as f:
	headers = f.readline().split()

	for line in f:
		data = line.split()
```