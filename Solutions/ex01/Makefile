# 															\
															\
Let's get started !											\
															\
- Faire en sorte de compiler le fichier main.c				\
															\
- Le Makefile doit avoir les règles standard d'Epitech:		\
all: Convertit les fichiers .c en .o et génère le binaire	\
clean: Supprime tout les fichiers .o						\
fclean: Supprime tout les fichiers .o ET le binaire			\
re: appelle la règle fclean et all

NAME	=	a.out

SRCS	=	main.c

OBJS	=	$(SRCS:.c=.o)

all: $(NAME)

$(NAME):	$(OBJS)
	$(CC)	-o	$(NAME)	$(OBJS)

clean:
	rm	-f	$(OBJS)

fclean:	clean
	rm	-f	$(NAME)

re:	fclean	all
