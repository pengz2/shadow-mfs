sbin_PROGRAMS=mfsmaster

AM_CPPFLAGS=-lpthread -std=c99 -I$(top_srcdir)/mfscommon -DAPPNAME=mfsmaster
AM_LDFLAGS=-lpthread $(PTHREAD_LIBS) $(ZLIB_LIBS)

mfsmaster_SOURCES=\
	acl.h acl.c \
	changelog.c changelog.h \
	chunks.c chunks.h \
	filesystem.c filesystem.h \
	matocsserv.c matocsserv.h \
	matocuserv.c matocuserv.h \
	matomlserv.c matomlserv.h \
	random.c random.h \
	datacachemgr.c datacachemgr.h \
	chartsdata.c chartsdata.h \
	nettopology.c nettopology.h \
	masterconn.c masterconn.h \
	matoslaserv.c matoslaserv.h \
	replay.c replay.h \
	state.c state.h \
	init.h \
	../mfscommon/main.c ../mfscommon/main.h \
	../mfscommon/cfg.c ../mfscommon/cfg.h \
	../mfscommon/md5.c ../mfscommon/md5.h \
	../mfscommon/crc.c ../mfscommon/crc.h \
	../mfscommon/sockets.c ../mfscommon/sockets.h \
	../mfscommon/charts.c ../mfscommon/charts.h \
	../mfscommon/datapack.h \
	../mfscommon/MFSCommunication.h
