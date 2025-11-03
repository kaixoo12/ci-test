cmake_minimum_required(VERSION 3.1)

project(SampleProject)

find_program(PYTHON_EXECUTABLE NAMES python3 python)

execute_process(${PYTHON_EXECUTABLE} --version)
