# These might be a good idea
.POSIX:
AM_CFLAGS = -std=c99 -pedantic -D_POSIX_C_SOURCE=200809L -Wall -Wextra
AM_LDFLAGS = 

# This might be how to add CPP stuff
# AM_CPPFLAGS =  -pedantic -Wall -Wextra
# AM_CPPFLAGS+= -std=c++11

# This might be how to link against things:
# AM_CFLAGS += -lmv-binary-binary-tree
# AM_LDFLAGS += -lsome_library


# === Libraries ===
# Libraries that are generated and to be installed by this:
pkgconfigdir = ${libdir}/pkgconfig
pkgconfig_DATA = mv-binary-binary-tree.pc

lib_LTLIBRARIES = libmv-binary-binary-tree.la

libmv_binary_binary_tree_la_SOURCES = \
	mv-binary-binary-tree.c \
	mv-binary-binary-tree.h

include_HEADERS = mv-binary-binary-tree.h

libmv_binary_binary_tree_la_LDFLAGS = -version-info 0:0:0

# === End Libraries ===
