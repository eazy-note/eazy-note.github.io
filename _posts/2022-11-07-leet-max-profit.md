---
layout: single
title : "[leetcode]Best Time to Buy and Sell Stock"
categories: "leetcode_ps"
menu: "ps"
---  
  
[# 문제링크](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/description/){:target="_blank"}

##### 풀이
입력 범위가 10^5 이므로 완전 탐색으로 배열을 돌면서 이익을 구하면 시간초과가 납니다.
O(N)안에 해결하려면, 최소 이익이 발생하는 지점을 잡고, 그 이후로 최대 이익이 발생하는 날을 찾습니다.  
  
  
i번째날 이익이 현재 최소값보다 작으면 최대, 최소를 모두 갱신 해주고  
그게 아니라면 최대 값만 갱신해서 최대 최소값을 구해 놓습니다.  

마지막에 최대 이익을 구합니다.


<script src="https://gist.github.com/eyou-note/49192c84ea49a348f6864aed844c5bc8.js"></script>