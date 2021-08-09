# Numpy - part 3

## 6. Array operation

```pyth
a = np.arange(1,7).reshape(2,3)
a
```

```
array([[1, 2, 3],
       [4, 5, 6]])
```



```pyth
a + a
```

```
array([[ 2,  4,  6],
       [ 8, 10, 12]])
```



```pyth
a - a
```

```
array([[0, 0, 0],
       [0, 0, 0]])
```



```pyth
a * a
```

```
array([[ 1,  4,  9],
       [16, 25, 36]])
```



### dot product

```pyth
np.dot(a, a.T)
```

```
array([[14, 32],
       [32, 77]])
```



```pyth
a.dot(a.T)
```

```
array([[14, 32],
       [32, 77]])
```

### 

### broadcasting

```pyth
a
```

```
array([[1, 2, 3],
       [4, 5, 6]])
```



```pyth
a + 3
```

```
array([[4, 5, 6],
       [7, 8, 9]])
```



```pyth
a // 3
```

```
array([[0, 0, 1],
       [1, 1, 2]])
```



```pyth
a % 3
```

```
array([[1, 2, 0],
       [1, 2, 0]])
```



```pyth
b = np.array([10,20,30])

# 2D matrix, 1D vector plus possible
a + b
```

```
array([[11, 22, 33],
       [14, 25, 36]])
```

