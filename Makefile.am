###############################################################################
#  Copyright (c) 2014-2015 libbitcoin-network developers (see COPYING).
#
#         GENERATED SOURCE CODE, DO NOT EDIT EXCEPT EXPERIMENTALLY
#
###############################################################################

# Automake settings.
#==============================================================================
# Look for macros in the m4 subdirectory.
#------------------------------------------------------------------------------
ACLOCAL_AMFLAGS = -I m4


# Distribute, make and install products.
#==============================================================================
# files => ${pkgconfigdir}
#------------------------------------------------------------------------------
pkgconfig_DATA = \
    libbitcoin-c.pc

# files => ${docdir}
#------------------------------------------------------------------------------
doc_DATA = \
    AUTHORS \
    COPYING \
    ChangeLog \
    INSTALL \
    NEWS \
    README

# src/libbitcoin-c.la => ${libdir}
#------------------------------------------------------------------------------
lib_LTLIBRARIES = src/libbitcoin-c.la
src_libbitcoin_c_la_CPPFLAGS = -I${srcdir}/include ${bitcoin_CPPFLAGS}
src_libbitcoin_c_la_LIBADD = ${bitcoin_LIBS}
src_libbitcoin_c_la_SOURCES = \
    src/version.cpp \
    src/constants.cpp \
    src/error.cpp \
    src/utility/binary.cpp \
    src/utility/string.cpp \
    src/utility/data.cpp \
    src/utility/istream_reader.cpp \
    src/utility/ostream_writer.cpp \
    src/utility/flush_lock.cpp \
    src/utility/random.cpp \
    src/math/limits.cpp \
    src/math/hash.cpp \
    src/formats/base_16.cpp \
    src/formats/base_85.cpp \
    src/formats/base_64.cpp \
    src/formats/base_58.cpp \
    src/formats/base_10.cpp \
    src/chain/script.cpp \
    src/machine/script_pattern.cpp \
    src/machine/rule_fork.cpp \
    src/machine/sighash_algorithm.cpp \
    src/machine/opcode.cpp \
    src/machine/operation.cpp \
    src/machine/number.cpp \
    src/machine/program.cpp \
    src/machine/interpreter.cpp \
    src/chain/transaction.cpp \
    src/chain/header.cpp \
    src/chain/point_iterator.cpp \
    src/chain/input.cpp \
    src/chain/output_point.cpp \
    src/chain/output.cpp \
    src/chain/chain_state.cpp \
    src/chain/stealth.cpp \
    src/chain/history.cpp \
    src/chain/block.cpp \
    src/math/stealth.cpp \
    src/math/elliptic_curve.cpp \
    src/math/checksum.cpp \
    src/math/crypto.cpp \
    src/chain/point.cpp \
    src/chain/point_value.cpp \
    src/chain/points_value.cpp \
    src/wallet/bitcoin_uri.cpp \
    src/wallet/encrypted_keys.cpp \
    src/wallet/ek_public.cpp \
    src/wallet/ek_private.cpp \
    src/wallet/mini_keys.cpp \
    src/wallet/uri.cpp \
    src/wallet/ec_private.cpp \
    src/wallet/mnemonic.cpp \
    src/wallet/ek_token.cpp \
    src/wallet/message.cpp \
    src/wallet/ec_public.cpp \
    src/wallet/hd_public.cpp \
    src/wallet/hd_private.cpp \
    src/wallet/stealth_address.cpp \
    src/wallet/payment_address.cpp \
    src/wallet/dictionary.cpp \
    src/wallet/select_outputs.cpp

# local: test/libbitcoin_network_test
#------------------------------------------------------------------------------
if WITH_TESTS

TESTS = libbitcoin_c_test_runner.sh

check_PROGRAMS = test/libbitcoin_c_test
test_libbitcoin_c_test_CPPFLAGS = -I${srcdir}/include ${bitcoin_CPPFLAGS}
test_libbitcoin_c_test_LDADD = src/libbitcoin-c.la ${boost_unit_test_framework_LIBS} ${bitcoin_LIBS}
test_libbitcoin_c_test_SOURCES = \
    test/main.cpp \
    test/utility/binary.cpp \
    test/utility/data.cpp \
    test/math/hash.cpp \
    test/formats/base_16.cpp \
    test/formats/base_58.cpp \
    test/formats/base_64.cpp \
    test/formats/base_85.cpp \
    test/formats/base_10.cpp \
    test/math/stealth.cpp \
    test/math/checksum.cpp \
    test/math/elliptic_curve.cpp \
    test/wallet/bitcoin_uri.cpp \
    test/wallet/hd_public.cpp \
    test/wallet/hd_private.cpp \
    test/wallet/payment_address.cpp \
    test/chain/point.cpp \
    test/chain/header.cpp \
    test/chain/satoshi_words.cpp \
    test/chain/input.cpp \
    test/chain/output.cpp \
    test/chain/transaction.cpp \
    test/chain/block.cpp \
    test/chain/script.cpp \
    #test/math/hash_number.cpp \
    #test/math/script_number.cpp

endif WITH_TESTS

# files => ${includedir}/bitcoin
#------------------------------------------------------------------------------
include_bitcoindir = ${includedir}/bitcoin
include_bitcoin_HEADERS = \
    include/bitcoin/bitcoin.h

include_bitcoin_bitcoin_cdir = ${includedir}/bitcoin/bitcoin/c/
include_bitcoin_bitcoin_c_HEADERS = \
    include/bitcoin/bitcoin/c/version.h \
    include/bitcoin/bitcoin/c/error.h \
    include/bitcoin/bitcoin/c/constants.h

include_bitcoin_bitcoin_c_chaindir = ${includedir}/bitcoin/bitcoin/c/chain
include_bitcoin_bitcoin_c_chain_HEADERS = \
    include/bitcoin/bitcoin/c/chain/output.h \
    include/bitcoin/bitcoin/c/chain/output_point.h \
    include/bitcoin/bitcoin/c/chain/input.h \
    include/bitcoin/bitcoin/c/chain/chain_state.h \
    include/bitcoin/bitcoin/c/chain/input_point.h \
    include/bitcoin/bitcoin/c/chain/transaction.h \
    include/bitcoin/bitcoin/c/chain/header.h \
    include/bitcoin/bitcoin/c/chain/block.h \
    include/bitcoin/bitcoin/c/chain/point_iterator.h \
    include/bitcoin/bitcoin/c/chain/stealth.h \
    include/bitcoin/bitcoin/c/chain/history.h \
    include/bitcoin/bitcoin/c/chain/script.h \
    include/bitcoin/bitcoin/c/chain/point_value.h \
    include/bitcoin/bitcoin/c/chain/points_value.h \
    include/bitcoin/bitcoin/c/chain/point.h

include_bitcoin_bitcoin_c_machine_scriptdir = ${includedir}/bitcoin/bitcoin/c/machine
include_bitcoin_bitcoin_c_machine_script_HEADERS = \
    include/bitcoin/bitcoin/c/machine/opcode.h \
    include/bitcoin/bitcoin/c/machine/script_pattern.h \
    include/bitcoin/bitcoin/c/machine/operation.h

include_bitcoin_bitcoin_c_mathdir = ${includedir}/bitcoin/bitcoin/c/math
include_bitcoin_bitcoin_c_math_HEADERS = \
    include/bitcoin/bitcoin/c/math/elliptic_curve.h \
    include/bitcoin/bitcoin/c/math/limits.h \
    include/bitcoin/bitcoin/c/math/crypto.h \
    include/bitcoin/bitcoin/c/math/checksum.h \
    include/bitcoin/bitcoin/c/math/stealth.h \
    include/bitcoin/bitcoin/c/math/hash.h

include_bitcoin_bitcoin_c_utilitydir = ${includedir}/bitcoin/bitcoin/c/utility
include_bitcoin_bitcoin_c_utility_HEADERS = \
    include/bitcoin/bitcoin/c/utility/binary.h \
    include/bitcoin/bitcoin/c/utility/random.h \
    include/bitcoin/bitcoin/c/utility/data.h \
    include/bitcoin/bitcoin/c/utility/string.h \
    include/bitcoin/bitcoin/c/utility/istream_reader.h \
    include/bitcoin/bitcoin/c/utility/ostream_writer.h \
    include/bitcoin/bitcoin/c/utility/flush_lock.h \
    include/bitcoin/bitcoin/c/utility/vector.h

include_bitcoin_bitcoin_c_formatsdir = ${includedir}/bitcoin/bitcoin/c/formats
include_bitcoin_bitcoin_c_formats_HEADERS = \
    include/bitcoin/bitcoin/c/formats/base_16.h \
    include/bitcoin/bitcoin/c/formats/base_64.h \
    include/bitcoin/bitcoin/c/formats/base_85.h \
    include/bitcoin/bitcoin/c/formats/base_58.h \
    include/bitcoin/bitcoin/c/formats/base_10.h

include_bitcoin_bitcoin_c_walletdir = ${includedir}/bitcoin/bitcoin/c/wallet
include_bitcoin_bitcoin_c_wallet_HEADERS = \
    include/bitcoin/bitcoin/c/wallet/bitcoin_uri.h \
    include/bitcoin/bitcoin/c/wallet/uri.h \
    include/bitcoin/bitcoin/c/wallet/ek_token.h \
    include/bitcoin/bitcoin/c/wallet/ek_private.h \
    include/bitcoin/bitcoin/c/wallet/ek_public.h \
    include/bitcoin/bitcoin/c/wallet/dictionary.h \
    include/bitcoin/bitcoin/c/wallet/encrypted_keys.h \
    include/bitcoin/bitcoin/c/wallet/message.h \
    include/bitcoin/bitcoin/c/wallet/ec_private.h \
    include/bitcoin/bitcoin/c/wallet/ec_public.h \
    include/bitcoin/bitcoin/c/wallet/hd_public.h \
    include/bitcoin/bitcoin/c/wallet/hd_private.h \
    include/bitcoin/bitcoin/c/wallet/mini_keys.h \
    include/bitcoin/bitcoin/c/wallet/payment_address.h \
    include/bitcoin/bitcoin/c/wallet/mnemonic.h \
    include/bitcoin/bitcoin/c/wallet/select_outputs.h \
    include/bitcoin/bitcoin/c/wallet/stealth_address.h

include_bitcoin_bitcoin_c_internal_chaindir = ${includedir}/bitcoin/bitcoin/c/internal/chain
include_bitcoin_bitcoin_c_internal_chain_HEADERS = \
    include/bitcoin/bitcoin/c/internal/chain/output.hpp \
    include/bitcoin/bitcoin/c/internal/chain/output_point.hpp \
    include/bitcoin/bitcoin/c/internal/chain/input.hpp \
    include/bitcoin/bitcoin/c/internal/chain/chain_state.hpp \
    include/bitcoin/bitcoin/c/internal/chain/transaction.hpp \
    include/bitcoin/bitcoin/c/internal/chain/header.hpp \
    include/bitcoin/bitcoin/c/internal/chain/block.hpp \
    include/bitcoin/bitcoin/c/internal/chain/point.hpp \
    include/bitcoin/bitcoin/c/internal/chain/point_value.hpp \
    include/bitcoin/bitcoin/c/internal/chain/points_value.hpp \
    include/bitcoin/bitcoin/c/internal/chain/stealth.hpp \
    include/bitcoin/bitcoin/c/internal/chain/history.hpp \
    include/bitcoin/bitcoin/c/internal/chain/script.hpp \
    include/bitcoin/bitcoin/c/internal/chain/point_iterator.hpp

include_bitcoin_bitcoin_c_internal_machinedir = ${includedir}/bitcoin/bitcoin/c/internal/machine
include_bitcoin_bitcoin_c_internal_machine_HEADERS = \
    include/bitcoin/bitcoin/c/internal/machine/opcode.hpp \
    include/bitcoin/bitcoin/c/internal/machine/script_pattern.hpp \
    include/bitcoin/bitcoin/c/internal/machine/sighash_algorithm.hpp \
    include/bitcoin/bitcoin/c/internal/machine/rule_fork.hpp \
    include/bitcoin/bitcoin/c/internal/machine/operation.hpp

include_bitcoin_bitcoin_c_internal_mathdir = ${includedir}/bitcoin/bitcoin/c/internal/math
include_bitcoin_bitcoin_c_internal_math_HEADERS = \
    include/bitcoin/bitcoin/c/internal/math/hash.hpp \
    include/bitcoin/bitcoin/c/internal/math/crypto.hpp \
    include/bitcoin/bitcoin/c/internal/math/elliptic_curve.hpp

include_bitcoin_bitcoin_c_internal_utilitydir = ${includedir}/bitcoin/bitcoin/c/internal/utility
include_bitcoin_bitcoin_c_internal_utility_HEADERS = \
    include/bitcoin/bitcoin/c/internal/utility/binary.hpp \
    include/bitcoin/bitcoin/c/internal/utility/data.hpp \
    include/bitcoin/bitcoin/c/internal/utility/istream_reader.hpp \
    include/bitcoin/bitcoin/c/internal/utility/ostream_writer.hpp \
    include/bitcoin/bitcoin/c/internal/utility/flush_lock.hpp \
    include/bitcoin/bitcoin/c/internal/utility/vector.hpp \
    include/bitcoin/bitcoin/c/internal/utility/string.hpp

include_bitcoin_bitcoin_c_internal_walletdir = ${includedir}/bitcoin/bitcoin/c/internal/wallet
include_bitcoin_bitcoin_c_internal_wallet_HEADERS = \
    include/bitcoin/bitcoin/c/internal/wallet/bitcoin_uri.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/uri.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/ek_token.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/ek_private.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/ek_public.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/dictionary.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/encrypted_keys.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/message.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/ec_private.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/ec_public.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/hd_public.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/mnemonic.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/hd_private.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/payment_address.hpp \
    include/bitcoin/bitcoin/c/internal/wallet/stealth_address.hpp

