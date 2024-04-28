PORTNAME=		    wayfire-desktop
PORTVERSION=	    1.0.0
CATEGORIES=		    x11-wm
DISTNAME=		    ${PORTNAME}-${ISCVERSION}
DISTVERSIONPREFIX=	v

MAINTAINER=		    mark@cloudbsd.org
COMMENT=		    Instantly installs a Wayfire desktop environment
WWW=			    https://github.com/cloudbsdorg/wayfire-desktop

LICENSE=		    BSD2CLAUSE

RUN_DEPENDS=		wayfire:x11-wm/wayfire \
                    wayfire-plugins-extra:x11-wm/wayfire-plugins-extra \
                    wf-shell:x11/wf-shell \
                    zsh:shells/zsh \
                    ohmyzsh:shells/ohmyzsh \
                    sddm:x11/sddm \
                    drm-kmod:graphics/drm-kmod \


MASTER_SITES=		GH
USE_GITHUB=		    yes
GL_SITE=		    https://github.com
GH_ACCOUNT=		    cloudbsdorg
GH_PROJECT=		    wayfire-desktop

.include <bsd.port.mk>