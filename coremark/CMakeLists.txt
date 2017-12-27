set(COREMARK_SOURCES core_list_join.c core_main.c core_matrix.c core_state.c core_util.c core_portme.c)

add_application(coremark "${COREMARK_SOURCES}")