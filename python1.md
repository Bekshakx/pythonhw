# Python жылдам бастау 

Life is short, Come and Use Python! Welcome to Python Quick Start!

Python is a widely used high-level programming language for  general-purpose programming, created by Guido van Rossum and first  released in 1991.

Өмір қысқа, Python-ды қолданыңыз! Python Жылдам бастау жүйесіне қош келдіңіз!

Python - бұл Гуидо ван Россум құрған және 1991 жылы алғаш шығарылған,  жалпы мақсаттағы бағдарламалауға арналған жоғары деңгейлі бағдарламалау  тілі.

# Питонды жылдам бастау

 

## 1  Preparing Python development environtment

## 2  Python дамыту ортасын дайындау

### 2.1  Installing Python on Windows

### 2.2  Windows-қа Python орнату

### 2.3  Installing Python on Mac OS

### 2.4  Mac OS-ге Python орнату

### 2.5  Installing Python on Linux 

### 2.6  Linux-қа Python орнату

### 2.7  Installing Python on Raspberry Pi

### 2.8  Таңқурай Pi-ге Python орнату

### 2.9  Verify Python installation

### 2.10  Python қондырғысын тексеріңіз

To confirm that Python was installed correctly, you can verify that by running the following command in your favorite terminal:

Python дұрыс орнатылғанын растау үшін сүйікті терминалда келесі пәрменді іске қосу арқылы тексеруге болады:

```
python --version
```

If you have Python 3 installed, and it is your default version you should see
something like this:

Егер сізде Python3 орнатылған болса, және бұл әдепкі нұсқасы болса, Сізге осындай нәрсе көру керек:

`python --version`
Python 3.7.4

## 3  Python basic syntax

## 4  Python негізгі синтаксисі

### 4.1  'Hello, World' in Python using command line

###  Python командалық жолы арқылы" Сәлем, Әлем"

Now write the following code in the prompt:

Шақыру үшін келесі кодты жазыңыз:

```
print('Hello, World')
```

### 4.2  'Hello, World' Python file

### "Сәлем, Әлем" Python файлы

Create a new file `hello.py` that contains the following line:

Келесі жолды қамтитын hello.py деген жаңа файлды жасаңыз :

```
# script: hello.py
print('Hello, World')
```

In your terminal, navigate to the directory containing the file `hello.py`.
Type `python hello.py`, then hit the **Enter** key.

Терминалда hello.py файлын қамтитын каталогқа өтіңіз 

Типті Python hello.py, содан кейін Enter пернесін басыңыз.

you should see *Hello, World* printed to the console.

сіз консольге басылған  Hello, World-ды көру керек.

```
Hello,World
```

### 4.3  Launch an interactive Python shell

### 4.3 Python интерактивті қабығын іске қосу

By executing (running) the `python` command in your terminal, you are presented with an interactive Python shell. This is also known as the Python Interpreter.

терминалда python командасын орындау (іске қосу) кезінде сізге Python интерактивті қабығы беріледі. Бұл сондай-ақ Python интерпретаторы ретінде белгілі.

from your terminal, execute the command `python`.

терминалдан Python командасын орындаңыз.

```
python
```

Alternatively, start the interactive prompt and load file with `python -i <file.py>`.

Сонымен қатар, интерактивті шақыруды іске қосыңыз және Python-i арқылы файлды жүктеп алыңыз <file.py>.

In command line, run:

Командалық жолда команданы орындаңыз:

```
python -i hello.py
```

```
Hello, World
>>>
```

There are multiple ways to close the Python shell:

Python қабығын жабудың бірнеше жолы бар:

```
exit()
```

or

немесе

```
quit()
```

Alternatively, **CTRL + D** will close the shell and put you back on your terminal's command line.

Сонымен қатар, CTRL + D батырмасы қабығын  жабады және сізді терминалдың командалық жолына қайтарады.

If you want to cancel a command you're in the middle of typing and get 
back to a clean command prompt, while staying inside the Interpreter 
shell, use **CTRL + C** .

Егер сіз теретін команданы алып тастағыңыз келсе, және интерпретатор қабықшасының ішінде қалып, таза командалық жолға қайта оралғыңыз келсе, **Ctrl + C** пайдаланыңыз.

### 4.4  Run commands as a string

### 4.4 Командаларды жол түрінде орындау

Python can be passed arbitrary code as a string in the shell:

Python еркін кодты қабықшада жол түрінде бере алады:

```
python -c 'print("Hello, World")'
```

This can be useful when concatenating the results of scripts together in the shell.

Бұл скрипттердің нәтижелерін қабықшамен біріктірген кезде пайдалы болуы мүмкін.

## 5  Variables

## 5 Айнымалы

To create a variable in Python, all you need to do is specify the variable name, and then assign a value to it.

Python-да айнымалыны құру үшін, сіз істеу керек барлық айнымалы атауын көрсетіп, оған мән беру керек.

```
<variable name> = <value>
```

Python uses = to assign values to variables. There's no need to  declare a variable in advance (or to assign a data type to it),  assigning a value to a variable itself declares and initializes the  variable with that value. There's no way to declare a variable without  assigning it an initial value.

Python "= " мәндерді айнымалыға беру үшін пайдаланады. Айнымалыны алдын ала жариялау қажет емес (немесе оған деректер түрін тағайындау), айнымалының мәнін беру осы мәнмен айнымалыны өзі жариялайды және бастамалайды. Бастапқы мәнді тағайындамай, айнымалыны жариялау мүмкін емес.

```
# Integer
a = 2
print(a)
```

```
# Integer
b = 9876541325489
print(b)
```

```
# Floating point
pi = 3.14 
print(pi) 
```

```
# String
c = 'A' 
print(c)
# Output: A
```

```
# String
name = 'John Doe' 
print(name)
```

```
# Boolean
q = True 
print(q)
# Output: True
```

```
# Empty value or null data type
x = None 
print(x)
# Output: None
```

Variable assignment works from left to right. So the following will give you an syntax error.

Айнымалыны беру солдан оңға қарай жұмыс істейді. Осылайша, сізге синтаксистік қате береді.

```
 0=x
```

You can not use python's keywords as a valid variable name. You can see the list of keyword by:

Python кілт сөздерін айнымалы деп пайдалануға болмайды. Сіз негізгі кілт сөздер тізімін көре аласыз:

```
import keyword 
print(keyword.kwlist)
```

### 5.1  Rules for variable naming:

### 5.1 айнымалыларды атау ережелері:

Variables names must start with a letter or an underscore.

Айнымалылардың аттары әріптен немесе астын сызу символынан басталуы керек.

```
x = True # valid 
_y = True # valid 
```

```
9x = False # starts with numeral
```

```
$y = False # starts with symbol
```

1. The remainder of your variable name may consist of letters, numbers and underscores.

Айнымалының қалған бөлігі әріптерден, цифрлардан және астын сызу символдарынан тұруы мүмкін.

```
azat_0_ai_87 = 'Still Valid'
```

Names are case sensitive.

Аттар тіркелімге сезімтал.

```
x=9
X=10 
```

```
x == X
```

You can assign multiple values to multiple variables in one line. Note 
that there must be the same number of arguments on the right and left 
sides of the **=** operator:

Бір жолда бірнеше айнымалы мәндерді тағайындай аласыз. Оператордың оң және сол бөліктерінде = бірдей аргументтер болуы тиіс екенін ескеріңіз:

```
a, b, c = 1, 2, 3 
print(a, b, c)
# Output: 1 2 3
```

```
a, b, c = 1, 2
```

```
a, b = 1, 2, 3
```

You can also assign a single value to several variables simultaneously.

Сондай-ақ, бір мәнді бірнеше айнымалы бір уақытта тағайындауға болады.

```
 a=b=c=1 
print(a, b, c)
```

When using such cascading assignment, it is important to note that all 
three variables a, b and c refer to the same object in memory, an `int`
object with the value of 1. In other words, a, b and c are three 
different names given to the same int object. Assigning a different 
object to one of them afterwards doesn't change the others, just as 
expected:

Мұндай каскадты мақсатты пайдалану кезінде барлық үш A, B және Сайнымалылары жадындағы бір объектіге, 1 мәні бар int объектісіне сілтеме жасайды. Басқаша айтқанда, А, B және C-бір int объектісіне берілген үш түрлі атау. Олардың біреуіне басқа объектіні тағайындау кейіннен күтілгендей басқаларын өзгертпейді:

```
a = b = c = 1 # all three names a, b and c refer to same int object with value 1
# a, b және c үш Атауы 1 мәні бар бір int объектісіне жатады
print(a, b, c)
# Output: 1 1 1
```

```
b = 2 # b now refers to another int object, one with a value of 2 
print(a, b, c)
# Output: 1 2 1  # so output is as expected.
```

The above is also true for mutable types (like list, dict, etc.) just as
it is true for immutable types (like int, string, tuple, etc.):

Жоғарыда айтылғандар сондай-ақ өзгертілетін түрлерге (мысалы, list, dict және т. б.), өзгермейтін түрлерге (мысалы, int, string, tuple және т. б.):

```
x = y = [7, 8, 9] # x and y refer to the same list object just created, [7, 8, 9]
x = [13, 8, 9]  #x now refers to a different list object just created, [13, 8, 9]
print(y) # y still refers to the list it was first assigned
```

Nested lists are also valid in python. This means that a list can contain another list as an element.

Салынған тізімдер де python-да жарамды. Бұл тізім элемент ретінде басқа тізімді қамтуы мүмкін дегенді білдіреді.

```
x = [1, 2, [3, 4, 5], 6, 7] # this is nested list
print(x[2])
# Output: [3, 4, 5]
print(x[2][1])
# Output: 4
```

Lastly, variables in Python do not have to stay the same type as 
which they were first defined -- you can simply use = to assign a new 
value to a variable, even if that value is of a different type.

Соңында, Python айнымалылары олар алғаш анықталған сияқты бірдей түр қалуға тиіс емес, -- сіз жай ғана пайдалануға болады = жаңа мән беру үшін айнымалы, тіпті басқа түрі мәні.

```
a=2 
print(a)
# Output: 2
```

```
a = "New value" 
print(a)
# Output: New value
```

If this bothers you, think about the fact that what's on the left of =
is just a name for an object. First you call the int object with value 2
a, then you change your mind and decide to give the name a to a string 
object, having value 'New value'. Simple, right?

Егер сіз алаңдатсаңыз, сол жақта орналасқан нәрсе туралы ойлаңыз = - бұл объект үшін ғана аты. Алдымен сіз 2 a мәні бар int нысанын шақырасыз, содан кейін қайта ойлайсыз және 'New value'мәні бар жол объектісіне a атауын беруді шешесіз. Қарапайым, шындық?

### 5.2  Built in data types

### 5.2 Деректердің кірістірілген түрлері 

#### 5.2.1  Booleans 

#### 5.2.1 логикалық мәндер

`bool`: A **boolean** value of either `True` or `False`. Logical operations like `and`, `or`, `not` can be performed on booleans.

bool: **True** немесе **false** логикалық мәні. **And, or, not** сияқты логикалық операциялар boolean-ға орындалуы мүмкін.

```
x or y 
x and y # if x is False then x otherwise y 
not x # if x is True then False, otherwise True
```

If boolean values are used in arithmetic operations, their integer values (1 and 0 for True and False) will be used to return an integer 
result:

Егер арифметикалық операцияларда булевтар мәндер пайдаланылса, онда олардың бүтін мәндері (1 және 0 True және False үшін) бүтін нәтиже алу үшін пайдаланылады:

```
True * True == 1 # 1 * 1 == 1
True + False == 1 # 1 + 0 == 1
```

#### 5.2.2  Numbers

#### 5.2.2  Нөмірлер

##### 5.2.2.1  int: Integer number

##### 5.2.2.1  int: Бүтін сан

```
a=2
b = 100
c = 123456789
d = 38563846326424324
```

##### 5.2.2.2  float: Floating point number;

##### 5.2.2.2  float: өзгермелі нүкте саны;

```
a = 2.0
b = 100.e0
c = 123456789.e1
```

#### 5.2.3  Strings

#### 5.2.3  Жолдар

`str`: a **unicode** string. The type of 'hello'
 `bytes`: a **byte** string. The type of b'hello'

#### 5.2.4  Sequences and collections

#### 5.2.4  Тізбектер және коллекциялар