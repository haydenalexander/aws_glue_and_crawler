# aws_glue_and_crawler

Made a web crawler via AWS, took the contents of the customers.csv, grabbed the orders.csv, and managed to pick up the entire schema which stopped us from manual entry as AWS did the rest in indentifying their data types (int,string).
Used for large datasets.

![image](https://github.com/user-attachments/assets/bce189ff-4481-4ecc-a0d0-cd4a8b1c641e)


ELT Job:

Take the data, add a timetamp, transform it to parque, save it to S3, create a data glue table called customers process, create a partion key for proessed_timestamp

![image](https://github.com/user-attachments/assets/92e246a0-6fea-4dd0-8f9e-040086501f5e)

GOT IT!

![image](https://github.com/user-attachments/assets/4d0299a9-6429-4226-9143-2dd9aa6248e0)

Other exampels ive done, removing additional fields that are not needed for Tableau. 
Dropping Null Fields
Dropping Duplicates
