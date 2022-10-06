# Sales_Insights Data Analysis Project

### Instructions to setup mysql on your local computer
1. Follow step in this video to install mysql on your local computer https://www.youtube.com/watch?v=WuBcTJnIuz0o

2. SQL database dump is in sales_db.sql file above. Download sales_db.sql file to your local computer and import it as per instructions given in the tutorial video

### Data Analysis Using MySQL

1. Show all customer records
`SELECT * FROM CUSTOMERS;`
2. Show total number of customers
`SELECT COUNT(*) FROM CUSTOMERS;`
3. Show transactions for Delhi NCR market (market code for delhi ncr is Mark004)
`SELECT DISTINCT(PRODUCT_CODE) FROM TRANSACTIONS WHERE MARKET_CODE ='Mark004';`
