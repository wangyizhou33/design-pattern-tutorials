# CMake entry point
cmake_minimum_required (VERSION 2.6)
project (Tutorials)

# Abstract factory
add_executable(abstract_factory_01
	creational/abstract_factory/example1.cc
)

add_executable(abstract_factory_02
	creational/abstract_factory/example2.cc
)

# Builder
add_executable(builder
	creational/builder/example.cc
)

# Factory method
add_executable(factory_method_01
	creational/factory_method/example1.cc
)

add_executable(factory_method_02
	creational/factory_method/example2.cc
)

# Prototype
add_executable(prototype_01
	creational/prototype/example1.cc
)

add_executable(prototype_02
	creational/prototype/example2.cc
)

# Prototype
add_executable(singleton_01
	creational/singleton/example1.cc
)

add_executable(singleton_02
	creational/singleton/example2.cc
)