`for (double score : scores)`

**意思就是：把 scores 数组里的每一个数，挨个取出来，放进变量 score 里。**

---

## 拆开看是什么意思


```C++
for (double score : scores)
{
    sum += score;
}
```

- `scores`：你的成绩数组（vector）
- `double score`：**临时变量**，用来接住每一个取出来的成绩
- `:`：读作 **“里面的每一个”**

整句翻译：

**遍历 scores 里的每一个成绩，把它们挨个加到 sum 里。**