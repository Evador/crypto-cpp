add_subdirectory(ffi)

add_library(starkware-crypto STATIC elliptic_curve_constants.cc pedersen_hash.cc ecdsa.cc)
target_link_libraries(starkware-crypto algebra)
