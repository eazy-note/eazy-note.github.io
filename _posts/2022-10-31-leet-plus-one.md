---
layout: single
title : "[leetcode]66.Plus One"
categories: "leetcode_ps"
menu: "ps"
---  
  
[# 문제링크](https://leetcode.com/problems/plus-one/description/){:target="_blank"}

##### 풀이 
길이가 100이하 int 배열이 주어지면 해당 배열 마지막 원소에 +1 을 했을때 결과를 리턴하는 문제 입니다.
길이가 100이므로 숫자형으로 처리하기보다 string으로 변환 후, 마지막 자리를 +1 해주는것으로 풀었습니다.  
string 덧셈이므로 carry 값을 신경써 줍니다.  


<script src="https://gist.github.com/eyou-note/876aacd0155e460a5c16a664f17584fb.js"></script>