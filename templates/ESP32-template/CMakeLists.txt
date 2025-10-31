file(GLOB_RECURSE app_sources
    "*.c"
    "*.cpp"
)

# Define this directory as the "main" component
idf_component_register(SRCS "${app_sources}" INCLUDE_DIRS ".")
