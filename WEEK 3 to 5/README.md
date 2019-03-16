# week 3 to 5 `CH06`
----------------
`int maximum(int x, int y);`  //function prototype

-----------------------------
### `<cstdlib>` //rand function

> srand(static\_cast\<unsigned int\>(time(0))

> srand(unsigned (time(NULL));

> srand(seed) //從seed開始跑

### `<ctime>` //time function

## *fig6.9*
--------------------
### global/block scope

`int num{7}; //global`

`{int num{8}; //block`

`    cout << num; //8`

`    cout << ::num; //7`

## *fig 6.22*

> `constructor(建構子)\<---\>discontructor(解構子)`
-----------------
### `#ifndef` *if not defined(若未執行過，則...)*
### `#endif`
-------------------

### setfill(0) //使數字空白部分都補0

### setw(n) //使後面數字為n位數

`int n=2, m=10;`

`cout << setw(2) << n << endl`

`cout << m << endl;`

`output:`

` 2`

`10`
--------------------------
### \<stdexcept\> //例外情況(ex. invalid\_argument is in it)

* 測試: try
* 抓出: 
`catch (invalid\_argument &e) //將訊息存到e中
 cout << e.what();`

> 若錯誤會throw exception
         
