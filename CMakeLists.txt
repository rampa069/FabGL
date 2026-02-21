idf_component_register(SRC_DIRS src
                                src/comdrivers
                                src/devdrivers
                                src/dispdrivers
                                src/emudevs
                                src/network
                       INCLUDE_DIRS src
                                src/fonts
                                src/images
                                src/comdrivers
                                src/devdrivers
                                src/dispdrivers
                                src/emudevs
                                src/network
                       REQUIRES fatfs
                                spiffs
                                esp_adc
                                ulp
                                nvs_flash
                                soc
                                esp_wifi
                                esp_driver_i2s
                                esp_driver_i2c
                                esp_driver_dac
                                esp_driver_sdm
                                esp_hw_support
                                 esp_rom
                                 esp_timer
                                 esp_http_client
                                 driver)