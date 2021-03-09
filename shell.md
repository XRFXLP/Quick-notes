Motivation: Shell is quite a powerful tool for getting things done, but most of the things are just plain non-obvious and smell like perl.

---
1. String splitting by delimiter: 
Accepts a string, and returns the word, in this case, one can do `d=$1` for accepting command line arguments.
Here `//` stands for global and replace all occurences of `.` (which here works as a dilimiter) with ` `, makes `d` a space seperated string, which is treated as array because of curly braces `{}`
```shell
d="this.is.my.string.which.is.seperated.by.dots"
arr=(${d//./ })
for i in "${arr[@]}"; do
  echo $i
done
```

To emphasize the role of curly braces, here's a script which accepts a string seperated by space, and return the words.

```shell
d=$1
arr=(${d})
for i in "${arr[@]}"; do
  echo $i
done
```
