# Created by: Daniel Walter <sahne@0x90.at>
# $FreeBSD$

PORTNAME=	bsdmoted
PORTVERSION=	0.4.0
CATEGORIES=	sysutils
MASTER_SITES=	SF

MAINTAINER=	sahne@0x90.at
COMMENT=	Use Wii remote as mouse

LICENSE=	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/LICENSE

BROKEN_powerpc64=	does not build: warning Make sure new member of socket address initialized
BROKEN_FreeBSD_11=	does not build (bluetooth changes in 11.x need to be handled)
BROKEN_FreeBSD_12=	does not build (bluetooth changes in 11.x need to be handled)
DEPRECATED=	does not build on FreeBSD 11+
EXPIRATION_DATE=	2018-10-31

USES=		uidfix
PLIST_FILES=	sbin/bsdmoted

.include <bsd.port.mk>
