# CMakeLists.txt
# Tệp cấu hình CMake để xây dựng dự án helloworld.

# Phiên bản CMake tối thiểu yêu cầu.
cmake_minimum_required(VERSION 3.10)

# Định nghĩa tên dự án.
project(HelloWorld)

# Thêm tệp thực thi.
# Lệnh này tạo một tệp thực thi có tên "helloworld" từ tệp nguồn "main.cpp".
add_executable(helloworld main.cpp)

# (Tùy chọn) Chỉ định tiêu chuẩn C++
# Dòng này đảm bảo dự án sử dụng C++11. Bạn có thể thay đổi thành C++14, C++17, v.v.
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

