AC_INIT

AC_ARG_WITH([target-board],
    AS_HELP_STRING([--with-target-board=BOARD], [Specify the target DejaGnu board]),
    [target_board="--target_board $withval"], [target_board=""])

AC_ARG_WITH([target-toolchain],
    AS_HELP_STRING([--with-target-toolchain=TOOLCHAIN], [Specify the target toolchain]),
    [target_toolchain="--target=$withval"], [target_toolchain=""])

AC_ARG_WITH([gcc-src],
    AS_HELP_STRING([--with-gcc-src=GCC_SRC], [Specify the gcc source directory]),
    [gcc_src="$withval"], [gcc_src=""])

AC_SUBST(target_board)
AC_SUBST(target_toolchain)
AC_SUBST(gcc_src)

AC_CONFIG_FILES([Makefile])
AC_OUTPUT

