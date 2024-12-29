![coding like there's no tomorrow](./programming.gif)
```bash
$ echo -n "What's Kramer's name? " \
  && read ANSWER \
  && echo U2FsdGVkX1+/fnw2Ck+r8YCFqYz+wH2lNDyF2qoMc2E= \
  | openssl enc -aes-256-cbc -a -d -salt -pbkdf2 -pass pass:"$ANSWER"
```
( ͡° ͜ʖ ͡°)
