AUTOMAKE_OPTIONS = foreign subdir-objects

TESTS = \
    trace.sh

check_PROGRAMS = mil_analyze
mil_analyze_SOURCES = \
    Source/analyze.cpp

mil_analyze_CPPFLAGS = -I../../../../Source -I../../../../../ZenLib/Source

mil_analyze_LDFLAGS = ../libmediainfo.la
