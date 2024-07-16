# banner_DONGUK777

## **사용방법**

**방법 1.**

```py
from pyfiglet import Figlet
f = Figlet(font='slant')
print(f.renderText('text to render'))
```  
  


**방법 2.**

```py
import pyfiglet
f = pyfiglet.figlet_format("text to render", font="slant")
print(f)
```
  
  

**글꼴 파일 설치 방법**

`pyfiglet -L <font file>`

pyfiglet을 설치한 방법에 따라 글꼴을 설치하려면 루트 액세스가 필요할 수 있다.  
ex) `sudo pyfiglet -L <font file>`.
  
## **설치 방법**  

```py
$ pip install banner_DONGUK777
```  
  
**사용법**
```
$ show-banner
```
  
**결과**
```
    ____  ____  _   __________  ____ __
   / __ \/ __ \/ | / / ____/ / / / //_/
  / / / / / / /  |/ / / __/ / / / ,<
 / /_/ / /_/ / /|  / /_/ / /_/ / /| |
/_____/\____/_/ |_/\____/\____/_/ |_|
```

