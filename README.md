# 1. Installation
```
Plug 'logicdomain/vim-md-autonum', {'do': './install.sh'}
```

# 2. How to use?
- Call in vim:
```
:Autonum
```
```
:CleanNum
```
```
:AddNum
```

girls when they DON'T document anything

like ok I understand what autonum does.... but what's all the rest of this

and your PYTHON is no better! 4 comments in the whole thing. the rest is just regex

alright i'll stop bitching and start reading. anyways.

# 3. How many levels?
- 5 means 1.2.3.4.5.
- Extendable: Alternate the initial_num_level to bigger range in logic-autonum file.

# 4. Sample
- Before autonum:
```
# title
## t1
### t11
## t2
```
- After autonum:
```
# 1. title
## 1.1. t1
### 2. t11
## 2.1. t2
```
