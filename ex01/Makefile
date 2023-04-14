# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: zanejar <zanejar@student.1337.ma>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/04/14 00:57:48 by zanejar           #+#    #+#              #
#    Updated: 2023/04/14 00:57:49 by zanejar          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = Fixed
CPP = c++
CPPFLAGS = -Wall -Wextra -Werror
SOURCE = Fixed.cpp main.cpp 
RM = rm -rf
OBJ = $(SOURCE:.cpp=.o)
HEADER = Fixed.hpp

all: 		$(NAME)

$(NAME):	$(OBJ) $(HEADER)
			$(CPP) $(CPPFLAGS) $(OBJ) -o $(NAME)

clean:
		$(RM) $(OBJ)

fclean: clean
		$(RM) $(NAME)

re: fclean all
.PHONY: all clean fclean re