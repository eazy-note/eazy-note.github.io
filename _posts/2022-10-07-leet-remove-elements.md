---
layout: single
title : "[leetcode]remove element"
categories: "leetcode_ps"
menu: "ps"
---  
  
  
[# 문제링크](https://leetcode.com/problems/remove-element/description/){:target="_blank"}

##### 풀이
배열내의 중복된 요소를 제거하는 문제. 
in place 알고리즘으로 배열의 추가공간 할당 없이 해결하는게 조건이다.

> Do not allocate extra space for another array. 
>You must do this by modifying the input array in-place with O(1) extra memory.

입력값이 그리 크지 않으므로 배열 양끝에 인덱스를 두고 val 값과 같으면 뒤로 보내는 것(swap)으로 풀었다.


##### 코드
<script src="https://gist.github.com/eyou-note/32471d163d87e992e288b4333df8e18e.js"></script>