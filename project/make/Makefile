##############################################################################
#
#     LINGLKERNEL
#
#     Copyright (c) 2008 Rehno Lindeque. All rights reserved.
#
##############################################################################

USER_TOOL = g++

USER_BUILD_DIR  = ../../lib
USER_TARGET     = linglkernel.a
USER_MAKE_DIRS  = ../../../basekernel/project/make ../../../base/project/make
USER_LIB_DIRS   = 
USER_LIBS       = #libstdc++.a
USER_INCLUDE_DIRS = ../../../../api \
                    ../../../basekernel/src \
                    ../../../base/src
USER_DEFINITIONS =
USER_DEBUGFLAGS = -g -D_DEBUG -Wall

all: $(USER_TARGET)
		
#$(USER_TARGET):
#	$(USER_TOOL) ../../src/*.cpp -I $(USER_INCLUDE_DIRS) -o $@
		
$(USER_TARGET):
	$(USER_TOOL) ../../src/*.cpp $(addprefix -I,$(USER_INCLUDE_DIRS)) -o $@



