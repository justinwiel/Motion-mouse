#set(COMPONENT_SRCS "main.cpp")
#set(COMPONENT_ADD_INCLUDEDIRS "")

#register_component()

idf_component_register(SRCS "main.cpp"
                    INCLUDE_DIRS ".")
