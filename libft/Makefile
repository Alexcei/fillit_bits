# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: bpole <marvin@42.fr>                       +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/09/07 12:11:32 by bpole             #+#    #+#              #
#    Updated: 2019/09/26 17:24:06 by bpole            ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SRC = ft_strlen.c \
	  ft_isdigit.c \
	  ft_isspace.c \
	  ft_atoi.c \
	  ft_isalpha.c \
	  ft_strcmp.c \
	  ft_strncmp.c \
	  ft_strcpy.c \
	  ft_strncpy.c \
	  ft_strdup.c \
	  ft_memset.c \
	  ft_bzero.c \
	  ft_memcpy.c \
	  ft_memmove.c \
	  ft_memccpy.c \
	  ft_memchr.c \
	  ft_memcmp.c \
	  ft_toupper.c \
	  ft_tolower.c \
	  ft_isalnum.c \
	  ft_isascii.c \
	  ft_isprint.c \
	  ft_strcat.c \
	  ft_strncat.c \
	  ft_strnlen.c \
	  ft_strlcat.c \
	  ft_strchr.c \
	  ft_strrchr.c \
	  ft_strstr.c \
	  ft_strnstr.c \
	  ft_memalloc.c \
	  ft_memdel.c \
	  ft_strnew.c \
	  ft_strdel.c \
	  ft_strclr.c \
	  ft_striter.c \
	  ft_striteri.c \
	  ft_strequ.c \
	  ft_strnequ.c \
	  ft_putchar.c \
	  ft_putstr.c \
	  ft_putendl.c \
	  ft_putnbr.c \
	  ft_putchar_fd.c \
	  ft_putstr_fd.c \
	  ft_putendl_fd.c \
	  ft_putnbr_fd.c \
	  ft_strmap.c \
	  ft_strmapi.c \
	  ft_strsub.c \
	  ft_strjoin.c \
	  ft_isblank.c \
	  ft_strtrim.c \
	  ft_itoa.c \
	  ft_intlen.c \
	  ft_strsplit.c \
	  ft_lstnew.c \
	  ft_lstdel.c \
	  ft_lstadd.c \
	  ft_lstdelone.c \
	  ft_lstmap.c \
	  ft_lstiter.c \
	  ft_list_reverse.c \

OBJ = $(SRC:.c=.o)

FLAGS = -Wall -Wextra -Werror

HEAD = libft.h

all: $(NAME)

$(NAME): $(OBJ)
	ar rc $(NAME) $(OBJ)
	ranlib $(NAME)

%.o: %.c
	gcc $(FLAGS) -I $(HEAD) -c $<

clean:
	rm -rf $(OBJ)

fclean: clean
	rm -rf $(NAME)

re: fclean all
