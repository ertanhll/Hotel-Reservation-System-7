Below, you can find the description of your seventh assignment, which also
includes its output in the Application Walkthrough section.
In this assignment, you are expected to improve your existing Hotel
Reservation System by incorporating an interface.
Fig.1 Calculable interface hierarchy
This assignment introduces a new structure for calculating the finances of the
hotel. As you are already keeping track of the income using the Services, you
now need to keep track of the expenses too. This would be achieved by the use
of two new classes, namely Bills and Employees. These classes need to be
polymorphically connected to the Calculable interface, which is another new
Java structure you need to implement (see Fig.1). Furthermore, you need to 
utilize a new list for the Calculable interface and keep the relevant information
for calculating the revenue of the hotel in this list.
When the application starts, it should prompt the user with the following
menu:
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an Employee
8. Add a Bill
9. Get Monthly Balance
10. Exit
On top of the existing options implemented as part of the previous assignment,
this one introduces 3 more menu items, whose functionality is described below.
When the user selects the 7th option, the system should ask the user for the
employee’s name and surname variables, as well as the ID of the employee and
their monthly payments and create a new Employee with the respective
information. As the employee will receive their wage every month, you do not
need to specify the month they have been hired.
When the user selects the 8th option, the system should inquire the user about
the type of the Bill that is going to be paid (water, electricity etc…), as well as
the amount of the bill. On the contrary to Employees, the bills should be
handled on a monthly basis - i.e. every month’s utility bill should be added to
the system separately.
When the user selects the 9th option, the system should ask the user for a
month to calculate the general balance of the hotel for that particular month.
For this calculation, you need to separate incomes and expenses. In this case,
incomes of the hotel are Reservations and Extra Services, while the
expenditures include Bills and Employees. You need to iterate through the
Calculable list, display the monthly income, bills due, employee payments and
show the total balance of the hotel by subtracting the expenditures from the
overall revenue. If the hotel is making a profit, the end of month balance must
be positive, whereas if the hotel is losing money, the end of month balance
should be negative. 
Application Walkthrough
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
1
ROOM INFOS:
Room Type: Single, Daily Cost: 100, Room Size: 15, Has Bath: false
Room Type: Double, Daily Cost: 180, Room Size: 30, Has Bath: false
Room Type: Club, Daily Cost: 250, Room Size: 45, Has Bath: true
Room Type: Family, Daily Cost: 400, Room Size: 50, Has Bath: false
Room Type: Family With View, Daily Cost: 450, Room Size: 50, Has Bath: true
Room Type: Suite, Daily Cost: 650, Room Size: 80, Has Bath: true
Hotel Name: Hilton Istanbul
Room Type: Family
Reservation Month: April
Reservation Start: 2
Reservation End: 12
Reservation ID: 1 is created!
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
1
ROOM INFOS:
Room Type: Single, Daily Cost: 100, Room Size: 15, Has Bath: false
Room Type: Double, Daily Cost: 180, Room Size: 30, Has Bath: false
Room Type: Club, Daily Cost: 250, Room Size: 45, Has Bath: true
Room Type: Family, Daily Cost: 400, Room Size: 50, Has Bath: false
Room Type: Family With View, Daily Cost: 450, Room Size: 50, Has Bath: true
Room Type: Suite, Daily Cost: 650, Room Size: 80, Has Bath: true
Hotel Name: Ramada Bursa
Room Type: Double
Reservation Month: May
Reservation Start: 13
Reservation End: 17
Reservation ID: 2 is created!
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
4
Please select one of the extra services from below:
1. Laundry Service
2. Spa Service
1
Type the reservation ID to credit this service:
1
How many pieces of clothing?
3
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
4
Please select one of the extra services from below:
1. Laundry Service
2. Spa Service
2
Type the reservation ID to credit this service:
1
How many days?
3
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
4
Please select one of the extra services from below:
1. Laundry Service
2. Spa Service
1
Type the reservation ID to credit this service:
2
How many pieces of clothing?
5
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
7
Name:
Bill
Surname:
Gates
ID:
123
Monthly Payment:
250
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
7
Name:
Steve
Surname:
Jobs
ID:
234
Monthly Payment:
280
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
8
Type:
Water
Amount
210
Month:
April
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
8
Type:
Electricity
Amount
380
Month:
April
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
8
Type:
Water
Amount
330
Month:
May
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
9
Enter Month:
April
For reservation ID: 1, Service type: Room booking, Service Cost: 4000.00
For reservation ID: 1, Service type: Room booking, Service Cost: 720.00
For reservation ID: 1, Service type: Laundry, Service Cost: 60.00
For reservation ID: 1, Service type: Spa, Service Cost: 300.00
For reservation ID: 1, Service type: Laundry, Service Cost: 100.00
Total monthly income: 5180.00
Total monthly bills due: 590.00
Total monthly employee cost: 530.00
End of month balance: 4060.00
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
9
Enter Month:
May
For reservation ID: 2, Service type: Room booking, Service Cost: 4000.00
For reservation ID: 2, Service type: Room booking, Service Cost: 720.00
For reservation ID: 2, Service type: Laundry, Service Cost: 60.00
For reservation ID: 2, Service type: Spa, Service Cost: 300.00
For reservation ID: 2, Service type: Laundry, Service Cost: 100.00
Total monthly income: 5180.00
Total monthly bills due: 330.00
Total monthly employee cost: 530.00
End of month balance: 4320.00
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. Exit
10
Exiting, Goodbye!


