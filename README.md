# 21st_june_task
simple coding for anonymous
1) Print odd numbers in an array using anonymous function
var t=function()
{
  var odd= [2,3,4,5,6,7,8,9]
  for(i=0;i<odd.length;i++)
  {
    if(i%2!==0)
    console.log(odd[i])
  }
}
t();

2) Convert all the strings to title caps in a string array

var t=function()
{
  var str= ["kanniga is geeking in guvi"]
  for(i=0;i<str.length;i++)
  {
    let upp=str.toUpperCase()
    console.log(upp)
  }
}
t();

3) Sum of all numbers in an array
var t=function()
{
  var num= [10 , 20 , 30, 40]
  var sum=0;
  for(i=0;i<num.length;i++)
  {
    sum=sum+num[i];
    
  }console.log(sum)
}
t();








