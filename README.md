# A Kernel Seedling
TODO: intro

## Building
```shell
TODO: cmd for build
make
```

## Running
```shell
TODO: cmd for running binary
sudo insmod proc_count.ko
cat /proc/count
```
TODO: results?
80

## Cleaning Up
```shell
TODO: cmd for cleaning the built binary
make clean
sudo rmmod proc_count.ko

```

## Testing
```python
python -m unittest
```
TODO: results?
paste output of python test script here
...
----------------------------------------------------------------------
Ran 3 tests in 14.936s

OK

Report which kernel release version you tested your module on
(hint: use `uname`, check for options with `man uname`).
It should match release numbers as seen on https://www.kernel.org/.

```shell
uname -r -s -v
```
TODO: kernel ver?
My kernel version is 5.14.8-arch1-1
Linux 5.14.8-arch1-1 #1 SMP PREEMPT Sun, 26 Sep 2021 19:36:15 +0000
