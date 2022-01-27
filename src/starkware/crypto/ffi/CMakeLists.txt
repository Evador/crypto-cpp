add_subdirectory(js)

add_library(crypto_c_exports STATIC pedersen_hash.cc ecdsa.cc utils.cc)
target_link_libraries(crypto_c_exports crypto)
