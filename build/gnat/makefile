TOP		=	../..
SRC		=	$(TOP)/src
DOC_SRC		=	$(TOP)/doc

GEN		=	gen
DOC_GEN		=	$(GEN)/doc

DESTDIR		?=	/opt

GPRBUILD	=	gprbuild
GPRINSTALL	=	gprinstall
GPRCLEAN	=	gprclean
INSTALL		=	install
CAT		=	cat

#########################################################################################################################

all: spirv.gpr

.PHONY: spirv.gpr

# Add lib targets here.
spirv.gpr:
	$(GPRBUILD) -p -XSPIRV_MODE=$(SPIRV_MODE) -Pspirv.gpr

# Add clean lib targets here

.PHONY: clean

clean:
	$(GPRCLEAN) -Pspirv.gpr

#########################################################################################################################

.PHONY: todo

todo:
	grep -riw --color TODO $(SRC)

