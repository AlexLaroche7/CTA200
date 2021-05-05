# compiler:
CC = gcc

# compiler flags: 
CFLAGS  = -g -Wall

# the build target executable:
TARGET = executable

# object files to build:
OBJ = main.o average.o

all: $(TARGET)

$(TARGET): $(OBJ)
	$(CC) $(CFLAGS) -o $(TARGET) $(OBJ)