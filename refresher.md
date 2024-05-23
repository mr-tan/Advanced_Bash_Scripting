## Refresher ##

Review:

- basic commands
- functions
- general script flow
- shebang
- loops
- perform tasks
- branching

Script flow:
- conditional statement
- loops
- functions
- source code

Loops:
- know exactly how many times we want to repeat the loop
- while is better to loop until a condition is met without knowing how many times it would take
- for reading files, it is better to use while than for
- while runs the loop while the condition is true, and until runs the loop until the condition is true

Read source file:
- eg. see below

Functions:
- organized
- efficient
- easy to understand
- shorter code
- manageable

---

```bash
# if then statement
if [[ ... ]]; then
# actions
fi

# case statement
case word in 
  pattern1)
    Statement(s)
    ;;
  *)
    Default condition to be executed
    ;;
esac

# read from source
$ cat .conf
name="Bob"
$ ./conf_read-v1.sh
```


