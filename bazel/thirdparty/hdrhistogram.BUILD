cc_library(
    name = "hdrhistogram",
    srcs = [
        "src/hdr_atomic.h",
        "src/hdr_encoding.c",
        "src/hdr_encoding.h",
        "src/hdr_endian.h",
        "src/hdr_histogram.c",
        "src/hdr_histogram_log.c",
        "src/hdr_interval_recorder.c",
        "src/hdr_malloc.h",
        "src/hdr_tests.h",
        "src/hdr_thread.c",
        "src/hdr_time.c",
        "src/hdr_writer_reader_phaser.c",
    ],
    hdrs = [
        "include/hdr/hdr_histogram.h",
        "include/hdr/hdr_histogram_log.h",
        "include/hdr/hdr_histogram_version.h",
        "include/hdr/hdr_interval_recorder.h",
        "include/hdr/hdr_thread.h",
        "include/hdr/hdr_time.h",
        "include/hdr/hdr_writer_reader_phaser.h",
    ],
    copts = [
        "-std=gnu99",
        "-Wno-implicit-function-declaration",
        "-Wno-error",
    ],
    strip_include_prefix = "include",
    visibility = ["//visibility:public"],
    deps = ["@zlib"],
)
