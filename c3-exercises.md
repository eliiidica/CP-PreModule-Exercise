```python
students={'Mandy':{'name':'Mandy Fok',\
                  'modules_number':3,\
                  'ID':'u1001',\
                   'PPMC':56,\
                   'PPS':68,\
                   'MOC':90
                  },\
         'Pete':{'name':'Pete Fung',\
                'modules_number':3,\
                'ID':'u1002',\
                 'PPMC':68,\
                 'PPS':65,\
                 'MOC':75
                },\
         'Katie':{'name':'Katie Fung',\
                 'modules_number':3,\
                 'ID':'u1003',\
                  'PPMC':67,\
                  'PPS':78,\
                  'MOC':55,\
                 }
         }
```


```python
for student in students:
    if students[student]['PPMC']<50:
        print(students[student]['name']+' PPMC: fail')
    if students[student]['PPMC']<60:
        print(students[student]['name']+' PPMC: pass')
    if students[student]['PPMC']<70:
        print(students[student]['name']+' PPMC: merit')
    else:
        print(students[student]['name']+' PPMC: distinction')
print('\n')
        
for student in students:
    if students[student]['PPS']<50:
        print(students[student]['name']+' PPS: fail')
    if students[student]['PPS']<60:
        print(students[student]['name']+' PPS: pass')
    if students[student]['PPS']<70:
        print(students[student]['name']+' PPS: merit')
    else:
        print(students[student]['name']+' PPS: distinction')
print('\n')
        
for student in students:
    if students[student]['MOC']<50:
        print(students[student]['name']+' MOC: fail')
    if students[student]['MOC']<60:
        print(students[student]['name']+' MOC: pass')
    if students[student]['MOC']<70:
        print(students[student]['name']+' MOC: merit')
    else:
        print(students[student]['name']+' MOC: distinction')
```

    Mandy Fok PPMC: pass
    Mandy Fok PPMC: merit
    Pete Fung PPMC: merit
    Katie Fung PPMC: merit
    
    
    Mandy Fok PPS: merit
    Pete Fung PPS: merit
    Katie Fung PPS: distinction
    
    
    Mandy Fok MOC: distinction
    Pete Fung MOC: distinction
    Katie Fung MOC: pass
    Katie Fung MOC: merit



```python
average_marks_katie=round((students['Katie']['PPMC']+students['Katie']['PPS']+students['Katie']['MOC'])/3,1)
average_marks_mandy=round((students['Mandy']['PPMC']+students['Mandy']['PPS']+students['Mandy']['MOC'])/3,1)
average_marks_pete=round((students['Pete']['PPMC']+students['Pete']['PPS']+students['Pete']['MOC'])/3,1)
```


```python
average_marks=[average_marks_katie,average_marks_mandy,average_marks_pete]
average_marks.sort(reverse=True)
average_marks
```




    [71.3, 69.3, 66.7]




```python
students['Mandy']['MMPE']:75
```


```python
students['Mandy']
```




    'MMPE'




```python
students={'Mandy':{'name':'Mandy Fok',\
                  'modules_number':3,\
                  'ID':'u1001',\
                   'PPMC':56,\
                   'PPS':68,\
                   'MOC':90
                  },\
         'Pete':{'name':'Pete Fung',\
                'modules_number':3,\
                'ID':'u1002',\
                 'PPMC':68,\
                 'PPS':65,\
                 'MOC':75
                },\
         'Katie':{'name':'Katie Fung',\
                 'modules_number':3,\
                 'ID':'u1003',\
                  'PPMC':67,\
                  'PPS':78,\
                  'MOC':55,\
                 }
         }
```


```python
new_mandy={'MMPE':55}
students['Mandy']=new_mandy
```


```python
students['Mandy']
```




    {'MMPE': 55}




```python
students={'Mandy':{'name':'Mandy Fok',\
                  'modules_number':3,\
                  'ID':'u1001',\
                   'PPMC':56,\
                   'PPS':68,\
                   'MOC':90
                  },\
         'Pete':{'name':'Pete Fung',\
                'modules_number':3,\
                'ID':'u1002',\
                 'PPMC':68,\
                 'PPS':65,\
                 'MOC':75
                },\
         'Katie':{'name':'Katie Fung',\
                 'modules_number':3,\
                 'ID':'u1003',\
                  'PPMC':67,\
                  'PPS':78,\
                  'MOC':55,\
                 }
         }
```


```python
students['Mandy']={'name':'Mandy Fok',\
                  'modules_number':3,\
                  'ID':'u1001',\
                   'PPMC':56,\
                   'PPS':68,\
                   'MOC':90,\
                   'MMPE':55
                  },\
```


```python
students['Mandy']
```




    ({'name': 'Mandy Fok',
      'modules_number': 3,
      'ID': 'u1001',
      'PPMC': 56,
      'PPS': 68,
      'MOC': 90,
      'MMPE': 55},)




```python

```
