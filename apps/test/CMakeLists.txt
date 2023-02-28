add_executable(test test.c)

target_link_libraries(test PRIVATE
    pico_stdlib
    )

pico_add_extra_outputs(test)

pico_enable_stdio_usb(test 0)
pico_enable_stdio_uart(test 1)