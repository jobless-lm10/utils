### Write a string data to a text file in current directory in Javascript
	fs.writeFile(`${__dirname}/test.txt`, JSON.stringify(data), (err) => {
	if (err) {
	  console.error(err);
	}
	});

### How to create symlinks
	https://www.linode.com/docs/guides/linux-symlinks/

### HOw to unzip all .gz files while keeping the original
	for file in *.gz; do gunzip -dk "$file"; done
