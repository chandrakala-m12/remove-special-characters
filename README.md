# remove-special-characters
This code can be used to remove any special characters and number from any test messages from uploaded documents
string = open('/content/drive/MyDrive/input.txt').read()
s=['*','_','i','3','!','0','1','5','-','$','7','#']
for i in s:
    string=string.replace(i,"")
print(string)
string = open('/content/drive/MyDrive/input.txt').read()
special=['*','_','i','!','-','$','#']
arr=list()
digit=1,2,3,4,5,6,7,8,9,0
for i in special:
  if i in digit:
      arr.append(i)
      print(arr)
  else:
      string=string.replace(i,"")
print(string)
