#-----------------------------------------------------------------------

MINIFE_TYPES =  \
        -DMINIFE_SCALAR=double   \
        -DMINIFE_LOCAL_ORDINAL=int      \
        -DMINIFE_GLOBAL_ORDINAL=int

MINIFE_MATRIX_TYPE = -DMINIFE_CSR_MATRIX
# MINIFE_MATRIX_TYPE = -DMINIFE_ELL_MATRIX

#-----------------------------------------------------------------------

CFLAGS = -O3 -g
CXXFLAGS = $(CFLAGS)

CPPFLAGS = -I. -I../utils -I../fem $(MINIFE_TYPES) $(MINIFE_MATRIX_TYPE) \

LDFLAGS=
LIBS=

CXX=./nvcc_wrapper
CC=gcc

#CXX=g++
#CC=gcc

include make_targets

