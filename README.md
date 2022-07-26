# cloud-database-services
Comparison of free cloud services

## Microsoft Azure free account
If you’re a new Azure customer, you can sign up for a free account. This includes a mixture of services — some free forever, some for the first year — including several cloud databases:

Azure Cosmos DB, a NoSQL database. You get 5GB of storage and 1,000 request units per second.
Azure Database for MySQL and for PostgreSQL. You get a year of use with up to 32GB of storage.
Azure SQL Database, which uses Microsoft’s SQL Server database engine. You get a year of use.
A free Azure account also comes with a $200 credit to spend in the first 30 days, which you could use to pay for a database if you only need it for a short period.

If you start with an Azure free account, you have to explicitly opt-in to a paid account, so there’s no risk of surprise charges. You have to opt in to a paid account after 30 days; after that, your services stop working and data is deleted. If you do go for the paid solution, you can set up a spending limit to keep your bill manageable.

Who it’s for: This is a good choice if you want to learn how to use Azure.

## Google Cloud Free Tier
If you’re a new Google Cloud customer, you can sign up for a free trial. This includes a $300 credit to spend in the first 90 days, which you could use to run a short-lived database.

You have to upgrade to a paid account after 90 days or when your credits run out; after that, your data is deleted. There’s no way to enforce a hard spending limit if you upgrade, so be careful about what you spin up — this could leave you with an unexpected bill.

The Google Cloud Free Tier includes 1GB of storage with Cloud Firestore, a NoSQL document database.

Who it’s for: I’d consider this if I wanted to get some experience with Google Cloud in particular. Otherwise, the risk of an unexpected bill from a paid account would cause me to look elsewhere.

## Not recommended: AWS Free Tier
You may be surprised that I haven’t mentioned the AWS Free Tier, even though it features no less than six database offerings, including DynamoDB and RDS. (Route 53 isn’t available in the Free Tier because it’s too valuable to give away.)

I’ve avoided mentioning it because the AWS Free Tier is free in name only.

The problems with the AWS Free Tier are numerous and well-documented. It’s easy to run up an unexpected bill, even for experienced cloud engineers. The “Free” databases all come with soft limits that you can accidentally exceed, and you only get a warning that you’ve spent money after the fact.

There are lots of good choices for a free cloud database, but AWS ain’t one of them.
