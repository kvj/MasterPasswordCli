bin_PROGRAMS = mpw
mpw_SOURCES =  libcperciva/alg/sha256.h \
			   libcperciva/util/sysendian.h \
			   libcperciva/alg/sha256.c \
			   libscrypt/scrypt_platform.h \
			   libscrypt/crypto/crypto_scrypt.h \
			   libscrypt/crypto/crypto_scrypt-nosse.c \
			   mpw-algorithm.c \
			   mpw-algorithm_v0.c \
			   mpw-algorithm_v2.c \
			   mpw-cli.c \
			   mpw-types.c \
			   mpw-util.h \
			   mpw-algorithm.h \
			   mpw-algorithm_v1.c \
			   mpw-algorithm_v3.c \
			   mpw-types.h \
			   mpw-util.c
AM_CPPFLAGS = -std=c99 -I$(srcdir)/libscrypt -I$(srcdir)/libcperciva/alg -I$(srcdir)/libcperciva/util
