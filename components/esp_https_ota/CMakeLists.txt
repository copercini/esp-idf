idf_component_register(SRCS "src/esp_https_ota.c"
                    INCLUDE_DIRS "include"
                    REQUIRES esp_http_client app_update
                    PRIV_REQUIRES log app_update)
