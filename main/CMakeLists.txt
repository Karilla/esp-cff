idf_component_register(SRCS "main.c"
                       PRIV_REQUIRES spi_flash esp_lcd esp_driver_spi esp_driver_gpio esp_timer json
                       INCLUDE_DIRS ".")