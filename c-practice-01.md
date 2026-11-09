# C 语言练习 1

先自己做，做完再对答案。

## 1. 输出 1 到 10

```c
for (int i = 1; i <= 10; i++) {
    printf("%d ", i);
}
```

问：第一个输出几？最后一个输出几？一共输出几个数？

## 2. while 和 do-while 的区别

```c
int n = 5;
while (n < 5) { printf("%d", n); n++; }

int m = 5;
do { printf("%d", m); m++; } while (m < 5);
```

问：上面两段各输出什么？为什么不一样？

## 3. ++ 在前和在后

```c
int a = 3;
printf("%d\n", a++);
printf("%d\n", ++a);
printf("%d\n", a);
```

问：三行各输出几？

## 4. 判断奇偶

```c
int x = 7;
if (x % 2 == 0) printf("even");
else printf("odd");
```

问：输出什么？把 7 改成 8 呢？

## 5. 求和

```c
int sum = 0;
for (int i = 1; i <= 100; i++) {
    sum += i;
}
printf("%d", sum);
```

问：最后输出几？
