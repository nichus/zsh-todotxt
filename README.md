# zsh-todotxt
My zsh configurations wrapping ([todo.txt](https://github.com/todotxt/todo.txt-cli)) how I like. It depends on one [add on](https://github.com/todotxt/todo.txt-cli/wiki/Todo.sh-Add-on-Directory), which is called [lately](https://github.com/todotxt/todo.txt-cli/wiki/Todo.sh-Add-on-Directory#lately-report-of-recently-completed-tasks).

This defines a number of functions/aliases

`todo` - adds a new task, converting standalone priority letters to uppercase and wrapping them in parentheses

`I` - adds a completed task

`didlog` - runs the _lately_ plugin, reporting what's been going on

`did <#>` - Marks the item identified by `#` as completed
