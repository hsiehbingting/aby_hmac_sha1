
add_executable(hmac_sha1_test hmac_sha1_test.cpp common/hmac_sha1_circuit.cpp)
target_link_libraries(hmac_sha1_test ABY::aby ENCRYPTO_utils::encrypto_utils)
