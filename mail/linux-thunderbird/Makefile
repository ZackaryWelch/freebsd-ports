# Created by: Andrew Pantyukhin <infofarmer@FreeBSD.org>
# $FreeBSD$

PORTNAME=	thunderbird
DISTVERSION=	45.8.0
PORTREVISION=	0
CATEGORIES=	mail news net-im ipv6
MASTER_SITES=	MOZILLA/${PORTNAME}/releases/${DISTVERSION}/linux-i686/en-US \
		MOZILLA/${PORTNAME}/candidates/${DISTVERSION}-candidates/build1/linux-i686/en-US

MAINTAINER=	gecko@FreeBSD.org
COMMENT=	Mozilla Thunderbird is standalone mail and news that stands above

USES=		tar:bzip2

DEPRECATED=	Use the native thunderbird mail/thunderbird instead
EXPIRATION_DATE=	2017-05-31

.include "${.CURDIR}/../../www/linux-seamonkey/Makefile.common"
.include <bsd.port.mk>
