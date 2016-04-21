# Created by: Cedric Ricard <ricard+freebsd@free.fr>
# $FreeBSD: $

PORTNAME=	mogo
PORTVERSION=	0.4.0
CATEGORIES=	databases python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	ricard+freebsd@free.fr
COMMENT=	Simple PyMongo "schema-less" object wrapper.

LICENSE=	APACHE20

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}pymongo>=3.0:${PORTSDIR}/databases/pymongo

USES=		python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
