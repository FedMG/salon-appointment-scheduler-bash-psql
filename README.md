# Salon Database & Salon Appointment Scheduler Bash Project

This project has a PostgreSQL database for a salon. Additionally, a Bash script query or inserts new customers whether exists or not, give new appointments and display differents services.

## Database Tables

![Alt text](/public/salon-tables.webp)

### Appointments Table

![Alt text](/public/appointments.webp)


### Services Table

![Alt text](/public/services.webp)


### Customers Table

![Alt text](/public/customers.webp)


## Bash Script

The Bash script interacts with the salon database and performs various tasks such as adding appointments according to the user data, query user data, displaying services, and updating customer information. Here is the commands and its output:<br>

- Enter `./salon.sh` command in the bash terminal to run the script and interacts with the SalonDB.
It adds a new appointment and register you as a new customer (if you are not registered) to the database.

#### Part 1
![Alt text](/public/salon-result-1.webp)

#### Part 2

![Alt text](/public/salon-result-2.webp)

There are more features beyond the scope of this readme.

## Conclusion

This salon database project demonstrates the use of PostgreSQL for storing and managing salon data. Also, the hability to relate differents table using efficients JOIN.
