# generated by genlibbuild

cc_library(
    name = 'time',
    srcs = [
        'clock.cpp',
        'posix_time.cpp'
    ],
    deps = '#rt'
)


cc_test(
    name = 'clock_test',
    srcs = ['clock_test.cpp'],
    deps = [':time']
)

