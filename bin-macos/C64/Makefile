# Makefile.in generated by automake 1.16.5 from Makefile.am.
# data/C64/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2021 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.




am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/vice
pkgincludedir = $(includedir)/vice
pkglibdir = $(libdir)/vice
pkglibexecdir = $(libexecdir)/vice
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = aarch64-apple-darwin24.1.0
host_triplet = aarch64-apple-darwin24.1.0
subdir = data/C64
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/ax_cxx_compile_stdcxx.m4 \
	$(top_srcdir)/m4/lib-ld.m4 \
	$(top_srcdir)/m4/m4_ax_subdirs_configure.m4 \
	$(top_srcdir)/m4/pkg.m4 $(top_srcdir)/m4/vice_args.m4 \
	$(top_srcdir)/m4/vice_compiler_checks.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(am__DIST_COMMON)
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/src/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
SOURCES =
DIST_SOURCES =
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
am__installdirs = "$(DESTDIR)$(c64dir)"
DATA = $(c64_DATA)
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
am__DIST_COMMON = $(srcdir)/Makefile.in $(top_srcdir)/mkinstalldirs
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} '/Users/roger/Data/Projects-Retro/Apps/emu-vice/vice/missing' aclocal-1.16
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AR = $(top_srcdir)/src/arch/shared/macOS-wrap-ar.sh
ARCH_DIR = $(top_builddir)/src/arch/sdl
ARCH_EXTRA_SUBDIR = 
ARCH_INCLUDES = -I$(top_srcdir)/src/arch/sdl -I$(top_srcdir)/src/arch/shared
ARCH_LIBS = $(top_builddir)/src/arch/sdl/libarch.a
ARCH_MAKE_BINDIST_DIR = 
ARCH_SRC_DIR = $(top_srcdir)/src/arch/sdl
ARFLAGS = cr
AR_FLAGS = cr
AUTOCONF = ${SHELL} '/Users/roger/Data/Projects-Retro/Apps/emu-vice/vice/missing' autoconf
AUTOHEADER = ${SHELL} '/Users/roger/Data/Projects-Retro/Apps/emu-vice/vice/missing' autoheader
AUTOMAKE = ${SHELL} '/Users/roger/Data/Projects-Retro/Apps/emu-vice/vice/missing' automake-1.16
AWK = awk
CC = cc
CCAS = cc
CCASDEPMODE = depmode=gcc3
CCASFLAGS = 
CCDEPMODE = depmode=gcc3
CFLAGS = 
CPP = cc -E
CPPFLAGS =   -isystem/opt/homebrew/include
CROSS = false
CSCOPE = cscope
CTAGS = ctags
CXX = c++ -std=gnu++11 -std=c++11 -std=gnu++11
CXXCPP = c++ -std=gnu++11 -std=c++11 -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS =  -fno-exceptions
CYGPATH_W = echo
DEBUGBUILD = 0
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DOS2UNIX = dos2unix
DYNLIB_LIBS = 
ECHO_C = \c
ECHO_N = 
ECHO_T = 
ENABLE_ARCH = yes
ETAGS = etags
EXEEXT = 
FCCACHE = /opt/homebrew/bin/fc-cache
FONTCONFIG_CFLAGS = 
FONTCONFIG_LIBS = 
FW_DIR = 
GFXOUTPUT_DRIVERS =  pngdrv.o
GFXOUTPUT_LIBS = -lpng 
GLEW_CFLAGS = 
GLEW_LIBS = 
GLIB_CFLAGS = -I/opt/homebrew/Cellar/glib/2.82.2/include/glib-2.0 -I/opt/homebrew/Cellar/glib/2.82.2/lib/glib-2.0/include -I/opt/homebrew/opt/gettext/include -I/opt/homebrew/Cellar/pcre2/10.44/include
GLIB_COMPILE_RESOURCES = glib-compile-resources
GLIB_GENMARSHAL = glib-genmarshal
GLIB_LIBS = -L/opt/homebrew/Cellar/glib/2.82.2/lib -lglib-2.0 -L/opt/homebrew/opt/gettext/lib -lintl
GTK_CFLAGS = 
GTK_LIBS = 
HAVE_CXX11 = 1
ICONV = iconv
ICOTOOL = no
INLINE_UNIT_GROWTH = 
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
JOYSTICK_DRIVERS = 
JOY_LIBS = 
LDFLAGS =  -headerpad_max_install_names -L/opt/homebrew/lib -Wl,-rpath,/opt/homebrew/lib
LEX = flex
LEXLIB = -ll 
LEX_OUTPUT_ROOT = lex.yy
LIBOBJS = 
LIBS = -lm  -framework CoreText -framework CoreServices -framework AppKit -framework CoreGraphics -L/opt/homebrew/lib -lSDL2 -L/opt/homebrew/Cellar/sdl2_image/2.8.2_1/lib -lSDL2_image -L/opt/homebrew/lib -lSDL2 -L/usr/lib -lcurl
LINKCC = $(CXX)
LN_S = ln -s
LTLIBOBJS = 
MAKEINFO = ${SHELL} '/Users/roger/Data/Projects-Retro/Apps/emu-vice/vice/missing' makeinfo
MAX_INLINE_INSN_SINGLE = 
MKDIR_P = mkdir -p
MONITOR_CFLAGS =  -Wno-unused-label -Wno-unreachable-code -Wno-misleading-indentation
NETPLAY_LIBS = -lintl 
OBJC = cc
OBJCDEPMODE = depmode=gcc3
OBJCFLAGS = 
OBJCPP = cc -E
OBJEXT = o
PACKAGE = vice
PACKAGE_BUGREPORT = 
PACKAGE_NAME = vice
PACKAGE_STRING = vice 3.9
PACKAGE_TARNAME = vice
PACKAGE_URL = 
PACKAGE_VERSION = 3.9
PATH_SEPARATOR = :
PDFTEX = 
PERL = perl
PKG_CONFIG = /opt/homebrew/bin/pkg-config
PLATFORM_DOX_FLAGS = platformall
PNG_CFLAGS = 
PNG_LIBS = 
PROGRAM_PREFIX = 
PROGRAM_SUFFIX = 
RANLIB = $(top_srcdir)/src/arch/shared/macOS-wrap-ranlib.sh
RESIDDTVSUB = resid-dtv
RESIDSUB = resid
RESID_DEP = libresid
RESID_DIR = resid
RESID_DTV_DEP = libresiddtv
RESID_DTV_DIR = resid-dtv
RESID_DTV_INCLUDES = -I$(top_builddir)/src/resid-dtv
RESID_DTV_LIBS = $(top_builddir)/src/resid-dtv/libresiddtv.a
RESID_INCLUDES = -I$(top_builddir)/src/resid
RESID_LIBS = $(top_builddir)/src/resid/libresid.a
SDL2_CFLAGS = -I/opt/homebrew/include -I/opt/homebrew/include/SDL2 -D_THREAD_SAFE
SDL2_IMAGE_CFLAGS = -I/opt/homebrew/include/SDL2 -I/opt/homebrew/include -D_THREAD_SAFE -I/opt/homebrew/opt/libpng/include/libpng16 -I/opt/homebrew/Cellar/jpeg-xl/0.10.2/include -I/opt/homebrew/Cellar/highway/1.2.0/include -DHWY_SHARED_DEFINE -I/opt/homebrew/Cellar/brotli/1.1.0/include -I/opt/homebrew/Cellar/little-cms2/2.16/include -I/opt/homebrew/Cellar/libtiff/4.7.0/include -I/opt/homebrew/opt/zstd/include -I/opt/homebrew/Cellar/xz/5.6.3/include -I/opt/homebrew/Cellar/jpeg-turbo/3.0.4/include -I/opt/homebrew/Cellar/libavif/1.0.4/include -DAVIF_DLL -I/opt/homebrew/Cellar/webp/1.4.0/include -I/opt/homebrew/Cellar/webp/1.4.0/include/webp
SDL2_IMAGE_LIBS = -L/opt/homebrew/Cellar/sdl2_image/2.8.2_1/lib -lSDL2_image -L/opt/homebrew/lib -lSDL2
SDL2_LIBS = -L/opt/homebrew/lib -lSDL2
SDLCONFIG = 
SDL_EXTRA_LIBS = 
SDL_IMAGE_CFLAGS = 
SDL_IMAGE_LIBS = 
SET_MAKE = 
SHELL = /bin/sh
SOUND_DRIVERS =  soundcoreaudio.o
SOUND_LIBS =  -framework CoreAudio -framework AudioToolbox -framework AudioUnit
SOUND_MIDAS_OBJ = 
SOUND_SDL_OBJ = 
STRIP = strip
SVN = :
SVNVERSION = :
SVN_REVISION_OVERRIDE = 
TAR = tar
TEXI2DVI = 
TFE_LIBS = 
UI_LIBS = 
UNZIPBIN = no
VERSION = 3.9
VERSION_COMBINED = 198912
VERSION_RC = 3,9,0,0
VICE_CFLAGS = -g -O3 -W -Wall -Wextra -Wformat -Wformat-pedantic -Wformat-security -Wshadow -Wpointer-arith -Wmissing-prototypes -Wstrict-prototypes -Wuninitialized -Wmissing-field-initializers -Wunreachable-code -Wmacro-redefined -Werror=implicit-function-declaration -Wfatal-errors -fdiagnostics-absolute-paths -Wshorten-64-to-32 -Wno-unknown-pragmas -Wunused-but-set-variable -Wno-sign-compare -Wno-ignored-qualifiers -Wno-unused-parameter -mmacosx-version-min=15.0 -Wno-deprecated-declarations -I/opt/homebrew/include -I/opt/homebrew/include/SDL2 -D_THREAD_SAFE -I/opt/homebrew/include/SDL2 -I/opt/homebrew/include -D_THREAD_SAFE -I/opt/homebrew/opt/libpng/include/libpng16 -I/opt/homebrew/Cellar/jpeg-xl/0.10.2/include -I/opt/homebrew/Cellar/highway/1.2.0/include -DHWY_SHARED_DEFINE -I/opt/homebrew/Cellar/brotli/1.1.0/include -I/opt/homebrew/Cellar/little-cms2/2.16/include -I/opt/homebrew/Cellar/libtiff/4.7.0/include -I/opt/homebrew/opt/zstd/include -I/opt/homebrew/Cellar/xz/5.6.3/include -I/opt/homebrew/Cellar/jpeg-turbo/3.0.4/include -I/opt/homebrew/Cellar/libavif/1.0.4/include -DAVIF_DLL -I/opt/homebrew/Cellar/webp/1.4.0/include -I/opt/homebrew/Cellar/webp/1.4.0/include/webp 
VICE_CPPFLAGS = -I$(top_srcdir)/src/arch/systemheaderoverride  -isystem/opt/homebrew/include -DNDEBUG
VICE_CXXFLAGS = -g -O3 -Wall -Wformat -Wformat-pedantic -Wshadow -Wpointer-arith -Wuninitialized -Wunreachable-code -Wno-unused-parameter -Wmissing-prototypes -Werror=implicit-function-declaration -Wfatal-errors -fdiagnostics-absolute-paths -Wshorten-64-to-32 -mmacosx-version-min=15.0 -Wno-deprecated-declarations -I/opt/homebrew/include -I/opt/homebrew/include/SDL2 -D_THREAD_SAFE -I/opt/homebrew/include/SDL2 -I/opt/homebrew/include -D_THREAD_SAFE -I/opt/homebrew/opt/libpng/include/libpng16 -I/opt/homebrew/Cellar/jpeg-xl/0.10.2/include -I/opt/homebrew/Cellar/highway/1.2.0/include -DHWY_SHARED_DEFINE -I/opt/homebrew/Cellar/brotli/1.1.0/include -I/opt/homebrew/Cellar/little-cms2/2.16/include -I/opt/homebrew/Cellar/libtiff/4.7.0/include -I/opt/homebrew/opt/zstd/include -I/opt/homebrew/Cellar/xz/5.6.3/include -I/opt/homebrew/Cellar/jpeg-turbo/3.0.4/include -I/opt/homebrew/Cellar/libavif/1.0.4/include -DAVIF_DLL -I/opt/homebrew/Cellar/webp/1.4.0/include -I/opt/homebrew/Cellar/webp/1.4.0/include/webp
VICE_DATADIR = ${datarootdir}/vice
VICE_DOCDIR = ${datarootdir}/doc/${PACKAGE_TARNAME}
VICE_LDFLAGS =  -mmacosx-version-min=15.0 -headerpad_max_install_names -L/opt/homebrew/lib -Wl,-rpath,/opt/homebrew/lib 
VICE_OBJCFLAGS = -g -O3 -W -Wall -Wextra -Wformat -Wformat-pedantic -Wformat-security -Wshadow -Wpointer-arith -Wmissing-prototypes -Wstrict-prototypes -Wuninitialized -Wmissing-field-initializers -Wunreachable-code -Wmacro-redefined -Werror=implicit-function-declaration -Wfatal-errors -fdiagnostics-absolute-paths -Wshorten-64-to-32 -Wno-unknown-pragmas -Wunused-but-set-variable -Wno-sign-compare -Wno-ignored-qualifiers -Wno-unused-parameter -mmacosx-version-min=15.0 -Wno-deprecated-declarations -I/opt/homebrew/include -I/opt/homebrew/include/SDL2 -D_THREAD_SAFE -I/opt/homebrew/include/SDL2 -I/opt/homebrew/include -D_THREAD_SAFE -I/opt/homebrew/opt/libpng/include/libpng16 -I/opt/homebrew/Cellar/jpeg-xl/0.10.2/include -I/opt/homebrew/Cellar/highway/1.2.0/include -DHWY_SHARED_DEFINE -I/opt/homebrew/Cellar/brotli/1.1.0/include -I/opt/homebrew/Cellar/little-cms2/2.16/include -I/opt/homebrew/Cellar/libtiff/4.7.0/include -I/opt/homebrew/opt/zstd/include -I/opt/homebrew/Cellar/xz/5.6.3/include -I/opt/homebrew/Cellar/jpeg-turbo/3.0.4/include -I/opt/homebrew/Cellar/libavif/1.0.4/include -DAVIF_DLL -I/opt/homebrew/Cellar/webp/1.4.0/include -I/opt/homebrew/Cellar/webp/1.4.0/include/webp  
VICE_PDF_FILE_NAME = 
VICE_VERSION = 3.9
VICE_VERSION_BUILD = 0
VICE_VERSION_MAJOR = 3
VICE_VERSION_MINOR = 9
VTE_CXXFLAGS =  -Wno-address-of-packed-member -Wno-char-subscripts -Wno-missing-prototypes -Wno-c99-designator -Wno-shorten-64-to-32
WINDRES = 
WINDRES_LIB = $(top_builddir)/src/arch/sdl/icon.res
XA = xa
XDG_DESKTOP_MENU = 
YACC = yacc
ZLIB_LIBS = -lz
abs_builddir = /Users/roger/Data/Projects-Retro/Apps/emu-vice/vice/data/C64
abs_srcdir = /Users/roger/Data/Projects-Retro/Apps/emu-vice/vice/data/C64
abs_top_builddir = /Users/roger/Data/Projects-Retro/Apps/emu-vice/vice
abs_top_srcdir = /Users/roger/Data/Projects-Retro/Apps/emu-vice/vice
ac_ct_CC = cc
ac_ct_CXX = c++
ac_ct_OBJC = cc
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = aarch64-apple-darwin24.1.0
build_alias = 
build_cpu = aarch64
build_os = darwin24.1.0
build_vendor = apple
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = aarch64-apple-darwin24.1.0
host_alias = 
host_cpu = aarch64
host_os = darwin24.1.0
host_vendor = apple
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /Users/roger/Data/Projects-Retro/Apps/emu-vice/vice/install-sh
libcurl_CFLAGS = 
libcurl_LIBS = -L/usr/lib -lcurl
libdir = ${exec_prefix}/lib
libevdev_CFLAGS = 
libevdev_LIBS = 
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
objdump = objdump
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
runstatedir = ${localstatedir}/run
sbindir = ${exec_prefix}/sbin
sdl_config = no
sharedstatedir = ${prefix}/com
srcdir = .
subdirs_extra =  src/resid src/resid-dtv
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = ../..
vsid_LDFLAGS = 
x128_LDFLAGS = 
x64_LDFLAGS = 
xcbm2_LDFLAGS = 
xpet_LDFLAGS = 
xplus4_LDFLAGS = 
xscpu64_LDFLAGS = 
xvic_LDFLAGS = 
c64dir = $(VICE_DATADIR)/C64
roms = \
	basic-901226-01.bin \
	chargen-901225-01.bin \
	chargen-906143-02.bin \
	kernal-901227-01.bin \
	kernal-901227-02.bin \
	kernal-901227-03.bin \
	kernal-251104-04.bin \
	kernal-901246-01.bin \
	kernal-390852-01.bin \
	kernal-906145-02.bin

romsets = \
	default.vrs

palettes = \
	c64hq.vpl \
	c64s.vpl \
	ccs64.vpl \
	frodo.vpl \
	godot.vpl \
	pc64.vpl \
	vice.vpl \
	pepto-ntsc-sony.vpl \
	pepto-ntsc.vpl \
	pepto-pal.vpl \
	pepto-palold.vpl \
	community-colors.vpl \
	colodore.vpl \
	ptoing.vpl \
	deekay.vpl \
	cjam.vpl \
	palette.vpl \
	pixcen.vpl \
	rgb.vpl \
	the64.vpl \
	palette_6569R1_v1r.vpl \
	palette_6569R5_v1r.vpl \
	palette_8565R2_v1r.vpl \
	palette_C64_amber.vpl \
	palette_C64_cyan.vpl \
	palette_C64_green.vpl \
	lemon64.vpl

gtk3_keymaps = \
	gtk3_sym.vkm \
	gtk3_pos.vkm \
	gtk3_pos_de.vkm \
	gtk3_pos_se.vkm \
	gtk3_pos_it.vkm \
	gtk3_pos_es.vkm \
	gtk3_pos_uk.vkm \
	gtk3_pos_tr.vkm \
	gtk3_sym_de.vkm \
	gtk3_sym_be.vkm \
	gtk3_sym_nl.vkm \
	gtk3_sym_da.vkm \
	gtk3_sym_uk.vkm \
	gtk3_sym_tr.vkm \
	gtk3_keyrah.vkm \
	gtk3_keyrah_de.vkm \
	gtk3_the64_de.vkm \
	gtk3_sym_it.vkm \
	gtk3_sym_se.vkm \
	gtk3_sym_fr.vkm \
	gtk3_pos_bmc64.vkm

sdl_keymaps = \
	sdl_joymap_ps3.vjm \
	sdl_joymap_thec64.vjm \
	sdl_joymap_keyrah_v3.vjm \
	sdl_joymap_xbox360.vjm \
	sdl_pos.vkm \
	sdl_pos_uk.vkm \
	sdl_pos_ch.vkm \
	sdl_pos_da.vkm \
	sdl_pos_de.vkm \
	sdl_pos_fi.vkm \
	sdl_pos_no.vkm \
	sdl_pos_tr.vkm \
	sdl_keyrah.vkm \
	sdl_keyrah_de.vkm \
	sdl_keyrah_retropie.vkm \
	sdl_keyrah_retropie_de.vkm \
	sdl_keyrah_combian.vkm \
	sdl_sym.vkm \
	sdl_sym_uk.vkm \
	sdl_sym_de.vkm \
	sdl_sym_nl.vkm \
	sdl_sym_it.vkm \
	sdl_sym_fr.vkm \
	sdl_sym_tr.vkm \
	sdl_sym_da.vkm

sym_file = \
	c64mem.sym

#c64_DATA = $(roms) $(romsets) $(palettes) $(gtk3_keymaps) $(sym_file)
#c64_DATA = $(roms) $(romsets) $(palettes) $(sym_file)
c64_DATA = $(roms) $(romsets) $(palettes) $(sdl_keymaps) $(sym_file)
#c64_DATA = $(roms) $(romsets) $(palettes) $(sdl_keymaps) $(sym_file)
#EXTRA_DIST = $(c64_DATA) $(sdl_keymaps)
#EXTRA_DIST = $(c64_DATA) $(sdl_keymaps) $(gtk3_keymaps)
EXTRA_DIST = $(c64_DATA) $(gtk3_keymaps)
#EXTRA_DIST = $(c64_DATA) $(gtk3_keymaps)
all: all-am

.SUFFIXES:
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign data/C64/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign data/C64/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
install-c64DATA: $(c64_DATA)
	@$(NORMAL_INSTALL)
	@list='$(c64_DATA)'; test -n "$(c64dir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(c64dir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(c64dir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(c64dir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(c64dir)" || exit $$?; \
	done

uninstall-c64DATA:
	@$(NORMAL_UNINSTALL)
	@list='$(c64_DATA)'; test -n "$(c64dir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(c64dir)'; $(am__uninstall_files_from_dir)
tags TAGS:

ctags CTAGS:

cscope cscopelist:

distdir: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) distdir-am

distdir-am: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(DATA)
installdirs:
	for dir in "$(DESTDIR)$(c64dir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic mostlyclean-am

distclean: distclean-am
	-rm -f Makefile
distclean-am: clean-am distclean-generic

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-c64DATA

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-generic

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-c64DATA

.MAKE: install-am install-strip

.PHONY: all all-am check check-am clean clean-generic cscopelist-am \
	ctags-am distclean distclean-generic distdir dvi dvi-am html \
	html-am info info-am install install-am install-c64DATA \
	install-data install-data-am install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-info install-info-am install-man install-pdf \
	install-pdf-am install-ps install-ps-am install-strip \
	installcheck installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-generic pdf \
	pdf-am ps ps-am tags-am uninstall uninstall-am \
	uninstall-c64DATA

.PRECIOUS: Makefile


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
