##loany的博客

###下面是流程图
``` flow
  st=>开始
  en=>结束
  co=>opration:这里是内容
  cond=>condition:退出 or 重选 ?
  
  st-co-cond
  cond(退出)-en
  cond(重选)-co
```

```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```
