# string_contains_vowels_only
#if a string contains  only vowels
#approach-1
s=input()
v="aeiouAEIOU"
for i in range(len(s)):
  if s[i] not in v:
    print("No")
    break
else:
  print("Yes")
  
#approach-2
s=input()
v="aeiouAEIOU"
for i in s:
  if i not in v:
    print("No")
    break
else:
  print("Yes")
  
#approach-3
s=input()
v="aeiouAEIOU"
vc=0
for i in range(len(s)):
  if s[i] in v:
    vc=vc+1
if vc==len(s):
  print("yes")
else:
  print("no")

#approach-4
s=input()
v="aeiouAEIOU"
vc=0
for i in s:
  if i in v:
    vc=vc+1
if vc==s:
  print("yes")
else:
  print("no")
