# Fork of NREL SOLPOS
# https://www.nrel.gov/grid/solar-resource/solpos.html

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "solpos",
    srcs = ["solpos.cc"],
    hdrs = ["solpos.h"],
    deps = [
        "@com_google_absl//absl/base",
        "@com_google_absl//absl/strings",
    ],
)

cc_test(
    name = "solpos_test",
    srcs = ["solpos_test.cc"],
    deps = [
        ":solpos",
        "@com_google_googletest//:gtest_main",
    ],
)
