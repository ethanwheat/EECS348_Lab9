# Set the base image to use
FROM gcc:latest 
# Copy the C program into the container
COPY football.h .
COPY football.c .
COPY ScorePossibilities.c .
# Compile the C program
RUN gcc -o ScorePossibilities ScorePossibilities.c football.c football.h
# Set the command to run when the container starts
CMD ["./ScorePossibilities"]
