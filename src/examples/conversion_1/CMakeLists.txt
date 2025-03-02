add_executable(readfile readfile.cpp)
add_executable(appendfile appendfile.cpp)
add_executable(machine_learning machine_learning.cpp)
add_executable(machine_learning_10 machine_learning_10.cpp)
add_executable(sharegen sharegen.cpp)
add_executable(matrixmultiply_test matrixmultiply_test.cpp)

find_package(Boost COMPONENTS json log program_options REQUIRED)

target_compile_features(readfile PRIVATE cxx_std_20)
target_compile_features(appendfile PRIVATE cxx_std_20)
target_compile_features(machine_learning PRIVATE cxx_std_20)
target_compile_features(machine_learning_10 PRIVATE cxx_std_20)
target_compile_features(sharegen PRIVATE cxx_std_20)
target_compile_features(matrixmultiply_test PRIVATE cxx_std_20)

target_link_libraries(readfile
    MOTION::motion
    Boost::json
    Boost::log
    Boost::program_options
)

target_link_libraries(appendfile
    MOTION::motion
    Boost::json
    Boost::log
    Boost::program_options
)

target_link_libraries(machine_learning
    MOTION::motion
    Boost::json
    Boost::log
    Boost::program_options
)

target_link_libraries(machine_learning_10
    MOTION::motion
    Boost::json
    Boost::log
    Boost::program_options
)

target_link_libraries(sharegen
    MOTION::motion
    Boost::json
    Boost::log
    Boost::program_options
)

target_link_libraries(matrixmultiply_test
    MOTION::motion
    Boost::json
    Boost::log
    Boost::program_options
)
