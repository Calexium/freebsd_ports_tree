# Created by: Cedric Ricard <ricard+freebsd@free.fr>
# $FreeBSD: $

PORTNAME=	txmongo
PORTVERSION=	16.0.1
CATEGORIES=	databases python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	ricard+freebsd@free.fr
COMMENT=	Asynchronous Python driver for MongoDB.

LICENSE=	APACHE20

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}pymongo>=3.0:${PORTSDIR}/databases/pymongo \
				${PYTHON_PKGNAMEPREFIX}twisted>=14.0:${PORTSDIR}/devel/py-twisted

USES=		python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
