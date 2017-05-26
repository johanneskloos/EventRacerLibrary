SET(BUILD_SHARED_LIBS ON)
add_library(EventRacer ActionLog.cpp base.cpp BitClocks.cpp CallTraceBuilder.cpp config.cpp EventGraph.cpp EventGraphInfo.cpp GraphFix.cpp stringprintf.cpp StringSet.cpp ThreadMapping.cpp TimerGraph.cpp VarsInfo.cpp)
INSTALL(TARGETS EventRacer LIBRARY DESTINATION lib)

