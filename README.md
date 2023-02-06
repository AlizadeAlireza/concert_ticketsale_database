# concert_ticketsale_database
this is a concert ticket sale database that create it for my database lab.


# Introduction

This system is designed to sell concert tickets
After creating a user profile,
the user has the ability to log in and is allowed to perform activities such as buying tickets and viewing the information of concerts and bands available, as well as the venue and capacity, etc.
Our main focus in this environment is on the concert, which is our main nature, and what concert the ticket we buy is related to and by whom.
Also, all tickets have a price group.

# System Features
  -  Ordering tickets by the user for the desired number (available number), which can be identified and tracked by a unique identifier.
  -  Viewing information of various music groups and accessing information of various artists.
  -  Informing the user about different tickets available on different days of the week by defining the relationship between ticket and concert entities.
  -  Tracking the user by storing information such as name, phone and address in the system and assigning a unique ID to the user
  
# Entities

  -  Band of music
  -  Concert
  -  Artist
  -  Event Place
  -  Ticket
  -  User profile
  -  Music sense

# Description of entities

  ## Concert
  
   - The existence of a concert or music is the main nature of our project, which includes attributes such as the singer's name, ID, duration, etc.

  ## Event Place
  
   - Information about where this concert will be held, which includes features such as address, landline,  phone number and etc.
  
  ## Music sense
    
   - The concept of performing is a concert that wants to be performed at the venue, which is considered a weak entity for the concert. Because if there      is no concert, there will be no sense and it has no special identifier.
  
  ## Ticket
  
   - In order to go to a specific concert that will be held at a certain time and in a certain place, we have to prepare a ticket that is an independent      entity and has features such as the name of the ticket, ID and etc.
   
  ## Artist
    
   - It is an independent entity that shows the individual characteristics and skills of that artist (eg: musicianship).

  ## Band of music
   
   - The music group is a weak entity for the two strong entities of the artist and the concert, in which the name-the number of members and the musical      style of the group that are prepared to perform the concert are specified.
  
  ## User profile
  
   - User's personal information to enter to enter the site and allow access, which includes name, surname, national code and photo.

  ## purchase
  
   - For the payment of tickets, there is a connection between the profile and the ticket, which covers this problem, which makes it unique.
