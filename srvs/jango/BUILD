python_requirement(
    name="django",
    requirements=["django==4.1.1"],
)


python_sources(
    name="lib",
    dependencies=[
        ":django",
        "//srvs/jango/jango",
    ],
)

pex_binary(
    name="manage",
    entry_point="manage.py",
    restartable=True,
)