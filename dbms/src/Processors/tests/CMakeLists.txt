add_executable (processors_test processors_test.cpp)
add_executable (processors_test_chain processors_test_chain.cpp)

target_link_libraries (processors_test dbms)
target_link_libraries (processors_test_chain dbms)
