java_binary(
    name = "ProjectRunner",
    srcs = glob(["src/main/jgame/ProjectRunner.java"]),
    main_class = "main.jgame.ProjectRunner",
    deps = [":greeter"],
)

java_library(
    name = "greeter",
    srcs = ["src/main/jgame/Greeting.java"],
    visibility = ["//src/main/jgame/cmdline:__pkg__"],
)
