add_executable(test_blink test_blink.c)

target_link_libraries(test_blink PRIVATE
    pico_stdlib
    pico_cyw43_arch_none
    )

pico_add_extra_outputs(test_blink)

pico_enable_stdio_usb(test_blink 0)
pico_enable_stdio_uart(test_blink 1)