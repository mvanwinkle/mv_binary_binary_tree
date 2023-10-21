# .POSIX might be a good idea.
.POSIX:
AM_CFLAGS = -std=c99 -pedantic -D_POSIX_C_SOURCE=200809L -Wall -Wextra -I$(top_srcdir)/lib
AM_LDFLAGS = -L../lib

# This might be how to add CPP stuff
# AM_CPPFLAGS =  -pedantic -Wall -Wextra
# AM_CPPFLAGS+= -std=c++11

# This might be how to link against a library in this project which might
# not be available with pkgconfig yet.
AM_CFLAGS += -lmv-binary-binary-tree
# AM_LDFLAGS += -lsome_library

# AM_CFLAGS += -pthread
# AM_LDFLAGS += -lpthread

# === Programs ===

bin_PROGRAMS = mv-binary-binary-tree_runner
mv_binary_binary_tree_runner_SOURCES = \
	main.c

# Needed, as per:
# https://www.gnu.org/software/automake/manual/html_node/Objects-created-both-with-libtool-and-without.html
mv_binary_binary_tree_runner_CFLAGS = $(AM_CFLAGS)
# Included for completeness:
mv_binary_binary_tree_runner_LDFLAGS = $(AM_LDFLAGS)

# === End Programs ===

