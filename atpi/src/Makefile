CXX=g++
CXXFLAGS=-std=c++17 -Wall -g3 -I /usr/local/include/boost_1_71_0
LDFLAGS=-lpqxx -lpq -lboost_serialization -pthread

AUX_OBJS=Atpi.o AuxFunctions.o

MAIN_OBJS=$(AUX_OBJS) main.o

PROGS=main

all:	$(PROGS)

main:	$(MAIN_OBJS)
						$(CXX) $(CXXFLAGS) -o $@ $(MAIN_OBJS) $(LDFLAGS)
