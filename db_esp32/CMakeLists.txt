cmake_minimum_required(VERSION 2.8)
project(db_esp32)

include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/avdt/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/a2dp/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/l2cap/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/avct/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/smp/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/sdp/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/gap/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/rfcomm/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/gatt/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/avrc/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/stack/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/external/sbc/decoder/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/external/sbc/encoder/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/device/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/api/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/osi/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/btcore/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/bta/sys/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/bta/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/utils/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/hci/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/btc/profile/std/a2dp/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/btc/profile/std/battery/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/btc/profile/std/hid/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/btc/profile/std/dis/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/btc/profile/std/smp/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/btc/profile/std/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/btc/profile/esp/blufi/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/btc/profile/esp/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/btc/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/bluedroid/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/aws_iot/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/aws_iot/aws-iot-device-sdk-embedded-C/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/app_trace/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/app_update/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/xtensa-debug-module/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bootloader_support/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bootloader_support/include_priv")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/bt/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/coap/port/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/coap/port/include/coap")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/coap/libcoap/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/coap/libcoap/include/coap")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/console")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/cxx/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/driver/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/driver/include/driver")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/esp_adc_cal/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/esp32/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/ethernet/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/expat/include/expat")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/expat/port/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/fatfs/src")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/freertos/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/jsmn/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/json/cJSON")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/json/port/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/libsodium/libsodium/src/libsodium/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/libsodium/libsodium/src/libsodium/include/sodium")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/log/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/lwip/include/lwip")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/lwip/include/lwip/port")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/lwip/include/lwip/posix")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/lwip/apps/ping")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/mbedtls/port/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/mbedtls/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/mdns/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/micro-ecc/micro-ecc")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/newlib")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/newlib/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/newlib/platform_include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/newlib/include/sys")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/newlib/include/sys/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/nghttp/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/nghttp/port/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/nvs_flash/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/openssl/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/openssl/include/internal")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/openssl/include/platform")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/openssl/include/openssl")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/sdmmc/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/spi_flash/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/spiffs/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/tcpip_adapter/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/soc/esp32/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/soc/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/heap/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/ulp/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/vfs/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/wear_levelling/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/wpa_supplicant/include")
include_directories("/home/cyber/Dokumente/Programming/esp32_SDK/esp/esp-idf/components/wpa_supplicant/port/include")

ADD_EXECUTABLE(db_esp32 main/main.c main/db_esp32_control.c main/globals.h main/sdkconfig.h main/msp_ltm_serial.c
        main/msp_ltm_serial.h main/db_protocol.h main/tcp_server.c main/tcp_server.h main/db_esp32_comm.c
        main/db_esp32_comm.h main/db_comm_protocol.h main/db_comm.c main/db_comm.h)