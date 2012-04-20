# *****************************************************************
# This file is part of ThunderAnt.

# ThunderAnt is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.

# ThunderAnt is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.

# You should have received a copy of the GNU General Public License
# along with ThunderAnt.  If not, see <http://www.gnu.org/licenses/>.

# *****************************************************************

objects = main.o rect_coord.o
cflags = -Wall -Wextra -O2 -lpng -lpari
#-lm

bh : $(objects)
	$(CC) $(cflags) -o bh $(objects)

main.o : main.c
	$(CC) $(cflags) -c main.c

rect_coord.o : rect_coord.c
	$(CC) $(cflags) -c rect_coord.c
