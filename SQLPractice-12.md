# SQLPractice-12

1. film tablosunda film uzunluğu length sütununda 
   gösterilmektedir. Uzunluğu ortalama film uzunluğundan 
   fazla kaç tane film vardır?
   
* SELECT title, length FROM film
* WHERE length >
* ( 
* 	SELECT AVG(length) FROM film 
* ) 


2. film tablosunda en yüksek rental_rate değerine sahip 
   kaç tane film vardır?

* SELECT COUNT(rental_rate) FROM film
* WHERE rental_rate = 
* (
* 	SELECT MAX(rental_rate) FROM film 
* )

3. film tablosunda en düşük rental_rate ve en düşük replacement_cost 
   değerlerine sahip filmleri sıralayınız.
   
* SELECT title, rental_rate, replacement_cost
*  FROM film
* WHERE rental_rate = (
*    SELECT MIN(rental_rate)
*    FROM film
* )
* AND replacement_cost = (
*    SELECT MIN(replacement_cost)
*    FROM film
* );

4. payment tablosunda en fazla sayıda alışveriş yapan 
   müşterileri(customer) sıralayınız.

* SELECT customer_id, COUNT(*) AS num_payments
* FROM payment
* GROUP BY customer_id
* ORDER BY num_payments DESC;
