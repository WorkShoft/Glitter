# OBJS specifies which files to compile as part of the project
OBJS = texture.cpp

# CC specifies which compiler we're using
CC = g++ glad.c -I. -std=c++11

# COMPILER_FLAGS specifies the additional compilation options we're using
# -Wall will turn on all standard warnings
COMPILER_FLAGS = -Wall

# LINKER_FLAGS specifies the libraries we're linking against
LINKER_FLAGS = -lglfw3 -lGL -lX11 -lpthread -lXrandr -lXi -ldl -lXxf86vm -lXinerama -lXcursor -lGLU -lGL -lglut 

# OBJ_NAME specifies the name of our exectuable
OBJ_NAME = texture

#This is the target that compiles our executable
all: $(OBJS)
	$(CC) $(OBJS) $(COMPILER_FLAGS) $(LINKER_FLAGS) -o $(OBJ_NAME)

