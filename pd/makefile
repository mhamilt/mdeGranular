# Makefile to build class 'mdeGranular' for Pure Data.
# Needs Makefile.pdlibbuilder as helper makefile for platform-dependent build
# settings and rules.

# library name
lib.name = mdeGranular~

cflags = -Wno-undefined-inline

common.sources = ../src/mdeGranular~.c
# lib.setup.sources = ../src/mdeGranular~.c

# input source file (class name == source file basename)
mdegranular~.class.sources = ../src/mdeGranular~pd.c

# all extra files to be included in binary distribution of the library
datafiles =

PDLIBDIR = ../pd
# include Makefile.pdlibbuilder from submodule directory 'pd-lib-builder'
PDLIBBUILDER_DIR = ./pd-lib-builder
include $(PDLIBBUILDER_DIR)/Makefile.pdlibbuilder
