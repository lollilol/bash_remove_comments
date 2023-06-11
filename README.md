# shell_remove_comments

### this is a very simple script that lives in your path, which you can pipe to to remove comments.

# One-liner install

```bash
sudo curl -L https://github.com/lollilol/shell_remove_comments/blob/master/remove_comments?raw=1 -o /usr/local/bin/remove_comments && sudo chmod +x /usr/local/bin/remove_comments
```

# Manual Install
- place [remove_comments](remove_comments?raw=1) in /usr/local/bin/
- make it executable: chmod +x /usr/local/bin/remove_comments

# Usage:
```bash
$ cat /etc/locale.gen | remove_comments
en_US.UTF-8 UTF-8
```
