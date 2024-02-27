# Railway-Booking-System
1.The code defines two classes: Main and Passenger.
2.Main class contains the main method to run the program and manage ticket booking and cancellation.
3.Passenger class encapsulates passenger details like name, age, berth preference, assigned berth, and passenger ID.
4.The TicketBooker class handles ticket booking, cancellation, and maintains available seats and passenger records.
5.Available seats are divided into lower, middle, and upper berths, along with RAC (Reservation Against Cancellation) and waiting list slots.
6.The program allows users to book tickets, cancel tickets, view available tickets, view booked tickets, and exit the program.
7.Users input their details for ticket booking: name, age, and berth preference (L, M, or U).
8.Bookings are made based on berth preference and availability, with fallbacks to RAC and waiting list if necessary.
9.Canceling a ticket involves removing the passenger from records and making their seat available again.
10.If a canceled ticket frees up a RAC slot, the system automatically promotes a waiting list passenger to RAC and tries to book their ticket.
11.The program keeps track of available seats and passenger records using collections like queues, lists, and maps.
12.It ensures the integrity of bookings by handling cases of RAC and waiting list passengers.
13.The code utilizes static variables for tracking seat availability across instances of the TicketBooker class.
14.Methods in the TicketBooker class manage the booking process by assigning seats, updating availability, and handling cancellations efficiently.
15.The program provides clear feedback messages for successful bookings, cancellations, and seat availability.
