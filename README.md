# Hola C Challenge (2012-2014)

Thanks to all the participants of the Hola C challenge and congratulations to the winners ([see the winners list](#winners)) - winning a total of 82,000 USD. We are no longer accepting any new C challenge responses, but we may re-open this C challenge again in the future. 

## Guildlines:
* Look at `main()`: it calls various functions.
* You are asked to implement two functions: `str_cpy()` and `str_cat()`. No need to implement `str_printf()` and `str_free()` (Jungo employees: you are required to implement them).
* Reading `main()` carefully will allow to understand `str_cpy()` and `str_cat()` signature and usage.
* The code you write needs to be "library quality"; as good as you would expect a good libc to implement such functions.
* At the top of the page, you see 4 includes - indicating the functions that can be used to implement `str_cpy()` and `str_cat()`.
* You have 15 minutes to implement the whole solution.
* **FYI**: It is possible to implement `str_cpy()` and `str_cat()` efficiently in no more than 7 lines of code per function, and in less than 5 minutes.
* Every "perfect" solution wins 2000 USD. If not perfect - we will provide comments, and if "perfect"
 on 2nd try, you win 1000 USD.


```c
/* Copyright (C) Hola 2014
 *
 * Welcome to TheCodeIL.com Challenge!
 */
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <stdarg.h>

int main(int argc, char *argv[])
{
    char *s = NULL;
    str_cpy(&s, "Hola Hola");
    str_cpy(&s, s+5);
    str_cat(&s, " World");
    str_printf(&s, "%s!", s);
    puts(s); /* result: "Hola World!" */
    str_free(&s);
    return 0;
}
```



## <a name="winners"></a> Winners List
Are you one of the best C coders in the world?
The following people have submitted a "perfect" solution and received the prize (total prizes given 82,000 USD):

| Date | Name	| Home Town | Referred by |
| --- | --- | --- | --- |
| 21-Feb-2012 |	Bahaa A.	| Haifa	| -- |
| 1-Mar-2012 | Avner S.	| Ginot Shomron	| Dmitry V. |
| 4-Mar-2012 |	Igor L.	| Haifa	| Dmitry V. |
| 11-Mar-2012 |	George M.	| Jerusalem	| Michael S. |
| 19-Mar-2012	| S. L.	| Tel Aviv	| Igor L. |
| 20-Mar-2012	| Eyal B.	| Tel Aviv	| Igor L. |
| 21-Mar-2012	| Felix K.	| Nirit	| -- |
| 26-Mar-2012	| Zeev T.	| Petach Tikva	| Igor G. |
| 27-Mar-2012	| Costy B.	| --	| Yuri P. |
| 28-Mar-2012	| A. W.	| Tel Aviv	| -- |
| 29-Mar-2012	| Haggai E.	| Yokneam	| Ilia K. |
| 1-Apr-2012	| Shachar R.	| Haifa	| Ilia K. |
| 2-Apr-2012	| Adam K.	| Holon	| Pavel K. |
| 1-Apr-2012	| Ilia K.	| Haifa	| -- |
| 4-Apr-2012	| C. B.	| Or Yehuda	| Yuri P. |
| 8-Apr-2012	| A. Kaplan	| Holon	| Pavel K. |
| 8-Apr-2012	| Elazar L.	| Lod	| -- |
| 9-Apr-2012	| N. Elner	| Nesher	| -- |
| 10-Apr-2012	| Dmitry L.	| Or Yehuda	| Pavel K. |
| 11-Apr-2012	| Lev V.	| Kiryat Yam	| David M. |
| 16-Apr-2012	| Jonathan P.	| Bat-Yam	| A. W. |
| 16-Apr-2012	| Yaniv S.	| Lod	| N. Dayan |
| 18-Apr-2012	| Elad D.	| Tel Aviv	| Shlomo M. |
| 19-Apr-2012	| Dmitriy L.	| Ashdod	| -- |
| 29-Apr-2012	| Dror S.	| Petach Tikva	| Elad D. |
| 30-Apr-2012	| Yoni R.	| Tel Aviv	| -- |
| 30-Apr-2012	| Ziv S.	| Raanana	| -- |
| 6-May-2012	| Amit W.	| Kiryat Motzkin	| Eli T. |
| 8-May-2012	| Gil M.	| Rishon Letzion	| -- |
| 16-May-2012	| Koby W.	| Tel Aviv	| -- |
| 28-Jun-2012	| Opher L. | Kfar Saba	| -- |
| 1-Jul-2012	| Gil S.	| Haifa	| -- |
| 3-Jul-2012	| Avi K.	| Raanana	| Roni L. |
| 4-Jul-2012	| Kirill H.	| Haifa	| -- |
| 17-Jul-2012	| Roni L.	| Raanana	| -- |
| 19-Jul-2012	| Noam B.	| Kiryat Motzkin	| -- |
| 10-Sep-2012	| Dimitry R.	| Haifa	| -- |
| 28-Sep-2012	| Hagai B.	| Kfar Hachoresh	| -- |
| 9-Oct-2012	| Avishay T.	| Modiin	| Assaf A. |
| 25-Oct-2012	| Tomer G.	| Tel Aviv	| Hagai B. |
| 8-Nov-2012	| Yuval G.	| Tel Aviv	| -- |
| 26-Nov-2012	| Ben L.	| Rosh Haayin	| -- |
| 27-Nov-2012	| Gal R.	| Tel Aviv	| -- |
| 2-Dec-2012	| Sergey P.	| Petah Tiqwa	| -- |
| 11-Dec-2012	| Yannay L.	| Givat Shmuel	| Yuval G. |
| 23-Dec-2012	| Stas O.	| Tel Aviv	| Oleg B. |
| 1-Jan-2013	| Mikhail G.	| Norway	| -- |
| 13-Jan-2013	| Nachman S.	| Tzfat	| Menachem M. |
| 30-Jan-2013	| Slavik M.	| --	| Pesach G. |
| 25-Feb-2013	| Victor V.	| Netanya	| Vadim S. |
| 18-Mar-2013	| Lior K.	| Rishon	| Eli B. |
| 19-Mar-2013	| E. G.	| Tel Aviv	| Yigal S. |
| 20-Jul-2013	| Amit F.	| Hogla	| -- |
| 3-Oct-2013	| Victor I.	| Ukraine	| -- |
| 3-Oct-2013	| Alexey F.	| Norway	| -- |
| 20-Oct-2013	| Maxim I.	| Ireland	| -- |
| 21-Oct-2013	| Novikov D.	| Russia	| -- |
| 23-Oct-2013	| Roman B.	| Netanya	| Alexander G. |
| 24-Oct-2013	| Gregory S.	| Haifa	| -- |
| 11-Nov-2013	| Julien P.	| Norway	| Alexey F. |
| 11-Nov-2013	| Atis E.	| Latvija	| -- |
| 28-Nov-2013	| Konstantin M.	| Netanya	| -- |
| 9-Dec-2013	| Nikolay P.	| Ukraine	| -- |
| 24-Dec-2013	| Vadim D.	| Ukraine	| -- |
| 29-Dec-2013	| Egor P.	| Russia	| Andrey K. |
| 29-Dec-2013	| Dmitry B.	| Ukraine	| Olga K. |
| 27-Jan-2014	| Andrey Z.	| Russia	| -- |
| 2-Mar-2014	| Oren B.	| Poland	| Roman B. |
| 9-Mar-2014	| Ilya K.	| Russia	| -- |
| 23-Mar-2014	| Stanislav J.	| Bulgaria	| -- |

(If you're listed above and want us to publish your full name or to remove your name, email meytal@hola.org)
