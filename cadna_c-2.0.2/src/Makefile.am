lib_LIBRARIES=libcadnaC.a

AM_CXXFLAGS= 
AM_CPPFLAGS=
AM_CFLAGS=

libcadnaC_a_SOURCES= \
cadna_intr.cc cadna_math.cc \
cadna_convert.cc \
cadna_type.cc \
cadna_complex.cc

EXTRA_libcadnaC_a_SOURCES = \
cadna_math_other.cc cadna_math_gnu.cc

libcadnaC_a_CXXFLAGS=$(FPFLAGS)

# -O3 -g -Wunused -frounding-math

include_HEADERS = \
cadna.h cadna_private.h \
cadna_add.h cadna_sub.h cadna_mul.h cadna_div.h \
cadna_eq.h cadna_ne.h \
cadna_ge.h cadna_gt.h cadna_le.h cadna_lt.h\
cadna_digitnumber.h cadna_computedzero.h cadna_numericalnoise.h \
cadna_unstab.h cadna_str.h cadna_to.h cadna_random.h
