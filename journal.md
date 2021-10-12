# Learning version control and Github's Magic

_With: [Franck](https://github.com/FranckPrts)_

## Some .md syntax
### Some visuals

Let's do a table
First col | second | third
:----: | :----:|:----:|
26 | 728|17 weeks
36|1008|24 weeks
42|1176|28 weeks

Now, let's try to make a `code cell`. First in Shell:
```shell
$ brew install tree
```

Then in python:

```python
# Set nice to -20: extremely high PID priority
new_nice = -20
sysErr = os.system("sudo renice -n %s %s" % (new_nice, os.getpid()))
if sysErr:
    print('Warning: Failed to renice, probably you arent authorized as superuser')
```
And R:

```R
# Keep columns of interest
da <- da %>% 
  filter(event_type=='response',
         !is.na(rt)) %>%
  select(trial_nr, condition, correct_response, rt, choice_key)
```

And now an image:

<img src="https://github.com/FranckPrts/git-papers/blob/master/common-git/LBA-MODEL.png" width="400">

### More text syntaxe
I am learning, that's nice. I can reference file in other folder of that repo such as [reference.txt folder in common-git](https://github.com/FranckPrts/git-papers/blob/master/common-git/reference.txt).

> Here i'm making a quote

And now; i'm making a reference [REF 2](https://www.merriam-webster.com/dictionary/reference). Let's now add a dividing line:

---

And now list**s**
- That's a list
- It's madde with bullet points
  - and sub bullet
  - because indentation is key
3. Not with numbers
4. like this one

And more importantly, checked list!!
- [x] This is a complete item
- [ ] This is an incomplete item