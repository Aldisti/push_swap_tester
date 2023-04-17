# push_swap_tester

### Installation

First, go to the root of your repository (which is where you can find your
Makefile) and do:

```git clone https://github.com/Aldisti/push_swap_tester.git```

after this you have to compile your push_swap and if you have done the bonus
part then you have to compile it too. If your Makefile is correct you can do:

```make all```

next just go inside the tester folder with this command:

```cd push_swap_tester```

now you can test your push_swap with 2 different scripts, one is wrote in
python and the other one is in bash. Enjoy the test...

### tester.py usage

The python script will no longer be updated so I suggest you to use the bash
script. But I'll leave you a little guide on how to use it, for more info
just run:

```python3 tester.py```

You can run this tester in 4 different ways.
1) to check if your push_swap works correctly do:
```python3 tester.py m```
2) to check if your checker works correctly do:
```python3 tester.py b```
3) to check both just do:
```python3 tester.py a```
4) to do a custom number of tests with a custom stack size do:
```python3 tester.py [how_many_tests] [stack_size]```

#### Pro tip

If you want to launch the tester with a particular checker executable you can
add the path of the executable as second or third flag when running the tester:

```python3 tester.py m [path_to_the_checker_you_want_to_use]```

### tester usage

The bash script is an executable file, so you can run it just by typing
```./tester```. But to use it you have to add an option, at the moment there
are 4 different options. You can see them doing:

```bash
./tester --help
```

the output you'd get should be like this:
```
  -m		check the mandatory part
  -b		check the bonus part
  -a		check both, mandatory and bonus
  -p		allow you to do custom tests
  -h, --help	display this help and exit
```



## Bug report

If you find some bugs or errors of any type, please, report them to me. You can
contact me on slack: @adi-stef