idf_component_register(SRCS "main.c" "wifi_station.c" "led_handler.c"
                    PRIV_REQUIRES esp_wifi nvs_flash esp_driver_gpio spi_flash
                    INCLUDE_DIRS ".")
