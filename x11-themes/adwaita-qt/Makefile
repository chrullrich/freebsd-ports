# Created by: Olivier Duchateau
# $FreeBSD$

PORTNAME=	adwaita-qt
DISTVERSION=	1.2.0
CATEGORIES=	x11-themes
PKGNAMESUFFIX=	5

MAINTAINER=	tcberner@FreeBSD.org
COMMENT=	Adwaita theme for Qt applications

LICENSE=	GPLv2 LGPL20
LICENSE_COMB=	multi

USES=		cmake compiler:c++11-lib localbase pkgconfig qt:5 xorg
USE_QT=		core dbus gui widgets x11extras \
		buildtools_build qmake_build
USE_XORG=	xcb
CMAKE_OFF=	USE_QT4

USE_GITHUB=	yes
GH_ACCOUNT=	FedoraQt

.include <bsd.port.mk>
