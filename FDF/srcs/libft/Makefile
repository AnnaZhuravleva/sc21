# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: tkelsie <tkelsie@student.42.fr>            +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/04/07 17:58:25 by tkelsie           #+#    #+#              #
#    Updated: 2019/07/27 13:08:02 by tkelsie          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a
FILES = ./ft_atoi.c \
./ft_bzero.c \
./ft_isalnum.c \
./ft_isalpha.c \
./ft_isascii.c \
./ft_isdigit.c \
./ft_isprint.c \
./ft_itoa.c \
./ft_memalloc.c \
./ft_memccpy.c \
./ft_memchr.c \
./ft_memcmp.c \
./ft_memcpy.c \
./ft_memdel.c \
./ft_memmove.c \
./ft_memset.c \
./ft_putchar_fd.c \
./ft_putchar.c \
./ft_putendl_fd.c \
./ft_putendl.c \
./ft_putnbr_fd.c \
./ft_putnbr.c \
./ft_putstr_fd.c \
./ft_putstr.c \
./ft_strcat.c \
./ft_strchr.c \
./ft_strclr.c \
./ft_strcmp.c \
./ft_strcpy.c \
./ft_strdel.c \
./ft_strdup.c \
./ft_strequ.c \
./ft_striter.c \
./ft_striteri.c \
./ft_strjoin.c \
./ft_strlcat.c \
./ft_strlen.c \
./ft_strmap.c \
./ft_strmapi.c \
./ft_strncat.c \
./ft_strncmp.c \
./ft_strncpy.c \
./ft_strnequ.c \
./ft_strnew.c \
./ft_strnstr.c \
./ft_strrchr.c \
./ft_strsplit.c \
./ft_strstr.c \
./ft_strsub.c \
./ft_strtrim.c \
./ft_tolower.c \
./ft_toupper.c \
./ft_lstnew.c \
./ft_lstdelone.c \
./ft_lstdel.c \
./ft_lstadd.c \
./ft_lstiter.c \
./ft_lstmap.c \
./ft_lstsize.c \
./ft_lst_push_front.c \
./ft_lst_push_back.c \
./ft_lst_reverse.c \
./ft_max.c \
./ft_maxsingle.c \
./ft_counter.c \
./get_next_line.c \
./ft_abs.c \
./ft_equals.c \
./ft_ncounter.c \
./ft_atoi_base.c \
./ft_pow.c \
./ft_arrlen.c \

OFILES			= $(FILES:./%.c= %.o)

$(NAME): $(OFILES)
	gcc -Wall -Wextra -Werror -c $(FILES) -I/./libft.h
	ar rc $(NAME) $(OFILES)
	ranlib $(NAME)

all: $(NAME)

clean:
	rm -f $(OFILES)

fclean: clean
	rm -f $(NAME)

re: fclean all
