# correct-horse-battery-staple

This is a Unix command line tool that generates passwords using four common words.

To use this command, clone this repo, then run:

Install core utilities, if you don't have them:

```sh
brew install coreutils
```

Clone this repo:

```sh
git clone https://github.com/SixArm/correct-horse-battery-staple.git
```

Change directory:

```sh
cd correct-horse-battery-staple
```

Run:

```sh
./correct-horse-battery-staple
```

Output:

```stdout
during-billion-travel-result
```

Repeat as many times as you want and copy to clipboard:

```sh
repeat 80 {./correct-horse-battery-staple} | pbcopy  
```

If you wish to customize the word list, then edit this file:

```txt
correct-horse-battery-staple.txt
```
