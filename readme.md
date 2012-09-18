```Bash
#github clone
function github () {
    git clone git@github.com:$1/$2.git
    cd $2
}
#sublime-text
function sub () {
    sublime-text $1
}
```