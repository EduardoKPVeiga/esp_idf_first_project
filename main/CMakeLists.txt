idf_component_register(SRCS "sntp_time_sync.c" "main.c" "wifi_app.c" "http_server.c" "app_nvs.c" "wifi_reset_button.c" "sntp_time_sync.c"
                    INCLUDE_DIRS "."
                    EMBED_FILES webpage/app.css webpage/app.js webpage/favicon.ico webpage/index.html webpage/jquery-3.3.1.min.js)
