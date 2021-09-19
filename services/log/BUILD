genrule(
    name = "library",
    srcs = glob(["src/*.mjs", "*.json"]),
    cmd = "mkdir $OUT && echo $SRCS | xargs -n1 -I{} cp {} $OUT/",
    outs = ["dist"],
    visibility = ["PUBLIC"]
)
