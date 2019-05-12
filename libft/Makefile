# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: elfetoua <elfetoua@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/03/31 18:37:47 by elfetoua          #+#    #+#              #
#    Updated: 2019/04/18 11:34:49 by elfetoua         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a
OUT = ft_*.o


all: $(NAME)

$(NAME):
	@gcc -Wall -Wextra -Werror -c ft_*.c 
	@ar rc $(NAME) $(OUT)
	@ranlib $(NAME)

clean:
	@/bin/rm -f $(OUT)

fclean:	clean
	@/bin/rm -f $(NAME)

re: fclean all
