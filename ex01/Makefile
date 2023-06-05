NAME = ScavTrap

CC = c++
FLAGS = -Wall -Werror -Wextra -std=c++98
RM = rm -rf

SRCS = ClapTrap.cpp main.cpp ScavTrap.cpp
OBJS = $(SRCS:.cpp=.o)

all: $(NAME)

$(NAME): $(OBJS)
		$(CC) $(FLAGS) $(OBJS) -o $(NAME)

clean:
		$(RM) *.o

fclean: clean
	$(RM) $(NAME)

re: fclean all

.PHONY: all clean fclean re
