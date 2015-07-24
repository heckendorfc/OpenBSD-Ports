# $OpenBSD$

COMMENT =		console news feed reader
GH_VER=			1.01
DISTNAME =		newsbaoter-${GH_VER}
CATEGORIES =		www

HOMEPAGE =		http://github.com/heckendorfc/newsbaoter

MAINTAINER =		Christian Heckendorf <heckendorfc@gmail.com>

# BSD
PERMIT_PACKAGE_CDROM =	Yes

WANTLIB += c curl m ncursesw sqlite3 xml2 xslt

#MASTER_SITES =		https://github.com/heckendorfc/newsbaoter/archive/
GH_ACCOUNT =		heckendorfc
GH_PROJECT =		newsbaoter
GH_TAGNAME =		${GH_VER}
GH_COMMIT =		88c7463

MODULES =		devel/cmake

LIB_DEPENDS =		textproc/libxml	\
			textproc/libxslt	\
			net/curl

SEPARATE_BUILD =	yes

.include <bsd.port.mk>
