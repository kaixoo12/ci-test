cmake_minimum_required(VERSION 3.1)

project(SampleProject)

find_program(PYTHON_EXECUTABLE NAMES python3 python)

execute_process(COMMAND ${PYTHON_EXECUTABLE} --version)
