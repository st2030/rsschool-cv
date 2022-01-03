# **Dmitriy Kisselev**
<p><img src="images/DVK.png" alt="Dmitriy Kisselev, Junior Programmer" title="Dmitriy Kisselev" height="11%" width="11%" align="left"></p>

## ***Contact Details:***
---
&nbsp;&nbsp;&nbsp;**Phone number:** +77054020797

&nbsp;&nbsp;&nbsp;**E-mail:** strateg2030@gmail.com

&nbsp;&nbsp;&nbsp;**Discord:** Dmitriy K.#6280

&nbsp;&nbsp;&nbsp;**Github:** [st2030](https://github.com/st2030/)

## ***About Me***
---
Successful technical translator with over 16 years of professional experience in the oil & gas industry, and with about 7 years of engineering experience as a QC engineer in construction projects, oil&gas production engineer, and oil field development supervisor in the same industry. Currently working as a freelance technical translator providing services for international oil and gas projects. Planning to relaunch my career in IT as a programmer. In process of pursuing the Bachelor of Computer Science degree at the University of the People. Being an intrinsically motivated person and having good critical thinking skills I am capable of quick learning and improving relevant skills to reach the assigned objectives and resolve work tasks within a limited time frame. My short-term goal is to re-start a career as a front-end developer. My long-term goal is to be involved as a programmer in Natural Languages Processing (NLP), Artificial Intelligence (AI), or Robotic Engineering projects.

## ***Skills***

- **Markup languages:** HTML5, CSS3, Markdown
- **Programming languages:** PHP, Python, Java, R
- **IDEs:** Intellij IDEA, Visual Studio Code
- **VCS:** Git

## ***Code Examples***
"**Sum of odd numbers**" task (kata) at CodeWars:

**Task description:**
```
Given the triangle of consecutive odd numbers:

             1
          3     5
       7     9    11
   13    15    17    19
21    23    25    27    29
...
Calculate the sum of the numbers in the nth row of this triangle (starting at index 1) e.g.: (Input --> Output)
1 -->  1
2 --> 3 + 5 = 8
```

**Task solution using PHP:**
```
function rowSumOddNumbers($n) {
    $num = 0;
    for ($i = $n; $i > 0; $i--) {
        $num += $i;
    }
    $sum = $num**2 - ($num - $n)**2;
    return $sum;
}
```

"**Boiled eggs**" task (kata) at CodeWars:

**Task description:** 
```
You are the greatest chef on earth. No one boils eggs like you! Your restaurant is always full of guests, who love your boiled eggs. But when there is a greater order of boiled eggs, you need some time, because you have only one pot for your job. How much time do you need?
Your Task

Implement a function, which takes a non-negative integer, representing the number of eggs to boil. It must return the time in minutes (integer), which it takes to have all the eggs boiled.
Rules

    you can put at most 8 eggs into the pot at once
    it takes 5 minutes to boil an egg
    we assume, that the water is boiling all the time (no time to heat up)
    for simplicity we also don't consider the time it takes to put eggs into the pot or get them out of it

Example (Input --> Output)
0 --> 0
5 --> 5
10 --> 10
```
**Task solution using PHP:**
```
function cooking_time(int $eggs): int {
   $cooking_time = 0;
   if ($eggs == 0) {
      return 0;
   }
   elseif ($eggs > 8) {
         $cook_main=intdiv($eggs, 8);
         if ($eggs % 8 > 0) {$cook_extra = 5;
         $cooking_time = $cook_main*5 + $cook_extra;}
         else $cooking_time = $cook_main*5;
         return $cooking_time;
      }
   else {
         $cooking_time = 5;
         return $cooking_time;
   }
}
```

## ***Work Experience***
*No relevant  IT experience as of today. Non-IT work experience is described below.*

| Periods  | Company, City - Job Title |
|--------|--------------------|
| April 2017 - till now  | Self-Employed as Freelance Technical Translator |
| November 2018 - May 2019 | Kaz Project Operating LLC, Almaty - Technical Translator  |
| May 2013 - March 2017 | Tethys Services Kazakhstan LLP (Branch of Tethys Petroleum Limited), Almaty - Oilfield Development Supervisor |
| April 2011 - May 2013 | Tethys Services Kazakhstan LLP (Branch of Tethys Petroleum Limited), Almaty - Assistant to Technical Director / Technical Translator/Interpreter |
| December 2010 - February 2011 | Moody International Kazakhstan, Almaty - Technical Translator (temporary replacing in-house translator) |
| August 2010 - December 2010 | Aker Process B.V. (branch of Aker Solutions Australia), Almaty - Technical Translator/Interpreter |
| August 2009 - May 2010 | Akmaral LLP, Aksai - Technical Translator/Interpreter / QC Engineer |
| April 2008 - June 2008 | Kazakh Institute of Oil and Gas Transportation LLP, LangFang (China) - Technical Translator (within integrated engineering team) |
| November 2006 - April 2008  |  Kazakh Institute of Oil and Gas Transportation LLP, Almaty - Technical Translator/Interpreter |
| March 2005 - April 2006 | KazGiproGaz LLP, Almaty - Technical Translator |
| June 2004 - March 2005 | IT Administrator (Linux/Windows) / Helpdesk / Web Developer (HTML4, XHTML1.0/1.1, CSS1/2, PHP4) |

## ***Education***

**University Education**
- 2020-2024 (expected) - [University of the People](https://www.uopeople.edu/), Major: Computer Science, Qualification (upon graduation): Bachelor of Computer Science
- 2012-2014 - [Satbayev University - previously known as Kazakh National Technical University](https://satbayev.university/en), Major: Petroleum Engineering, Specialization: Oil and Gas Fields Development and Operation, Qualification: Bachelor of Petroleum Engineering
- 1999-2004 - [Al-Farabi Kazakh National University](https://www.kaznu.kz/en), Major: Physics, Specialization: Thermal Physics, Qualifications: Physicist, Translator

**IT Courses**
- 2021 - [HTML Basics](https://ru.code-basics.com/languages/html) at Code Basics
- 2021 - [CSS Basic](https://ru.code-basics.com/languages/css) at Code Basics
- 2021-2022 - [RS School](https://rs.school/) (in progress)

