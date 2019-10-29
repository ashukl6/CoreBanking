all:executable
executable:main.o login.o employee.o generalmanager.o manager.o validation.o regionalmanager.o branchmanager.o bankemployee.o 
	gcc -L $(ORACLE_HOME)/lib/ -I $(ORACLE_HOME)/rdbms/public/  main.o login.o employee.o generalmanager.o manager.o validation.o regionalmanager.o branchmanager.o bankemployee.o -locci -lclntsh -o executable
main.o:main.cpp
	gcc -L $(ORACLE_HOME)/lib/ -I $(ORACLE_HOME)/rdbms/public/ -c main.cpp -locci -lclntsh -o main.o
login.o:login.cpp
	gcc -L $(ORACLE_HOME)/lib/ -I $(ORACLE_HOME)/rdbms/public/ -c login.cpp -locci -lclntsh -o login.o
employee.o:employee.cpp
	gcc -L $(ORACLE_HOME)/lib/ -I $(ORACLE_HOME)/rdbms/public/ -c employee.cpp -locci -lclntsh -o employee.o
generalmanager.o:generalmanager.cpp
	gcc -L $(ORACLE_HOME)/lib/ -I $(ORACLE_HOME)/rdbms/public/ -c generalmanager.cpp -locci -lclntsh -o generalmanager.o
manager.o:manager.cpp
	gcc -L $(ORACLE_HOME)/lib/ -I $(ORACLE_HOME)/rdbms/public/ -c manager.cpp -locci -lclntsh -o manager.o
validation.o:validation.cpp
	gcc -L $(ORACLE_HOME)/lib/ -I $(ORACLE_HOME)/rdbms/public/ -c validation.cpp -locci -lclntsh -o validation.o
regionalmanager.o:regionalmanager.cpp
	gcc -L $(ORACLE_HOME)/lib/ -I $(ORACLE_HOME)/rdbms/public/ -c regionalmanager.cpp -locci -lclntsh -o regionalmanager.o
branchmanager.o:branchmanager.cpp
	gcc -L $(ORACLE_HOME)/lib/ -I $(ORACLE_HOME)/rdbms/public/ -c branchmanager.cpp -locci -lclntsh -o branchmanager.o
bankemployee.o:bankemployee.cpp
	gcc -L $(ORACLE_HOME)/lib/ -I $(ORACLE_HOME)/rdbms/public/ -c bankemployee.cpp -locci -lclntsh -o bankemployee.o


clean:
	rm -rf *o executable
