# [20203266 김수은] 오픈소스SW개론 두번째 과제

<br/>

1. Add quotes to ansible playbook
```
G$a"<Esc>ywbbbPZZ
```

<br/>

2. simple replacements
```
:%s/\(emacs\|sublime\)/vim/g<CR>ZZ
```

<br/>

3. Satisfy the go linter
```
:4<CR>yyPi// <Esc>2wcwTODO<Esc>yy:6<CR>PwcwDebug<Esc>ZZ
```

<br/>

4. Plotting some variables in python
```
:%s/y1/abs(y1)/g<CR>:3s/1/2/g<CR>:4s/1/3/g<CR>:5s/1/4/g<CR>/k<CR>cwg<Up><BS>r<Up><BS>b<Esc>ZZ
```

<br/>

5. Python dataclasses
```
:5<CR>yw:10<CR>$Pa,<Esc>:6<CR>yw:10<CR>$Pa,<Esc>:7<CR>yw:10<CR>$Pa,<Esc>:8<CR>yw:10<CR>$PZZ
```
