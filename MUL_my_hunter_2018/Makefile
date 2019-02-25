##
## EPITECH PROJECT, 2017
## Makefile
## File description:
## M
##

SRC	=	./lib/my/my_convert_char_int.c \
		./lib/my/my_putchar.c \
		./lib/my/my_put_nbr.c \
		./lib/my/my_putstr.c \
		./lib/my/my_revstr.c \
		./lib/my/my_strlen.c \
		./lib/my/my_strlennbr.c \
		./lib/my/my_putnbr_base.c \
		./src/my_hunter.c \
		./src/menu/menu.c \
		./src/tools/destroy.c \
		./src/levels/duck/duck.c \
		./src/levels/dragon_ball/dragon_ball.c \
		./src/levels/hell/hell.c \
		./src/game_over/game_over.c \
		./src/levels/duck/move_rect_duck.c \
		./src/levels/dragon_ball/move_rect_goku.c \
		./src/levels/hell/move_rect_boss.c \
		./src/game_over/move_rect_dog.c \
		./src/levels/duck/duck_position.c \
		./src/levels/hell/boss_move.c \
		./src/create/create_clock.c \
		./src/create/create_music.c \
		./src/create/create_text.c \
		./src/create/start_window.c \
		./src/create/variables.c \
		./src/create/variables_lvl.c \
		./src/create/rect.c \
		./src/create/create_sprite.c \
		./src/menu/menu_display.c \
		./src/game_over/game_over_display.c \
		./src/levels/duck/duck_display.c \
		./src/tools/cursor.c \
		./src/levels/duck/duck_hitbox.c \
		./src/levels/duck/duck_params.c \
		./src/levels/dragon_ball/dragon_ball_params.c \
		./src/levels/dragon_ball/dragon_ball_display.c \
		./src/levels/dragon_ball/dragon_ball_hitbox.c \
		./src/levels/dragon_ball/shenron.c \
		./src/levels/hell/hell_display.c \
		./src/levels/hell/boss_hitbox.c \
		./src/levels/hell/hell_params.c \
		./src/tools/cursor_red.c \


OBJ	=	$(SRC:.c=.o)

NAME	=	my_hunter

FLAG	=	-W -Wall -Werror -Wextra

all:	$(NAME)

$(NAME):	$(OBJ)
	gcc $(SRC) -o $(NAME) -L -lmy -lcsfml-graphics -lcsfml-window -lcsfml-system -lcsfml-audio
	rm -f $(OBJ)
clean:
	rm -f $(OBJ)

fclean:	clean
	rm -f $(NAME)

re:	fclean all

#.PHONY
