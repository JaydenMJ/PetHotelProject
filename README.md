# PetHotelProject
School-Based Project

This is a school Based Project for creating a website for Pet Hotel.

It uses google.colab.widgets,ipywidgetsfor tab page, cx_Oracle and sql for backend Database.
seaborn,matplotlib.pyplot for data vitualising.
We set up the database from scratch. And use conn.cursor to execute sql statements to insert and amend db data.


dsn_tns = cx_Oracle.makedsn(HOST_NAME, PORT_NUMBER, service_name=SERVICE_NAME) 
conn = cx_Oracle.connect(user=USERNAME, password=PASSWORD, dsn=dsn_tns) 
c = conn.cursor()


