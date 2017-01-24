#Todo-cli

Small shell script that helps me with my todo list.

```html
  Usage: ${0} [OPTIONS]... [ARGS]...

  Simplifying your todo list.

  OPTIONS:
    --shownotesnotify     show if there are remaining notes as notification
    -h, --help            display the help and exit
    --del                 delete the note given as an argument
    --clean               clean all notes
    
    no options will add your note

  EXAMPLES:
    todo "this note will be added to the list"
    todo --del 5
    todo --clean
```
