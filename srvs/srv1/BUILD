subinclude("///pleasings//docker")

python_binary(
    name = "main",
    main = "main.py",
    deps = [
        "//libs/lib1:lib1",
    ],
)


docker_image(
    name = "image",
    srcs = [
        "//srvs/srv1:main"
    ],
    dockerfile = "Dockerfile",
)