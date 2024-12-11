project(test-high)

add_compile_options(
        -Wno-unsafe-buffer-usage
        -Wno-sign-conversion
        -Weverything
        -Wno-unknown-warning-option
        -Wno-c++98-compat
        -Wno-c++98-compat-pedantic
        -Wno-date-time
        -Wno-undef
        -Wno-header-hygiene
        -Wno-unused-macros
)

add_executable(check-pcg8_once_insecure check-pcg8_once_insecure.cpp)
add_executable(check-pcg8_oneseq_once_insecure check-pcg8_oneseq_once_insecure.cpp)
add_executable(check-pcg16_once_insecure check-pcg16_once_insecure.cpp)
add_executable(check-pcg16_oneseq_once_insecure check-pcg16_oneseq_once_insecure.cpp)
add_executable(check-pcg32 check-pcg32.cpp)
add_executable(check-pcg32_c64 check-pcg32_c64.cpp)
add_executable(check-pcg32_c64_fast check-pcg32_c64_fast.cpp)
add_executable(check-pcg32_c64_oneseq check-pcg32_c64_oneseq.cpp)
add_executable(check-pcg32_c1024 check-pcg32_c1024.cpp)
add_executable(check-pcg32_c1024_fast check-pcg32_c1024_fast.cpp)
add_executable(check-pcg32_fast check-pcg32_fast.cpp)
add_executable(check-pcg32_k2 check-pcg32_k2.cpp)
add_executable(check-pcg32_k2_fast check-pcg32_k2_fast.cpp)
add_executable(check-pcg32_k64 check-pcg32_k64.cpp)
add_executable(check-pcg32_k64_fast check-pcg32_k64_fast.cpp)
add_executable(check-pcg32_k64_oneseq check-pcg32_k64_oneseq.cpp)
add_executable(check-pcg32_k1024 check-pcg32_k1024.cpp)
add_executable(check-pcg32_k1024_fast check-pcg32_k1024_fast.cpp)
add_executable(check-pcg32_k16384 check-pcg32_k16384.cpp)
add_executable(check-pcg32_k16384_fast check-pcg32_k16384_fast.cpp)
add_executable(check-pcg32_once_insecure check-pcg32_once_insecure.cpp)
add_executable(check-pcg32_oneseq check-pcg32_oneseq.cpp)
add_executable(check-pcg32_oneseq_once_insecure check-pcg32_oneseq_once_insecure.cpp)
add_executable(check-pcg32_unique check-pcg32_unique.cpp)
add_executable(check-pcg64 check-pcg64.cpp)
add_executable(check-pcg64_c32 check-pcg64_c32.cpp)
add_executable(check-pcg64_c32_fast check-pcg64_c32_fast.cpp)
add_executable(check-pcg64_c32_oneseq check-pcg64_c32_oneseq.cpp)
add_executable(check-pcg64_c1024 check-pcg64_c1024.cpp)
add_executable(check-pcg64_c1024_fast check-pcg64_c1024_fast.cpp)
add_executable(check-pcg64_fast check-pcg64_fast.cpp)
add_executable(check-pcg64_k32 check-pcg64_k32.cpp)
add_executable(check-pcg64_k32_fast check-pcg64_k32_fast.cpp)
add_executable(check-pcg64_k32_oneseq check-pcg64_k32_oneseq.cpp)
add_executable(check-pcg64_k1024 check-pcg64_k1024.cpp)
add_executable(check-pcg64_k1024_fast check-pcg64_k1024_fast.cpp)
add_executable(check-pcg64_once_insecure check-pcg64_once_insecure.cpp)
add_executable(check-pcg64_oneseq check-pcg64_oneseq.cpp)
add_executable(check-pcg64_oneseq_once_insecure check-pcg64_oneseq_once_insecure.cpp)
add_executable(check-pcg64_unique check-pcg64_unique.cpp)
add_executable(check-pcg128_once_insecure check-pcg128_once_insecure.cpp)
add_executable(check-pcg128_oneseq_once_insecure check-pcg128_oneseq_once_insecure.cpp)