# Databases-Project

The main purpose of this project was to build a web application that included import CSV files into the database and manage the visualization of the collected data.

The data came from Istituto Nazionale di Astrofisica. From those we have information about different celestial bodies (Stars and Filaments) from Spitzer and Herschel space telescope.

The documentation is composed by:
- The Entity-Relationship (ER) diagram
- Dictionary of data, business rules, class diagram and database's dump made on PostgresSQL.

The communication between application client and database was made using the JPA approach.

The Singleton pattern was implemented to make the connection with Persistence more efficient.
