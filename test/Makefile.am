AM_CFLAGS = -I$(top_builddir)/src/include

LDADD = \
	$(top_builddir)/zbox-binding/target/release/libzbox.a \
	-lsodium

TESTS_TARGETS = \
	test_ffi

check_PROGRAMS = $(TESTS_TARGETS)

TESTS = $(TESTS_TARGETS)
