define_utest(
    my_api_utest
    SRC_DIR
        .
    SOURCES
        main.cpp
    #PRIV_HEADERS
    #API_HEADERS
    #API_DIR
    LIBS
        demo_headers::my_api
    #SYS_LIBS
)
