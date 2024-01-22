## select sum(tax) as tax,sum(salesAmount) as salesAmount ,sum(realAmount) as realAmount , date(timey) as datey, days from tblsales where date(timey) BETWEEN '2024-01-15' And '2024-01-24' GROUP BY date(timey) ASC;

```
select sum(tax) as tax,sum(salesAmount) as salesAmount ,sum(realAmount) as realAmount , date(timey) as datey, days from tblsales where date(timey) BETWEEN '2024-01-15' And '2024-01-24' GROUP BY date(timey) ASC;
```
