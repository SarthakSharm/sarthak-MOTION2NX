add_subdirectory(aes128)
add_subdirectory(benchmark_garbling)
add_subdirectory(benchmark_integers)
add_subdirectory(benchmark_nn_layers)
add_subdirectory(benchmark_operations)
add_subdirectory(benchmark_providers)
add_subdirectory(cryptonets)
add_subdirectory(evaluate_circuit_from_file)
add_subdirectory(example_template)
add_subdirectory(millionaires_problem)
add_subdirectory(sha256)
add_subdirectory(triple_generator)
add_subdirectory(test)

add_subdirectory(beavy_arithmetic)
add_subdirectory(beavy_dot_product)
add_subdirectory(beavy_gemm)
add_subdirectory(data_provider_operations)
add_subdirectory(data_provider_dot_product_1d)
add_subdirectory(file_dot_product_1d)
add_subdirectory(file_multiplication)
add_subdirectory(modified_dot_product)
add_subdirectory(other_stuff)
add_subdirectory(tensor_constant_multiplication)
add_subdirectory(tensor_dot_product)
add_subdirectory(tensor_gt)
add_subdirectory(tensor_matrix_multiplication)
add_subdirectory(tensor_relu)
add_subdirectory(tensor_relu_maxpool_dp)
add_subdirectory(tensor_gt_mul)
add_subdirectory(accuracy_testing)
add_subdirectory(conversion_1)
add_subdirectory(logistic_regression)
add_subdirectory(server)

if (MOTION_BUILD_ONNX_ADAPTER)
  add_subdirectory(onnx2motion)
endif (MOTION_BUILD_ONNX_ADAPTER)

if (MOTION_BUILD_HYCC_ADAPTER)
  add_subdirectory(hycc2motion)
endif (MOTION_BUILD_HYCC_ADAPTER)
