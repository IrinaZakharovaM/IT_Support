
# MD 5

## create a text file of a single line
```bash
echo 'This is some text in a file, just so we have some data' > file.txt
```

## generate the MD5 sum for the file and store it
```bash
md5sum file.txt > file.txt.md5
cat file.txt.md5
```

## verify that the hash is correct and original file hasn't been tampered with since the sum was made
```bash
md5sum -c file.txt.md5
```

# Verifying an invalid file

## make a copy of file
```bash
cp file.txt badfile.txt
```

## generate new md5sum for the new file
```bash
md5sum badfile.txt > badfile.txt.md5
```

## check the resulting hash
```bash
cat badfile.txt.md5
cat file.txt.md5
```

## edit file and add a space character to the end of the file
```bash
nano badfile.txt
```
## verify
```bash
md5sum -c badfile.txt.md5
```

## generate new hash
```bash
md5sum badfile.txt > new.badfile.txt.md5
cat new.badfile.txt.md5
```

# SHA1

## create sh1 sum
```bash
shasum file.txt > file.txt.sha1
cat file.txt.sha1
```

## verify
```bash
shasum -c file.txt.sha1
```

# SHA256

## generate sha256 sum
```bash
shasum -a 256 file.txt > file.txt.sha256
cat file.txt.sha256
shasum -c file.txt.sha256
```