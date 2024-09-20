idf_component_register(SRCS "i2s_recorder.c"
                    PRIV_REQUIRES esp_driver_i2s esp_driver_gpio esp_driver_uart
                    INCLUDE_DIRS "." "$ENV{IDF_PATH}/examples/peripherals/i2s/common")
