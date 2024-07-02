# SQLPractice-11

1. actor ve customer tablolarında bulunan first_name 
   sütunları için tüm verileri sıralayalım.
   
* ( 
*	SELECT first_name AS 
*	"ACTOR NAME" FROM actor
*	ORDER BY first_name ASC
* )
* UNION
* (
*	SELECT first_name AS 
*	"CUSTOMER NAME" FROM customer
*	ORDER BY first_name ASC
* );
  

2. actor ve customer tablolarında bulunan first_name 
   sütunları için kesişen verileri sıralayalım.
   
* ( 
*	SELECT first_name AS 
*	"ACTOR NAME" FROM actor
*	ORDER BY first_name ASC
* )
* INTERSECT
* (
*	SELECT first_name AS 
*	"CUSTOMER NAME" FROM customer
*	ORDER BY first_name ASC
* );

3. actor ve customer tablolarında bulunan first_name 
   sütunları için ilk tabloda bulunan ancak ikinci tabloda 
   bulunmayan verileri sıralayalım.

* ( 
*	SELECT first_name AS 
*	"ACTOR NAME" FROM actor
*	ORDER BY first_name ASC
* )
* EXCEPT
* (
*	SELECT first_name AS 
*	"CUSTOMER NAME" FROM customer
*	ORDER BY first_name ASC
* );

4. İlk 3 sorguyu tekrar eden veriler için de yapalım.
      1. 
        * ( 
        *	SELECT first_name AS 
        *	"ACTOR NAME" FROM actor
        *	ORDER BY first_name ASC
        * )
        * UNION ALL
        * (
        *	SELECT first_name AS 
        *	"CUSTOMER NAME" FROM customer
        *	ORDER BY first_name ASC
        * );

      2. 
       * ( 
       *	SELECT first_name AS 
       *	"ACTOR NAME" FROM actor
       *	ORDER BY first_name ASC
       * )
       * INTERSECT ALL
       * (
       *	SELECT first_name AS 
       *	"CUSTOMER NAME" FROM customer
       *	ORDER BY first_name ASC
       * );  
  
      3. 
       * ( 
       *	SELECT first_name AS 
       *	"ACTOR NAME" FROM actor
       *	ORDER BY first_name ASC
       * )
       * EXCEPT ALL
       * (
       *	SELECT first_name AS 
       *	"CUSTOMER NAME" FROM customer
       *	ORDER BY first_name ASC
       * );