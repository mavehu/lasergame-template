# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES )
set(COMPONENT_PRIV_REQUIRES )

set(COMPONENT_SRCS 
"main.cpp" 
"../libs/hx711/src/HX711.cpp"
"../libs/CleanCore/src/crt_FromArduinoIDE.cpp"
"../libs/TFT_eSPI/TFT_eSPI.cpp"
"../libs/TFT_eWidget/src/TFT_eWidget.cpp"
"../libs/TFT_eWidget/src/widgets/button/ButtonWidget.cpp"
#"../libs/esp_littlefs/src/esp_littlefs.c"
#"../libs/esp_littlefs/src/lfs_config.c"
#"../libs/esp_littlefs/src/littlefs_api.c"
"../libs/LITTLEFS/src/esp_littlefs.c"
"../libs/LITTLEFS/src/lfs_util.c"
"../libs/LITTLEFS/src/littlefs_api.c"
"../libs/LITTLEFS/src/lfs.c"
"../libs/LITTLEFS/src/LITTLEFS.cpp"
)

set(COMPONENT_ADD_INCLUDEDIRS 
"."
"../libs/CleanRTOS/src" 
"../libs/CleanRTOS/src/internals" 
"../libs/CleanRTOS/examples/AllWaitables"
"../libs/CleanRTOS/examples/Flag"
"../libs/CleanRTOS/examples/Queue"
"../libs/CleanRTOS/examples/Timer"
"../libs/CleanRTOS/examples/HelloWorld"
"../libs/CleanRTOS/examples/TwoTasks"
"../libs/CleanRTOS/examples/MutexSection"
"../libs/CleanRTOS/examples/Pool"
"../libs/CleanRTOS/examples/Handler"
"../libs/CleanRTOS/examples/Logger"
"../libs/CleanRTOS/examples/TenTasks"
"../libs/CleanRTOS_extraTests/examples/Handler2"
"../libs/CleanRTOS_extraTests/examples/HasFired"
"../libs/CleanRTOS_extraTests/examples/Mutex"
"../libs/CleanRTOS_extraTests/examples/Queue2"
"../libs/CleanCore/src"
"../libs/CleanCore/examples/StdQueue"
"../libs/LaserGameUtils/src"
"../libs/LaserGameUtils/examples/ClockPin"
"../libs/hx711/src"
"../libs/hx711/tests"
"../libs/TFT_eSPI"
"../libs/TFT_eSPI/TFT_Drivers"
"../libs/TFT_eSPI/Fonts"
"../libs/TFT_eSPI/Extensions"
"../libs/TFT_eSPI/examples/480x320/Free_Font_Demo"
"../libs/TFT_eWidget/src"
"../libs/TFT_eWidget/src/widgets/button"
"../libs/TFT_eWidget/examples/Buttons/Button_demo"
#"../libs/esp_littlefs/src"
"../libs/LITTLEFS/src"
"../libs/LITTLEFS/examples/LITTLEFS_test"
"../libs/CleanGUI/src"
"../libs/CleanGUI/src/Internals"
"../libs/CleanGUI_async/src"
"../libs/CleanGUI_async/src/Internals"
"../libs/CleanGUI_extraTests/examples/Vec2"
"../libs/CleanGUI_for_TFT_eSPI/examples/Panel"
"../libs/CleanGUI_for_TFT_eSPI/examples/AsyncDisplay"
"../libs/CleanGUI_for_TFT_eSPI/examples/TouchscreenButton"
"../libs/CleanGUI_for_TFT_eSPI/examples/TouchscreenButtonGroup"
"../libs/CleanGUI_for_TFT_eSPI/examples/TouchscreenKeyboardLowerCase"
"../libs/CleanGUI_for_TFT_eSPI"
"../libs"
"../components/arduino-esp32/libraries/WiFi/examples/WifiScan"
"../components/arduino-esp32/libraries/LittleFS/examples/LITTLEFS_test"
)

register_component()
