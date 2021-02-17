# fundamentals_frontend_test
## Task 1 - I’ve Been Everywhere, Man
Alice travels a lot for her work. Each time she travels, she visits a single city before returning home.

Someone recently asked her "how many different cities have you visited for work?" Thankfully Alice has kept a log of her trips. Help Alice figure out the number of cities she has visited at least once.

### Input
The first line contains a single positive integer `t (t ≤ 50)` indicating the number of test cases. The first line of each test case also contains a single positive integer `n` indicating the number of work trips Alice has taken so far. The following `n` lines describe these trips. The `i`-th such line simply contains the name of the city Alice visited on her `i`-th trip.

Alice's work only sends her to cities with simple names: city names only contain lowercase letters, have at least one letter, and do not contain spaces.

The number of trips is at most `100` and no city name contains more than `20` characters.

### Output
For each test case, simply output a single line containing a single integer that is the number of distinct cities that Alice has visited on her work trips.

```
### Input example #1
2
7
saskatoon
toronto
winnipeg
toronto
vancouver
saskatoon
toronto
3
edmonton
edmonton
edmonton
```

```
### Output example #1
4
1
```

## Task 2 - Elections
Sema and Yura take part in the elections. But it seems to them too boring, and they interviewed all the voters for whom they had voted.

It is known that there are only `n` voters and `k` candidates. You need to determine whether the election will end in one round, that is, whether there is a candidate for whom there was given more than half of the votes.

### Input
First line contains two integers `n` and `k` `(1 ≤ n ≤ 105, 1 ≤ k ≤ 100)` - the numbers of voters and the number of candidates.

Second line contains `n` integers `a1, a2, ..., an (1 ≤ a[i] ≤ k),` where `a[i]` is the candidate's number, for whom the `i`-th voter gave his vote.

### Output
Print  `"YES"`, if the elections will run in one round, and `"NO"` otherwise.

---
```
Input example #1
7 4
2 4 1 2 2 3 2
```
```
Output example #1 content_copy
YES
```
---
```
Input example #2 content_copy
4 4
1 2 3 4
```
```
Output example #2 content_copy
NO
```
---
```
Input example #3 content_copy
8 3
3 1 2 1 3 3 1 3
```
```
Output example #3 content_copy
NO
```
---
