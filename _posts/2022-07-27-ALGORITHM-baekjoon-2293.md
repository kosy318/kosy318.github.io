---
layout: post
title: Baekjoon - Gold5 2293. 동전1(C++)
subtitle : Dynamic Programming(DP)
tags: [C++, Algorithm, Dynamic Programming, Baekjoon]
author: Sooyeon Ko
comments : False
---

```c++
#include <iostream>
#include <vector>
#include <algorithm>

using namespace std;

int main() {
    int n, k;
    cin >> n >> k;

    vector<int> coin(n);

    for(int i=0; i<n; i++){
        cin >> coin[i];
    }
    sort(coin.begin(), coin.end());

    vector<int> dp(k+1, 0);

    for(int i=0; i<n; i++){
        for(int j=1; j<=k; j++){
            if(j < coin[i]) continue;
            if(j == coin[i]) dp[j] += 1;
            else if(j-coin[i] > 0) dp[j] += dp[j-coin[i]];
        }
    }

    cout << dp[k] << endl;

    return 0;
}
```
