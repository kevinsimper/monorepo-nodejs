genrule(
    name = "hello",
    srcs = {
        "srcs": glob(["index.mjs", "*.json", "Dockerfile"]),
        "tslog": ["//services/log:library"],
    },
    cmd = "docker build --file apps/hello/Dockerfile -t hello -q . > $OUT",
    out = "./dist",
)
