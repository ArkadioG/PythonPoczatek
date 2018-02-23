# Witaj

Znajdziesz tutaj informacje dla osób chcących zacząć przygodę z programowaniem.

Informacje te zebrane zostały dla uczestników [bezpłatnego webinara Python](https://www.facebook.com/events/2034252873514135/) zorganizowanego przez [infoShare Academy](http://infoshareacademy.com/).

# Python

## Instalacja

Najnowsza wersja Python to **3.6.4**.  
Instalatory znajdują się na stronie <https://www.python.org/downloads/>.

## Dokumentacja

Oficjalna dokumentacja: <https://docs.python.org/3/>.

* [Tutorial](https://docs.python.org/3/tutorial/index.html)  
zawiera krótkie omówienia poszczególnych zagadnień języka
* [Language reference](https://docs.python.org/3/reference/index.html)  
opis składni oraz semantyki jezyka
* [Library reference](https://docs.python.org/3/library/index.html)  
opisy funkcjonalności i modułów dostępnych w ramach biblioteki standardowej

## PyPI - baza pakietów Pythona

<https://pypi.python.org/pypi>

Zawiera funkcjonalności udostępnione przez społeczność, jeśli chcesz coś zrobić, to najprawdopodobniej jest do tego napisana w Python biblioteka ;)

## pip - Instalowanie dodatkowych pakietów

**pip** jest instalatorem pakietów - jeśli znalazła(e)ś coś w PyPI i chcesz to zainstalować, to skorzystaj z pip. pip najprawdopodobniej masz już zainstalowany razem z Pythonem.

Dokumentacja: <https://pip.pypa.io/en/stable/>.

## venv / virtualenv

**virtualenv** lub **venv** służą do izolowania różnych "zestawów" Pythona. Pozwala to na istnienie obok siebie różnych wersji tych samych bibliotek.

    venv jest dostępny od razu z Pythonem, virtualenv trzeba doinstalować za pomocą pip

* venv  
dokumentacja: <https://docs.python.org/3/library/venv.html>
* virtualenv  
dokumentacja: <https://virtualenv.pypa.io/en/stable/>

# Nauka Python

## Kursy stacjonarne

* [infoShare Academy](http://infoshareacademy.com/)  
kursy w Gdańsku, Warszawie, Lublinie, Krakowie, Szczecinie

## Kursy online

### [edX](https://www.edx.org)

* [Microsoft - Introduction to Python: Absolute Beginner](https://www.edx.org/course/introduction-python-absolute-beginner-microsoft-dev236x-1)
* [Microsoft - Introduction to Python for Data Science](https://www.edx.org/course/introduction-python-data-science-microsoft-dat208x-8)

 ### [Coursera](https://www.coursera.org)

* [University of Toronto - Learn to Program - Fundamentals](https://www.coursera.org/learn/learn-to-program)

## Youtube

### Dla zupełnie początkujących

1. [Socratica](https://youtu.be/bY6m6_IIN94)

### Dla tych co już coś wiedzą

1. [Prezentacje Raymonda Hettingera (core developer Python)](https://www.youtube.com/playlist?list=PLRVdut2KPAguz3xcd22i_o_onnmDKj3MA)

## Książki

1. Automate the boring stuff with Python
    * wersja angielska, darmowa online: [automatetheboringstuff.com/](https://automatetheboringstuff.com/)
    * wersja polska, papierowa do kupienia w sklepach n.p.: [Helion - 89 zł](https://helion.pl/ksiazki/automatyzacja-nudnych-zadan-z-pythonem-nauka-programowania-al-sweigart,autopy.htm)
2. Python. Wprowadzenie. Mark Lutz wyd. O'Reilly: [Helion - 149 zł](https://helion.pl/ksiazki/python-wprowadzenie-wydanie-iv-mark-lutz,pytho4.htm#format/d)
    * jest to książka raczej dla osób, które już trochę rozumieją Pythona
3. Full Stack Python - online
    * darmowa, j. angielski<https://www.fullstackpython.com/>

# Gdzie szukać pomocy - fora

1. [Google](https://google.com)
1. [Stackoverflow](https://stackoverflow.com/)
1. [Forum 4programmers - polskie](https://4programmers.net/Forum/)

# Narzędzia

## IDE - Integrated Development Environment

* [PyCharm Community - bezpłatny](https://www.jetbrains.com/pycharm/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Thony](http://thonny.org/)
  * stworzony na Uniwersytecie w Tartu (Estonia) z myślą o początkujących
* [CodeSculptor](http://py3.codeskulptor.org/)
  * IDE online, pozwala również na tworzenie apliakcji graficznych!
  * dokumentacja: <http://py3.codeskulptor.org/docs.html>
* [Python Tutor](http://www.pythontutor.com/)
  * wizualizacja tego co się dzieje w pamięci podczas wykonywania instrukcji

## System kontroli wersji git

Instalator: <https://git-scm.com/>

### Zdalne repozytoria

* [GitHub](https://github.com) - bezpłatne tylko publiczne repozytoria
* [GitLab](https://about.gitlab.com/) - bezpłatne prywatne repozytoria
* [Bitbucket](https://bitbucket.org/) - bezpłatne prywatne repozytoria

### Kursy

* <https://try.github.io/levels/1/challenges/1>
* <https://git-scm.com/videos>
* <https://backlog.com/git-tutorial/>
* <https://www.tutorialspoint.com/git/index.htm>

### Narzędzia okienkowe

* [GitKraken](https://www.gitkraken.com/)
* [SourceTree](https://www.sourcetreeapp.com/)
* [GitHub desktop](https://desktop.github.com/)

# Zastosowania Python

Ze względu na swoją uniwersalnośc oraz szybkość developmentu Python jest używany do wielu zadań. Duża i aktywna społeczność wokół Pythona, która tworzy nowe pakiety sprawia, że w większości Twoich potrzeb wystarczy zainstalować pip-em i zaimportować odpowiedni moduł.

Czy wiesz, że w Pythonie jest nawet moduł antygrawitacji?  
Wystarczy go zaimportować - wpisz poniższą komendę w interpreterze Python, tylko uważaj!

```Python
import antigravity
```

Żarty żartami, ale czy wiesz że **Instagram** działa na Python'ie?

Przeczytaj ten ciekawy artykuł, w którym opisano przejście Instagrama z Pythona 2 na Pythona 3:  
[Instagram Makes a Smooth Move to Python 3](https://thenewstack.io/instagram-makes-smooth-move-python-3/)

<img src="https://cdn.thenewstack.io/media/2017/06/eabeb0f2-f897a954-instagramheartspython.jpg" width=300>

## Web development

Tworzenie aplikacji webowych.

* [Django](https://www.djangoproject.com/)
  * tutorial: <https://docs.djangoproject.com/en/2.0/intro/tutorial01/>
  * tutorial Django Girls: <https://tutorial.djangogirls.org/pl/django/>
* [Flask](http://flask.pocoo.org/)
  * tutorial: <https://www.tutorialspoint.com/flask/index.htm>

## Data Science, Machine Learning

Analiza danych, uczenie maszynowe.

* [Anaconda](https://www.anaconda.com/download/) - zestaw ponad 150 bibliotek do przetwarzania i analizy danych, analizy predykcyjnej, obliczeń naukowych, wizualizacji.
  * dokumentacja: <https://docs.anaconda.com/>

## Computer vision

Analiza zdjęć oraz ruchomych obrazów.

* [OpenCV](https://opencv.org/)

## GUI development

Tworzenie aplikacji okienkowych.

* [tkinter](https://docs.python.org/3/library/tkinter.html)
  * tutorial: <https://www.tutorialspoint.com/python/python_gui_programming.htm>
* [wxPython](https://www.wxpython.org/)
* [PyGame](https://www.pygame.org/news)
* [Kivy](https://kivy.org/#home)
* [pyqt](https://riverbankcomputing.com/software/pyqt/intro)

## Automatyzacja (testy automatyczne)

* [Selenium](https://www.seleniumhq.org/)
  * [Pakiet dla Python](https://pypi.python.org/pypi/selenium)  
  dokumentacja: <https://seleniumhq.github.io/selenium/docs/api/py/api.html>

## Web scraping

Roboty - pająki, zbierające informacje z internetu, n. adresy email, zdjęcia, artykuły itp.

* [Beautiful Soup](https://pypi.python.org/pypi/beautifulsoup4) - *wymaga instalacji przez pip*
  * dokumentacja: <https://www.crummy.com/software/BeautifulSoup/bs4/doc/>
  * tutorial 1: <https://automatetheboringstuff.com/chapter11/>
  * tutorial 2: <https://www.dataquest.io/blog/web-scraping-tutorial-python/>

## NEO Blockchain - Smart Contracts

Tworzenie inteligentnych kontraktów w jednym z największych blockchain'ów - [NEO](https://neo.org/).

* Workshop: <https://github.com/CityOfZion/python-smart-contract-workshop>

# Praca

## Niech Cię znajdą!

Obecność w sieci jest dzisiaj kluczowa, dobry profil na LinkedIn, czy własny blog sprawi, że rekruterzy sami bedą do Ciebie sie odzywać.

* stwórz swój profil na [LinkedIn](https://www.linkedin.com/)
  * uzupełnij wszystkie informacje
  * nie zapomnij o zdjęciu
  * dodaj znajome osoby do Twojej sieci - im więcej tym większa jest Twoja widoczność
* załóż bloga, lub własną stronę - wizytówkę
  * jeśli decydujesz się na bloga - pamiętaj aby regularnie publikować
  * weź udział w konkursie [daj się poznać](https://devstyle.pl/daj-sie-poznac/)

## Ile można zarobić

* [forum 4programmers.pl](https://4programmers.net/Forum/Kariera/233131-ile_zarabiacie?page=143) - w tym wątku programiści piszą ile zarabiają
* [wynagrodzenia.pl - zarobki programistów Python](https://wynagrodzenia.pl/moja-placa/ile-zarabia-programista-python) - mediana 6828 PLN
* [wynagrodzenia.pl - ranking zarobków w USA wg. języka programowania](https://wynagrodzenia.pl/artykul/top-10-jezykow-programowania-z-najwyzszymi-zarobkami-w-2017-w-usa) - Python na 3 miejscu, roczne zarobki seniora ok 100.000 USD

## Gdzie szukać pracy

* [nofluffjobs.com](https://nofluffjobs.com/?criteria=python)
* [4programmers](https://4programmers.net/Praca?q=&tag%5B%5D=python&remote_range=100&salary=&currency=1)
* []()

# Ćwicz programowanie

Najprostsza odpowiedź: **pisz kod, dużo kodu**.

Ale co?

Najprościej - to co się Tobie przyda:

* szukasz mieszkania - napisz scrappera, który będzie codziennie sprawdzać ogłoszenia, i jeśli znajdzie odpowiednie to powiadomi Cię mailem
* chcesz prowadzić bloga - utwórz aplikację Django
* naucz się korzystać z API - np. wypróbuj API [Microsoft Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/) i analizuj obrazy, rozpoznawaj twarze i emocje, rozpoznawaj mowę.

Strony z pomysłami:

* [1000 pomysłow - reddit](https://www.reddit.com/r/learnprogramming/comments/2a9ygh/1000_beginner_programming_projects_xpost/)
* [reddit daily programmer](https://www.reddit.com/r/dailyprogrammer/) - codzienne zadania programistyczne
* [karan mega project](https://github.com/ArkadioG/Projects) - lista zadań w różnym stopniu trudności
* [Invent with Python Blog](http://inventwithpython.com/blog/2012/02/20/i-need-practice-programming-49-ideas-for-game-clones-to-code/) - pomysł na wykonanie 49 klonów gier
* [Google Code Jam](https://code.google.com/codejam/about) - coroczny konkurs algorytmiczny, na stronie są dostępne zadania z poprzednich edycji, możesz więc sprawdzić się w dowolnej chwili.
* [Practice Python](http://www.practicepython.org/) - zadania
* [w3resource](https://www.w3resource.com/python-exercises/) - zadania

# Ciekawe blogi, vlogi, meetupy

## Uczestnicz w meetupach

* [infoShare po godzinach](https://www.facebook.com/pg/infoshareacademy/events/?ref=page_internal)
* [meetup.com](https://www.meetup.com/)
* [crossweb.pl](https://crossweb.pl/)
* [spotkania-it.pl](http://spotkania-it.pl/)

## Czytaj blogi - nie tylko związane z Pythonem.

<img src="https://devstyle.pl/wp-content/uploads/2017/08/devstyle-2017.png" width="300px">

* [devstyle.pl](https://devstyle.pl/junior/) - Największy blog w polskim, programistycznym świecie. Maciej Aniserowicz bardzo ciekawie opowiada o dobrych i złych stronach pracy programisty. Sporo uwagi poświęca początkującym programistom. Oprócz bloga, Maciej robi również:
  * [kanał devstyle.pl na YouTube](https://www.youtube.com/channel/UCACp5rqV3Ki0SNdXWDBLhRA)
  * [książka "Zawód programista"](http://zawodprogramista.pl/)
  * [devtalk.pl - podcast](http://devtalk.pl/)
  * [konkurs Daj Się Poznać](https://devstyle.pl/daj-sie-poznac/)

* [Medium - platforma blogowa - artykuły nt. Python](https://medium.com/search?q=python)
* [Planet Python - agragat blogów o tematyce Python](http://planetpython.org/)
* [Love Python](http://love-python.blogspot.com/)
