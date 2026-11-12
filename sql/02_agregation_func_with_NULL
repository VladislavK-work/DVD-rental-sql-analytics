SELECT
COUNT(*) AS total_rental,
COUNT(return_date) AS returned_rentals,
COUNT(*) - COUNT(return_date) AS not_returned
FROM rental;

SELECT
SUM(val) AS sum_val,
AVG(val) AS avg_val,
COUNT(*) AS cnt_all,
COUNT(val) AS cnt_val
FROM (VALUES (10), (NULL::int), (20)) AS t(val);
