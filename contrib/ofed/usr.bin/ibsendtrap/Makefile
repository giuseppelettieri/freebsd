# $FreeBSD$

.include "../Makefile.inc"
.PATH: ${DIAGPATH}/src ${DIAGPATH}/man

PROG=   ibsendtrap
SRCS=   ibsendtrap.c ibdiag_common.c
LDADD=	-libumad -libcommon -libmad
CFLAGS+= -I${DIAGPATH}/include
MAN=

WARNS?= 1

.include <bsd.prog.mk>
