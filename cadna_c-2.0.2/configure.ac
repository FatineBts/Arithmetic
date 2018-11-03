#                                               -*- Autoconf -*-	
# Process this file with autoconf to produce a configure script.

AC_PREREQ(2.59)
AC_INIT(CADNA_C, 2.0.2, cadna-team@lip6.fr)
AC_CONFIG_AUX_DIR(admin)

AC_CONFIG_HEADERS(config.h)
AM_INIT_AUTOMAKE([-Wall])

# debut JL
#AN_MAKEVAR([AR], [AC_PROG_AR])
#AN_PROGRAM([ar], [AC_PROG_AR])
#AC_DEFUN([AC_PROG_AR], [AC_CHECK_TOOL(AR, ar, :)])
# fin JL


# Checks for programs.
AC_PROG_CC
AC_PROG_CXX 
AM_PROG_AR
AM_PROG_AS

AC_PROG_INSTALL
AC_PROG_RANLIB
AC_PROG_MAKE_SET

dnl AX_CXX_COMPILE_STDCXX_11([noext])

AC_MSG_CHECKING([if 64bit support is requested])
AC_ARG_ENABLE(64bit,[  --enable-64bit          enable 64bit support (where applicable)],architecture="64",architecture="32")
AC_MSG_RESULT($architecture)

AC_MSG_CHECKING([if OpenMP support is requested])
AC_ARG_ENABLE(omp,[  --enable-omp          enable OpenMP support (where applicable)])
AC_MSG_RESULT($enable_omp)

AC_CHECK_HEADERS(math.h,,
[AC_MSG_ERROR([cannot find math.h])])

AC_CHECK_LIB(m, acos,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m, acosf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,acosh,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,acoshf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,asin,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,asinf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,asinh,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,asinhf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,atan,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,atan2,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,atan2f,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,atanf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,atanh,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,atanhf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,cbrt,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,cbrtf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,cos,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,cosf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,cosh,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,coshf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,exp,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,exp2,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,exp2f,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,expf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,expm1,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,expm1f,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,fmax,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,fmaxf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,fmin,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,fminf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,hypot,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,hypotf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,log,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,log10,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,log10f,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,log1p,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,log1pf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,log2,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,log2f,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,logb,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,logbf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,logf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,pow,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,powf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,sin,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,sinf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,sinh,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,sinhf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,sqrt,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,sqrtf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,tan,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,tanf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,tanh,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,tanhf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,tanf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,tanh,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,tanhf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (powf, cosf, expf, ....)))
AC_CHECK_LIB(m,frexp,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,frexpf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (frexpf, ....)))
AC_CHECK_LIB(m,ldexp,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,ldexpf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (ldexpf, ....)))
AC_CHECK_LIB(m,fmod,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,fmodf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (fmodf, ....)))
AC_CHECK_LIB(m,modf,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm))
AC_CHECK_LIB(m,modff,AC_MSG_RESULT([]),AC_MSG_ERROR(You need libm with functions on float (fmodf, ....)))



AC_CONFIG_FILES([
	Makefile
	src/Makefile
	examples/Makefile
	])


AC_CANONICAL_HOST

__cadna_compiler_problem=1	

CFLAGS="$CFLAGS -g -Wall -O3"			

case "$CXX" in
     	*g++*  )
  	CXXFLAGS="-g -Wall -O3 -I${includedir} -frounding-math"
  	CADNA_MATH_FILE=src/cadna_math_gnu.cc 
  	;;
	*icpc* | *icc* )
  	CXXFLAGS="-fp-model strict -fp-model no-except  -I${includedir} "
#  	CADNA_MATH_FILE=src/cadna_math_other.cc
	CADNA_MATH_FILE=src/cadna_math_gnu.cc 
  	;;

	*xlC* | *xlc*  )
#  	CXXFLAGS="-I. -q64 -qlanglvl=extended0x  -I${includedir} "	
  	CXXFLAGS="-I. -qstrict=ieeefp -qfloat=rrm -O3 -I${includedir} "	
#  	 CADNA_MATH_FILE=src/cadna_math_other.cc
  	 CADNA_MATH_FILE=src/cadna_math_gnu.cc
  	 ;;
	*  )
	   AC_MSG_ERROR([Configuration script supports only gcc, icpc, xlc.])
	  ;;
esac


AC_LANG_PUSH([C++])
AC_MSG_CHECKING([$CXX ... ])
AC_RUN_IFELSE(
        [AC_LANG_PROGRAM(
                [[]],
                [[
                       return 0;
                ]])],
              [
               AC_MSG_RESULT(OK)
               AM_CFLAGS="$CFLAGS"
              ],
              [AC_MSG_FAILURE(NO)])
AC_LANG_POP



echo "configure.ac $host $CXX $__cadna_compiler_problem"


CFLAGS="-g -Wall -O3"
LIBS="$LDFLAGS -lm" 
LDFLAGSCADNA="-L${libdir} -lcadnaC $LDFLAGS " 

AC_SUBST(LDFLAGSCADNA)


AS_IF([test "$enable_omp" = "yes"], [
   CXXFLAGS="$CXXFLAGS -fopenmp"
])

AC_CONFIG_LINKS([src/cadna_math.cc:$CADNA_MATH_FILE])

AC_OUTPUT
