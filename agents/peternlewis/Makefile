#Makefile for basic_cpp
# Sample C++ Stratego AI
# UCC Programming Competition 2012 

CPP = g++ -Wall -pedantic -g
OBJ = peternlewis.o

BIN = peternlewis

$(BIN) : $(OBJ) 
	$(CPP) -o $(BIN) $(OBJ)

%.o : %.cpp %.h
	$(CPP) -c $<

clean :
	$(RM) $(BIN) $(OBJ) $(LINKOBJ)

#Cleans up all backup files
clean_full: 
	$(RM) $(BIN) $(OBJ) $(LINKOBJ)
	$(RM) *.*~
	$(RM) *~


