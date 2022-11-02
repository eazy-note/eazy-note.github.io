---
layout: single
title : "[leetcode]69.Sqrt(x)"
categories: "leetcode_ps"
menu: "ps"
---  
  
[# 문제링크](https://leetcode.com/problems/sqrtx/description/){:target="_blank"}

##### 풀이 
정수 x가 주어지면 x의 제곱근을 구하는 문제입니다.  
내장 함수를 써서 문제를 풀면 안되는 조건이 있습니다.  
 
x의 범위가 0 부터 2^31-1 이므로 코드상에서 i*i 가 int 오버플로우가 날 수 있으니 조심해야 합니다.  


<script src="https://gist.github.com/eyou-note/b069b8bc56d258b858f5f344aa0a274c.js"></script>