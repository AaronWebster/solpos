# Fork of NREL SOLPOS
# https://www.nrel.gov/grid/solar-resource/solpos.html

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "solpos",
    srcs = ["solpos.cc"],
    hdrs = ["solpos.h"],
    deps = [ ],
)

cc_binary(
    name = "stest",
    srcs = ["stest.cc"],
    deps = [":solpos" ],
)
