project(shm_example)
add_executable(shm_consume shm_consume.cpp)
target_link_libraries(shm_consume pthread rt)
add_executable(shm_produce shm_produce.cpp)
target_link_libraries(shm_produce pthread rt)
