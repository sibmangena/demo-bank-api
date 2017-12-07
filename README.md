Demo Bank
==========

Demo Online Bank application to test programming concepts, Angular and Rest web services

Webservices layer running in separate application on port 8080 and web layer built on Angular. Charting is based on D3.

Analytics layer will be based off data in an Apache Cassandra repository. Hadoop will keep some of the unstructured data for analytics. Spark will be used in the analytics engine piece.

The objects that are in this program are as follows:

Account
Customer
Merchant
User
Transactions
Role
Transfers
BalanceHistory
Products_and_services
customer_purchases
addresses

The demo schema can be found at databaseanswers.com. You could add more but the purpose of this application  is for demonstration of dependency injection, caching and performing limited Data Analytics.

The following functionality will be added as well:
  - Bill Pay
  - Transaction History lookup
  - Loader functions for migrations
  - Big Data analytics
  